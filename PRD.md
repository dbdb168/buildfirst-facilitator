1# Subscription Audit Agent

Automated monthly subscription analysis and optimization using Plaid + Claude AI.

## Overview

This agent automatically:
1. **Pulls transactions** from your bank accounts via Plaid API
2. **Analyzes subscriptions** using Claude AI to categorize as Keep/Cancel/Agent
3. **Generates a report** as a PowerPoint presentation
4. **Sends email** with findings and approval links
5. **Executes cancellations** for approved items

## Architecture

```
EventBridge (Monthly) → Step Functions Workflow
    ↓
┌─────────────────────────────────────────────┐
│ 1. Pull Transactions (Plaid)                │
│ 2. Analyze with Claude AI                   │
│ 3. Generate PowerPoint Report               │
│ 4. Send Email with Approval Links           │
│ 5. Wait for User Approval (up to 48h)       │
│ 6. Execute Approved Cancellations           │
│ 7. Send Summary Email                       │
└─────────────────────────────────────────────┘
```

## Setup

### 1. Prerequisites

- AWS Account with Serverless Framework configured
- Plaid Account (https://dashboard.plaid.com)
- Anthropic API Key (https://console.anthropic.com)
- Verified SES domain for sending emails

### 2. Install Dependencies

```bash
npm install -g serverless
npm install

# Python dependencies (for local testing)
pip install -r requirements.txt
```

### 3. Configure Secrets

Store these in AWS Systems Manager Parameter Store:

```bash
# Plaid credentials
aws ssm put-parameter --name "/subscription-audit/dev/plaid-client-id" --value "YOUR_CLIENT_ID" --type SecureString
aws ssm put-parameter --name "/subscription-audit/dev/plaid-secret" --value "YOUR_SECRET" --type SecureString

# Anthropic API key
aws ssm put-parameter --name "/subscription-audit/dev/anthropic-api-key" --value "YOUR_API_KEY" --type SecureString

# Approval link secret (generate a random string)
aws ssm put-parameter --name "/subscription-audit/dev/approval-secret" --value "$(openssl rand -hex 32)" --type SecureString

# Email configuration
aws ssm put-parameter --name "/subscription-audit/dev/ses-from-email" --value "audit@yourdomain.com" --type String
aws ssm put-parameter --name "/subscription-audit/dev/user-email" --value "you@email.com" --type String
aws ssm put-parameter --name "/subscription-audit/dev/user-name" --value "Your Name" --type String
```

### 4. Connect Bank Accounts

Run the Plaid Link setup script to connect your accounts:

```bash
export PLAID_CLIENT_ID=your_client_id
export PLAID_SECRET=your_secret
export PLAID_ENV=production  # or sandbox for testing

python scripts/setup_plaid_link.py
```

This opens a browser to connect your bank accounts. Save the access tokens in SSM:

```bash
aws ssm put-parameter --name "/subscription-audit/dev/plaid-access-tokens" --value '{"personal":"access-xxx","business":"access-yyy"}' --type SecureString
```

### 5. Deploy

```bash
# Deploy to dev
serverless deploy --stage dev

# Deploy to production
serverless deploy --stage prod
```

### 6. Test

Manually trigger the workflow:

```bash
aws stepfunctions start-execution \
  --state-machine-arn $(aws cloudformation describe-stacks --stack-name subscription-audit-agent-dev --query "Stacks[0].Outputs[?OutputKey=='StateMachineArn'].OutputValue" --output text) \
  --input '{}'
```

## Configuration

### Customizing Analysis

Edit `src/analyzer.py` to customize the user context:

```python
user_context = """
- User runs a consulting business
- Has a family with kids
- Heavy Claude AI user
- Values automation
"""
```

### Adding Cancellation Contacts

Edit `src/cancellation_handler.py` to add service contacts:

```python
CANCELLATION_CONTACTS = {
    "service-name": {"email": "support@service.com", "method": "email"},
    ...
}
```

### Schedule

The workflow runs on the 1st of each month at 9am ET by default. Modify `serverless.yml`:

```yaml
events:
  - schedule:
      rate: cron(0 14 1 * ? *)  # 14:00 UTC = 9:00 ET
```

## Cost Estimate

| Service | Monthly Cost |
|---------|-------------|
| Plaid API | ~$0-5 |
| AWS Lambda | ~$0 (free tier) |
| AWS Step Functions | ~$0.025 |
| AWS S3 | ~$0.10 |
| AWS SES | ~$0.10 |
| Claude API | ~$1-2 |
| **Total** | **~$5-10/month** |

## Development

### Local Testing

```bash
# Run individual handlers
python -c "from src.plaid_client import get_all_subscriptions; print(get_all_subscriptions({'personal': 'access-xxx'}))"

# Run analyzer
python -c "from src.analyzer import analyze_and_categorize; print(analyze_and_categorize([...]))"
```

### Project Structure

```
subscription-audit-agent/
├── src/
│   ├── plaid_client.py         # Plaid API integration
│   ├── analyzer.py             # Claude AI categorization
│   ├── report_generator.py     # PowerPoint generation
│   ├── email_sender.py         # SES emails with approval links
│   ├── cancellation_handler.py # Cancellation email sending
│   └── handlers/               # Lambda handlers
├── templates/                  # Email templates
├── scripts/
│   └── setup_plaid_link.py    # One-time Plaid setup
├── state-machine.json         # Step Functions definition
├── serverless.yml             # Infrastructure as code
└── requirements.txt           # Python dependencies
```

## Security

- All secrets stored in AWS Secrets Manager / SSM Parameter Store
- Approval links use HMAC-signed tokens with 48-hour expiry
- S3 reports are private with pre-signed URLs only
- User is CC'd on all cancellation emails

## License

MIT

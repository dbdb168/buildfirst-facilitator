# Facilitator Guide

A guide for running BuildFirst workshops. This is for the human facilitator — the skills handle the Claude side.

---

## The Narrative Arc

**Friction → Vision → Structure → Agency**

| Phase | What Happens | Emotional Beat |
|-------|--------------|----------------|
| **Friction** | Surface what's broken, annoying, or missing | "I'm not alone in this" |
| **Vision** | Dream big, imagine the perfect solution | "This could actually exist" |
| **Structure** | Shape dreams into something buildable | "Now I know what I'm making" |
| **Agency** | Build it, use it, own it | "I made this" |

Every workshop follows this arc. The skills support it, but the facilitator holds the emotional throughline.

---

## Workshop Flow

### Pre-Workshop (Async)

**Prep Prompt** — Sent a few days before. Participants paste it into Claude Chat to set up:
- Claude Pro (they should already have this)
- Claude Code (included with Pro)
- GitHub account
- Wispr Flow

### Workshop Day

| Time | Phase | Activity | Tool |
|------|-------|----------|------|
| 0:00–0:15 | Setup | Welcome, settle in, verify setup | In-person |
| 0:15–0:45 | **Friction** | Quick Win — build something small that works | Claude Chat |
| 0:45–1:00 | **Friction** | Creative Exercise — "Where's the Person Who..." | Away from computer |
| 1:00–1:30 | **Vision** | Dream Capture — messy brainstorm, magic wand thinking | Claude Chat |
| 1:30–2:15 | **Structure** | PRD Builder — Vision PRD, Scoped v1, Backlog | Claude Chat |
| 2:15–3:00 | **Agency** | Build — incremental build-test cycles | Claude Code |
| 3:00–3:15 | **Agency** | Use — try it for real | Their build |
| 3:15–3:35 | **Agency** | Refine — fix now vs. fix later | Claude Code |
| 3:35–3:50 | Reflection | Retrospective — discover what they learned | Claude Chat |
| 3:50–4:00 | Momentum | Next Project — leave with a starter prompt | Claude Chat |

---

## Creative Exercise: "Where's the Person Who..."

**Timing:** After Quick Win, before Dream Capture (~15 min)

**Purpose:** Surface friction, spark ambition, build connection between participants.

**Format:** Away from the computer. Physical movement encouraged.

### How to Run It

1. **Frame it:** "Before we dive into what you want to build, let's surface what's broken. Not just for you — for everyone in this room."

2. **Prompt the room:** "Where's the person who... [friction prompt]?"

   Example prompts:
   - "...spends too much time on something that should be automatic?"
   - "...has information scattered across too many places?"
   - "...wishes they had a second brain for a specific part of their work?"
   - "...keeps forgetting to follow up on something important?"
   - "...does the same tedious task every week?"

3. **Let people respond:** Raise hands, share briefly, connect with others who share the same friction.

4. **Build energy:** "You're not alone. And in the next few hours, you're going to build something that addresses one of these."

### Why This Works

- Surfaces friction before they have to articulate a solution
- Creates solidarity ("I'm not the only one")
- Primes them to dream bigger in Dream Capture
- Gets them away from screens before the intensive build phase

### Facilitator Notes

- Keep it moving — don't let any one share go too long
- Encourage physical movement (stand up, raise hands, cluster by theme)
- End with energy, not exhaustion
- This is a placeholder — refine based on what works in practice

---

## Tiered Outcomes

Not everyone will reach the same endpoint. That's fine. Set expectations early:

| Tier | What They Leave With | Requires |
|------|---------------------|----------|
| **Bronze** | Working artifact in Claude Chat | Quick Win complete |
| **Silver** | Working system in Claude Code (local) | Build phase complete |
| **Gold** | Deployed + connected to external services | Stretch goal achieved |

**Silver is the target.** Most participants should leave with a working local build they can use.

**Gold is a stretch.** If time and energy allow, some will deploy to Vercel or connect to Supabase.

**Bronze is a valid fallback.** If the build phase gets complicated, the Quick Win artifact is still a real accomplishment.

### How to Talk About Tiers

Early in the workshop:
> "By the end of today, you'll have something working. For some of you, that'll be a polished local tool. For some, it might be deployed and live. For others, it might be a simpler artifact that still does something useful. All of those are wins."

If someone's struggling:
> "Let's make sure the core works before we add complexity. A working Bronze is better than a broken Gold."

---

## Facilitator Responsibilities

### Time Awareness

- Gently check in on time throughout
- At the 2-hour mark: "We're halfway. How's everyone feeling about scope?"
- At the 3-hour mark: "We've got an hour left. Let's make sure we refine what's working rather than adding new features."

### Scope Coaching

- Watch for participants who are over-scoping
- "That's ambitious. What's the smallest version that would still be useful?"
- "You can always add that later. Let's nail the core first."

### Energy Management

- The Build phase can be draining — check in on energy
- Quick breaks are okay if needed
- If someone's frustrated, offer to pair or troubleshoot

### Emotional Throughline

Remember the arc: **Friction → Vision → Structure → Agency**

- In Friction: Let them feel the problem
- In Vision: Let them dream without limits
- In Structure: Help them feel clarity, not constraint
- In Agency: Celebrate what they made, not what they didn't

---

## Common Failure Modes

| Problem | Signs | Intervention |
|---------|-------|--------------|
| Over-scoping | PRD has 10 features, build hasn't started | "Let's pick the one thing that matters most" |
| Under-scoping | Building something trivial | "What would make this genuinely useful to you?" |
| Auth spiral | Stuck on login flows for 30+ minutes | "Auth is hard. Let's skip it for now and add it later" |
| Perfectionism | Iterating endlessly on small details | "This is good enough to use. The rest can wait" |
| Lost | Don't know what to do next | Orient them to the arc, point to next skill |

---

## After the Workshop

### What They Leave With

1. **A working build** (Bronze, Silver, or Gold)
2. **Three PRD documents** (Vision, Scoped v1, Backlog)
3. **A parking lot** of ideas for later
4. **A personal glossary** of tech terms they now understand
5. **A starter prompt** for their next project

### Follow-Up (Optional)

- Check in a week later: "Did you use your build? What did you discover?"
- Offer accountability hours if you have a support offering
- Invite them to share what they built

---

## Notes for Future Iteration

- The "Where's the Person Who..." exercise is a placeholder — test and refine
- Timing is approximate — adjust based on group size and energy
- Consider adding a "show and tell" moment at the end
- Track which tiers people land in to calibrate expectations

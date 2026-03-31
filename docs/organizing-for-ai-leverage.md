# Organizing for AI Leverage

## Tensions, Patterns, and Leaders at the Edge

*A BuildFirst Research Dossier — March 2026*
*Internal document for design sprint preparation*

---

## How to Read This Document

This is a provocation engine, not a literature review. It is designed to surface hard questions, not provide easy answers.

The document is structured in three layers:

1. **The Landscape Shift** — the structural argument for why organizational design is changing (not "AI is changing everything" but *specifically how*)
2. **The Tensions** — seven unresolved organizational tensions that every leader navigating AI will have to confront, each grounded in named companies, named people, and real outcomes
3. **The Leaders Map** — the people and organizations worth watching, organized by what they represent

Each tension follows the same structure: the tension stated plainly, who's on each side, who's bridging the gap between AI-native and incumbent organizations, what's surprising, and provocations for the sprint.

---

# Layer 1: The Landscape Shift

## AI Is a Coordination Technology, Not Just a Productivity Tool

The dominant narrative about AI in organizations is: *do the same things, faster and cheaper.* This narrative is wrong — not because AI doesn't make things faster and cheaper (it does), but because it mistakes the side effect for the main event.

AI is a coordination technology. It changes the cost of organizing.

When the steam engine dropped the cost of physical power, it didn't just make existing workshops faster — it made the factory possible. When telecommunications dropped the cost of information transfer, it didn't just speed up existing companies — it made the multinational corporation possible. Each time a coordination cost drops dramatically, the optimal shape of an organization changes.

AI drops the cost of cognitive coordination — the work of synthesizing information, making routine decisions, translating between domains, monitoring processes, and generating structured output. When that cost drops toward zero, the economics of organizing shift in three specific ways:

**1. The minimum viable team shrinks radically.**

Cursor (Anysphere) has ~20 employees and generates $100M+ in annual recurring revenue. Midjourney has ~40 employees and generates $200M+. ElevenLabs has ~50 people and $80M+ ARR. These are not outliers — they represent a new structural category. Revenue per employee at AI-native companies runs 5-20x the SaaS benchmark of $200-300K. The roles that are *missing* are as telling as the roles that exist: no dedicated QA, no product management layer, no middle management, minimal marketing. The work those roles did hasn't disappeared — it has been absorbed into a smaller number of people augmented by AI.

**2. The boundary of the firm becomes negotiable.**

Ronald Coase won the Nobel Prize for explaining why firms exist: because the cost of coordinating activity inside a firm is lower than coordinating through the market. When AI drops coordination costs on both sides, the boundary moves. The share of new startups with a solo founder rose from 23.7% in 2019 to 36.3% in the first half of 2025. Over 44% of profitable SaaS businesses are now run by solo founders. Sam Altman has revealed that his "group chat with tech CEO friends" has a betting pool for the first one-person billion-dollar company. But this isn't just about smallness — Thierry Warin (HEC Montreal), writing in the *California Management Review*, argues that AI creates *new* transaction costs (hallucination management, output verification, model selection) even as it eliminates old ones. The firm doesn't disappear; it reconstitutes around different coordination problems.

**3. The hierarchy flattens — but not the way people think.**

A team of economists (Xu, Hou, Chen, and Xie) built a formal model showing that organizational span of control *contracts initially and then expands later* as AI advances. The immediate flattening narrative is wrong — the dynamics are non-monotonic. Early-career employment in AI-exposed occupations declined approximately 13% after 2022, while senior employment remained stable or rose. The hierarchy doesn't just flatten; it reshapes, with the middle compressed while the top and the edge gain relative power.

## The Cold Shower

Before going further, a necessary corrective.

A February 2026 NBER study surveyed nearly 6,000 senior executives across the US, UK, Germany, and Australia. Nine in ten reported *no impact* of AI on employment or productivity over the prior three years. Two-thirds of executives use AI but average only 1.5 hours per week. Apollo chief economist Torsten Slok observed: "AI is everywhere except in the incoming macroeconomic data."

Daron Acemoglu, the 2024 Nobel laureate in economics, estimates AI will increase GDP by 1.1-1.6% over the next decade — roughly 0.05% annual productivity gain. His concept of "so-so automation" describes technologies that cut labor costs without making work more efficient.

This is not a reason to ignore AI-driven organizational change. It is a reason to take it seriously — to distinguish between what's actually happening at the edge and what's hype, between structural shifts and temporary enthusiasm. The tension between the radical restructuring happening at AI-native companies and the near-zero measured impact at most incumbents is itself the most important finding. The gap is the story.

---

# Layer 2: The Tensions

## Tension 1: Compression vs. Capability Building

*AI lets you run lean. But lean can become hollow. Where is the line between efficient compression and dangerous hollowing?*

### The AI-Native Position

AI-native companies are built compressed from day one. Cursor's four MIT co-founders run a team of ~20 people generating $100M+ ARR. There is no traditional product management function — the founders collectively own product direction through what they call "taste-driven development." Midjourney's David Holz built a company around Discord, where the community *is* the marketing, support, and distribution organization. Pieter Levels (Levelsio) runs multiple profitable products generating millions in revenue as a single person, posting on X: "I'm a mass-produced one-person company. AI lets me do what used to take a team of 10."

These companies weren't compressed after the fact. They were born small. The compression isn't a cost play — it's a structural advantage. Fewer people means faster decisions, less coordination overhead, and stronger alignment.

### The Incumbent Position

The most aggressive incumbent compressor is Klarna. CEO Sebastian Siemiatkowski reduced headcount from 5,527 to ~3,422 (40%) primarily through attrition. The AI chatbot handled 2.3 million conversations in its first month, doing the work of 700 agents. Revenue grew 108%. Remaining employee pay rose from $126K to $203K. It looked like a triumph.

Then Siemiatkowski publicly admitted: **"We went too far. We focused too much on efficiency and cost. The result was lower quality, and that's not sustainable."** Klarna is now rehiring human staff.

Duolingo cut ~10% of its contractor workforce and replaced them with AI content generation. CEO Luis von Ahn stated: "We'd rather move with urgency and take occasional small hits on quality than move slowly and miss the moment." Users complained content felt "repetitive, robotic, or lacked the playful tone that made Duolingo iconic." Gross margins actually *dropped* due to AI compute costs. Von Ahn later admitted his AI-first memo "did not give enough context."

### The Bridge

**Shopify's Tobi Lutke** found the most elegant bridging mechanism. Rather than cutting headcount, he changed the decision process: "Before asking for more headcount and resources, teams must demonstrate why they cannot get what they want done using AI." AI competency is part of performance reviews. This is augmentation-first compression — it changes incentives rather than prescribing behavior. Teams self-compress where it makes sense. Shopify has not reported the mass quality failures seen at Klarna or Duolingo.

**Coinbase's Brian Armstrong** took a harder line but with specificity: he gave engineers one week to adopt AI coding assistants or face termination. By mid-2025, ~40% of daily code was AI-generated. But Armstrong isn't cutting roles — he's amplifying individuals through DRIs (Directly Responsible Individuals) who maintain accountability. Compression with accountability.

### The Surprise

Klarna's compression initially succeeded by every financial metric — revenue up, pay up, headcount down. The failure was invisible: it was in quality and trust, which are *lagging indicators.* **Financial metrics are leading indicators of compression success but lagging indicators of capability loss.** By the time the numbers show the problem, the institutional knowledge is already gone.

Also counterintuitive: Duolingo's AI-first move actually *increased* costs (compute) while *decreasing* quality. The assumption that AI replacement equals cost savings is not always true.

### How Might We...

- Distinguish between "fat" that can safely be compressed and "muscle" that looks like fat but is load-bearing institutional capability?
- Create leading indicators for capability loss before it shows up in financial metrics or customer satisfaction?
- Help leaders set a "compression floor" — the minimum human capability below which the organization becomes brittle?

---

## Tension 2: Autonomy vs. Coherence

*AI pushes decision-making power to the edges. But distributed power without shared context creates chaos. When everyone has superpowers, how do you stay coherent?*

### The AI-Native Position

McKinsey's 2025 research on the "agentic organization" describes a new paradigm: small teams of 2-5 people supervising 50-100 specialized AI agents running end-to-end processes. Organization charts pivot from hierarchy to "agentic networks or work charts based on exchanging tasks and outcomes." One manager with a small human team could orchestrate hundreds of agents running 24/7.

Perplexity's Aravind Srinivas keeps the company flat at ~50-60 people, with engineers expected to be full-stack across search infrastructure, ML, and product. As he said on the No Priors podcast: "The best thing about being an AI company is you don't need as many people. The worst thing is that everyone you do hire has to be exceptional."

### The Incumbent Position

**Valve Corporation** is the classic cautionary tale. Valve operates without formal managers, with employees choosing their projects. But co-founder Gabe Newell admitted the structure "fails to catch bad decisions early due to a lack of internal controls." Former employees describe a "pseudo-flat structure" with hidden hierarchy where personal relationships overshadow merit.

**Lattice** tried to treat AI agents as employees on its HR platform — with records, managers, and performance reviews. The backlash was immediate. Within three days they reversed course. The lesson: autonomy requires shared ontology. When the organization couldn't agree on what constituted a "worker," giving AI agents organizational autonomy was premature.

### The Bridge

The most surprising bridge comes from the U.S. military. Mission command doctrine — the framework for empowering subordinate decision-making — is built on "competence, mutual trust, shared understanding, commander's intent, mission-type orders, disciplined initiative, and risk acceptance." This is coherent autonomy: distributed execution within shared intent.

**Benjamin Jensen** (CSIS Futures Lab, Marine Corps University) wargamed three AI-enabled staff models: Networked (decentralized nodes), Relational (trust-based human-AI relationships), and Adaptive (self-reconfiguring based on mission). The Adaptive model proved most effective: "Smaller, faster staffs generate better options more quickly than larger legacy organizations."

The corporate equivalent of "commander's intent" is what McKinsey calls "high context sharing and alignment across agentic teams." But the military has been iterating on this for decades. The corporate world is reinventing what the military already knows.

### The Surprise

The most hierarchical institution in society has the deepest thinking about coherent autonomy. The military — not Silicon Valley — is the thought leader on how to distribute decision-making while maintaining strategic direction. Lt. Gen. (ret.) S. Clinton Hinote, the Air Force's former official futurist (now at RAND), led a 400-person team designing the framework for distributed, elastic command structures. His work on moving from centralized command posts to distributed decision-making directly parallels the corporate debate about flattening hierarchies.

### How Might We...

- Create the organizational equivalent of "commander's intent" — a coherence mechanism that enables autonomy rather than constraining it?
- Distinguish between productive autonomy and mere fragmentation before the chaos becomes visible?
- Scale the coordination mechanisms that work at 15-person companies to organizations of thousands?

---

## Tension 3: Speed vs. Judgment

*AI-native companies ship at a pace that terrifies incumbents. But speed without judgment creates damage that moves equally fast.*

### The AI-Native Position

AI-native companies have collapsed cycle times to a degree that breaks incumbent assumptions. Mistral shipped its first competitive model in four months with ~60 researchers. CEO Arthur Mensch: "We have a very strong team with people experienced enough to produce and deliver in a very short period of time." Coinbase saw over 500 pull requests go up in 15 minutes during an AI-assisted coding sprint.

### The Incumbent Position

Google rushed AI Overviews into Search and immediately produced errors: recommending users add glue to pizza (from satirical Reddit content), suggesting eating rocks daily, and confidently telling users the year was still 2024. The speed-judgment gap: AI systems couldn't recognize satire, and the organizational decision to ship before solving this was a judgment failure, not a technology failure.

A 2025 study of AI coding tools found that Devin AI correctly fixed only 13.86% of real-world GitHub issues end-to-end. Cursor's 2.1 release corrupted chat histories and worktrees. As one analysis put it: "2025 was the year of AI speed. 2026 will be the year of AI quality."

### The Bridge

**Anthropic's Responsible Scaling Policy (RSP)** is the exemplar. It uses AI Safety Levels modeled on biosafety levels — graduated standards requiring stricter security, red-teaming, and deployment controls as model capability increases. The approval chain is deliberately layered: internal assessment, executive approval from both CEO and Responsible Scaling Officer, governance notification to Board and LTBT. The fastest-moving AI company in terms of capability development has also built the most structured judgment apparatus. Speed and judgment are not on a spectrum — they can be orthogonal if you design for both.

**Stewart Brand's pace layers framework** (from *The Clock of the Long Now*) is being applied to AI organizational design. The insight: AI supercharges the fast layers (fashion, commerce) but ignores the slow layers (governance, culture) unless you deliberately build and reinforce them. Practitioners argue: "Your pace layer system becomes your substitute for organizational structure. If you don't intentionally design the slow layers, you don't have any."

**Productboard** articulates it sharply: "Velocity stops being the differentiator. Judgment is. With speed at their fingertips, product teams are now constrained by how clearly they can define the problem they are trying to solve. Without that clarity, speed only accelerates misalignment."

### The Surprise

The key is *structural* judgment (baked into process) rather than *individual* judgment (dependent on the decision-maker in the moment). Anthropic's RSP doesn't rely on any single person exercising good judgment under pressure — it creates a structural apparatus that forces judgment to happen regardless of time pressure. This is the lesson for incumbents: don't ask people to slow down; build structures that inject judgment at the right moments automatically.

### How Might We...

- Build organizational "pace layers" that let the fast layers move at AI speed while the slow layers maintain stability?
- Create "judgment infrastructure" that scales with the speed of AI-assisted output?
- Distinguish between problems where speed is the bottleneck and problems where judgment is the bottleneck?

---

## Tension 4: Roles vs. Flows

*AI-native organizations think in workflows, not job descriptions. Roles are fluid, recombined constantly. But humans need identity, career paths, and legibility.*

### The AI-Native Position

Guillermo Rauch (Vercel CEO) advocates for "taste" as the primary hiring criterion over raw technical skill. He describes a model where designers and engineers converge into a single "product craftsperson" role. Shawn "swyx" Wang (Latent Space) coined "AI Engineer" as a distinct role — neither traditional ML researcher nor traditional software engineer — and documented an entirely new professional category.

AI-native companies don't have job descriptions in the traditional sense. At Cursor, the founders function as player-coaches across everything. At Midjourney, David Holz's vision and direct community feedback drive product direction with no PM layer. The "role" is whatever the work requires this week.

### The Incumbent Position

**Ravin Jesuthasan** (Mercer) and **John Boudreau** (USC) wrote the foundational framework in "Work Without Jobs": decompose jobs into tasks, evaluate which tasks AI should do, identify where human judgment is needed, reconstruct around outcomes. **Josh Bersin** argues: "Jobs are giving way to skills as the currency of work. This pivot from jobs to skills will require us to rethink everything we know about work."

New platforms are emerging to enable this: **Reejig** (CEO Siobhan Savage) launched "Work Architecture" to "replace outdated job architectures." Across clients, Reejig mapped over 44,000 tasks and 36,000 skills, surfacing ~40% average AI potential across work and identifying >$7.4B in value opportunities. **Gloat** decomposes jobs into projects, tasks, and skills. **TechWolf** built a complete job architecture in two weeks using its own AI agent — a process that traditionally takes months.

McKinsey identifies new role types emerging in the agentic organization: **agent orchestrators** (design and supervise agent workflows), **hybrid managers** (lead blended human-agent teams), and **AI coaches** (help employees integrate AI into daily work).

### The Bridge

The bridge builders here are the platform companies — Reejig, Gloat, TechWolf, Draup — that are creating the infrastructure for flow-based work inside incumbent organizations. Savage's insight is crucial: "AI doesn't automate skills; it automates tasks." The unit of redesign is the task, not the role. But the task-level redesign has to connect back to something humans can build a career around.

### The Surprise

The biggest barrier to flow-based work isn't technology or management resistance — it's **HR systems.** Compensation, benefits, career ladders, performance reviews, and compliance frameworks are all built around static job descriptions. Moving to flows requires rebuilding HR infrastructure. The slowest-moving part of the organization is the binding constraint on the fastest-moving change. This is the pace layers problem in action.

### How Might We...

- Give people career identity and progression when their "role" changes quarterly?
- Redesign compensation systems for flow-based work where output is variable and roles are fluid?
- Maintain professional development and mastery when the "profession" keeps shifting?

---

## Tension 5: Internal vs. External

*AI collapses the boundary between what you build inside and what you orchestrate outside. Where does the organization end?*

### The AI-Native Position

The existence proof is already here. Midjourney: fewer than 40 people, $200M+ revenue, multi-billion-dollar valuation. Pieter Levels: a single person running multiple profitable products generating millions. The share of solo-founder startups is surging. These are tiny human cores orchestrating AI capabilities for millions of users, with no traditional departments at all.

Kai-Fu Lee (01.AI) articulates the endpoint: "You can completely use agents as Lego blocks. A Lego block that's HR, a Lego block that's legal, a Lego block that is finance, and then a Lego block for customer service. You can have a huge, giant Lego-created machinery that is your company agent, where the CEO interacts and manages the company."

### The Incumbent Position

Most incumbents are doing the opposite of what AI-native companies do — they're building *more* internal AI capability, not less. JPMorgan has over 2,000 AI/ML specialists and built LLM Suite internally. Goldman Sachs is restructuring around internal AI tools. The logic: in regulated industries, you can't orchestrate externally when compliance requires you to own the process end-to-end.

### The Bridge

**Thierry Warin** (HEC Montreal), writing in the *California Management Review*, updates Coase for the AI era: AI doesn't eliminate transaction costs — it transforms them. New costs emerge around model selection, prompt engineering, output verification, and hallucination management. An NBER working paper on "The Coasean Singularity" finds that "property rights ambiguity is the new transaction cost" and "trust becomes the scarce resource — as functional costs approach zero, trust commands premium prices."

**Palantir's "bootcamp" model** is a literal bridge-building service. They send teams into incumbent organizations for intensive 1-5 day engagements where they rebuild actual workflows on AI-native infrastructure. CEO Alex Karp: "The question isn't whether AI works. The question is whether your organization can absorb it."

### The Surprise

AI may not collapse the firm boundary — it may *move* it. Organizations that tried to become pure orchestrators discovered they needed more internal capability to manage AI effectively, not less. The new transaction costs (hallucination management, output verification) replace old ones. Trust — the most human of capabilities — becomes the ultimate competitive advantage precisely when functional costs approach zero.

### How Might We...

- Help organizations identify which capabilities are core (must be internal) vs. which can be orchestrated externally?
- Build trust as organizational infrastructure when the firm boundary becomes permeable?
- Manage the new transaction costs that AI creates even as it eliminates old ones?

---

## Tension 6: Transparency vs. Trust

*AI makes work visible at unprecedented granularity. Visibility can empower or surveil — the difference is in design and intent.*

### The AI-Native Position

AI-native organizations are built on radical transparency because they were born that way. Buffer (CEO Joel Gascoigne) has published all employee salaries publicly since 2013, including the formula for calculating them. This works because the transparency is *symmetrical* — everyone is visible, including leadership — and *equity-oriented* — designed to eliminate pay gaps, not maximize extraction.

### The Incumbent Position

**Amazon** has built what researchers call "a surveillance and enforcement stack designed not only to optimize logistics but to preempt solidarity, fracture trust, and atomize resistance." Monitoring includes 43+ Facebook groups, numerous subreddits, and Twitter keywords worldwide.

**Microsoft** launched Productivity Score in 2020, tracking individual employees' emails sent, chat frequency, and document participation. Backlash forced them to remove individual names. In 2025, they introduced Copilot usage benchmarks in Viva Insights — drawing immediate comparisons. 80% of U.S. companies now track employee performance digitally. Eight in ten employees report that monitoring erodes trust.

### The Bridge

Research by Van Zoonen, von Bonsdorff, and van der Heijden (2025, *Human Relations*) found the key distinction: **transparency *about* algorithms builds trust; transparency *through* algorithms erodes it.** When you explain how the AI system works and what it measures, trust increases. When you use AI to measure people, trust decreases. Same technology, opposite outcomes.

The principle: symmetrical visibility (everyone sees the same data, including leadership) empowers. Asymmetrical visibility (management watches workers, not vice versa) controls.

### The Surprise

The difference between empowering transparency and controlling surveillance is not about *what* is made visible but **who controls the visibility and for whose benefit.** Buffer's radical salary transparency and Amazon's algorithmic surveillance are the same mechanism — making work visible — with opposite outcomes. The variable is power dynamics and design intent.

### How Might We...

- Design AI visibility tools that are symmetrical — giving workers the same insight into organizational decisions that managers have into worker behavior?
- Create transparency standards that distinguish between empowering visibility and controlling surveillance?
- Ensure workers have ownership of the data generated about their own work?

---

## Tension 7: New Value vs. Optimization

*Most AI organizational changes are about doing the same things cheaper and faster. The real prize is creating things that couldn't exist before.*

### The AI-Native Position

**Recursion Pharmaceuticals** and **Insilico Medicine** didn't just optimize drug discovery — they redesigned the *organization* to make previously impossible science possible. Recursion employs computational biologists, data engineers, ML specialists, and software developers in roughly equal numbers to wet lab scientists — a fundamentally different org structure than any traditional pharma company. Insilico identified a novel target and designed a clinical candidate in 18 months versus the traditional 4-6 years. AI-designed molecules show 80-90% Phase I success rates versus 40-65% for traditional discovery. **The organizational structure IS the innovation.**

### The Incumbent Position

McKinsey's 2025 survey found that 80% of organizations using AI focus primarily on efficiency. Only the highest-performing organizations set growth or innovation as *additional* objectives. The optimization trap: AI makes efficiency gains so visible and measurable that they crowd out harder-to-quantify innovation investments.

**Axel Springer's Mathias Dopfner** eliminated hundreds of editorial positions at BILD, explicitly attributing it to AI. This is optimization masquerading as transformation — doing less of the same thing, not creating new things.

### The Bridge

BCG's 2025 agentic AI research found that the companies seeing the most value "often set growth or innovation as additional objectives, beyond the efficiency focus that 80% of respondents prioritize." A global consumer goods company rebuilt product innovation around meta-agents orchestrating worker agents, cutting cycle time by ~60% while improving product fit. The key finding: **workflow redesign — not AI tool adoption — is the biggest predictor of financial impact.** The organizational change matters more than the technology.

McKinsey's "ambidextrous organization" model suggests AI may enable simultaneous optimization in core operations (run by AI agents) and radical innovation (led by human teams focused on novel problems). But this requires deliberately designing the organization to support both modes, not hoping innovation happens alongside optimization.

### The Surprise

The companies creating genuinely new value with AI-driven organizational design are not Big Tech. They're biotech. Recursion's organizational model — computational-experimental fusion — represents a structural innovation that has no parallel in the tech industry. Meanwhile, the most prominent AI "transformations" at tech companies (Klarna, Duolingo) are cost optimization stories. **The industries least associated with AI culture are doing the most innovative organizational design with it.**

### How Might We...

- Help leaders distinguish between AI projects that optimize existing value and AI projects that create genuinely new value — and resource both appropriately?
- Design organizational structures that make innovation the *default* use of AI rather than the exception?
- Apply the Recursion/Insilico model of "computational-experimental fusion" to industries beyond pharma?

---

# Layer 3: The Leaders Map

## Structural Innovators

*People and organizations that have built fundamentally new organizational forms.*

**Liang Wenfeng** — Founder/CEO, DeepSeek (~150 employees, Hangzhou, China). Completely bottom-up work model with no fixed positions. Research groups form organically. More than 60% of the core team have math competition backgrounds. The company typically passes on candidates with more than 8 years' experience, actively discounting industry mental models. Liang's mantra: "unleash innovation speed and break through technological bottlenecks."

**Zhang Ruimin** — Founder/Chairman Emeritus, Haier (~80,000 employees, Qingdao, China). Eliminated the entire middle management layer — more than 12,000 employees removed — and replaced the pyramid with a network of 4,000+ microenterprises of 10-15 people each. The model is called RenDanHeYi. Each microenterprise has full CEO-level authority: decision-making, hiring, resource allocation. Now integrating AI through HomeGPT. "We removed the intermediate layer of more than 12,000 employees. After bureaucracy was eliminated, the organization was no longer hierarchical."

**David Holz** — Founder, Midjourney (~40 employees). Perhaps the most extreme revenue-per-employee ratio in tech history (~$5M/employee). No traditional office — the company was organized through Discord, which is also the product distribution channel. No CMO, no VP Sales, no support org. The community is the organization.

**Arthur Mensch** — CEO, Mistral AI (~200 employees, Paris). Built competitive frontier models with a fraction of OpenAI's headcount. "You don't need thousands of people to build frontier AI. You need the right dozens." Explicitly positions Mistral as a European sovereignty play — open-source-first, European data and compute.

**Dr. Gundbert Scherf & Torsten Reil** — Co-CEOs, Helsing (~600-1,000 employees, Munich/Paris/London). Organized as a tri-national defense AI company deliberately structured across Germany, France, and the UK. The multi-sovereign organizational structure is itself the competitive advantage — navigating European defense procurement boundaries that single-nation companies cannot.

## Value Creators

*People creating genuinely new value that wasn't possible without AI-driven organizational design.*

**Chris Gibson** — CEO, Recursion Pharmaceuticals. Redesigned pharma around computational-experimental fusion. Equal ratios of computational and wet lab scientists. AI-designed molecules showing 80-90% Phase I success rates. The organizational structure is the innovation.

**Alex Zhavoronkov** — CEO, Insilico Medicine. Novel target identification to clinical candidate in 18 months. The organization is built around AI-human integration from day one, not AI layered onto traditional pharma.

**David Ha & Llion Jones** — CEO and CTO, Sakana AI (~20 employees, Tokyo). Jones co-invented the Transformer. All three founders are former Google researchers who chose Tokyo over Silicon Valley. "AI models could grow the way nature does" — the philosophy shapes both research and organizational structure. Japan's most valuable unicorn.

**Kai-Fu Lee** — CEO, 01.AI (Beijing). Bridges Chinese and Western perspectives uniquely (former head of Google China, Microsoft Research Asia). His "Lego blocks" theory of agent-composed organizations: "A Lego block that's HR, a Lego block that's legal, a Lego block that is finance... You can have a huge, giant Lego-created machinery that is your company agent."

## Bridge Builders

*People successfully translating AI-native practices into incumbent organizations.*

**Tobi Lutke** — CEO, Shopify. The "prove AI can't do it" mandate before approving headcount is the most elegant bridging mechanism discovered so far. Changes incentives rather than prescribing behavior. AI competency in performance reviews. Augmentation-first, not replacement-first.

**Ethan Mollick** — Professor, Wharton. Author of *Co-Intelligence* (2024). Arguably the most important bridge builder in the advisory space. His centaur/cyborg/self-automator framework gives practitioners vocabulary for organizational design choices. His Substack "One Useful Thing" is the most influential independent voice on AI and work. When a Fortune 500 CHRO decides to redesign roles around AI, there's a decent chance they've read Mollick.

**Alex Karp** — CEO, Palantir. The bootcamp model — sending teams into incumbent organizations for 1-5 day intensive engagements to rebuild actual workflows on AI-native infrastructure — is a literal bridge-building service. "The question isn't whether AI works. The question is whether your organization can absorb it."

**Mustafa Suleyman** — CEO of Microsoft AI. Brought from Inflection AI to lead Microsoft's AI efforts under a single organization rather than having AI dispersed across product groups. A bridge hire: someone from the AI-native world leading transformation inside a 220K+ person incumbent.

**Ravin Jesuthasan** — Global Transformation Leader, Mercer. Co-author of "Work Without Jobs." The foundational framework for decomposing jobs into tasks and reconstructing around outcomes. Operating at the intersection of AI capability and workforce architecture.

**Siobhan Savage** — CEO, Reejig. Building the infrastructure layer for flow-based work inside incumbent organizations. "AI doesn't automate skills; it automates tasks." Mapped 44,000+ tasks and 36,000+ skills across clients.

**Benjamin Jensen** — Senior Fellow, CSIS Futures Lab; Professor, Marine Corps University. Wargamed AI-enabled organizational models (Networked, Relational, Adaptive). The Adaptive model proved most effective. His work translates military organizational design directly to corporate questions about distributed decision-making.

## Unconventional Thinkers

*People bringing fresh perspectives from outside the mainstream AI/business conversation.*

**Matt Beane** — UC Santa Barbara; Digital Fellow at Stanford and MIT. Author of *The Skill Code* (2024). His argument: AI is destroying the apprenticeship pipeline. The concept of "shadow learning" — workers driven underground to develop skills because AI-monitored environments punish experimentation. While everyone talks about AI replacing tasks, Beane focuses on the organizational *reproduction* problem: how do you create the next generation of experts if AI eliminates the learning pathway?

**Phanish Puranam** — INSEAD. Leads the "Organizations and Algorithms" research programme. When AI adoption erodes the non-monetary benefits of work (autonomy, relatedness, competence), organizations must offset this with higher wages, more supervision, or accept lower discretionary effort. The rare organizational theorist treating AI as something that reshapes the attractiveness of organizational membership itself.

**Reza Baygi & Marleen Huysman** — VU Amsterdam. GenAI rewires the social fabric of organizations — the pathways along which expertise, trust, and collegiality flow. Three organizational pathologies: "polymaths" (people who appear to know everything), "oracles" (AI outputs treated as authoritative truth), and "sirens" (personalized AI that seduces workers away from organizational knowledge flows). Their GenAI@Work project studies eight real organizations.

**Scott Page** — University of Michigan; Santa Fe Institute. The "Inferential Trilemma": when AI produces a surprising recommendation for a high-stakes decision, organizations cannot determine whether the AI is (1) correct and using novel reasoning, (2) hallucinating, or (3) misaligned with actual goals. AI is most dangerous precisely where it could be most valuable.

**Jaime Teevan** — Chief Scientist, Microsoft. Five years of longitudinal research on AI and work. Individual AI productivity gains plateau quickly. The next frontier is *collective productivity* — how teams "get better together." AI agents make team structure "elastic and no longer fixed by human headcount."

**Lt. Gen. (ret.) S. Clinton Hinote** — RAND Corporation (formerly Air Force Deputy Chief of Staff for Strategy). Led a 400-person team designing the future Air Force's command structure. His framework for moving from centralized command posts to distributed, elastic command structures directly parallels corporate debates about hierarchy.

**Aaron Dignan** — Founder, The Ready / Brave New Work. His company Murmur Labs pivoted to AI-powered organizational decision-making tools. The Ready converted to an Employee Ownership Trust in 2025. Comes from the responsive organization movement — now applying those principles to AI-era org design.

## Contrarians

*People with credible arguments against the prevailing narrative.*

**Daron Acemoglu** — MIT (Nobel Laureate, 2024). AI will increase GDP by only 1.1-1.6% over the next decade. His concept of "so-so automation": technologies that cut labor costs without making work more efficient. "My argument is that we currently have the wrong direction for AI."

**Kristina McElheran** — University of Toronto, with affiliations at Harvard and Stanford. Has the actual Census Bureau firm-level data. Most firms deploying AI do so merely to cut costs and shrink headcounts rather than redesign work. "AI's limitations are less about code and more about context — tax systems, labor laws, management decisions."

**David Autor** — MIT. Distinguishes between automation AI (eliminates expertise) and augmentation AI (force multiplier for expertise). The consequences depend on the *design and integration* of the technology, not the technology itself. AI could either devalue human expertise or elevate it — the difference is a design choice.

**The NBER 6,000-CEO Study** (Davis, Yotzov, Barrero, Bloom, et al., February 2026). Nine in ten executives reported no AI impact on employment or productivity over three years. The strongest empirical counter to "AI is already transforming organizations."

**The Middle Management Persistence Paradox.** Despite decades of predictions about the end of middle management, the proportion of middle managers grew from 9.2% of the US labor force in 1983 to 13% in 2022. The organizational hierarchy thesis has been wrong before.

---

# Appendix: Source Trail

## Where We Went — and Where to Keep Going

### Podcasts and Interviews (Operator Perspectives)
- **No Priors** (Sarah Guo, Ravi Gupta) — Best source for AI-native founder interviews on organizational structure
- **Latent Space** (swyx) — Most detailed ongoing record of how AI-native companies actually operate
- **Lenny's Podcast** (Lenny Rachitsky) — Covers product org structure at AI companies
- **Invest Like the Best** (Patrick O'Shaughnessy) — Long-form interviews with founders and investors
- **The Pragmatic Engineer** (Gergely Orosz) — AI's impact on engineering org structure

### Substacks and Long-Form Writing
- **One Useful Thing** (Ethan Mollick) — Most influential independent voice on AI and work
- **Latent Space** (swyx) — AI engineering and organizational patterns
- **ChinaTalk** — Deep coverage of Chinese tech organizational models
- **Winterspeak** — Economic analysis of AI and firm boundaries
- **Workforce Futurist** (Andy Spence) — Future of work trends

### Academic and Research Sources
- **Santa Fe Institute ACtioN** — Complexity science applied to organizational AI decisions (Scott Page)
- **GenAI@Work** (VU Amsterdam, Marleen Huysman) — Ethnographic study of eight organizations
- **MIT Shaping the Future of Work Initiative** — Cross-disciplinary AI/labor/org research
- **INSEAD Organizations and Algorithms** (Phanish Puranam) — AI's impact on organizational attractiveness
- **Stanford HAI / Digital Economy Lab** — AI economic and organizational impacts
- **Microsoft New Future of Work Initiative** (Jaime Teevan) — Five years of longitudinal AI/work research

### Military and Defense
- **CSIS Futures Lab** (Benjamin Jensen) — Most actionable military org design thinking
- **SCSP Defense Paper Series** — AI and command/control restructuring
- **War on the Rocks** — De facto salon for military AI organizational debate
- **NATO C2 Centre of Excellence** — AI in military command systems
- **Army War College** (C. Anthony Pfaff) — "Trusting AI" monograph on expertise boundaries

### Chinese Tech and Organization
- **ChinaTalk** — DeepSeek organizational analysis, translated primary sources
- **Value Added** — How new labor practices propelled DeepSeek
- **Pandaily** — Kai-Fu Lee's "Lego blocks" organizational theory
- **EqualOcean** — ByteDance organizational structure analysis
- **ThoughtWorks (Zhongtai)** — Alibaba's middle platform strategy documentation

### European Ecosystem
- **Sifted** — European startup organizational models
- **re:publica** — DeepL and European AI identity
- **McKinsey Europe interviews** — Arthur Mensch on Mistral
- **Contrary Research** — Helsing business breakdown
- **Orrick / Bird & Bird** — German co-determination and AI legal frameworks

### Organizational Design Platforms and Practitioners
- **Reejig** (Siobhan Savage) — Work architecture and task-level redesign
- **Gloat** — Job decomposition and internal talent marketplace
- **TechWolf** — AI-built job architecture
- **Josh Bersin** — Job redesign frameworks and tool landscape
- **Ravin Jesuthasan** — "Work Without Jobs" framework

### Policy and Economics
- **NBER Working Papers** — Firm-level AI adoption data, Coasean analysis
- **California Management Review** — Warin's Coase-to-AI analysis
- **AI Now Institute** — Algorithmic management and surveillance frameworks
- **World Economic Forum** — Future of Jobs Report 2025

---

## Cross-Cutting Themes

Six patterns emerged across the research that cut across all seven tensions:

**1. The Klarna Parabola.** Initial compression looks successful on every metric. The capability loss is a lagging indicator. By the time the numbers show the problem, the institutional knowledge is already gone. This pattern repeats across Tensions 1, 3, and 7.

**2. Military Wisdom.** The most hierarchical institution in society has the deepest thinking about coherent autonomy, speed with judgment, and distributed decision-making. Corporate AI transformation would benefit enormously from studying mission command doctrine, adaptive staff models, and pace layer thinking.

**3. HR as the Binding Constraint.** Across Tensions 1, 4, and 6, HR systems (job descriptions, compensation, performance reviews, career ladders) emerge as the slowest-moving component and the binding constraint on transformation. The fastest-moving change (AI-driven work redesign) is bottlenecked by the slowest-moving infrastructure.

**4. Trust as the New Scarce Resource.** When AI makes functional costs approach zero, trust becomes the competitive advantage. This appears in firm boundary economics (Tension 5), transparency design (Tension 6), and the Klarna reversal (Tension 1). Trust is the asset that appreciates as everything else gets cheaper.

**5. Organizational Design IS the Innovation.** The most transformative uses of AI are not tool adoptions but organizational redesigns. Recursion's computational-experimental fusion, Anthropic's RSP, Haier's RenDanHeYi, the military's adaptive command model — in each case, the organizational architecture is the primary innovation.

**6. The Pace Layers Imperative.** Organizations that accelerate their fast layers (shipping, coding, content) without investing in their slow layers (governance, culture, trust) consistently produce the worst outcomes across all seven tensions. Klarna, Duolingo, and Google AI Overviews all accelerated the fast layers while ignoring the slow ones.

---

*Research compiled March 31, 2026. First layer of a multi-session research effort.*
*A BuildFirst internal document.*

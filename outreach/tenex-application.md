# Tenex — AI Strategist · Application Answers

> Drafted 2026-06-18 in Adam's voice (direct, concrete, no clichés). Based on the
> Aeon drilling-report engagement + the Agentech sales platform. Adam to review/edit
> before submitting. No fabricated metrics — add real numbers where you have them.

---

## Q1. Describe a time you owned a complex client or stakeholder relationship while juggling competing priorities. What did you own, how did you keep stakeholders aligned, and what was the outcome?

At Aeon, I owned an engagement with a regionally top-tier upstream oil & gas operator (nine-figure budget) end to end — the executive relationship, the discovery, the scope, and the rollout — while running our other client work and a build that depended on my cofounder's bandwidth.

The relationship was complex because the stakeholders didn't all want the same thing. I ran a discovery workshop spanning the COO down to individual field engineers. The COO was focused on a drilling budget about to double that the team couldn't staff for; the engineers cared about the hours they personally lost every day standardizing contractor drilling reports and hunting for field issues. I owned reconciling those into one build: automated morning reporting, plus a tool that builds a strategy for a new well from their historical offset-well data.

I kept everyone aligned by never letting them guess where things stood. We set clear checkpoints, ran feedback sessions on real MVPs early and often instead of saving a big reveal for the end, and I sent daily and weekly updates so the COO saw progress against the timeline and the engineers saw their input showing up in the product. When priorities competed — their urgent field needs versus our build sequence — I made the tradeoffs explicit and let them weigh in rather than deciding in a vacuum.

Outcome: we shipped, trained the team on it, and converted into an ongoing support-and-iteration contract. The reporting that used to eat hours a day is automated, and the system is built to absorb the doubled drilling workload they were about to drown in.

---

## Q2. Describe your experience translating between senior business stakeholders and technical teams. How do you adapt the way you communicate for each audience?

It comes down to giving each side the version of the truth they can actually act on.

With senior business stakeholders, I lead with the outcome. What bottleneck are we removing, what will be different about how their team works, and what it's worth. They don't need the architecture — they need to know the daily drilling-report grind goes away and the system scales to a doubled budget. I keep it in their language: time, cost, risk, capacity.

With the technical team, I get specific, because vagueness is what kills a build. I translate the business ask into an exact spec: What's the input, and in what format? What has to happen to it inside our system? What's the output? What do we need to connect to, what data will we have access to, and how does it reach us? A lot of my job in discovery is pulling all of that out of the client so my cofounder can build against a real spec instead of a wish.

The skill is holding both views at once — sitting with a CEO one hour and a field engineer the next — and making sure the thing the executive was promised is the same thing the technical team is actually building.

---

## Q3. Describe an AI agent/workflow/app you built (internal tool is fine).

I'll give you two — one I built solo, and one we shipped to a client at Aeon.

### Agentech sales operations platform (built it personally)

**What it does + who used it.** A Claude-based operations platform that runs the daily workflow of Agentech's sales team. The reps used it every day.

**Inputs → outputs.** It consumes HubSpot CRM data, Fathom call transcripts, and Google Drive/Gmail/calendar, and produces: (1) a daily morning brief on each active client — prior-day meetings turned into to-dos and drafted follow-up emails on a 24-hour SLA; (2) meeting prep that pulls all prior context and builds the next agenda around what's still unknown (economic buyer, price sensitivity, timeline); and (3) drafted proposals/SOWs generated from the full conversation history plus our internal policy and precedent, routed to the rep for review.

**Tooling.** Claude as the LLM, integrated across HubSpot, Fathom, Google Workspace, and our contract software.

**Link.** Internal tool — no public demo.

### Aeon — drilling-report + offset-well system (shipped to a client)

**What it does + who used it.** For an upstream oil & gas operator, a system that ingests contractor daily drilling reports arriving in every format and auto-generates their exact standardized morning reporting (BHA analysis, depth-vs-days curves, field callouts), plus a tool that designs a strategy for a new well from their historical offset-well data and explains the why behind it. Used by their drilling and operations team.

**Inputs → outputs.** Inputs: daily drilling reports in many formats, and historical offset-well report data. Outputs: standardized morning reports and visuals with surfaced field issues, and a recommended strategy for a new well with the reasoning — compressing a weeks-long manual analysis into minutes.

**Tooling.** Built on the modern agentic stack (Claude Code, GitHub) with my cofounder, a CS PhD, on the build.

**Link.** Client-confidential — no public demo.

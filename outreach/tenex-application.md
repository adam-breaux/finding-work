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

The clearest one I can walk you through is a sales operations platform I built — by myself — for Agentech, an AI-insurance company I helped build from zero.

The problem was the reps' mornings. Every day started the same way: re-reading yesterday's call transcripts, digging through HubSpot and email to reconstruct where each deal stood, then trying to remember what they'd promised to whom. Proposals were worse — a rep would sit down to write a SOW and have to reassemble the entire conversation history plus our internal pricing and policy from scratch. The actual selling kept getting pushed to the afternoon.

So I built a Claude-based platform that did that work for them. It plugged into the systems where the truth actually lived — HubSpot for pipeline, Fathom for call transcripts, and Google Drive, Gmail, and calendar for everything around them — and turned all of it into three things the reps used every day:

- **A morning brief on each active client.** It read the prior day's meetings and turned them into a clean list of to-dos and drafted follow-up emails, ready before the rep sat down — on a 24-hour SLA so nothing slipped.
- **Meeting prep.** Before a call, it pulled every piece of prior context and built the next agenda around what we still *didn't* know — who the economic buyer was, how price-sensitive they were, what the real timeline looked like — instead of around what we'd already covered.
- **Proposal and SOW drafting.** This was the big one. It read the full history of a prospect's conversations alongside our internal policy and precedent, drafted the proposal, and routed it to the rep to review and send — so a document that used to eat an afternoon started life as a near-final draft.

Inputs in: HubSpot, Fathom transcripts, Gmail, Drive, calendar, and our contract software. Outputs out: morning briefs, meeting agendas, and drafted proposals and emails. The LLM was Claude, wired across all of those integrations. It's an internal tool, so there's no public demo to link.

What I'm proudest of isn't the integrations — it's that the reps actually used it. I built it close to them, watched where it got things wrong, and kept iterating until the morning brief was the first thing they opened instead of something they ignored.

I'm now doing the same kind of work at Aeon, the AI company I co-founded. For an upstream oil & gas operator, we built a system that ingests their contractor drilling reports — which arrive in every format imaginable — and auto-generates their exact standardized morning reporting (BHA analysis, depth-vs-days curves, field callouts), plus a tool that designs a strategy for a new well from their historical offset-well data and explains the reasoning behind it. Inputs: messy multi-format drilling reports and historical well data. Outputs: clean morning reports with the field issues surfaced, and a defensible strategy for the next well. Built on the agentic stack — Claude Code and GitHub — with my cofounder, a CS PhD, on the build.

Same pattern both times: find the task a smart team is grinding through by hand, and hand it to a system that does it in minutes.

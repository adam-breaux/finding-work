# finding-work — Adam Breaux's job-search system

This repo is a Claude-operated job-search assistant. It **searches** for roles,
**refines** that search over time, and maintains a **knowledge base** about Adam,
what fits, and how he answers questions. It does **not** auto-apply or auto-fill
anything — Adam stays in control.

## At the start of any session
Read these so you have full context:
- `knowledge-base/profile.md` — who Adam is, what he wants, his story (the intake interview).
- `knowledge-base/fit-criteria.md` — the 0–100 scoring rubric for any role.
- `knowledge-base/voice-guide.md` — how everything written for Adam should sound.
- `knowledge-base/decisions-log.md` — what's been learned about fit so far.

## The knowledge base (`knowledge-base/`)
| File | Purpose |
|---|---|
| `profile.md` | Master profile from the intake interview. Source of truth on Adam. |
| `fit-criteria.md` | Weighted scoring rubric + dealbreaker gates. |
| `voice-guide.md` | Tone/voice for resumes, outreach, answers. |
| `opportunities.md` | Live pipeline of roles found, scored, and tracked. |
| `decisions-log.md` | Why roles fit / didn't — the learning loop. |
| `answer-bank.md` | Reusable answers to common VC/CoS prompts (to be developed). |
| `network.md` | Connectors, references, warm-intro map, outreach log. |

## Resumes (`resumes/`)
- `master.json` — complete structured resume (source of truth).
- `variants/*.json` — role-tailored cuts (trim/reorder only; never fabricate).
- `render_resume.py` — renders any JSON to a clean `.docx`. Usage:
  `cd resumes && python3 render_resume.py variants/<name>.json -o output/AdamBreaux_<Name>.docx`
- `output/*.docx` — send-ready resumes. `AdamBreaux_Current_reference.docx` is Adam's original.
- Requires `python-docx` (`pip install python-docx`).

## Workflows (slash commands in `.claude/commands/`)
| Command | What it does |
|---|---|
| `/find-roles [focus]` | Sweep sources, score against the rubric, log hits, report a shortlist. |
| `/score-role <url/JD>` | Deep-dive one role: scored breakdown + tailoring notes. |
| `/tailor-resume <role>` | Build a role-tailored `.docx` from the master. |
| `/draft-outreach <who> [--flags]` | Warm-intro / cover letter / LinkedIn note in Adam's voice. |
| `/log-decision <role> <verdict>` | Record a fit/no-fit reaction into the learning loop. |
| `/refine-search` | Roll decisions up into sharper fit criteria (with approval). |

## Operating rules
- **Never auto-apply or submit anything.** Search, score, draft, advise.
- **Never fabricate** experience, metrics, or comp. Use only what's in `profile.md` / `master.json`; reframe and reorder, don't invent.
- **Geography is fixed:** Tulsa-anchored. Hybrid-to-a-hub (Dallas/Austin/Denver) or remote only. Never surface relocation-required roles as fits.
- **Equity/carry is a hard requirement.** No-ownership roles are gated out.
- **Keep the knowledge base current and committed.** After any workflow that changes files, commit with a clear message.
- The search should get **sharper over time** — read the decisions log before each new sweep.

## Roadmap / not yet built
- Automated source pulls via APIs/scrapers — see `integrations/README.md` (designed, deferred).
- Developed answer bank (deferred during intake).

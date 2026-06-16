# finding-work

A personal, Claude-operated job-search assistant for Adam Breaux. It finds roles
that fit, gets sharper over time, and keeps a knowledge base of what fits, what
doesn't, and how Adam answers questions — then helps adapt resumes and outreach fast.

It does **not** auto-apply. It searches, scores, drafts, and advises.

## Quick start (in a Claude Code session here)
1. `/find-roles` — sweep sources and get a scored shortlist.
2. `/score-role <url>` — deep-dive any role you like.
3. `/tailor-resume <role>` — get a tailored `.docx`.
4. `/draft-outreach <person/firm>` — get a warm intro or cover letter in your voice.
5. `/log-decision <role> <fit|no-fit>` — teach it, so the next sweep is sharper.

## What's where
- `knowledge-base/` — your profile, fit rubric, voice, pipeline, decisions, network.
- `resumes/` — structured master + tailored variants + `.docx` renderer.
- `.claude/commands/` — the workflows above.
- `integrations/` — automated source-pull layer (designed, deferred).
- `CLAUDE.md` — full operating guide for the assistant.

See `CLAUDE.md` for details.

# Integrations (designed, deferred)

Today `/find-roles` runs searches that Claude performs during a session and writes
results into `knowledge-base/opportunities.md`. That works immediately and needs no
credentials. This folder is where **automated source pulls** will live when we add them.

## Planned integration layer
A small, uniform interface so any source can feed the same scoring pipeline:

```
fetch(source, query) -> [ {firm, title, location, model, comp, url, posted_at, raw} ]
```

Each adapter normalizes its source into that shape; the existing rubric in
`fit-criteria.md` scores the results identically regardless of source.

### Candidate sources (priority order for Adam's VC focus)
1. **Getro / Consider talent networks** — many VC firms post portfolio + fund roles here; some have feeds/APIs.
2. **John Gannon's VC job board** — long-running list of VC/PE openings.
3. **LinkedIn Jobs** — broadest coverage; needs API access or careful, ToS-compliant collection.
4. **Wellfound (AngelList Talent)** — startup + some investor roles.
5. **Individual fund career pages** — highest-signal; often need lightweight per-site scraping.
6. **Family-office / CVC / PE boards** — secondary targets per Adam's scope.

## Requirements before building
- Outbound network access from the run environment.
- API keys / tokens where applicable (store as env vars, never commit secrets).
- A scheduler if we want unattended sweeps (e.g., the `/loop` skill or a cron-style trigger).

## Why deferred
Adam chose "add API integrations later." The system is fully usable now with
Claude-run searches; adapters can be added here without changing the rubric,
trackers, or commands.

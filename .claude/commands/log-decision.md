---
description: Record Adam's reaction to a role so the search learns
argument-hint: "<firm/role> <fit | no-fit | maybe> [why]"
---

Capture a decision into the learning loop. Input: "$ARGUMENTS".

## Steps
1. **Parse** the firm/role, the verdict (FIT / NO-FIT / MAYBE), and Adam's reasoning. If reasoning is thin, ask one sharp follow-up to get the real signal ("what specifically made it a no?").
2. **Append** a dated entry to `knowledge-base/decisions-log.md` using its format, capturing Adam's actual words and the underlying signal.
3. **Update** the role's status in `knowledge-base/opportunities.md` (→ PASSED / pursuing / DISQUALIFIED).
4. **Note the criteria implication** in the entry — what this suggests about weighting. If a clear, repeated pattern has emerged (2+ consistent signals), tell the user it may be time to run `/refine-search`.
5. Commit both files.

Keep it fast — this should be a 10-second habit for Adam after each role.

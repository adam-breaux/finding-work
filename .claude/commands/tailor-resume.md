---
description: Build a role-tailored .docx resume from the master
argument-hint: "<firm / role, or path to a role block in opportunities.md>"
---

Produce a tailored resume for a specific role. Input: "$ARGUMENTS".

## Steps
1. **Gather the target.** Pull the role's requirements (from the opportunities.md block, a pasted JD, or a URL). Identify the 3–5 things this employer most wants.
2. **Start from the master.** Read `resumes/master.json` (and `resumes/variants/vc-investor.json` if it's an investor role — closer starting point).
3. **Tailor the data, not the layout.** Copy to `resumes/variants/<slug>.json` and edit:
   - Rewrite the summary to mirror the role's priorities (in Adam's voice — see `knowledge-base/voice-guide.md`).
   - Reorder/emphasize the most relevant experience and bullets first.
   - Adjust the skills list to surface what this role values.
   - **Never fabricate.** Only use facts from `profile.md` / `master.json`. Trim, reframe, reorder — don't invent.
4. **Render:** `cd resumes && python3 render_resume.py variants/<slug>.json -o output/AdamBreaux_<Slug>.docx`
5. **Deliver** the .docx to the user with `SendUserFile`, plus a 2–3 line summary of what you changed and why.
6. Commit the new variant JSON and output.

Keep it tight (target ~1 page). Concrete, metric-driven, no clichés.

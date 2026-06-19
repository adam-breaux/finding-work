# Opportunities Tracker

> The live pipeline. `/find-roles` appends scored hits here; `/score-role` deep-dives one.
> Status flows: `NEW → REVIEWING → APPLIED → INTERVIEWING → OFFER → CLOSED` (or `DISQUALIFIED` / `PASSED`).
> Keep newest at top. When a role's status changes, update its row and add a dated note.

## How to read the score
Fit Score is 0–100 per `fit-criteria.md`. ⭐ = warm-intro path exists.

---

## Active pipeline

> ✅ **LIVE-STATUS VERIFICATION PASS (2026-06-17).** ATS + LinkedIn hosts were added to the egress
> allowlist (`boards-api.greenhouse.io`, `api.lever.co`, `api.ashbyhq.com`, `jobs.ashbyhq.com`,
> `www.linkedin.com`), so live status was machine-checked for the first time. Results:
> - **❌ Confirmed CLOSED** (LinkedIn returns "No longer accepting applications", posted 1–2 yrs ago):
>   Perot Jain Associate (`3919688347`) & Principal-SF (`3534871143`), LiveOak Associate (`3908892921`),
>   and **Trust Ventures** Investment Analyst/Associate (`3758952878`) — the last one disproves the
>   earlier "verified live" note.
> - **No directly-attributable live posting** turned up on LinkedIn's public guest search for any of:
>   Perot Jain, LiveOak, Silverton, Trust, HOLT, SPLY, Capital Factory, TYH, Paperboy, Amboy, Ironspring.
> - **8VC** (Ashby `8vc`): 9 live reqs confirmed, but all portfolio-company or internal-ops — **no fund/CoS fit.**
> - **Still un-machine-verifiable** (no Greenhouse/Lever/Ashby board; app host not allowlisted — needs a
>   human click): Silverton, HOLT, SPLY (splycapital.com), TYH, Paperboy (paperboyventures.com),
>   Amboy (lovable.app), Capital Factory (Getro board). **SPLY** stays confirmed-live via Adam's own conversation.
> **Bottom line: none of the archive-sourced postings are live. Treat the TX funds as relationship targets, not open reqs.**

| Date found | Firm | Role | Loc / Model | Score | Status | Notes |
|---|---|---|---|---|---|---|
| 2026-06-19 | **M12 (Microsoft)** | Associate (CVC, IC3) | SF HQ + Seattle · **work model unstated → must ask** | **~78** | 🟢 PREPARING (Adam applying) | Microsoft's corporate VC arm (100+ cos since 2016). Sectors: **AI, B2B SaaS, cloud infra, cybersecurity, DevOps, gaming/web3** — his B2B-SaaS + frontier-AI background is the bullseye, NOT his hard-tech thesis. JD = thesis-building + market research + sourcing + diligence (financial / unit-economics / **valuation modeling multiple methods**) + IC memos + portfolio support + thought-leadership content. Req: BA + **3+ yrs venture investing OR equivalent** + **1+ yr on a deal team** (Adam: ~3 yrs venture/ops + Atento diligence on Core Fund I deals — defensible reach). **Title "Associate" below his Sr-Assoc floor → title-flex applies (Microsoft = unambiguously top-tier).** Comp **$113.3K–$187.4K** base (SF/NYC band) + bonus + RSUs → top hits his band. **Geo = the live risk:** SF HQ + Seattle, no remote language → clarify work model (Tulsa-anchored) before/at recruiter contact; per Tenex/Toyota precedent, pursuing a top-tier firm despite geo. Tailored resume built (`variants/m12.json` → `output/AdamBreaux_M12.docx`). **Key tailoring call: do NOT lead with the 'AI-SaaS-is-un-investable' thesis — M12 invests there; reframe his thesis work as research/thesis-building muscle.** |
| 2026-06-18 | **Tenex** | AI Strategist | NYC (**onsite** per Ashby) · ~monthly client travel | **~79** | ✅ **APPLIED 2026-06-18** | **Off the VC thesis, but the best *experience* match in the pipeline** — via **Aeon**, Adam's co-founded AI consulting practice (he owns discovery + the client; cofounder ships the build = their strategist + forward-deployed-engineer model). Applied-AI strategy for the Fortune 500; **Anthropic + OpenAI formal partners.** Comp **$150–180K base + quarterly bonus** + possible equity. **Geo = the live risk:** Ashby workplaceType=OnSite NYC — clarify remote/arrangement (Tulsa-anchored). Tailored resume + 3 application answers submitted. Ashby `tenexlabs`. |
| 2026-06-17 | **Toyota Ventures** | VC Associate (Frontier Fund) | **Remote-eligible (US)** · SF Bay Area HQ | ⭐ **85** | ✅ **APPLIED 2026-06-17** | **Best find of the VC sweep.** $800M+ deep-tech/climate fund (Joby, Stoke Space, Apex Space, Pickle Robot, Intuition Robotics, e-Zinc). Sources/screens **AI, advanced materials, automation & robotics, space tech** = **sector bullseye** for his hard-tech/physical thesis + 100 deep-tech founder interviews + SBIR/STTR fluency. **JD: "remote work within other U.S. cities is possible" → Tulsa-compatible.** Top-tier firm → title-flex applies for "Associate." Req: degree + **min 4 yrs** (he's ~3 — slight reach, defensible) + deep-tech understanding + cap tables/financials. Comp undisclosed (base + annual cash bonus). **Applied 2026-06-17.** Live, 1 wk old, 38 applicants (LinkedIn 4425168501). |
| 2026-06-17 | Circle (Circle Ventures) | Director, Circle Ventures | **Dallas–Fort Worth** · remote-friendly (posted in 10 metros) | ~48 | ⚠️ STRETCH · 12+ yr gap | CVC arm of Circle (USDC issuer, public co). **Geo + comp are excellent:** Dallas-Fort Worth hub, base **$212.5K–$272.5K**. **But the bar is 12+ yrs of venture investing / corp-dev / IB** — this is a Partner-level seat far above Adam's ~3 yrs; not a realistic application. Sector = fintech / crypto / stablecoin (off hard-tech). Log as aspirational / firm-on-radar only. Live, 3 days old (LinkedIn 4375560558). |
| 2026-06-17 | Schematic Ventures | VC Principal | **San Francisco (in-person required)** | 20 `DISQUALIFIED (geo)` | ❌ relationship / sector-watch | Solo-GP (Julian Counihan) early-stage fund — **"technology that makes and moves the world"** (supply chain / industrial / logistics deep tech) = **strong sector match.** Principal w/ path to partnership; 2–4+ yrs VC exp (he fits the years). **But JD: "seeking a full-time Principal in San Francisco… deeply plugged into the SF technology/startup/AI community" → SF-required, SF-network ask → trips the relocation gate.** No remote language. Great thesis-match firm for a future warm relationship, not an application. Live, 2 wks old (LinkedIn 4419352772). |
| 2026-06-17 | Samsung Next | Investor — AI & Robotics | Mountain View, CA · **hybrid 3–4 days/wk** | 20 `DISQUALIFIED (geo)` | ❌ PASSED | Robotics sector bullseye + base **$175K–195K**, but **requires in-office 3–4 days/wk in Mountain View** (relocation gate) and prefers a **CS/engineering degree** (he has Exercise Science BS + MBA). Geo kills it. Live, 2 wks old (LinkedIn 4420635190). |
| 2026-06-17 | Booz Allen Ventures | VC Associate (CVC) | Denver, CO · hybrid (confirm) | **82** | ✅ APPLIED 2026-06-17 | $300M corporate VC fund. **Sector bullseye** — defense tech / space / quantum / deep tech / cyber. JD = diligence + sourcing + IC memos + pipeline tools + founder/VC networking → near 1:1 with Adam's Atento sourcing/diligence + fund-ops + AI fluency. Comp band **$86.8K–$198K**. "Associate" is below his Sr-Assoc floor (flex for a strong institution; he's well-qualified at 2+ yrs req). Citizenship req satisfied (US citizen ✓); confirm work model. **Applied via Workday 2026-06-17** with tailored resume (LinkedIn 4428309259). |
| 2026-06-17 | GridStor | Investment Associate (energy-storage project finance) | Denver, CO · hybrid (HQ Portland) | **70** | NEW | Goldman-Sachs-AM-backed battery-storage developer (3GW pipeline). **Sector ⭐ (grid / energy / industrial)**, Denver hub. **Caveat:** this is a **project-finance / buy-side modeling** seat (DCF, project-finance debt + tax-equity structures, 4+ yrs PF/IB/buy-side) — a real skills gap vs Adam's operator/sourcing profile; not a VC/CoS seat. "Associate" below floor. Comp undisclosed (base + cash bonus + LTIP). **Live, posted 2026-06-16** (LinkedIn 4411826519). |
| 2026-06-17 | Kava Equity Partners | Senior Associate (PE) | Denver, CO · **work model unstated → must ask** | **70** | 🟡 LEAD · geo-pending | Direct PE arm of the Southern Ute Indian Tribe Growth Fund. **Sr Associate = at his title floor;** full deal cycle (source→underwrite→structure→close), lean team with the MD, high autonomy. Generalist lower-middle-market control buyouts. **Exp bar:** MBA + 2 yrs (PE/late-stage VC/IB/consulting/related) — Adam's MBA + ~3 yrs of diligence/fund-ops clears the *years*, but the JD also wants **M&A-transaction experience + strong financial accounting/modeling** = a real partial gap vs his operator/sourcing profile. **JD states only "Denver, CO" — no remote/hybrid/onsite language; "lean team / work closely with MD" hints in-office.** Geo is the deciding unknown → **ask before any effort.** Comp undisclosed. Fresh (1 day old, 29 applicants), LinkedIn 4426863510. |
| 2026-06-17 | Saturn Five | Operating Partner (PE) | **On-site, NW Denver office** + 2×/mo portco travel | **~45** `DISQUALIFIED` | ❌ PASSED 2026-06-17 | Long-term-hold LMM PE (buy-and-hold small businesses). Hands-on "board member" to 3–6 portfolio CEOs — **operator/portfolio role, not an investor-sourcing seat.** **Two hard gates confirmed from the JD:** (1) **On-site in the NW Denver office** → relocation gate from Tulsa; (2) wants **10+ yrs post-undergrad with hands-on experience as a business owner / SMB leader with P&L responsibility** — Adam (~3 yrs post-MBA, CoS/operator, never an owner-operator) **does not clear the bar.** Clean pass on geo + experience. LinkedIn 4416445817. |
| 2026-06-17 | CB Partners (for social-impact investor) | Senior Analyst | **Hybrid — Denver 3 days/wk (confirmed)** | **~52** | 🟠 LEAD · pass unless mission resonates | Recruiter (CB Partners) filling a seat at a mission-driven **social-impact** investment org (direct + fund commitments + grantmaking). Real hands-on investing (diligence→execution→monitoring), reports to an Investment Principal. **Confirmed concerns:** **hybrid requires Denver 3×/wk in normal business hours** (hard geo strain from Tulsa); title "Senior Analyst" below floor; comp **$110–150K** (at/below floor); off-thesis social-impact sector; **3–5 yrs** bar (Adam ~3 = bottom). Upside: AI-tools experience is *preferred* (his edge); mission could appeal. **Pass unless Adam personally connects with the mission.** LinkedIn 4406620333. |
| 2026-06-17 | Perot Jain | VC Associate (Principal = stretch) | Dallas, TX · hybrid-able | 80 (fit) | ❌ postings CLOSED (verified) | Strong FIRM fit (industrial/hard tech, Dallas). **Both LinkedIn postings verified CLOSED 2026-06-17 ("no longer accepting", 1–2 yrs old); no live req found.** → Relationship/warm-intro target, not an application. |
| 2026-06-17 | Ironspring Ventures | VC Principal | Austin, TX · hybrid | 88 (fit) | ❌ CLOSED | **Filled:** 2 Principals hired Mar-2025 (Reddy, Natbony). Best sector match — relationship/warm-intro target only, not an application. |
| 2026-06-17 | LiveOak Venture Partners | Principal (partner-track) | Austin, TX | 80 (fit) | ❌ posting CLOSED (verified) | Established TX generalist/B2B. **LinkedIn Associate posting verified CLOSED 2026-06-17; no live req found.** Firm-level relationship lead only. |
| 2026-06-17 | Silverton Partners | Principal (partner-track) | Austin, TX | 78 (fit) | ❌ likely CLOSED | Filled/promoted Principals Aug-2025 → open Principal seat doubtful. Relationship target (principal@silvertonpartners.com). |
| 2026-06-17 | Trust Ventures | Investment Analyst / Associate | Remote (occasional Austin travel) | 72 (fit) | ❌ posting CLOSED (verified) | Remote + regulated hard-tech = attractive shape, **but LinkedIn posting verified CLOSED 2026-06-17 (~2 yrs old) — the earlier "verified live" note was wrong.** No live req found. Watch for a re-post. |
| 2026-06-17 | HOLT Ventures | VC Associate / Principal | San Antonio, TX | 72 (fit) | ⚠️ LEAD · unverified | Industrial CVC (Holt Cat) — sector bullseye. Level + live status unconfirmed. Firm-level lead. |
| 2026-06-16 | SPLY Capital | VC Associate | Austin / Dallas TX · hybrid-able | ⭐ **100** | REVIEWING | **Adam's call — the bullseye; already in active conversation.** Contact: Tyler Williams (Co-Founder & Managing Partner, Dallas). |
| 2026-06-16 | TYH Ventures | Chief of Staff to Managing Partner | Remote (FL travel a few×/mo) | 63 | NEW | Adam: "interesting." Direct to MP; IR + infra build; $70–190K + bonus. |
| 2026-06-16 | Paperboy Ventures | Chief of Staff | Remote (US, likely) | 60 | NEW | 2nd hire; LP/investor-network + diligence research + systems/AI tooling — strong operating match. Consumer/CPG sector (off-target but he's open). |
| 2026-06-16 | Amboy Street Ventures | Principal, Life Sciences | Remote | 55 | PASSED | Adam: "doesn't fit my interests or experience." Requires healthcare-VC pedigree he lacks. |
| 2026-06-16 | Capital Factory | Venture Associate | Austin, TX · onsite | 54 | NEW | Re-opened: carry no longer a gate + Adam will flex title for a strong firm. Caveat: heavy outbound sourcing / "super-connector" flavor. Board is Getro-hosted (jobs.capitalfactory.com) — not on the egress allowlist, so **not machine-verified 2026-06-17; human click required.** Previously seen alongside an Investor Relations Associate posting across TX offices. |
| 2026-06-16 | Lockheed Martin Ventures | VC Senior Associate | Arlington, VA · onsite | 20 `DISQUALIFIED` | PASSED | Defense/aerospace = his love, but onsite VA → relocation gate. |
| 2026-06-16 | Partners Capital | Senior Associate, VC | San Francisco · onsite | 20 `DISQUALIFIED` | PASSED | Onsite SF → relocation gate. |

---

## Detailed entries
<!-- /score-role writes fuller analyses below, one block per role. Template: -->
<!--
### [Firm] — [Role]  ·  Score: NN/100  ·  Status: NEW
- **Source / link:**
- **Location / model:**
- **Comp signals:**
- **Why it scored this way:** (map to fit-criteria factors)
- **Gaps / risks:**
- **Warm-intro path:**
- **Tailoring notes:** (what to emphasize in resume/outreach)
- **Next action:**
-->

### M12 (Microsoft) — Associate (CVC, Corporate Ventures IC3)  ·  Score: ~78/100  ·  Status: 🟢 PREPARING (Adam applying, 2026-06-19)
- **Source / link:** Microsoft Careers (Corporate Ventures IC3) — JD supplied by Adam 2026-06-19. Verify the live req / apply host on careers.microsoft.com.
- **Firm:** M12 — Microsoft's corporate venture arm (HQ San Francisco, team in Seattle). Early-stage investing across **AI, B2B SaaS, cloud infrastructure, cybersecurity, DevOps, and gaming/web3**; 100+ companies backed since 2016; differentiates via special access to Microsoft's platform and services for portfolio companies.
- **Role:** Associate on the investment team — help build theses in current/new domains, monitor the market, source deals aligned to themes, build relationships with founders/co-investors, support diligence (technological, IP, commercial, financial, legal/compliance risk + **unit-economics analysis and valuation modeling using multiple methods**), document meetings, track/report deal flow, help write IC memos, run operational metrics/KPI reporting + portfolio-review decks, and create thought-leadership content.
- **Location / model:** SF HQ + Seattle team. **JD states no remote/hybrid/onsite detail → work model is the single deciding unknown.** Per the rubric, strictly onsite SF/Seattle would trip the relocation gate from Tulsa; Adam is pursuing it anyway on firm caliber (cf. Tenex onsite NYC, Toyota remote). **Confirm work model before/at first recruiter contact.**
- **Comp signals:** Corporate Ventures IC3 — US base **$86.1K–$169.8K**; **SF Bay Area / NYC base $113.3K–$187.4K**. Top of the SF/NYC band clears his $150–180K target. Plus Microsoft bonus + stock (RSUs). Carry/co-invest not stated — raise in conversation.
- **Why it scored ~78:** role ~17 (CVC investor seat, real deal work; "Associate" below his Sr-Assoc floor but title-flex applies for a top-tier institution); proximity ~16 (member of the investment team — sources, diligences, writes memos, supports portfolio); geo ~9 *provisional* (SF/Seattle, work model unstated — drops hard if strictly onsite, recovers if hybrid-tolerant/remote); comp ~12 (SF/NYC band top hits his target + bonus + RSUs); firm 10 (Microsoft / M12 — unambiguously top-tier); sector ~7 (AI + B2B SaaS = his operating background, though not his hard-tech love).
- **Fit / gaps:** **Strengths —** B2B SaaS operator (19days studio; Agentech 0→1) + **frontier-AI fluency** ("AdamGPT"; production multi-agent sourcing + agentic ops systems; Aeon building bespoke enterprise AI) is a near-perfect match for an AI-first CVC; Atento sourcing (14/20 finalists) + diligence delivered to a GP + the 3/3 validated pass calls; financial / unit-economics / returns modeling; thesis-building via ~100 primary founder interviews; IC-memo and LP/portfolio-reporting reps. **Gaps —** (1) **geo (SF/Seattle, work model unstated)** — the live risk; (2) the "3+ yrs venture investing supporting partners in sourcing/diligence/deal execution" + "1+ yr on a deal team" bar is a defensible reach (~3 yrs venture/ops + Atento deal-team diligence; the JD's "OR equivalent experience" helps); (3) gaming/web3 and cybersecurity are outside his depth — don't overstate.
- **Warm-intro path:** None known — check whether Joey/Atento touch the M12 / Microsoft / SF-Seattle CVC network.
- **Key tailoring call (important):** **Do NOT lead with the "AI application software is un-investable / hard tech is the frontier" thesis** — M12 invests heavily in AI app software + B2B SaaS, so that framing argues against the fund. Reframe the thesis work as **evidence of thesis-building and primary research** (the JD wants "opinionated views," "new ideas/research," "thought leadership"). Foreground **frontier-AI fluency + B2B SaaS operating depth + sourcing/diligence + unit-economics/valuation modeling**. Mirror their language: build theses in theme areas, market monitoring, unit economics, valuation modeling (multiple methods), IC memos, portfolio value-add.
- **Materials:** `resumes/variants/m12.json` → `output/AdamBreaux_M12.docx`. (Cover note / application answers / warm-intro: TBD with Adam.)
- **Next action:** Confirm with Adam what else to produce (cover letter, short-answer responses, warm-intro outreach); **clarify work model** (remote/hybrid/onsite + travel) at first recruiter contact; then submit on careers.microsoft.com.

### Tenex — AI Strategist  ·  Score: ~79/100  ·  Status: ✅ APPLIED 2026-06-18
- **Source / link:** Ashby `tenexlabs` (job id `a7b5a192-5ed9-469b-95e2-90d401c025b9`) — live, posted 2026-06-04.
- **Firm:** Tenex — applied-AI strategy consultancy embedding teams into Fortune 500 / $1B+ companies to find high-ROI AI bets and ship the workflows. **Anthropic and OpenAI are formal partners** (sits with their Applied AI teams); Vercel/Lovable partners; named on Anthropic's Claude for Small Business launch.
- **Role:** AI Strategist — owns an engagement from the first executive conversation to a shipped, adopted workflow; partners with Forward-Deployed Engineers; reports to the Head of Strategy. Wants 3–7 yrs strategy/ops/product/workflow design; **daily hands-on agentic-AI practitioner**; strong discovery instincts; credible with execs *and* engineers; bias to ship. Bonus: CoS / founder / consultant background, public writing.
- **Location / model:** Ashby lists **onsite NYC** (`workplaceType=OnSite`, `isRemote=false`); JD promises only ~monthly client-site travel. **This is the open risk** vs. Adam's Tulsa anchor — clarify if a recruiter engages. (Per the rubric, strictly-onsite NYC would trip the relocation gate; Adam applied on personal conviction + the exceptional fit, betting on flexibility.)
- **Comp signals:** **$150K–$180K base + quarterly discretionary bonus** ("target total cash meaningfully exceeds base") + possible equity/LTI. Hits his band squarely.
- **Why it scored ~79:** role 12 (strategy/consulting with very high C-suite ownership — not a VC seat); decision-maker proximity & ownership 17 (owns the CEO relationship + the build end to end); geo ~13 (hub city but onsite-flagged → the soft spot); comp 15 (in-band + real bonus); firm 10 (frontier-lab partners, high bar); sector 7 (applied AI across industries; his single biggest differentiator). **Off the VC thesis, but on raw qualification-match this is arguably his strongest application** — Aeon is the role, one altitude up.
- **Fit / gaps:** **Strengths —** Aeon *is* this job (discovery → ship → adoption; strategist + forward-deployed-engineer); "AdamGPT" daily-practitioner; the Agentech sales platform + Aeon drilling system are exact "AI app you built" proof; CEO-to-field-engineer translation. **Gaps —** (1) geo/onsite NYC (above); (2) it's consulting/embedded-team work, which pattern-matches his "never again: agency" — but elite applied-AI strategy (equity, frontier-lab access, owns engagements) is materially *not* the hours-billing agency work he meant; (3) no public artifact yet.
- **Warm-intro path:** None known — check whether Joey/Atento touch the Tenex / Anthropic-OpenAI applied-AI network.
- **Tailoring notes:** Lead with **Aeon** (strategist + FDE model, the drilling engagement) and the **agentic-AI/workflow-automation** body of work; pull VC/fund-ops framing back. Mirror their language: own the engagement, how work actually happens, ship past launch, drive adoption.
- **Materials:** `resumes/variants/tenex.json` → `output/AdamBreaux_Tenex.docx`; application answers in `outreach/tenex-application.md` (Q1 stakeholder ownership, Q2 business↔tech translation, Q3 narrative AI-build).
- **Next action:** ✅ **APPLIED 2026-06-18.** Watch for recruiter response; if it advances, **clarify work model first** (onsite NYC vs. remote/travel), resolve the Aeon-the-thing-vs-bridge question, and add a real metric to the answers.

### Toyota Ventures — VC Associate (Frontier Fund)  ·  Score: 85/100  ·  Status: ✅ APPLIED 2026-06-17 ⭐
- **Source / link:** LinkedIn job `4425168501` (Toyota Research Institute / Toyota Ventures, Los Altos Hills, CA) — **live, posted ~2026-06-07, "no longer accepting" flag absent, 38 applicants.**
- **Firm:** Toyota Ventures — SF-Bay-Area VC firm, **$800M+ AUM**, 100+ investments. Marquee deep-tech/climate portfolio: Joby Aviation (NYSE: Joby), Stoke Space, Apex Space, Pickle Robot, Intuition Robotics, Efficient Computer, e-Zinc, AM Batteries, Natura Resources. Hiring for the **Frontier Fund(s)**.
- **Location / model:** SF Bay Area HQ (SF + Los Altos offices), but the JD explicitly states **"remote work within other U.S. cities is possible."** → **Tulsa-compatible (geo 20).** Confirm remote eligibility in first contact.
- **Comp signals:** Undisclosed base + **annual cash bonus** + benefits (vacation/sick/parental). A $800M Toyota-backed fund → likely in or near his range; confirm. Carry not stated — raise in conversation.
- **Mandate:** Source and screen early-stage companies in **AI, advanced materials, automation & robotics, and space tech.** Requires a degree + **min 4 years** related work experience + **strong understanding of deep tech**; cap tables, financial-statement digestion, sourcing/screening; "natural networker plugged into the deep-tech startup ecosystem." Hands-on dev/PM experience in an investment area is a plus.
- **Why it scored this way (≈85):** Role **19** (real VC investor seat, sourcing/screening + diligence; "Associate" is below his Sr-Assoc floor, but **title-flex applies for a genuinely top-tier firm** with a track up — his stated rule); proximity **17** (sources founders, screens, supports portfolio); geo **20** (remote-eligible US); comp **9** (undisclosed but credible); firm **10** (top-tier $800M deep-tech fund, marquee portfolio); sector **10** (deep tech / space / robotics / advanced materials = **his exact thesis**).
- **Gaps / risks:** (1) **"Min 4 years"** vs his ~3 yrs post-MBA — a slight reach; argue total venture/operating experience + the depth of his deep-tech work. (2) **"Associate"** is below his floor — mitigated by his title-flex-for-top-firms rule + the firm's caliber. (3) Network ask skews SF deep-tech VC; his network is more Tulsa/SBIR/industrial — **but his 100 founder interviews, SBIR/STTR fluency, and industrial thesis are a real, differentiated asset.** (4) Confirm remote eligibility actually extends to Tulsa.
- **Warm-intro path:** None known — check whether Joey/Atento touch the Toyota Ventures / SF deep-tech network. The deep-tech market memo (from his 100 interviews) would be a high-leverage proof-of-work attachment here.
- **Tailoring notes:** Lead with the **deep-tech investment thesis** (physical AI / robotics / space / U.S. reindustrialization) + **100 founder/operator interviews** + **SBIR/STTR non-dilutive fluency** + Atento sourcing/diligence (sourced 14/20 finalists; 3/3 pass calls validated) + financial modeling / cap tables + AI-fluent sourcing engines. Mirror their language: deep tech, advanced materials, automation & robotics, space tech, early-stage sourcing. **This is the role his thesis was built for** — foreground it.
- **Next action:** ✅ **APPLIED 2026-06-17.** **Follow-ups:** (1) **confirm remote eligibility actually extends to Tulsa** in first contact — the JD's "remote within other U.S. cities is possible" is the one open geo question; (2) seek a warm intro to reinforce (check whether Joey/Atento touch the Toyota Ventures / SF deep-tech network); (3) **build the deep-tech market memo** (from his 100 founder interviews) as a high-leverage proof-of-work attachment — best-fit role in the pipeline for it; (4) watch for a recruiter response. Rivals SPLY/Booz Allen on sector + beats them on firm caliber and geo (remote).

### Booz Allen Ventures — VC Associate (CVC)  ·  Score: 82/100  ·  Status: NEW ✅ verified live
- **Source / link:** LinkedIn job `4428309259` (Booz Allen Hamilton Ventures, Denver, CO) — **live, posted 2026-06-13**, "not accepting applications" flag absent. Job # R0242160. Posting closes within 90 days of posting date.
- **Location / model:** Denver, CO — a named hub, Tulsa-compatible via travel-in. Work model not stated in JD (boilerplate lists remote/hybrid/onsite) → **confirm whether the Denver seat is hybrid (good) or onsite (would weaken geo).**
- **Comp signals:** Explicit range **$86,800–$198,000** (annualized). Wide; an Associate likely lands mid-band. Top of band clears his floor; midpoint sits at/just below it. Plus Booz Allen benefits. **Carry/LTIP not stated — raise in conversation.**
- **Why it scored this way (≈82):** Role **18** (CVC investor seat at right level — real deal work, not back-office; "Associate" title is below his Sr-Assoc floor but waived for a strong institution + he's well-qualified at the 2+ yr bar); proximity **18** (regularly meets founders/investors, owns diligence + IC memos + sourcing); geo **17** (Denver hub; pending work-model confirm); comp **10** (in-range at top, undisclosed where it lands); firm **9** (Booz Allen — major, credible; $300M fund); sector **10** (defense / space / quantum / deep tech / cyber = his hard-tech + defense love).
- **Gaps / risks:** (1) Title "Associate" is below his stated floor — frame as title-flex for a top institution with a real investing mandate. (2) A defense-focused CVC likely wants US citizenship — **not a problem: Adam is a US citizen ✓** (profile §). (3) Work model (hybrid vs onsite Denver) unconfirmed. (4) Comp lands where on the band?
- **Warm-intro path:** None known — check whether Joey/Atento touch the Booz Allen / DC-defense-VC network. High value given the firm's reach.
- **Tailoring notes:** Lead with Atento sourcing/diligence delivered to a GP + financial modeling + IC-memo writing + 0→1 fund-ops + **AI fluency** (they prize modern tooling and explicitly research AI/data-science theses). Mirror their thesis language: defense technology, dual-use, deep tech, space. Make the hard-tech/defense affinity explicit — this is his stated love.
- **Next action:** ✅ **APPLIED 2026-06-17** via Workday with the tailored resume (`resumes/variants/boozallen.json` → `output/AdamBreaux_BoozAllen.docx`) + tailored work-experience + skills. **Follow-ups:** seek a warm intro to reinforce; build the deep-tech market memo as a proof-of-work attachment; watch for a recruiter response. **Rivals SPLY on sector fit.**

### GridStor — Investment Associate (energy-storage project finance)  ·  Score: 70/100  ·  Status: NEW ✅ verified live
- **Source / link:** LinkedIn job `4411826519` (GridStor, Denver, CO) — **live, posted 2026-06-16**, "not accepting applications" flag absent.
- **Location / model:** HQ Portland, OR; regional offices Denver, CO + LA, CA. **Hybrid**, based in one of the three. Denver = a named hub, Tulsa-compatible. Geo is good.
- **Comp signals:** "Competitive base commensurate with experience + annual cash bonus + **Long Term Incentive Plan**" (real upside) + strong benefits. No number disclosed; Goldman-Sachs-AM-backed energy infra → likely in-range.
- **Why it scored this way (≈70):** Role **14** (a real investing seat with full-deal-lifecycle ownership + IC memos, **but it's corporate project-finance/buy-side, not a VC/fund or CoS seat**; "Associate" below floor); proximity **15** (works closely with senior deal team, prepares IC memoranda); geo **18** (Denver hub, hybrid); comp **11** (in-range base + bonus + LTIP, undisclosed); firm **8** (Goldman-AM-backed, 3GW pipeline — serious); sector **10** (battery storage / grid / energy = his industrial/hard-tech love).
- **Gaps / risks:** **The headline is a skills mismatch.** The JD wants 4+ yrs of **project finance / IB / buy-side** plus hands-on **project-finance modeling, DCF, debt + tax-equity structures** and a quantitative/engineering degree. Adam is an MBA operator (sourcing, diligence, fund-ops, CoS) — strong on diligence/modeling-adjacent work but **not a project-finance modeler**. This is a genuine qualification gap, and the role is narrower (asset-level deal execution) than his "own deals / investor proximity" target. Title also below floor.
- **Warm-intro path:** None known.
- **Tailoring notes:** Only pursue if he wants to make the transferable-diligence/financial-modeling case. Lead with financial modeling + diligence-process management + IC-memo writing; be honest that direct project-finance / tax-equity structuring is a stretch. Don't overstate energy-finance depth.
- **Next action:** Decide with Adam whether the sector pull (energy/industrial) justifies pursuing a project-finance seat that sits outside his core. If yes, `/tailor-resume GridStor` and apply; otherwise log as a sector-watch and pass.

### Kava Equity Partners — Senior Associate (PE)  ·  Score: 70/100  ·  Status: 🟡 LEAD · geo-pending (2026-06-17 research done)
- **Source / link:** LinkedIn `4426863510` — live, **1 day old (posted ~2026-06-16), 29 applicants**, "Mid-Senior level / Full-time / Finance." Firm: www.kavaequity.com / www.sugf.com (Southern Ute Indian Tribe Growth Fund).
- **What the JD actually says (pulled 2026-06-17):** Direct PE arm of the Southern Ute Indian Tribe Growth Fund. Lower-middle-market control buyouts + opportunistic minority/secondary/private credit. Sr Associate "actively participates in sourcing, underwriting, structuring, and closing" across acquisitions, portfolio mgmt, and divestments; lean team; "works closely with the Managing Director" + "operate independently with a high degree of autonomy."
  - **Min quals:** Master's (Business/Finance/Econ/Engineering) **+ 2 yrs** in PE / late-stage VC / IB / management consulting / *related field*, **OR** Bachelor's + 4 yrs. Plus **M&A transaction experience**, **strong financial accounting + modeling skills**, concise written investment recommendations, public speaking. **Preferred:** prior Associate/Sr-Associate at a PE firm / family office / IB.
  - **Benefits:** medical / vision / dental / 401(k). **Comp band not disclosed.**
  - **Work model:** JD states only "Denver, CO" — **no remote/hybrid/onsite language at all.** The "lean team / work closely with the MD / high autonomy" framing leans toward in-office. **This is the single deciding unknown.**
- **Why it's the best-shaped of the 3 Denver leads (≈70):** Role 16 (full-deal-cycle ownership, but generalist LMM PE not hard tech, and it's a buy-side modeling seat); proximity 18 (works directly with the MD, lean team); geo ~13 (Denver hub *if* hybrid/remote-tolerant — drops hard if strictly onsite); comp ~9 (undisclosed, standard benefits); firm 7 (tribal growth fund, credible/permanent capital); sector 7 (generalist LMM). Title is **at his Sr-Associate floor** ✓.
- **Gaps / risks:** (1) **M&A-transaction experience + strong financial accounting/modeling** is a genuine partial gap — Adam is an operator/sourcer/diligence generalist, not a PE deal-modeler (same theme as GridStor, milder). (2) **Work model unknown** — if strictly onsite Denver, geo weakens toward the relocation gate. (3) Sector is off his hard-tech thesis. Mitigant: his MBA clears the degree gate and his ~3 yrs + Atento diligence arguably satisfy the "related field" 2-yr bar; the operator angle (value-creation with management teams) maps to their "partnership with management teams" language.
- **Warm-intro path:** None known — check whether Joey/Atento touch the Southern Ute Growth Fund / SW-Colorado (Durango–Ignacio) network.
- **Tailoring notes:** Lead with diligence-process ownership + financial modeling + concise IC-memo writing + working directly with a GP/MD (Atento). Be honest that hands-on M&A deal execution is a stretch; make the "fast learner who owns the full process" case. Mirror their value language: enduring value, partnership with management teams, environmental stewardship / community development.
- **Next action:** **The geo question gates everything — confirm work model (remote/hybrid/onsite + travel cadence) before any tailoring.** No firm-direct/2nd-degree contact known and the careers host isn't on the allowlist, so this needs Adam (a LinkedIn message to the poster, or apply-and-ask). If hybrid/remote-tolerant → `/score-role` to lock the number, then `/tailor-resume Kava` (PE-diligence cut). If strictly onsite Denver → pass.

### Saturn Five — Operating Partner (PE)  ·  Score: ~45  ·  Status: ❌ PASSED / DISQUALIFIED (2026-06-17 research done)
- **Source / link:** LinkedIn `4416445817` — live, 1 day old, **over 200 applicants.** Poster: Hope Kahan (recruiter). Firm: Saturn Five (annual letters referenced in JD).
- **What the JD actually says (pulled 2026-06-17):** Long-term-hold LMM PE — buys and operates small businesses for the long term. Operating Partner is the "connective tissue" between the funds and portfolio CEOs: hands-on board-member role across 3–6 companies — transition new acquisitions (banking/insurance/payroll/systems), coach/mentor/assess senior leadership, lead CEO/President/GM hiring when sellers retire, monthly financial reviews, quarterly goals, annual operating plans, design portco comp/incentive programs, roll out an EOS-informed operating system.
  - **Location (decisive):** **"On-site in the Saturn Five office in Northwest Denver, with travel at least twice a month to visit portfolio companies"** — and "comfort being on-site with blue-collar portfolio companies, sometimes out-of-state, often quite intensively."
  - **Experience bar (decisive):** **"10+ years of post-undergrad work experience … including hands-on operating experience as a business owner or leader in an SMB with P&L responsibility"** (scaling/exiting an SMB a plus); solid financial acumen; MBA a plus.
  - **Comp:** base commensurate with experience + performance bonus + 401(k) 4% match + health/dental + self-directed PTO. No number.
- **Why it's a PASS (two hard gates):** (1) **Geo — strictly on-site in the NW Denver office** trips the relocation gate from Tulsa (this is not a hybrid/remote seat). (2) **Experience — 10+ yrs with hands-on owner/operator P&L responsibility.** Adam is ~3 yrs post-MBA, a CoS/operator who has never owned/run an SMB; he does not clear the bar. It's also an operating/portfolio-management seat, not the investor-sourcing/diligence seat he's targeting.
- **Next action:** **PASS — disqualified on geo (onsite Denver) + experience (10+ yr owner-operator).** Logged for the pattern (great-CEO-proximity operator roles that demand a former owner-operator are not his lane). No further effort.

### CB Partners (recruiting for a social-impact investor) — Senior Analyst  ·  Score: ~52  ·  Status: 🟠 LEAD · pass unless mission resonates (2026-06-17 research done)
- **Source / link:** LinkedIn `4406620333` — live, ~1 week old, **over 200 applicants.** CB Partners, LLC is a search firm; the employer is **still an unnamed** mission-driven social-impact investment organization (not disclosed in the JD).
- **What the JD actually says (pulled 2026-06-17):** Multi-strategy impact investor (direct investments + fund commitments + grantmaking) focused on human-capital / well-being / belonging / purpose. Hands-on Senior Analyst across pipeline development, due diligence (financial + market + impact), execution, portfolio monitoring, ongoing analytics; reports to an Investment Principal in a matrixed structure.
  - **Comp:** **$110,000–$150,000** base (employer-provided range).
  - **Geo (decisive):** "Our client offers a **hybrid work model and candidates must be present in Denver during normal business hours three days each week.**" → confirmed 3×/wk Denver, no stated remote flex.
  - **Experience:** **3–5 yrs** in IB / PE / VC / asset management / family office / comparable; demonstrated financial modeling, valuation, deal structuring across private equity / VC / private debt; CFA/CAIA a plus. **Preferred: experience with AI tools** + integrating impact considerations into analysis.
- **Why it's a PASS (multiple strikes):** (1) **Geo — 3 days/week in Denver** is a hard strain from Tulsa and edges into the relocation gate; no remote flex offered. (2) Title "Senior Analyst" is **below** his Sr-Associate floor. (3) Comp **$110–150K** sits at/below his floor. (4) Social-impact / human-capital sector is off his hard-tech thesis. (5) The **3–5 yr** bar puts Adam (~3 yrs) at the bottom. Upsides: real multi-strategy investing exposure, and **AI-tools experience is a *preferred* qualification** (his genuine edge); the mission could appeal if he personally connects.
- **Next action:** **Pass — unless Adam personally resonates with the impact mission.** If he does, the only way to salvage it is to press CB Partners on real remote flexibility (the 3×/wk Denver cadence is the dealbreaker); otherwise log as off-thesis and move on. No further effort by default.

### Perot Jain — VC Associate (Principal = stretch)  ·  Score: 80/100  ·  Status: ❌ postings CLOSED (verified 2026-06-17) — relationship target
- **Live-status check (2026-06-17):** Both LinkedIn postings (`3919688347` Associate, `3534871143` Principal-SF)
  return **"No longer accepting applications"** (posted ~1 yr and ~2 yrs ago). No live Perot Jain req found on
  LinkedIn guest search. Firm jobs page + John Gannon / Startup&VC archive links can't be machine-checked here.
- **Source / links (LinkedIn = CLOSED; others archive-dated):**
  - Firm jobs page: https://perotjain.com/job-openings/
  - VC Associate (Dallas) — John Gannon: https://johngannonblog.com/job/vc-associate-perot-jain-in-dallas-tx/
  - Associate (Dallas) — LinkedIn: https://www.linkedin.com/jobs/view/associate-at-perot-jain-3919688347
  - Investment Associate — Startup&VC: https://www.startupandvc.com/venture-capital-jobs/investment-associate-2031
  - VC Principal (Dallas) — John Gannon: https://johngannonblog.com/job/vc-principal-perot-jain-in-dallas-tx/
  - Investment Principal (SF) — LinkedIn: https://www.linkedin.com/jobs/view/investment-principal-at-perot-jain-3534871143
- **Location / model:** Dallas, TX. Hub → Tulsa-compatible hybrid/travel-in.
- **Comp signals:** Undisclosed. Raise in conversation.
- **Why it scored this way:** Strong *firm* fit (industrial / mobility / real-estate / gov-defense tech = his hard-tech love; Dallas hub; Ross Perot Jr. + Anurag Jain). **But the Principal JD requires 7+ years of VC/PE investing experience — Adam has ~3.** So the realistic seat is the **Associate** (below his Sr-Associate floor, but he flexes for fit/firm). Scored as Associate: role ~16, proximity 18, geo 18, comp ~10, firm 8, sector 10 ≈ 80.
- **Gaps / risks:** Experience-level mismatch for Principal. Associate is below his stated floor (mitigated by his SPLY precedent + title-flex for strong firms). Confirm postings are live.
- **Warm-intro path:** None known — check whether Joey/Atento touch the Perot/Jain or Dallas network. **High-value to find one** given the firm's caliber.
- **Tailoring notes:** Lead with hard-tech/industrial affinity + Atento sourcing/diligence delivered to a GP + 0→1 build (Agentech) + financial modeling. Mirror "transformative technology / early-stage / supply chain / mobility." Make the "deep-by-reps, ready to own deals" case for punching above the Associate title.
- **Next action:** Verify live → seek warm intro → if Associate, decide with Adam whether to pursue below floor → `/tailor-resume PerotJain` (VC-investor, hard-tech cut).

### Ironspring Ventures — VC Principal  ·  Score: 88/100 (fit-if-open)  ·  Status: PASSED — seats filled, keep warm
- **Source / links:**
  - VC Principal (Austin) — John Gannon (Jul-2024, now filled): https://johngannonblog.com/job/vc-principal-ironspring-ventures-in-austin-tx/
  - Firm site: https://ironspring.com · Portfolio job board: https://jobs.ironspring.com/jobs
  - Filled-seats confirmation — VCWire (Mar-2025): https://vcwire.tech/2025/03/14/ironspring-ventures-adds-two-principals/
- **Verified status:** **Likely filled.** VCWire (Mar-2025): Ironspring added *two* Principals — Natan Reddy and Sam Natbony. The Jul-2024 posting predates those hires, so the seat is almost certainly closed.
- **Location / model:** Austin, TX. Fund II = $100M. Sector = construction / manufacturing / transport & logistics / alt-energy.
- **Why it still matters:** This is Adam's **single best sector match** in Tier 1 (digital-industrial = his love). Even with no open seat, it's the top relationship to build for a future role.
- **Next action:** **Don't apply to a closed req.** Build a relationship — warm intro to a partner or one of the new Principals; follow the fund; revisit when they raise Fund III or post a new seat. Possible writing-sample play: a short industrial-tech market memo aimed at their thesis.

### LiveOak Venture Partners — Principal (partner-track)  ·  Score: 80/100  ·  Status: ❌ posting CLOSED (verified 2026-06-17) — relationship target
- **Live-status check (2026-06-17):** LinkedIn Associate posting (`3908892921`) returns **"No longer accepting
  applications"** (~2 yrs old). No live LiveOak req found on LinkedIn guest search. jobs.liveoakvp.com is a
  Getro portfolio board (not on the allowlist) — human click required for any firm-direct posting.
- **Source / links (LinkedIn = CLOSED; others archive-dated):**
  - Firm job board: https://jobs.liveoakvp.com/jobs · Associate applications → Associate@liveoak.vc
  - VC Associate (Austin) — John Gannon: https://johngannonblog.com/job/vc-associate-liveoak-ventures-in-austin-tx/
  - Associate (Austin) — LinkedIn: https://www.linkedin.com/jobs/view/associate-at-liveoak-ventures-3908892921
  - VC Partner (Austin) — John Gannon: https://johngannonblog.com/vc-careers/vc-partner-live-oak-venture-partners-in-austin-tx/
- **Verified status:** Principal described as partner-track tied to fund expansion, **but no current 2026 posting confirmed — treat as possibly stale.**
- **Location / model:** Austin, TX. Hub → Tulsa-compatible. Sector: generalist / B2B (strong, not his hard-tech love).
- **Why it scored this way:** Role ~25 (Principal/partner-track) *if open*; proximity 20; geo 18; comp ~10; firm 8 ($600M+ established TX); sector 7. Discounted to ≈ 80 on availability uncertainty.
- **Gaps / risks:** Seat may not be open; generalist sector; 3-yr experience may bump against Principal bar (same theme as Perot Jain — Associate/Sr-Associate is the realistic level).
- **Next action:** Verify on jobs.liveoakvp.com before effort. If only Associate is open, weigh as a strong-firm Associate. `/tailor-resume LiveOak` (VC-investor cut) once confirmed.

### Silverton Partners — Principal (partner-track)  ·  Score: 78/100  ·  Status: NEW — verify live
- **Source / links (verify current):**
  - Firm open positions: https://www.silvertonpartners.com/open-positions · Portfolio board: https://jobs.silvertonpartners.com/jobs · Investment-team contact: principal@silvertonpartners.com
  - VC Principal (Austin) — John Gannon (Jan-2022): https://johngannonblog.com/vc-careers/vc-principal-silverton-partners-in-austin-tx-2/
  - VC Associate (Austin) — John Gannon: https://johngannonblog.com/vc-careers/vc-associate-silverton-partners-in-austin-tx/
  - Recent Principal hires (Aug-2025): https://www.businesswire.com/news/home/20250825461524/en/Kristen-Dumbeck-Joins-Silverton-Partners-as-a-Principal-Addie-Rasche-Promoted-to-Principal
- **Verified status:** **Open Principal seat doubtful** — Silverton hired Kristen Dumbeck (Principal) and promoted Addie Rasche to Principal in **Aug-2025**. They keep a standing open-positions page + investment-team inbox, so a pipeline exists.
- **Location / model:** Austin, TX. Most-active / longest-standing TX firm, ~$655M AUM, generalist tech.
- **Why it scored this way:** Role 25 (Principal/partner-track) *if open*; proximity 20; geo 18; comp ~10; firm 9 (top TX reputation); sector 7. Discounted to ≈ 78 on availability.
- **Gaps / risks:** Likely no current Principal seat; same experience-band theme.
- **Next action:** Check open-positions page; if nothing fits, send a concise, relationship-oriented note to principal@silvertonpartners.com (per voice-guide) to get on their radar. Don't force an application.

### Trust Ventures — Investment Analyst / Associate  ·  Score: 72/100  ·  Status: ❌ posting CLOSED (verified 2026-06-17)
- **Live-status check (2026-06-17):** LinkedIn posting (`3758952878`) returns **"No longer accepting
  applications"** (~2 yrs old). **This overturns the prior "verified live" note below — it was based on an
  indexed archive, not a live check.** No current Trust Ventures req found on LinkedIn guest search. Good
  shape (remote + regulated hard-tech) → worth watching for a re-post, but nothing to apply to today.
- **Source / links (LinkedIn = CLOSED as of 2026-06-17):**
  - Investment Analyst/Associate (US, remote) — LinkedIn: https://www.linkedin.com/jobs/view/investment-analyst-associate-at-trust-ventures-3758952878
  - "Open Role: Investment Associate" — Trust Ventures (Medium): https://medium.com/@trustventures/open-role-investment-associate-ec257c6da4fe
  - VC Associate (Remote) — John Gannon: https://johngannonblog.com/job/vc-associate-trust-ventures-in-remote/
  - JD detail — Growth Equity Interview Guide: https://growthequityinterviewguide.com/job/trust-ventures-investment-analyst-associate-remote
- **~~Verified status: Live and remote~~ (CORRECTED 2026-06-17 — the posting is CLOSED; see live-status check above).** Role *was* described as remote (occasional Austin travel) with full deal exposure: sourcing → diligence → portfolio management on the core team.
- **Location / model:** Remote (Tulsa-compatible) — a real plus. Sector: hard tech in **highly-regulated industries** (energy, mobility, etc.) — sector-relevant.
- **Why it scored this way:** Role ~16 (Analyst/Associate, below Sr-Associate floor); proximity 18 (core-team deal work); geo 20 (remote); comp ~9 (undisclosed); firm 7; sector ~9 (regulated hard tech). ≈ 72.
- **Gaps / risks:** Asks **1–2 years** experience → junior; Adam (3 yrs post-MBA + more) would be a senior applicant and the title/comp may sit below his floor. Upside: remote + sector + full deal exposure at a thesis-driven fund.
- **Warm-intro path:** None known.
- **Tailoring notes:** Lead with diligence/sourcing reps (Atento), regulated-industry analytical rigor, and self-direction (they prize "significant self-direction" + "honesty/transparency" — mirror his actual working style from profile §7).
- **Next action:** Decide with Adam whether a remote Associate seat is worth it given the level. If yes, `/tailor-resume Trust` (VC-investor cut) + apply via LinkedIn.

### HOLT Ventures — VC Associate / Principal  ·  Score: 72/100  ·  Status: NEW — confirm level
- **Source / links (confirm current level):**
  - VC Analyst (San Antonio) — John Gannon: https://johngannonblog.com/vc-analyst-holt-ventures-in-san-antonio-tx/
  - Firm: https://www.holtventures.com · LinkedIn: https://www.linkedin.com/company/holtventures
- **Location / model:** San Antonio, TX. CVC arm of Holt Cat (~$25M fund). Sector: construction tech / heavy equipment / industrial = his hard-tech love.
- **Verified status:** Has posted VC Analyst / Associate / Principal + a Finance Analyst at various points; **current open level unconfirmed** — the most recent indexed posting reads "Analyst" (below floor).
- **Why it scored this way:** Role ~16–20 (level TBD); proximity 18 (CVC, partner Meg Paulus); geo ~13 (San Antonio — reachable by flight but not a primary hub, travel cadence TBD); comp ~10; firm 7; sector 10. ≈ 72.
- **Gaps / risks:** Level may be Analyst (below floor); San Antonio is a weaker geo than Dallas/Austin from Tulsa. Strong on sector.
- **Next action:** Confirm the current open level + travel expectations before effort. Good warm-intro candidate given the industrial thesis.

### Capital Factory — Venture Associate  ·  (see pipeline row, Score 54)
- **Source / links:**
  - Venture Associate (Austin): https://jobs.capitalfactory.com/companies/capital-factory/jobs/49734950-venture-associate-austin
  - Firm jobs (all TX offices): https://capitalfactory.com/jobs/ · Board: https://jobs.capitalfactory.com/companies/capital-factory
  - (Also an Investor Relations Associate posting across Austin/Dallas/Houston/San Antonio.)

### 8VC — platform / Chief-of-Staff-type roles (scan board)  ·  Status: ✅ scanned 2026-06-17 — no fit
- **Source / links:**
  - Firm roles (Ashby ATS): https://jobs.ashbyhq.com/8vc · Talent page: https://www.8vc.com/jobs
  - Note: jobs.8vc.com is the **portfolio** board (e.g. "Chief of Staff – MeritFirst" is a portfolio company, not the fund). Scan the Ashby board for actual 8VC firm/platform roles in Dallas/Austin.
- **Live scan (Ashby API `8vc`, 2026-06-17):** 9 live reqs, none a fit — all are portfolio-company roles
  (MeritFirst, Thorin) or 8VC internal ops/eng: *Head of Communications & Brand Marketing (Remote-US),
  IT Administrator (Dallas), Software Engineer New Grad (SF)*. No investing/platform/CoS seat for Adam.
  Re-scan the Ashby board periodically — it's now machine-checkable.

### SPLY Capital — VC Associate  ·  Score: 100/100 (Adam's call)  ·  Status: REVIEWING ⭐
- **Source / link:** Surfaced on VC Stack / Startup&VC job boards, posted ~2026-06-08. Firm: https://splycapital.com/team · profile: https://www.preqin.com/data/profile/fund-manager/sply-capital/776870.
- **Contact:** **Tyler Williams — Co-Founder & Managing Partner** (Dallas). Also Drew Leahy (GP), Haley Swank (CoS & Venture Partner). **Adam is already in active conversation with SPLY.**
- **Location / model:** Texas-based (Austin / Dallas). Hub → Tulsa-compatible hybrid.
- **Comp signals:** Not disclosed; raise in conversation (carry no longer treated as a screen).
- **Why it's the bullseye:** JD = LP communications + fund operations + due diligence + closings + fundraising at an **AI-forward** fund → near one-to-one with his 19days fund-ops build, Atento diligence, and AI fluency. Aerospace/defense in their thesis hits his hard-tech love. This tool independently ranked it #1 with no knowledge of his existing conversation.
- **Gaps / risks:** Confirm the seat carries a real deal voice (not pure ops) and the level/track. Minor.
- **Warm-intro path:** Direct — already talking to them. Joey / Atento could reinforce if useful.
- **Tailoring notes:** Lead with fund-ops-from-scratch (metrics, LP reporting, back office) + Atento sourcing/diligence delivered to a GP. Foreground AI fluency. Mirror their thesis language (AI, aerospace/defense).
- **Next action:** Outreach drafted to Tyler Williams (2026-06-16). Then `/tailor-resume SPLY` (VC-operator cut).

### Paperboy Ventures — Chief of Staff  ·  Score: 60/100  ·  Status: NEW
- **Source / link:** https://www.paperboyventures.com/paperboy-cos
- **Location / model:** Remote (likely — confirm). The CoS is the fund's **second full-time hire** → direct founder proximity.
- **Comp signals:** Not disclosed.
- **Why it scored this way:** Role 16 (CoS, with investor/LP-network building + investment research + systems); proximity 16 (2nd hire, direct to the principal); geo 18 (remote, pending confirmation); comp ~9 (undisclosed); firm 6 (small/new); sector ~5 (early-stage **consumer / CPG** — food & beverage; off his hard-tech love, but he's open to anything).
- **Gaps / risks:** (1) Sector is consumer CPG, not his stated interest — gauge genuine interest. (2) Remote status & comp unconfirmed. (3) Heavy systems/CRM/playbook build — make sure it grows toward real investing.
- **Warm-intro path:** None known.
- **Tailoring notes:** Strong fit on mechanics — "build internal systems, implement AI tooling, create repeatable playbooks, grow the LP network" maps directly to his 19days CRM/back-office/Fund-II work + AI fluency. Lead there.
- **Next action:** Confirm remote + comp; if he's interested in the sector, `/score-role` and `/tailor-resume Paperboy` (CoS cut).

### TYH Ventures — Chief of Staff to the Managing Partner  ·  Score: 60/100  ·  Status: NEW
- **Source / link:** https://johngannonblog.com/chief-of-staff-tyh-ventures-in-remote/ (page 403'd to automated fetch; details below from board summary — verify directly).
- **Location / model:** Remote, or Palm Beach County, FL. Remote candidates expected to travel to FL a few times/month — doable from Tulsa, Tulsa-compatible.
- **Comp signals:** $70K–$190K + performance bonus, commensurate with experience. **No carry/equity mentioned — this is the central risk.**
- **Why it scored this way:** Role ~16 (CoS to MP, but mandate skews IR + building infra/website); proximity 16 (direct to Managing Partner); geo 18 (remote, light FL travel); comp ~8 (wide band, top hits floor, no carry stated); firm 6 (small, unknown); sector 7 (generalist, "touch all kinds of industries").
- **Gaps / risks:** (1) **Carry not mentioned** — if there's no equity/ownership, this trips the hard gate. Confirm first. (2) Some duties (build the website/online presence) read junior/marketing — make sure scope grows into real investing/strategy. (3) Wide comp band — pin down the number.
- **Warm-intro path:** None known.
- **Tailoring notes:** His CoS-to-CEO experience at 19days is a direct analog (IR, LP reporting, standing up infrastructure). Emphasize "build the back office + investor reporting from zero" and AI-fluent tooling.
- **Next action:** Confirm equity/carry and comp number before investing effort. If carry exists, `/tailor-resume TYH` (CoS cut).

### Amboy Street Ventures — Principal, Life Sciences  ·  Score: 55/100  ·  Status: NEW
- **Source / link:** https://amboystjobs.lovable.app/ · firm: https://www.startupandvc.com/vc-firms/amboy-street-ventures (posted ~2026-06-01).
- **Location / model:** Remote, full-time. Track to Partner.
- **Comp signals:** Not disclosed; Principal-at-VC seat → carry likely (a plus if confirmed).
- **Why it scored this way:** On structure alone this is the best-shaped role found — Principal (25), remote (20), core team / track-to-Partner (18). But it's discounted hard because: sector 3 (women's-health therapeutics/diagnostics/devices — off his hard-tech target), and the posting **requires being "trained at a top-tier healthcare VC fund,"** a pedigree Adam does not have.
- **Gaps / risks:** **Candidate-qualification mismatch is the headline** — he's a generalist operator, not a healthcare-VC-trained life-sciences investor. Likely a screen-out despite the great structure. Logged so we see the pattern (great shape ≠ fit when the mandate demands domain pedigree).
- **Warm-intro path:** None known.
- **Tailoring notes:** Only pursue if he has a genuine women's-health/healthcare angle to argue; otherwise pass. Don't fabricate domain depth.
- **Next action:** Likely PASS. Flag to Adam; pursue only if he wants to make the generalist-operator case.

---

## Verifying live status — method + required config

**Rule going forward:** a role is only logged with status `NEW` (applyable) if its live status is
**confirmed against a source that lists only currently-open roles.** Anything else is `⚠️ LEAD · unverified`
and must be human-clicked before any work. No more surfacing dated archive links as opportunities.

**Reliable live sources (list only open reqs, timestamped):**
- Applicant-tracking JSON feeds — e.g. Greenhouse `https://boards-api.greenhouse.io/v1/boards/<firm>/jobs`,
  Lever `https://api.lever.co/v0/postings/<firm>?mode=json`, Ashby `https://api.ashbyhq.com/posting-api/job-board/<firm>`.
- The fund's own live application page (when not bot-blocked).
- A freshly-dated aggregator result (LinkedIn job IDs encode recency — current 2026 reqs are high-numbered).

**What now works (allowlist updated 2026-06-17):** the hosts below were added to egress, so live checks run via Bash `curl`:
- `boards-api.greenhouse.io`, `api.lever.co`, `api.ashbyhq.com`, `jobs.ashbyhq.com`, `www.linkedin.com`.

**Verification recipes that worked:**
- **Ashby board JSON:** `curl https://api.ashbyhq.com/posting-api/job-board/<token>` → `jobs[]` with `title`,
  `location`, `isListed`. (8VC token = `8vc`.)
- **Greenhouse / Lever:** `https://boards-api.greenhouse.io/v1/boards/<token>/jobs` and
  `https://api.lever.co/v0/postings/<token>?mode=json`. (No TX-fund tokens resolved — most don't use these.)
- **LinkedIn single posting (no login):** `https://www.linkedin.com/jobs-guest/jobs/api/jobPosting/<jobId>`
  — search the HTML for "no longer accepting applications" and the "N ago" timestamp. This is how the four
  closed postings were confirmed.
- **LinkedIn firm search (no login):**
  `https://www.linkedin.com/jobs-guest/jobs/api/seeMoreJobPostings/search?keywords=<firm>&location=United%20States`
  — note it returns *fuzzy* matches at other firms, so absence is a signal but not proof.

**Still blocked (not on the allowlist) → human click required:** firm career sites, Getro portfolio boards
(jobs.<firm>.com, jobs.capitalfactory.com), and Lovable app pages (amboystjobs.lovable.app).

**Standing rule:** treat TX funds primarily as *relationship* targets (warm-intro map in `network.md`) —
investor seats are mostly network-filled and rarely posted. Re-run the ATS/LinkedIn checks above before
logging anything `NEW`, and human-verify any posting that lives on a non-allowlisted host.

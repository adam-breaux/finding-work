# Fund Targets — career-page crawl list

> Curated, **fit-first** list of funds whose own careers/jobs pages we crawl for
> investor (Sr. Associate / Principal / track-to-Partner) and Chief-of-Staff seats.
> Scope chosen 2026-06-16: VC firms anchored in **Dallas / Austin / Denver hubs +
> genuinely remote-friendly**, weighted toward **hard tech / industrial / robotics /
> defense / energy** (Adam's love). See `knowledge-base/fit-criteria.md` for scoring.
>
> **Method:** go through each row, open the careers/jobs page, capture any open role,
> score it against the rubric, and log hits to `knowledge-base/opportunities.md`.

## How to use this file (the crawl loop)
1. Work top-down by tier (Tier 1 = best geographic + sector fit).
2. Open the **Careers/Jobs URL**. Where only a homepage is listed, find the
   careers/jobs/"join us" link on the site first, then update this row with the real URL.
3. Update **Status** + **Last checked** for every row you open.
4. Any open role → score it (`/score-role`) and log it to `opportunities.md`.

> ⚠️ **Crawl note (2026-06-17):** Direct `WebFetch` of fund sites is largely **blocked by
> anti-bot protection (HTTP 403 / Cloudflare)** — including John Gannon's board. The reliable
> method is **search-indexed lookups** (firm name + "careers/jobs/associate/principal"), which
> surface the live posting and its real application URL. Treat John-Gannon-sourced listings as
> *leads to verify* — they can lag the firm's actual openings.
>
> ⚠️ **Reality check on VC fund hiring:** funds rarely post their *own* (non-portfolio)
> openings publicly — many internal seats fill via warm intro. Getro/Consider boards linked
> from a fund usually list **portfolio-company** jobs, not fund roles — note the difference.

## Legend
- **Sector ⭐** = hard-tech / industrial / robotics / defense / energy lean (sector bonus).
- **Type:** VC · CVC (corporate venture) · PE · FO (family office).
- **Status:** 🔲 not checked · ✅ checked–role(s) found · ⬜ checked–no fund roles · ⚠️ URL needs fixing · ⛔ dead/renamed.
- URLs marked *(homepage)* still need the careers link located on first crawl.

---

## Tier 1 — Texas hubs (Austin · DFW · Houston / San Antonio) — ✅ CRAWLED 2026-06-17

| Firm | Location | Type | Sector ⭐ | Careers/Jobs URL | Status (result) | Last checked |
|---|---|---|---|---|---|---|
| Perot Jain | Dallas, TX | VC | ⭐ industrial / real estate tech / hard tech | https://perotjain.com/job-openings/ | ✅ logged (80). *Principal needs 7+ yrs → target Associate; postings 2023-dated, verify* | 2026-06-17 |
| Ironspring Ventures | Austin, TX | VC | ⭐ industrial / construction / supply chain | https://ironspring.com | ⛔ **Principal seats filled Mar-2025** (logged 88, PASSED — keep warm; best sector match) | 2026-06-17 |
| 8VC | Austin, TX | VC | ⭐ deep tech / defense / industrials / bio | https://www.8vc.com/jobs | ✅ CoS/platform roles on Ashby board (Dallas/Austin) — scan directly | 2026-06-17 |
| Trust Ventures | Austin, TX | VC | ⭐ hard tech in regulated industries / energy | https://www.trustventures.com | ✅ **Investment Associate** (Austin/remote) → logged (74) | 2026-06-17 |
| HOLT Ventures | San Antonio, TX | CVC | ⭐ industrial / heavy equipment / construction | https://www.holtventures.com (homepage) | ✅ Associate/Principal/Analyst → logged (72); confirm level | 2026-06-17 |
| Capital Factory | Austin / Dallas, TX | VC / accel | ⭐ generalist + TX defense network | https://jobs.capitalfactory.com | ✅ Venture Associate + IR Associate → already in pipeline (54) | 2026-06-17 |
| LiveOak Venture Partners | Austin, TX | VC | generalist / B2B (Texas) | https://jobs.liveoakvp.com | ✅ **Principal (partner-track)** + Associate → logged (86) | 2026-06-17 |
| Silverton Partners | Austin, TX | VC | generalist seed | https://jobs.silvertonpartners.com | ✅ **Principal (partner-track)** + Associate → logged (85); confirm open seat | 2026-06-17 |
| S3 Ventures | Austin, TX | VC | B2B / healthcare / infrastructure (TX-only) | https://jobs.s3vc.com | ⬜ Associate only — onsite Austin, up-or-out, below floor → pass | 2026-06-17 |
| Mercury Fund | Houston, TX | VC | ⭐ SaaS / data / industrial software | https://mercuryfund.com/position-opening-analyst/ | ⬜ Analyst only — below floor → pass | 2026-06-17 |
| SCOUT Ventures | Austin, TX / NY | VC | ⭐ dual-use / defense / frontier (veteran-led) | https://www.scout.vc | ⬜ Associate (NYC) — onsite + below floor → pass | 2026-06-17 |
| Sante Ventures | Austin, TX | VC | healthcare / biotech | https://www.santeventures.com | ⬜ Sr Analyst (healthcare) — below floor + off-sector → pass | 2026-06-17 |
| Tritium Partners | Austin, TX | PE (growth) | B2B / services / supply chain | http://www.tritiumpartners.com/pe-associate-job-posting-tritium-partners/ | ⬜ PE Associate — title below floor; PE secondary → low maybe | 2026-06-17 |
| Vista Equity Partners | Austin, TX | PE | enterprise software (large) | https://www.vistaequitypartners.com/careers | ⬜ multiple PE roles — large firm, deprioritized | 2026-06-17 |
| Moonshots Capital | Austin, TX | VC | ⭐ generalist, veteran-led (some defense) | https://www.moonshotscapital.com | ⬜ no current senior seat — monitor (posts Assoc/Analyst) | 2026-06-17 |
| KdT Ventures | Austin, TX | VC | ⭐ deep science / bio / chem / climate | https://www.kdtvc.com | ⬜ no fund roles open | 2026-06-17 |
| Ecliptic Capital | Austin, TX | VC | ⭐ deep tech / climate / materials / med | https://www.ecliptic.vc | ⬜ no fund roles open | 2026-06-17 |
| ATX Venture Partners | Austin, TX | VC | B2B SaaS / frontier / marketplaces | https://www.atxventurepartners.com | ⬜ no specific senior seat found | 2026-06-17 |
| Next Coast Ventures | Austin, TX | VC | consumer / B2B | https://www.nextcoastventures.com | ⬜ none found | 2026-06-17 |
| Elsewhere Partners | Austin, TX | VC (growth) | B2B software (non-hub outliers) | https://elsewhere.com (homepage) | ⬜ none found | 2026-06-17 |
| Breyer Capital | Austin, TX | VC | AI / generalist | https://breyercapital.com | ⬜ none found | 2026-06-17 |
| Multicoin Capital | Austin, TX | VC | crypto | https://www.multicoin.capital | ⬜ none confirmed (crypto sector) | 2026-06-17 |
| Trammell Venture Partners | Austin, TX | VC | bitcoin / early | https://tvp.fund/jobs/ | ⬜ board = portfolio bitcoin startups, no fund role | 2026-06-17 |
| Active Capital | San Antonio, TX | VC | B2B SaaS infrastructure | https://www.activecapital.com | ⬜ none found (small team) | 2026-06-17 |
| Dallas Venture Capital (DVC) / Naya | Irving, TX | VC | B2B SaaS / AI (relaunched as Dallas Venture Partners) | https://www.dallasventurecapital.com | ⬜ none found | 2026-06-17 |
| Green Park & Golf Ventures | Dallas, TX | VC | healthcare / medical | https://www.gpgventures.com | ⬜ none — healthcare focus, 5-person team | 2026-06-17 |
| RevTech Ventures | Dallas, TX | VC | retail / commerce tech | https://revtechventures.com | ⬜ internship only — below floor → pass | 2026-06-17 |
| New Climate Ventures | Houston, TX | VC | ⭐ climate / energy | https://www.newclimateventures.com | ⬜ no info / no roles found | 2026-06-17 |
| Artemis Fund | Houston, TX | VC | fintech / care / commerce | https://www.theartemisfund.com | ⬜ none found | 2026-06-17 |
| Genesis Park | Houston, TX | **PE** (reclassified) | aerospace / industrial — but **middle-market PE**, not VC | https://genesis-park.com | ⬜ no VC seats; middle-market PE | 2026-06-17 |
| ~~Cottonwood Venture Partners~~ → **Montrose Lane** | Houston, TX | VC | ⭐ energy / industrial digitization | (renamed) https://www.montroselane.com | ⛔ renamed to Montrose Lane — re-add under new name; no role found | 2026-06-17 |
| ~~Deep Space Ventures~~ | Dallas, TX | VC | — | — | ⛔ **defunct** (managing partner arrested 2018; inactive) — do not re-add | 2026-06-17 |

## Tier 2 — Denver / Colorado — ✅ CRAWLED 2026-06-17 (ATS + LinkedIn)

> **Result: no machine-verifiable live fund/investor/CoS seat at any of the 13.** None exposes a
> Greenhouse/Lever/Ashby board (probed across name variants — zero hits), and LinkedIn's public
> guest search surfaced only **portfolio-company** jobs (Blackhorn→Formic, Matchstick→Intelligems,
> Service Provider→NXC Imaging) or fuzzy matches at unrelated firms. These are mostly tiny seed funds
> that fill seats by network, not public posts. Firm career pages aren't on the egress allowlist, so a
> human click is still required to fully rule out an unposted seat. Nothing met the bar to log to `opportunities.md`.

| Firm | Location | Type | Sector ⭐ | Careers/Jobs URL | Status (result) | Last checked |
|---|---|---|---|---|---|---|
| Blackhorn Ventures | Denver, CO | VC | ⭐ industrial / built environment / resource efficiency | https://www.blackhornvc.com (homepage) | ⬜ no fund seat — LinkedIn shows only portfolio co (Formic) roles | 2026-06-17 |
| Foundry | Boulder, CO | VC | generalist (limited new investing) | https://www.foundry.vc (homepage) | ⬜ none — fund winding down new investing; 0 postings | 2026-06-17 |
| Access Venture Partners | Westminster, CO | VC | early B2B | https://www.accessvp.com (homepage) | ⬜ none found (fuzzy LinkedIn matches only) | 2026-06-17 |
| Range Ventures | Denver, CO | VC | early / local | https://www.rangevc.com (homepage) | ⬜ none found (fuzzy Denver-area matches only) | 2026-06-17 |
| Matchstick Ventures | Denver, CO / Mpls | VC | seed generalist | https://www.matchstick.vc (homepage) | ⬜ no fund seat — LinkedIn shows only portfolio co (Intelligems) | 2026-06-17 |
| Stout Street Capital | Denver, CO | VC | seed tech generalist | https://www.stoutstreetcapital.com (homepage) | ⬜ none found (no results) | 2026-06-17 |
| Service Provider Capital | Golden, CO | VC | co-invest / fund-of-funds | https://www.serviceprovidercapital.com (homepage) | ⬜ no fund seat — portfolio co only (NXC Imaging); FoF model anyway | 2026-06-17 |
| SpringTime Ventures | Denver, CO | VC | seed | https://www.springtime.vc (homepage) | ⬜ none found (fuzzy matches only) | 2026-06-17 |
| Boulder Ventures | Boulder, CO | VC | IT / life sciences | https://www.boulderventures.com (homepage) | ⬜ none found (fuzzy matches only) | 2026-06-17 |
| Techstars | Boulder, CO | accel / VC | generalist | https://www.techstars.com/careers | ⬜ posts accelerator/program-ops roles (e.g. Accelerator Program Manager, Boulder) — **no investor seat; below floor** | 2026-06-17 |
| Royal Street Ventures | Denver, CO / KC | VC | early generalist | https://www.royalstreet.vc (homepage) | ⬜ none found (no results) | 2026-06-17 |
| Greater Colorado Venture Fund | Telluride, CO | VC | rural / seed | https://www.greatercolorado.vc (homepage) | ⬜ none found (no results) | 2026-06-17 |
| Innosphere Ventures | Fort Collins, CO | VC | ⭐ hard science / health / cleantech | https://innosphereventures.org (homepage) | ⬜ none found (no results) | 2026-06-17 |

> **Incidental Denver-hub leads (NOT Tier 2 firms — surfaced repeatedly during the crawl; on-thesis, human-verify):**
> - **GridStor** — *Investment Associate*, Denver, posted 2026-06-16 — ⭐ energy storage / industrial. On-thesis.
> - **Booz Allen Ventures** — *Associate*, Denver, posted 2026-06-13 — ⭐ defense / dual-use CVC. Strong firm; level may sit below floor.
> - **Saturn Five** — *Operating Partner*, Denver, 2026-06-16 · **CB Partners** — *Senior Investment Analyst*, Denver, 2026-06-09 · **Kava Equity Partners** — *Senior Associate* (PE), Denver, 2026-06-16.
> → Consider adding GridStor + Booz Allen Ventures to the target list and `/score-role`-ing them after a human confirms they're live.

## Tier 3 — Remote-friendly + national hard-tech / industrial / defense

> Geography to confirm per-role (many are HQ'd on a coast but hire remote or for distributed roles).
> Sector fit is the reason they're here — strong ⭐ weighting.

| Firm | Location | Type | Sector ⭐ | Careers/Jobs URL | Status | Last checked |
|---|---|---|---|---|---|---|
| Eclipse Ventures | Palo Alto, CA | VC | ⭐ industrial / manufacturing / hard tech | https://www.eclipse.vc/careers | 🔲 | — |
| Lux Capital | New York / SF | VC | ⭐ deep tech / frontier | https://www.luxcapital.com/careers | 🔲 | — |
| DCVC (Data Collective) | San Francisco, CA | VC | ⭐ deep tech / compute / climate | https://www.dcvc.com/careers | 🔲 | — |
| Construct Capital | Washington DC / SF | VC | ⭐ industrial / manufacturing / supply chain | https://www.constructcap.com (homepage) | 🔲 | — |
| Founders Fund | San Francisco, CA | VC | ⭐ aerospace / defense / frontier | https://foundersfund.com (homepage) | 🔲 | — |
| Andreessen Horowitz (American Dynamism) | SF / DC | VC | ⭐ defense / industrial / space | https://a16z.com/jobs | 🔲 | — |
| Riot Ventures | Los Angeles, CA | VC | ⭐ hard tech / defense / autonomy | https://www.riot.vc (homepage) | 🔲 | — |
| Shield Capital | SF / DC | VC | ⭐ defense / security / AI | https://www.shieldcap.com (homepage) | 🔲 | — |
| Playground Global | Palo Alto, CA | VC | ⭐ robotics / hard tech / semis | https://www.playground.global (homepage) | 🔲 | — |
| Root Ventures | San Francisco, CA | VC | ⭐ hard tech / robotics seed | https://root.ventures (homepage) | 🔲 | — |
| Calibrate Ventures | Pasadena, CA | VC | ⭐ robotics / automation / AI | https://www.calibrate.vc (homepage) | 🔲 | — |
| Bee Partners | San Francisco, CA | VC | ⭐ robotics / frontier seed | https://www.beepartners.vc (homepage) | 🔲 | — |
| Cantos Ventures | San Francisco, CA | VC | ⭐ frontier / hard tech seed | https://www.cantos.vc (homepage) | 🔲 | — |
| Type One Ventures | Los Angeles, CA | VC | ⭐ deep tech / space | https://www.typeone.vc (homepage) | 🔲 | — |
| Embedded Ventures | Los Angeles, CA | VC | ⭐ dual-use / defense / space | https://www.embedded.ventures (homepage) | 🔲 | — |
| Marlinspike Partners | Arlington, VA | VC | ⭐ defense / national security | https://www.marlinspike.vc (homepage) | 🔲 | — |
| Razor's Edge Ventures | Reston, VA | VC | ⭐ defense / national security | https://www.razorsedge.vc (homepage) | 🔲 | — |
| Decisive Point | Washington DC | VC | ⭐ defense / dual-use | https://www.decisivepoint.com (homepage) | 🔲 | — |
| America's Frontier Fund | Washington DC | VC | ⭐ hard tech / national security | https://www.americasfrontierfund.org (homepage) | 🔲 | — |
| Space Capital | New York, NY | VC | ⭐ space / geospatial | https://www.spacecapital.com (homepage) | 🔲 | — |
| Toyota Ventures | Los Altos, CA | CVC | ⭐ robotics / climate / industrial | https://www.toyota.ventures (homepage) | 🔲 | — |
| AE Industrial Partners | Boca Raton, FL | PE | ⭐ aerospace / defense / industrial | https://www.aeroequity.com/careers | 🔲 | — |
| In-Q-Tel | Arlington, VA | strategic investor | ⭐ national security / deep tech | https://www.iqt.org/careers | 🔲 | — |
| At One Ventures | San Francisco, CA | VC | ⭐ climate / hard tech | https://www.atoneventures.com (homepage) | 🔲 | — |
| Congruent Ventures | San Francisco, CA | VC | ⭐ climate / industrial | https://www.congruentvc.com (homepage) | 🔲 | — |
| Energy Impact Partners | New York, NY | VC | ⭐ energy / industrial | https://www.energyimpactpartners.com (homepage) | 🔲 | — |
| Breakthrough Energy Ventures | Kirkland, WA | VC | ⭐ energy / climate hard tech | https://www.breakthroughenergy.org/careers | 🔲 | — |
| Fifty Years | San Francisco, CA | VC | ⭐ hard tech / climate / bio | https://www.fiftyyears.com (homepage) | 🔲 | — |
| Generate Capital | San Francisco, CA | sustainable infra | ⭐ infrastructure / energy | https://www.generatecapital.com/careers | 🔲 | — |
| Two Sigma Ventures | New York, NY | VC | ⭐ data / deep tech | https://www.twosigmaventures.com (homepage) | 🔲 | — |
| Pathbreaker Ventures | San Francisco, CA | VC | ⭐ frontier / hard tech seed | https://www.pathbreaker.vc (homepage) | 🔲 | — |
| Bessemer Venture Partners | Distributed | VC | generalist (remote-friendly) | https://www.bvp.com/careers | 🔲 | — |
| Initialized Capital | SF / remote | VC | generalist | https://initialized.com (homepage) | 🔲 | — |
| Hustle Fund | Remote-first | VC | pre-seed generalist | https://www.hustlefund.vc (homepage) | 🔲 | — |
| Precursor Ventures | San Francisco, CA | VC | pre-seed generalist | https://precursorvc.com (homepage) | 🔲 | — |
| NfX | San Francisco, CA | VC | generalist / network effects | https://www.nfx.com (homepage) | 🔲 | — |

---

## Tracking
- **Total firms:** 81 (Tier 1: 33 · Tier 2: 13 · Tier 3: 35) — *2 marked dead/renamed in Tier 1.*
- **Checked:** 46 / 81 (Tier 1 complete 2026-06-17 · Tier 2 complete 2026-06-17 via ATS + LinkedIn)
- **Roles logged to `opportunities.md` this crawl:** 6 from Tier 1 (Perot Jain · Ironspring · LiveOak · Silverton · Trust Ventures · HOLT) — **all later verified CLOSED/stale on 2026-06-17, see opportunities.md.** Tier 2 added **0** (no verifiable live fund seat).
- **Incidental Denver leads from Tier 2 crawl (not yet targets):** GridStor (Investment Associate ⭐), Booz Allen Ventures (Associate ⭐ defense CVC) — human-verify, then `/score-role`.
- **Next:** Tier 3 (remote + national hard-tech) — most are coastal but hire remote; sector-strong, worth the ATS/LinkedIn sweep.
- Add firms as discovered; mark dead/wound-down funds ⛔ with a note rather than deleting (so we don't re-add them). Montrose Lane (ex-Cottonwood) to be re-added cleanly under its new name.

> Note: Tier 2 & 3 careers URLs are still **seed entries, not yet verified** — confirm/fix each on first crawl.

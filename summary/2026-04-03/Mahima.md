# Weekly Performance Audit — Mahima
**Week: 30 Mar – 03 Apr 2026**

---

## SECTION A — EXECUTION AUDIT

### VALUE CREATED
- Budget scaled on PMax-Shoptimized1 (€6.40 → €10) against historical ROAS of 406.44 — defensible decision, but no post-scale metric delta reported to confirm it held
- New campaign created for low-stock products (<5 units) on Klarna Merchant platform — deployed artifact, no performance signal provided
- 7 new product listings created (02 Apr) — concrete inventory artifact, IDs documented
- Campaign cleanup executed (03 Apr): non-owned products excluded from campaign — direct structural fix preventing budget leakage, no metric delta provided
- Feed optimization across ~55 product IDs across the week targeting click-validated products — consistent methodology, zero ROAS delta reported

### OPPORTUNITY WASTED (COMPANY)
- Dead product intervention (2 products: 8299988975881, 5935512486055 — 3 months zero performance) → time invested in recovery with self-acknowledged low probability; removal would have freed budget signal immediately
- 12–16 products touched per day with no revenue-contribution ranking → optimization spread dilutes impact; top 3 revenue-driving SKUs never isolated or prioritized in any entry
- ROAS flagged AT RISK on 02 Apr; no corrective budget action or exclusion documented that day → one full trading day of potential bleed before Friday cleanup
- Budget scaled without documented ROAS guardrail or target floor → if PMax explores lower-intent traffic (self-identified risk), there is no stated threshold to trigger rollback

### OPPORTUNITY WASTED (CAREER)
- Self-critique is present in every EOD but behavior does not change day-to-day — spread across 12–16 products continues Monday through Friday despite flagging "shallow improvements" risk on Tuesday
- No single week-level output tied to a revenue number — 5 days of work, zero stated impact on spend efficiency, conversion rate, or revenue
- ROAS AT RISK declaration (02 Apr) is not followed by a documented corrective decision — flags a problem but does not own the fix; this is a visibility posture, not an ownership posture

### VALUE PER HOUR
**Low.** Estimated ~33 hours of work across the week produced no verifiable ROAS delta, no confirmed revenue lift, and no closed feedback loop between optimization actions and campaign performance. The single confirmed production artifact with structural impact is the campaign cleanup on Friday. Volume of activity was high; business impact is unconfirmed and self-rated as at-risk by mid-week.

### WEEKLY SCORE
**31 / 100**

### ONE-SENTENCE VERDICT
This week, Mahima was **Red** because five days of high-volume feed optimization produced zero documented ROAS improvement, ROAS was self-flagged as AT RISK by Thursday with no same-day corrective action, and no output was tied to a measurable revenue or efficiency outcome.

### NEXT-WEEK CORRECTION (SINGLE-THREAD FOCUS)
- **STOP:** Optimizing more than 5 products per day without ranking them by revenue contribution first
- **START:** Opening every day with a ROAS delta check (yesterday vs. 7-day avg) and making that the single decision gate before any feed or budget action
- **TEST:** By next Friday, PMax-Shoptimized1 post-scale ROAS must be documented with a before/after metric (baseline: 406.44 pre-scale); if ROAS has dropped >20%, a rollback or exclusion action must be logged with timestamp

---

## SECTION B — FORCED EXECUTION PIPE

**Single biggest failure: No closed feedback loop between optimization actions and ROAS/revenue outcomes.**

- **Task:** Build a daily ROAS delta log (spreadsheet or Google Sheet) tracking: campaign name | date | spend | revenue | ROAS | delta vs. 7-day avg | action taken
  - **Expected Outcome:** Every optimization decision is preceded and followed by a measurable signal; at-risk status is caught within 24h not 72h
  - **Success Signal:** Sheet exists, populated daily Mon–Fri, shared with STL by next Friday EOD

- **Task:** Rank all active product IDs by revenue generated (last 30 days) and create a tiered list: Tier 1 (top 10 revenue), Tier 2 (clicked, no revenue), Tier 3 (no clicks, no revenue)
  - **Expected Outcome:** All optimization effort next week is concentrated on Tier 1 only; Tier 3 products flagged for exclusion, not revival
  - **Success Signal:** Tiered list documented and attached to next Monday's EOD; zero Tier 3 products worked on next week

- **Task:** Set a ROAS floor guardrail on PMax-Shoptimized1 — define the minimum acceptable ROAS (suggest: 300, given historical 406.44) and document what budget/exclusion action triggers if breached
  - **Expected Outcome:** Budget scaling decisions have a defined rollback condition; no more open-ended scaling without a floor
  - **Success Signal:** Guardrail threshold documented in EOD by Monday; if ROAS drops below threshold, rollback action logged within same trading day

- **Task:** Exclude all Tier 3 (3+ months zero performance) products from all active campaigns — do not attempt revival
  - **Expected Outcome:** Budget signal concentrated on converting products; dead-weight removed from campaign learning
  - **Success Signal:** Exclusion list documented with product IDs and campaigns affected; completed by Wednesday EOD

- **Task:** Document post-scale performance of PMax-Shoptimized1 (budget €6.40 → €10) with week-over-week ROAS, spend, and revenue comparison
  - **Expected Outcome:** Decision to hold, increase, or rollback budget is data-driven and auditable
  - **Success Signal:** Before/after table (ROAS, spend, revenue, CPA) submitted in Friday EOD next week

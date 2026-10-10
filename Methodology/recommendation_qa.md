# Bean & Co. | Recommendation Quality Assurance

**Case snapshot:** October 2026  
**Decision under review:** Prioritise Bristol for site search and diligence; authorise **one pilot store only if site-level investment gates are satisfied**.  
**Scope:** Challenge the evidence, calculations, interpretation and proposed actions—not just the slide-deck narrative.

## 1. Executive recommendation and boundaries

**Recommended:** Prioritise **Bristol**, focusing initial property search on **Clifton / Whiteladies Road** and **Gloucester Road / Stokes Croft**. Pursue a **1 + 1 + 1 KPI-gated** rollout, starting with one proof-point store and no pre-commitment to stores two or three.

**Not recommended:** Immediate multi-store expansion, signing the example lease based on an incomplete occupancy-cost estimate, or eliminating Manchester from consideration.

**Reasoning:** Bristol leads the complete-city weighted screening (69.47), wins all six specified weighting scenarios, and offers a plausible premium-customer and neighbourhood-fit hypothesis. These are grounds for **priority diligence**, not proof of investability.

## 2. Core analytical QA checks

| Test | Expected / observed result | Status | Interpretation |
|---|---|---|---|
| Balanced weights | Customer 50% + Market 25% + Economics 25% = 100% | PASS | Defined scoring framework |
| Bristol balanced score | Approximately 69.47 | PASS | First among fully evaluated cities |
| Other complete-city scores | Birmingham 46.89; Leeds 36.31; Edinburgh 33.89 | PASS | Ranking reproducible from model |
| Manchester handling | Missing comparable Economics input; remains **unranked** | PASS | Not wrongly treated as zero or last |
| Edinburgh handling | Valid zero Economics score included | PASS | Corrected sensitivity logic |
| Weight sensitivity | Bristol wins six of six tested scenarios | PASS | Conditional on tested weights and data |
| Tightest scenario | Economics dominant: Bristol ~67.98 vs Birmingham ~65.94 | PASS | Lead only ~2.04 points |
| Revenue arithmetic | 300 × £5.38 × 360 = £581,040 gross | PASS | Hypothetical base case |
| Net sales simplification | £581,040 / 1.20 = £484,200 | PASS | Assumes all sales at 20% VAT |
| Pre-property contribution | £54,883.38 | PASS | Before occupancy costs |
| Known-cost Bristol contribution | £54,883.38 − £37,500 = £17,383.38 | PASS WITH CAVEAT | Excludes unverified rates/service charge |
| Fully loaded Bristol contribution | Blank until required property costs verified | OPEN | No investment-grade profitability claim |
| Source provenance | Working source register and evidence taxonomy exist | PARTIAL | Some original URLs/dates not independently reverified |
| Labour cost rule validation | Employer NI/pension application requires reconciliation | OPEN | Potentially changes P&L and hurdles |

`PASS` refers to an arithmetic or model-treatment check, **not** verification of the underlying commercial assumptions. For workbook-level tests, see `10_Formula_QA`, `02_Sensitivity` and `12_Publication_Check` in the Excel model.

## 3. Challenge the recommendation: five questions

### Q1. Is Bristol first because of a subjective scoring choice?

**Partly:** weights and some proxies are judgemental. Six alternative weightings still put Bristol first among four complete cities, but the Economics-heavy margin against Birmingham is small. A different evidence base, normalisation or set of weights could change the outcome.

**Decision response:** Use the score to allocate diligence effort, not as a stand-alone investment hurdle.

### Q2. Why is Manchester not ranked? Could it beat Bristol?

Manchester's comparable Economics score is missing. It is **not eliminated**. Under the balanced framework, the earlier analysis estimated that Manchester would need an Economics score of approximately **87.6** to tie Bristol, given the other inputs held constant. That is a *scenario threshold*, not an observed score.

**Decision response:** Source a comparable café-scale Manchester property, including rent, rateable value and service charges, then rerun the screen.

### Q3. Does Bristol's £17.4k contribution justify a lease?

**No.** The £17.4k is a known-cost-only illustrative contribution after asking rent; business rates and service charges are unresolved. It is not a fully loaded operating profit or a return on the illustrative £304k opening investment.

**Decision response:** Require a complete site P&L, cash-flow and downside investment case before lease approval.

### Q4. Are 300 transactions/day and £5.38 average ticket defensible forecasts?

They are **explicit assumptions**, not forecasts validated by store records or observed site footfall. Sensitivity testing demonstrates how formulas respond, not how likely a sales outcome is.

**Decision response:** Validate using manual footfall counts, catchment / daypart analysis, competitor observations, test trading or comparable operator benchmarks where lawful and available.

### Q5. Why launch one store instead of three?

Capital is limited and material demand, occupancy and execution uncertainties remain. A single proof-point store offers a way to test the commercial hypothesis before committing further capital. This is a **consulting recommendation**, not an empirically optimised rollout schedule.

**Decision response:** Stage further investment behind measurable pilot results rather than pre-signing multiple sites.

## 4. Pre-lease approval gates

| Gate | Evidence required | Current status |
|---|---|---|
| Location and customer demand | Defined catchment, footfall by daypart, competitor map, realistic conversion and average ticket | OPEN |
| Occupancy | Agreed rent terms, rateable value, rates estimate, service charge, insurance, lease obligations | OPEN |
| Operational feasibility | Planning / permitted use, layout, utilities, fit-out, staffing and supplier capacity | OPEN |
| Financial case | Fully loaded P&L, cash flow, capex quotations, downside scenarios and required return/payback threshold | OPEN |
| Pilot scorecard | Agreed KPIs, observation period, stop/go rules for Stores 2 and 3 | OPEN |

**No numeric go/no-go thresholds are presented as validated**: management would need to define its hurdle rate, acceptable payback and operating KPI gates before approving a real project.

## 5. Red-team alternative outcomes

- **Birmingham overtakes Bristol:** If actual Bristol occupancy and operating costs exceed assumptions, or Birmingham offers a better negotiated site and stronger measured conversion, Birmingham could be preferable despite its lower screening score.
- **Manchester re-enters:** New comparable occupancy evidence could produce a high Economics score and warrant rescoring.
- **Bristol wins the city screen but no site passes:** The correct decision is **do not invest yet**, not to force a lease to match the city recommendation.
- **Demand is weaker than expected:** A smaller format, revised location, delayed entry or no entry could dominate the base-case pilot.
- **Source refresh changes the rankings:** Changes to competitors, property availability or source definitions require documented model and deck updates.

## 6. Publication consistency checklist

Before making the GitHub repository public, confirm that:

- [ ] The deck, README, methodology and model use **Bristol as a provisional priority**, not an unconditional investment approval.
- [ ] Manchester is **unranked / active challenger**, not fifth.
- [ ] All six sensitivity scenarios include Edinburgh's valid zero Economics score.
- [ ] The £17,383 figure is labelled **known-cost-only**, not net profit or fully loaded return.
- [ ] Any deck slide showing post-property profit is updated to match the latest model's missing-cost treatment.
- [ ] The £304,000 opening requirement is clearly labelled illustrative.
- [ ] Labour rules and assumptions are reconciled before presenting a decision-grade P&L.
- [ ] Official-rule references and individual data-source links/dates are checked or explicitly marked outstanding.
- [ ] Canonical repository filenames and relative links work.
- [ ] No claim implies that Bean & Co. is a real client or that the author had access to proprietary trading data.

## 7. Final defensible answer

> **Prioritise Bristol for the next stage of market-entry due diligence, rather than committing capital immediately.** It leads the available weighted market screen and all six predefined sensitivity scenarios among fully scored cities. Begin with a single, KPI-gated pilot only if a specific Bristol property clears fully loaded commercial and financial hurdles. Keep Manchester under active review until its missing occupancy evidence is resolved, and retain Birmingham as a credible alternative.

This recommendation is intentionally **conditional**. The project demonstrates a structured decision process under imperfect public data, not a guaranteed store-level investment outcome.

---

*Companion references: [`methodology.md`](methodology.md), [`assumptions_and_limitations.md`](assumptions_and_limitations.md), [`../data/source_log.xlsx`](../data/source_log.xlsx).*

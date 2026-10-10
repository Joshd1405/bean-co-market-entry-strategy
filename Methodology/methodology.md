# Bean & Co. | Market Entry Strategy — Methodology

**Project type:** Independent strategy consulting portfolio case study  
**Client:** Bean & Co. (hypothetical UK premium coffee chain)  
**Case snapshot:** October 2026  
**Tools:** Microsoft Excel, public-source desk research, structured strategic analysis  
**Decision:** Prioritise Bristol for site-level due diligence; do not approve a lease until commercial and financial hurdles are met.

> **Important:** Bean & Co. is a hypothetical business created for this independent case study. Company-specific operating and financial inputs are illustrative assumptions, while external market indicators are drawn from public sources.

## 1. Business question and decision scope

Bean & Co. is assumed to operate 40 premium coffee shops concentrated in London and South-East England. Management is considering geographic expansion but has limited capital for the next phase. Five candidate cities were screened: **Manchester, Birmingham, Leeds, Bristol and Edinburgh**.

**Core question:** Which city should Bean & Co. enter next, and what market-entry strategy should it adopt?

The analysis separates two decisions:

1. **City prioritisation:** Which market appears most attractive under a consistent screening framework?
2. **Investment approval:** Does a specific site support a sufficiently robust, fully costed store-level investment case?

A city can rank first without any individual property yet being investable.

## 2. Problem structuring and hypotheses

The issue tree organised the decision around three primary branches:

| Branch | Decision question | Illustrative measures |
|---|---|---|
| Customer attractiveness | Is there a sufficiently large and commercially attractive potential customer base? | Population, growth, age profile, earnings, qualifications, student and employment-related indicators |
| Market attractiveness | Is there room for a differentiated premium coffee offer? | Broad café supply, premium competitors, chain presence and competitive density proxies |
| Economics and feasibility | Could a store operate sustainably at representative local property costs? | Asking rent per square foot, available units, site fit, rates, service charges and store contribution |

The initial working hypothesis was that a city with attractive premium-customer characteristics, manageable competitive intensity and viable occupancy economics would offer the strongest entry opportunity. The research tested this rather than presuming the largest city would win.

## 3. Geographic scope and comparability

The initial market screen used **local-authority / council-area boundaries** to obtain reasonably consistent public statistics. This is a practical screening geography, not a claim that local-authority boundaries equal the commercial catchment of a store.

Population, demographic, employment and education statistics may have different reference years and geographical definitions. These differences are retained in the underlying workbooks and evidence register rather than being treated as perfectly equivalent observations.

For actual site selection, analysis should move to a more granular trade area, such as a neighbourhood, postcode catchment, MSOA/LSOA (or Scottish data zone), supported by pedestrian flows, local demand generators, transport access and direct competitor mapping. The current work **does not** establish site-level footfall or customer conversion.

## 4. Data collection and evidence hierarchy

The research used public datasets and commercial-property listings, supplemented by clearly labelled analytical proxies and hypothetical operating assumptions.

| Evidence category | Treatment in this case |
|---|---|
| Reported / observed | Directly sourced measures, with the reference period and geography retained where available |
| Calculated | Transparent transformations of observed or assumed inputs, e.g. growth rates, densities and contribution calculations |
| Proxy | Indirect indicators where a direct measure was unavailable, e.g. SIC-based café supply or selected competitor counts |
| Calculated from proxy | Derived values whose reliability depends on proxy coverage |
| Assumption | Hypothetical Bean & Co. sales, staffing, costs, capex and trading conditions |
| Consulting judgement | Scoring weights, strategic interpretation, rollout gates and conditional recommendations |

**Traceability:** See [`../data/source_log.xlsx`](../data/source_log.xlsx) for the evidence classification, audit findings, official-rule references and open verification items. That register is a **working evidence log**: some individual primary-source URLs and publication/access dates remain incomplete and are not presented as verified.

### Important evidence limitations

- **Broad café supply:** SIC 56102 is broader than a precise census of specialty coffee shops.
- **Premium competitors:** A curated or mapped premium-competitor set is a market proxy, not an exhaustive, independently verified census.
- **Student population:** Provider-based enrolment does not necessarily map cleanly to a city-centre customer catchment.
- **Property listings:** Advertised rent is an asking price, not achieved rent. Availability, use permissions, fit-out condition and commercial terms may change.
- **Cross-city comparability:** Public data availability and property evidence quality differ across the five markets.

## 5. City scoring framework

The balanced screening model uses three weighted dimensions:

| Dimension | Weight |
|---|---:|
| Customer attractiveness | 50% |
| Market attractiveness | 25% |
| Economics | 25% |
| **Total** | **100%** |

The final score is calculated as:

\[
\text{Weighted city score} = 0.50(\text{Customer}) + 0.25(\text{Market}) + 0.25(\text{Economics})
\]

The component scores are modelled screening indices; **they are not probabilities of success or financial returns**. The weights are an explicit consulting judgement, not statistically estimated coefficients. The Excel model contains the component scores and formula-linked results.

### Balanced screening results

| City | Score | Screening status |
|---|---:|---|
| Bristol | 69.47 | 1st among fully evaluated cities |
| Birmingham | 46.89 | 2nd |
| Leeds | 36.31 | 3rd |
| Edinburgh | 33.89 | 4th |
| Manchester | — | **Unranked: incomplete comparable economics** |

**Missing-data rule:** A missing Economics input is not treated as zero. Manchester remains an active challenger, not an eliminated city. Edinburgh's **valid Economics score of zero** is included in calculations; a zero observed/modelled score is distinct from a missing score.

These rankings are a **prioritisation screen** rather than a precise measurement of total addressable demand or investment value.

## 6. Property market and site screening

The analysis reviewed representative retail / food-and-beverage properties in candidate trading areas. Properties were assessed for approximate size, location fit, stated use potential, asking rent, rent per square foot and available occupancy-cost disclosures.

Bristol's initial search focus is **Clifton / Whiteladies Road** and **Gloucester Road / Stokes Croft**, subject to site-level due diligence. A representative Whiteladies Road listing in the October 2026 research snapshot indicated approximately **1,331 sq ft** and **£37,500 annual asking rent** (approximately **£28.17 per sq ft**).

This listing is a modelling reference, **not** an instruction to lease that unit or a guarantee that it remains available. Before investment approval, Bean & Co. would need to confirm at least:

- Current availability, permitted use, lease terms and any premium or incentives.
- Actual rateable value, applicable business-rates treatment and relief eligibility.
- Service charge, insurance, utilities, repair obligations and fit-out requirements.
- Local pedestrian flow, daypart demand, competitor proximity and realistic transaction capture.

The model includes a 2026/27 business-rates calculation framework for England and Scotland, but **does not calculate an actual site's bill without its verified rateable value**. Asking rent is not a substitute for rateable value.

## 7. Store-level revenue and cost model

The model is a hypothetical mature-store screening case, built from explicit operating assumptions.

### Base-case revenue bridge

| Driver / output | Base case | Evidence treatment |
|---|---:|---|
| Transactions per trading day | 300 | Assumption; not an externally validated benchmark |
| Trading days per year | 360 | Assumption |
| Gross average transaction value | £5.38 | Model assumption informed by pricing work; not Bean & Co. actual sales |
| Gross till sales | £581,040 | 300 × 360 × £5.38 |
| Net revenue | £484,200 | Simplified all-sales-at-20%-VAT screening treatment |

The all-sales-at-20%-VAT treatment is a simplifying assumption; actual VAT treatment depends on the products and circumstances of supply. Gross consumer sales and net accounting revenue must not be conflated.

### Base-case contribution bridge

| Item | Annual value |
|---|---:|
| Net revenue | £484,200 |
| Cost of goods sold | (£132,075) |
| Gross profit | £352,125 |
| Labour | (£223,668.22) |
| Payment processing / packaging | (£13,073.40) |
| Other fixed operating costs | (£60,500) |
| **Pre-property contribution** | **£54,883.38** |
| Representative Bristol asking rent | (£37,500) |
| **Contribution after known costs only** | **£17,383.38** |

**Critical distinction:** £17,383.38 is **not a fully loaded operating profit or an approved investment return**. Business rates, service charges and other site-specific occupancy items remain incomplete. In the latest model, fully loaded contribution is intentionally left blank where required property-cost components are missing; a separate column retains the **known-cost-only** illustrative contribution.

The model also includes opening cash requirements (base-case **£304,000**) and scenario analysis. These are hypothetical investment-planning inputs rather than quotes or committed expenditure. An investment decision would additionally require credible sales validation, cash-flow timing, working capital, capex contingencies, lease obligations and an agreed return hurdle.

## 8. Sensitivity analysis and robustness

To challenge the scoring weights, the city screen was recalculated under six alternative weighting configurations:

| Scenario | Customer | Market | Economics | Highest-scoring fully evaluated city |
|---|---:|---:|---:|---|
| Balanced | 50% | 25% | 25% | Bristol |
| Demand dominant | 65% | 20% | 15% | Bristol |
| Economics dominant | 30% | 20% | 50% | Bristol |
| Competition dominant | 35% | 45% | 20% | Bristol |
| Customer + economics | 45% | 15% | 40% | Bristol |
| Near thirds | 34% | 33% | 33% | Bristol |

**Result:** Bristol ranks first in **six out of six tested weighting scenarios among the four fully evaluated cities**. This does **not** establish that Bristol would win every conceivable weighting or that Manchester would rank below Bristol once its economics are known.

The narrowest tested margin occurs in the **Economics-dominant** scenario, where Bristol scores approximately **67.98** versus Birmingham's **65.94**. This indicates that the conclusion is less comfortably separated when property economics receive a 50% weight.

The Excel workbook includes formula checks for scenario weight totals, completeness of evaluated cities, and Bristol's lead. It also includes revenue/P&L reconciliation checks and an input-change stress test; passing formula checks does not independently validate underlying market assumptions.

## 9. Recommendation and phased market entry

**Recommendation:** Prioritise **Bristol** for detailed site search and commercial due diligence. Start with **one proof-point store**, with Clifton / Whiteladies Road and Gloucester Road / Stokes Croft as initial trading-area candidates. Do not sign an unconditional lease on the basis of the city-screening score alone.

A potential expansion sequence is **1 + 1 + 1**, where further openings are gated by observed trading performance and satisfactory site-level economics rather than committed in advance.

### Investment gates before Store 1

1. Obtain and verify the full property cost stack: rent, business rates, service charges, insurance and other obligations.
2. Validate realistic daily transactions, ticket size, daypart mix and customer conversion using local evidence.
3. Confirm staffing, employer on-costs, VAT assumptions, cost of goods, capex and working-capital requirements.
4. Recalculate a fully loaded store P&L and cash-flow / return case under downside, base and upside scenarios.
5. Approve the lease only if the site clears management's explicitly defined financial and operational hurdles.

Manchester should remain an **active challenger** until a comparable, café-scale property and complete occupancy economics are available. Birmingham remains a useful comparison and potential fallback if Bristol fails site-level investment tests.

## 10. Quality assurance and outstanding limitations

The portfolio distinguishes **formula correctness**, **source reliability** and **commercial validation**:

- **Formula correctness:** Key revenue, cost and sensitivity calculations were linked and checked for arithmetic consistency. The base-case transactions/day input was also stress-tested and restored.
- **Source reliability:** Public-source provenance and evidence quality are tracked in `source_log.xlsx`; some primary-source links and dates require completion.
- **Commercial validation:** The model is **not yet decision-grade** because some site-specific property costs and actual demand evidence are unavailable.

Additional source-audit issues include verifying the application of employer National Insurance and pension assumptions, ensuring competitor-pricing provenance, and refreshing time-sensitive commercial-property observations. These are not silently treated as resolved by the scoring or financial formulas.

The conclusions are therefore conditional and deliberately narrower than a real-world investment approval.

## 11. Reproducibility and repository navigation

Recommended repository structure:

```text
bean-co-market-entry-strategy/
├── README.md
├── presentation/
│   └── Bean_and_Co_Market_Entry_Strategy.pdf
├── model/
│   └── Bean_and_Co_Market_Entry_Model.xlsx
├── data/
│   └── source_log.xlsx
└── methodology/
    ├── methodology.md
    ├── assumptions_and_limitations.md
    └── recommendation_qa.md
```

**Suggested review order:**

1. Read the final presentation for the executive storyline and conditional recommendation.
2. Inspect `model/Bean_and_Co_Market_Entry_Model.xlsx` for city scoring, sensitivity, revenue, costs and formula checks.
3. Review `data/source_log.xlsx` for evidence classification, audit findings and open source-verification items.
4. Read this document for the analytical logic and decision boundaries.

---

*This project was developed independently, It does not represent work commissioned by a real company, verified store trading results, or financial advice.*

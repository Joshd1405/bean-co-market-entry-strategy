# Bean & Co. | Assumptions and Limitations

**Case snapshot:** October 2026  
**Status:** Independent, hypothetical strategy consulting portfolio case  
**Companion files:** [`methodology.md`](methodology.md) · [`recommendation_qa.md`](recommendation_qa.md) · [`../data/source_log.xlsx`](../data/source_log.xlsx)

This document distinguishes externally sourced evidence from hypothetical operating assumptions and modelled outputs. It also identifies the principal uncertainties affecting the market-entry recommendation and the additional evidence required for investment approval.

## 1. What is assumed versus evidenced?

| Area | Input or approach | Classification | Key limitation / validation needed |
|---|---|---|---|
| Client | 40-store premium chain concentrated in London and South East England | Case premise | Fictional company, not a verified operator |
| Candidate markets | Manchester, Birmingham, Leeds, Bristol, Edinburgh | Case scope | Other UK cities were not assessed |
| Customer / market metrics | Population, earnings, qualifications, broad café supply and competitor mapping | Mixed: observed, calculated, proxy | Administrative geography and definitions do not equal site catchments; see source log |
| City scoring | Customer 50%; Market 25%; Economics 25% | Consulting judgement | Weight choice can affect rankings; not a statistical forecast |
| Property evidence | Sampled asking rents and selected property details | Reported listings / proxies | Listings may expire; rents are not agreed lease terms |
| Bristol example | Whiteladies Road, 1,331 sq ft, £37,500 annual asking rent | October 2026 listing snapshot | Rateable value, service charge, incentives, condition and permissions not fully established |
| Daily transactions | 300 in mature base case | Hypothetical assumption | Not measured footfall, conversion or company trading history |
| Trading days | 360 annually | Hypothetical assumption | No explicit downtime, closure or seasonal profile |
| Gross average ticket | £5.38 | Assumed basket | Not a validated Bean & Co. till-data average |
| VAT | All gross sales divided by 1.20 for net sales | Screening simplification | Actual VAT treatment varies by product and supply |
| COGS | £132,075 at base volume | Model assumption | Needs recipe, waste and procurement validation |
| Labour | £223,668.22 in base case | Model assumption | Staffing schedules, employer NI, pension and variable labour response need validation |
| Payment / packaging | £13,073.40 at base volume | Model assumption | Actual payment mix, fees and packaging costs unknown |
| Other fixed opex | £60,500 per year | Model assumption | Utilities, repairs, insurance and overhead allocations need quotations |
| Opening investment | £304,000 | Illustrative capex and cash requirement | Fit-out quotes, deposits, contingencies and financing not confirmed |
| Business rates | 2026/27 framework in `13_Rates_2026_27` | Statutory framework + conditional calculation | **Property-specific rateable value and relief eligibility missing** |
| Service charge | Not verified for Bristol example | Missing evidence | **Must not be silently treated as zero** |

The classifications above describe the provenance of the case inputs.

## 2. Financial model: what the numbers mean

The mature-store illustrative base case is:

| Metric | Base case | Calculation / interpretation |
|---|---:|---|
| Transactions per day | 300 | Assumed |
| Gross average transaction value | £5.38 | Assumed |
| Trading days | 360 | Assumed |
| Gross till sales | **£581,040** | 300 × £5.38 × 360 |
| Net sales | **£484,200** | Gross sales ÷ 1.20, simplified VAT treatment |
| COGS | £132,075 | Modelled |
| Gross profit | £352,125 | Net sales − COGS |
| Labour | £223,668.22 | Modelled |
| Payment / packaging | £13,073.40 | Modelled |
| Other fixed operating costs | £60,500 | Modelled |
| Pre-property contribution | **£54,883.38** | Before rent, rates and service charges |
| Sample Bristol asking rent | £37,500 | Representative listing |
| Contribution after *known* occupancy costs | **£17,383.38** | Pre-property contribution − asking rent; **not fully loaded** |
| Opening cash requirement | **£304,000** | Illustrative, not a validated investment budget |

£17,383.38 is *not* net profit, EBITDA, free cash flow, a verified site-level return or a lease approval metric. It omits unresolved occupancy components (notably rates and service charges) and does not establish financing, depreciation, taxation or capital recovery. The latest model intentionally leaves **fully loaded post-property contribution blank** when required property-cost inputs are missing. The separately labelled known-cost contribution is retained for transparency only.

A 10% transaction-volume test (300 to 330/day) demonstrates formula linkage, not real-world demand validation. In that test the labour assumption stays fixed, which may overstate incremental contribution at higher sales.

## 3. City-scoring and data-quality limitations

- **Geographic aggregation:** Local-authority / council-area statistics are a reasonable first-pass screen, but cannot substitute for a walkable trade-area study, observed pedestrian flows or store conversion.
- **Competitor measurement:** SIC 56102 includes businesses beyond specialty coffee shops; curated premium competitors and chain mapping are imperfect proxies.
- **Student demand:** Provider-based enrolment does not necessarily reflect students living, studying or spending in a particular neighbourhood.
- **Comparability:** Statistical reference years, data suppression and property listing availability vary across markets.
- **Weights and normalisation:** The 50/25/25 framework expresses strategic priorities. Scores are relative screening indices, not objective measures of probability or return.
- **Manchester:** Its comparable Economics input is unresolved, so it is **unranked**, not fifth. A missing input must not be replaced by zero.
- **Edinburgh:** Its Economics score of zero is a **valid modelled score** and is included in sensitivity testing. Zero is not missing.

## 4. Sensitivity analysis: what it does and does not prove

Bristol ranks first in **six of six predefined weighting scenarios** among the **four fully evaluated cities**. The narrowest margin is approximately **2.04 score points** against Birmingham under the Economics-dominant scenario.

This tests *weighting sensitivity only*. It does **not** test all plausible input errors, changes in competitor coverage, new site rents, actual trading performance or the missing Manchester Economics score. The six scenarios are not a probability distribution and do not make Bristol certain to succeed.

## 5. Business rates, employment costs and other open validation

The workbook's `13_Rates_2026_27` tab provides an **indicative** England / Scotland 2026/27 rates framework. It cannot determine the payable bill without a current rateable value, applicable reliefs and local confirmation. The sample asking rent must not be used as a substitute for rateable value.

The original source audit also flagged employer National Insurance threshold treatment and other labour-cost assumptions for checking. Any employer-cost update must be reconciled across `04_Store_PnL`, scenarios and presentation figures, with a recorded version change. **No such full recalculation is claimed here.**

Other material diligence gaps include:

1. Site-level rateable value, business rates, service charge, rent incentives and lease terms.
2. Planning / permitted use, landlord consent, fit-out specification, utilities and opening capex quotations.
3. Observed local footfall, conversion, customer ticket and trading-day seasonality.
4. Local wages, rota requirements, NI / pension implementation and capacity constraints.
5. Complete source URLs, publication dates and refresh dates for some external observations.
6. A comparable Manchester café-scale property to complete the five-city screen.

6. Implications for the recommendation

The analysis supports Bristol as the leading market for further investigation among the four cities with complete screening scores. However, the available evidence is insufficient to establish the commercial viability of any individual property.

The proposed entry strategy therefore prioritises site-level validation before capital commitment. This includes confirming occupancy costs, testing local customer demand, validating staffing requirements and preparing a fully costed investment case.

If Bristol fails to meet the required investment criteria, Birmingham remains an alternative for further consideration, while Manchester requires additional property evidence before it can be ranked.

---

*For methodology and source provenance, see the companion documents. This is an illustrative portfolio exercise, not a live commercial valuation or investment recommendation.*
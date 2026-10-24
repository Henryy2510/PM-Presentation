# Speaker Script — A New Value Strategy in the UK Stock Market

**Core route:** 14 slides, approximately 13 minutes (excluding Q&A). Names remain placeholders. Times are targets, not a requirement to rush. The slide footer carries source shorthand; full page/table references appear below and in `source_ledger_QA.md`.

## Speaker 1 — Hook and puzzle

### Slide 1 — A New Value Strategy in the UK Stock Market (0:20)
**Delivery:** Curious, open with the puzzle; do not read the title. **Emphasize:** “value” and “what investors pay.” **Cue:** Point from subtitle to the empty cover space.

“Value investing is often described as dead. This paper asks a more precise question: did value disappear, or did book-to-market stop measuring it well? We’ll follow the evidence from the UK market and finish with what the results still leave unresolved.”

**Transition:** “First, here is the paper’s answer in one minute.”

### Slide 2 — The paper argues that value survived, but book-to-market weakened as a signal (0:45)
**Delivery:** Confident, measured. **Emphasize:** 0.18%, 1.175%, implementation. **Cue:** Track the three numbered claims.

“The paper’s answer has three parts. First, the conventional book-to-market strategy becomes very weak after 2006: its reported average spread over 2006 to 2024 is 0.18 percent per month. Second, sorting on cash-based operating profitability divided by market capitalization produces a 1.175 percent monthly high-minus-low spread, with a t-statistic of 3.615. Third, a factor built from that signal adds information in several asset-pricing tests. That is strong evidence within this sample and test design. It does not tell us what an investor would keep after execution costs and shorting constraints. We’ll show how the measure works, then check how far the evidence carries.”

**Transition:** “The first clue is that one full-period average hides very different eras.”

### Slide 3 — Average B/M returns hide a post-2006 collapse and an unstable short leg (0:55)
**Delivery:** Investigative. **Emphasize:** +3.08%, −0.54%, +0.18%. **Cue:** Placeholder EXH-01; point to the subperiod values; preview that the leg decomposition follows on slide 9.

“The conventional strategy averages 0.79 percent per month across the full return period. But that headline combines a very strong 3.08 percent monthly spread from 2000 to 2005 with a negative 0.54 percent from 2006 to 2010. Across 2006 to 2024, the paper reports only 0.18 percent. The long and short legs also matter: in the full-period decile table, the high book-to-market portfolio earns 0.15 percent, while the low book-to-market portfolio loses 0.64 percent. The authors say most of the strategy’s profit comes from shorting that low-B/M decile. So a positive average alone does not establish a stable value mechanism.”

**Likely interruption:** “Does the paper show B/M is dead?” **Response:** “No. It documents weak UK performance in this sample, especially after 2006. It does not prove the signal has no use in every market or future period.”

**Transition:** “That motivates a different measure, but the idea has a prior lineage.”

### Slide 4 — The UK study tests whether Wang’s cash-based value signal travels across markets (0:55)
**Delivery:** Scholarly and precise; hand off clearly. **Emphasize:** inherited construct; UK evidence. **Cue:** DGM-01 lineage map.

“Fama and French made high-minus-low book-to-market a standard factor benchmark. Ball and coauthors developed cash-based operating profitability as an accrual-adjusted measure. Wang’s 2024 paper then used cash-based operating profitability relative to price to build a new US value strategy. Duong’s contribution is to test that strategy in the UK and to examine its role in factor models, including spanning, Fama–MacBeth, size partitions and GRS model comparisons. So the core measure is not invented here. The contribution is the UK application and its empirical evaluation. That distinction matters when we judge novelty.”

**Handoff to Speaker 2:** “The contribution therefore depends on more than a new ratio. We next need to see why the ratio might work and how the paper tests it.”

## Speaker 2 — Concept and methodology

### Slide 5 — CBOP/M links cash-based operating profitability to the price investors pay (0:55)
**Delivery:** Teacher-like, begin with intuition. **Emphasize:** accrual adjustments; divide by price. **Cue:** DGM-02 bridge, then formula.

“Start with operating profit: revenue less cost of goods sold and selling, general and administrative expenses. Accounting profit includes accruals, which shift recognition across periods. Ball and coauthors adjust operating profit for changes in working-capital accounts to form cash-based operating profitability, or CBOP. The paper adds increases in deferred revenue, accrued expenses and accounts payable, and subtracts increases in prepaid expense, inventory and accounts receivable. It then divides CBOP by market capitalization. That final step connects an operating signal to the market price investors pay. CBOP is accrual-adjusted profit; it is not literally a pure cash-flow measure. The idea is that this ratio may capture fundamentals relative to price more effectively than book equity does.”

**Likely interruption:** “Why call this value if it contains profitability?” **Response:** “The signal is profitability scaled by market price. The paper treats that as a fundamental-to-price measure; profitability and valuation are related components of the construct.”

**Transition:** “Now let’s see which stocks and months the test actually covers.”

### Slide 6 — A broad UK universe includes delisted firms, while the return test begins in 2000 (0:55)
**Delivery:** Clear, concise. **Emphasize:** 1995 vs 2000 start; delisted firms. **Cue:** Move left to right through the sample strip.

“The accounting universe runs from June 1995 through June 2024, while return tests begin in July 2000 because the paper needs five years of prior returns for one of its behavioral factors. The data combine London Share Price Database returns and Datastream accounting data. The final universe is about 1,700 non-financial firms listed on the London Stock Exchange. Foreign firms, financial firms, missing required accounting data and negative book equity are excluded. The authors include delisted firms where available, which reduces a clear survivorship concern. The data are proprietary or restricted, so we cannot claim an independent replication from the materials supplied.”

**Transition:** “The next design choice is how the annual signal becomes a return series.”

### Slide 7 — Annual accounting signals become twelve-month value-weighted portfolios (1:00)
**Delivery:** Process-focused; guard against look-ahead. **Emphasize:** July; next 12 months. **Cue:** Trace DGM-03 left to right.

“Each July, the study ranks eligible stocks using the previous fiscal year-end book-to-market or CBOP-to-market ratio. Stocks are sorted into deciles, and the portfolios are value weighted for monthly returns over the following twelve months. The process repeats annually, producing 288 monthly observations. The high-minus-low return is the return on the top signal decile minus the bottom signal decile. The paper describes the previous-year signal and July formation; for a strict replication, we would still want an explicit point-in-time reporting-lag convention for each accounting item. We should therefore describe the timing as the paper states it and identify publication-lag detail as a question, rather than assume the exact lag.”

**Likely interruption:** “Could there be look-ahead bias?” **Response:** “The paper uses prior fiscal-year-end accounting data at July formation, but the precise publication-lag rule is not detailed in the sample description. A point-in-time replication should document that rule explicitly.”

**Transition:** “The design uses four different tests because one return spread cannot answer every question.”

### Slide 8 — Four evidence layers test returns, incremental pricing, and robustness (1:00)
**Delivery:** Explanatory. **Emphasize:** each test answers one question. **Cue:** DGM-04 layers.

“First, portfolio sorts ask whether returns line up with the signal. Second, time-series alpha tests ask whether standard factors absorb the high-minus-low portfolio return. Third, spanning regressions ask whether the new factor is explained by existing factors; Fama–MacBeth asks whether its exposure carries a cross-sectional return premium. Fourth, size partitions and the GRS test look at robustness and joint model pricing. In the GRS comparison, a larger p-value means the model is less strongly rejected on those test portfolios. It does not directly measure expected returns, prove a model is true, or establish implementable superiority. The tests build a broader case, but each has a specific interpretation.”

**Handoff to Speaker 3:** “With the design in place, the decisive question is whether the new signal merely looks different—or actually survives these four tests.”

## Speaker 3 — Evidence, critique, and close

### Slide 9 — Traditional value is positive on average, yet structurally fragile (1:00)
**Delivery:** Analytical, skeptical but fair. **Emphasize:** 0.79%; short leg. **Cue:** EXH-02 diverging exhibit.

“The full-period B/M long-short result is 0.79 percent per month, with a t-statistic of 2.312. Yet the high-B/M long leg is only 0.15 percent, while the low-B/M short leg is minus 0.64 percent. Across subperiods, the strategy ranges from 3.08 percent in 2000 to 2005 to minus 0.54 percent in 2006 to 2010. The authors report 0.18 percent per month for 2006 to 2024. The point is not that shorting is illegitimate; it is that the result’s composition and time variation matter when assessing robustness and implementability.”

**Transition:** “Against that baseline, the CBOP/M deciles show a clearer ordering.”

### Slide 10 — CBOP/M produces an ordered return spread across deciles (0:55)
**Delivery:** Build energy at the result. **Emphasize:** high, low, spread. **Cue:** EXH-03 from decile 10 toward decile 1.

“The top CBOP/M decile earns 0.584 percent per month, while the bottom earns minus 0.592 percent. The high-minus-low spread is 1.175 percent per month, with a t-statistic of 3.615. The table shows the average return decreasing as we move down the CBOP/M ranking, and the paper describes this pattern as monotone. Unlike the B/M full-period spread, the authors describe the new strategy as having a balance between its long and short sides. This is the central empirical result. It is economically sizable as a gross historical average, but it is not yet a net return after trading frictions.”

**Likely interruption:** “Is the 1.175 percent annual?” **Response:** “No. It is a monthly average return. The study reports monthly portfolio returns; it does not report a transaction-cost-adjusted annual strategy return.”

**Transition:** “The next check is whether familiar factor exposures account for that spread.”

### Slide 11 — The CBOP/M premium remains positive after standard factor controls (1:00)
**Delivery:** Direct, careful. **Emphasize:** 0.532% minimum alpha; not arbitrage. **Cue:** EXH-04 dot plot.

“Across the reported benchmark models, the high-minus-low alpha ranges from 0.917 percent per month under the CAPM to 0.532 percent under the Fletcher five-factor model. The Fama–French three-, five- and six-factor estimates are 0.867, 0.716 and 0.606 percent. These are regression intercepts after controlling for the named factors. They show that these particular models do not absorb the entire historical return spread. They do not prove that investors can earn a free arbitrage, because implementation costs, borrow constraints and capacity are not measured here.”

**Likely interruption:** “Does alpha mean risk-free profit?” **Response:** “No. Alpha is relative to a specified model. Omitted risks and real-world trading frictions remain possible.”

**Transition:** “The factor tests then ask whether NVF adds information beyond HML.”

### Slide 12 — NVF adds information beyond HML in the paper’s tests (1:10)
**Delivery:** Technical but accessible; define each test in passing. **Emphasize:** 0.358%; 0.466%; p-value is model rejection evidence. **Cue:** EXH-05 and EXH-06 / Appendix A3.

“NVF’s average return is 0.831 percent per month, and its correlation with HML is 0.461, so the two factors overlap but are not identical. In a spanning regression, the NVF intercept is 0.358 percent per month with a t-statistic of 2.344. That asks whether existing factors explain NVF. In the joint Fama–MacBeth specification, NVF’s estimated premium is 0.466 percent with a t-statistic of 4.323, while HML’s estimate is 0.113 percent with a t-statistic of 1.576. Finally, when HML is replaced by NVF in the Fletcher five-factor model, the GRS p-value rises from 0.232 to 0.620. That is less evidence against the replacement model for these 25 test portfolios. It is not a direct test of net investment performance.”

**Likely interruption:** “Does the higher GRS p-value prove NVF is the better factor?” **Response:** “It supports improved joint fit in this test setup. A non-rejection is not proof of truth or universal superiority, and model selection and test assets matter.”

**Transition:** “The findings are promising, but the paper’s own conclusion leaves implementation as an open question.”

### Slide 13 — The evidence is strong statistically, but implementation remains open (1:05)
**Delivery:** Respectful reviewer voice. **Emphasize:** what paper does and does not test. **Cue:** Evidence / open / next test.

“The paper does several useful checks: it includes delisted firms where available, reports size-conditional CBOP/M results, uses alternative factor controls and compares GRS fit. It also explicitly acknowledges that transaction costs and income taxes are not addressed, while arguing that annual rebalancing limits their effect. That argument is plausible as motivation, but annual rebalancing alone does not quantify portfolio turnover, bid–ask costs, impact or the cost of shorting the low-signal leg. We would also want industry-neutral and liquidity-screened portfolios, exact point-in-time reporting lags, and a future holdout period. The authors themselves identify the source of the premium—risk or investor behavior—as a useful next question. A measured net-return study would strengthen the investment claim.”

**Likely interruption:** “Is the paper wrong to call this viable?” **Response:** “The return and factor evidence is reported correctly. Our narrower point is that a live, cost-adjusted implementation is not measured, so viability remains a hypothesis.”

**Transition:** “That brings us back to the opening question.”

### Slide 14 — The paper reframes value as a measurement problem, not a frictionless rule (0:55)
**Delivery:** Decisive, then calm. **Emphasize:** evidence; uncertainty; next study. **Cue:** Return to subtitle.

“The paper’s evidence says value did not simply vanish from the UK data: the signal used to measure it matters. CBOP/M and NVF outperform B/M in the reported return and factor tests. What remains uncertain is the economic mechanism and what survives realistic trading costs, shorting limits and a genuine future holdout. Our judgment is therefore precise: this is a persuasive measurement result and a promising factor result, not yet a demonstrated frictionless rule. A point-in-time, cost-aware replication is the next decisive test. Thank you.”

**Q&A lead:** Speaker 3 opens. Route construction questions to Speaker 2 and novelty questions to Speaker 1.

## Delivery routes

- **10-minute cut:** Slides 1, 2, 3, 5, 6, 7, 9, 10, 12, 13, 14. Give contribution in one sentence on slide 3; preview the test architecture in 15 seconds before slide 9; compress slide 11 into slide 12. Target 9:45–10:30.
- **20-minute route:** Use all 14 slides at a measured pace and open A1, A3 or A6 when a formula, estimate or implementation question benefits from detail. Do not add unrelated literature.
- **Core route timing:** approximately 13 minutes excluding Q&A. The script can be shortened by removing the labeled likely-interruption answers.

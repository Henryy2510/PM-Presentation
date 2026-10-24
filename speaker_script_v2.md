# Speaker script — V2

**Main deck:** 13 slides, three speakers, target 12–14 minutes. Appendices are reserved for Q&A. The script selects evidence rather than reading the slide. Figure/table locators are in `source_ledger_QA_v2.md`.

## Speaker 1 — The measurement puzzle (slides 1–4; ~3:10)

### Slide 1 — A New Value Strategy in the UK Stock Market (0:20)
**Script:** After 2006, the UK B/M spread averaged only 0.18% per month. This paper asks whether value weakened—or whether the conventional measure stopped capturing it well. We’ll follow the evidence from the accounting signal to the portfolio results, then ask what remains before calling it investable.
The percentage is a monthly portfolio spread, so read it as a historical average rather than a forecast for the next month.
The first sentence is the framing question; leave a beat after it so the audience can compare the two explanations.
**Cue:** Begin with the number, pause, then pose the question. Transition: “The paper’s answer is encouraging, with one important boundary.”

### Slide 2 — CBOP/M recovers a UK value premium that B/M largely lost after 2006 (0:50)
**Script:** The evidence has three anchors. The paper reports just 0.18% per month for B/M after 2006. Its alternative CBOP/M sort earns 1.175% per month between the high and low portfolios, with a t-statistic of 3.615. But net performance after trading costs is not tested. So our claim is specific: the accounting definition of value matters in this sample. The results do not yet establish that an investor could capture the gross spread after execution costs and shorting constraints.
The contrast motivates a new measurement question; it does not imply the strategies were compared after fees or under equal risk budgets.
This is the paper’s claim in compressed form, with the investment caveat visible before the technical details arrive.
**Cue:** Touch each anchor once. Transition: “To see why the paper changes the measure, first look at the old one.”

### Slide 3 — B/M weakened after 2006, while its full-period spread relied on the short leg (1:05)
**Script:** The left panel compares five subperiods. B/M falls from 3.08% in 2000–2005 to minus 0.54% in 2006–2010, then posts smaller positive averages. CBOP/M is positive in each reported period. The separate 0.18% figure is the paper’s aggregate 2006–2024 result, not one of those five bins. On the right, the full-period B/M spread is 0.79%, but its high portfolio earns only 0.15%; the low portfolio loses 0.64%. That composition makes the spread less reassuring as a stable long-only value signal. It motivates a different numerator and denominator, but does not by itself establish that the alternative is better.
That distinction is important because a full-period mean can conceal regime changes and concentration in one side of a long–short trade.
Because the periods differ in length, compare the direction and persistence rather than treating them as equally precise estimates.
**Cue:** Move left then right; distinguish periods from aggregate. Transition: “The alternative measure comes from a short research lineage.”

### Slide 4 — Research lineage: HML, CBOP, Wang, and the UK extension (0:55)
**Script:** Fama and French established book-to-market as a standard value factor. Ball and coauthors developed cash-based operating profitability as an accrual-adjusted accounting measure. Wang then used CBOP relative to price to build a US value strategy. Duong’s contribution is the UK application: testing whether the signal transfers to another market and whether its factor adds information in several pricing tests. Two natural extensions follow: measure real implementation frictions, and test whether accounting definitions that better reflect intangible investment change the comparison. The UK paper does not claim to have completed either extension.
The lineage also helps define novelty fairly: the UK contribution is an empirical extension and factor evaluation, not the invention of CBOP.
The arrows show where ideas converge and where the UK study adds evidence, keeping the contribution distinct from its antecedents.
**Cue:** Trace convergence to the UK study, then the two outgoing branches. Handoff: “Speaker 2 will show exactly how the accounting bridge works and how returns are formed.”

## Speaker 2 — Measurement and design (slides 5–8; ~4:00)

### Slide 5 — CBOP/M replaces book equity with an accrual-adjusted operating numerator (1:00)
**Script:** Begin with operating profit: revenue less cost of goods sold and selling, general and administrative expense. The paper adjusts this base for working-capital accruals. It adds changes in deferred revenue, accrued expenses, and accounts payable, while subtracting changes in prepaid expense, inventory, and accounts receivable. The resulting CBOP is then divided by market capitalization. This keeps the operating numerator but scales it by the price investors pay. It is an accrual-adjusted profit measure, not literally a pure cash-flow total. The appendix gives every variable and sign; the main point is that the signal changes both the accounting content and its scaling.
The denominator matters because two firms with similar operating fundamentals can offer different signals when their market valuations differ.
The parallel layout matters: each adjustment reconciles accrual recognition, rather than representing a separate chronological step.
**Cue:** Point to the parallel adds and subtracts, then the denominator. Transition: “That signal is tested in a broad but screened UK sample.”

### Slide 6 — The study covers about 1,700 nonfinancial LSE firms (0:55)
**Script:** Accounting data run from June 1995 to June 2024, while the return series starts in July 2000 and ends in June 2024. The paper reports roughly 1,700 nonfinancial London-listed firms and 288 monthly return observations. Financial firms, foreign firms, observations with missing required accounting data, and firms with negative book equity are excluded. Delisted firms are included where available, which helps reduce survivorship concerns, though it does not guarantee complete coverage. This is a substantial historical sample, but its accounting and return sources are not a public replication dataset in the supplied materials.
The exclusions define the population to which the evidence applies, and missing accounting records can still affect who enters the portfolios.
The return period is shorter than the accounting period because portfolio formation requires historical inputs and return availability.
**Cue:** Separate the two date ranges. Transition: “The timing rule turns those records into annual portfolios.”

### Slide 7 — Prior-year accounting data map to July–June portfolio returns (1:00)
**Script:** The paper uses previous fiscal-year-end accounting information to rank eligible stocks at the July formation. Stocks enter ten portfolios, which are value weighted and held over the following twelve months of returns. At the next July, the sort is repeated. That creates the monthly high-minus-low strategy and its time series. The paper’s description supports this prior-year and July–June sequence. It does not spell out a detailed, security-level public-reporting lag in the sample passage, so we flag that as a replication requirement. We should neither assume perfect point-in-time availability nor claim that look-ahead bias has been demonstrated.
The loop clarifies that the strategy is refreshed periodically, while monthly returns inside each holding window still vary with the market.
That caveat is a transparency point; a replication can resolve it by documenting filing dates and a fixed lag rule.
**Cue:** Trace the horizontal time axis and annual loop. Transition: “Different tests then answer different questions about the resulting returns.”

### Slide 8 — Four tests move from return patterns to incremental factor evidence (1:00)
**Script:** Portfolio sorts ask whether average returns line up with the signal. Time-series alpha asks whether standard factor models absorb the high-minus-low return. Correlation, spanning, and cross-sectional pricing ask whether the new factor contains information beyond HML. Finally, GRS tests compare joint model fit for specified test assets. Each result is conditional on its portfolios, sample, and model. A larger GRS p-value means the model is less strongly rejected in that test; it does not prove the model true. None of these tests includes the trading-cost and shorting analysis needed to establish implementability.
These tests are complementary evidence, but they are not a single ladder where passing one automatically validates the next.
In other words, the matrix separates a return pattern from pricing evidence and from practical investability.
**Cue:** Read the matrix by research question, not by box order. Handoff: “Speaker 3 will now focus on the central result and its limits.”

## Speaker 3 — Results and boundary (slides 9–13; ~5:00)

### Slide 9 — CBOP/M produces a strongly ordered decile pattern and a 1.175% monthly spread (1:05)
**Script:** This is the central result. The portfolios are ordered from high CBOP/M at D1 to low CBOP/M at D10. The high portfolio averages 0.584% per month; the low portfolio averages minus 0.592%. Their high-minus-low difference is 1.175%, with a t-statistic of 3.615. The intermediate portfolios show a strong overall ordering, although adjacent values are not perfectly descending at every step. This is a meaningful gross historical spread and the paper’s strongest visual result. It is still a portfolio-sort estimate, not a net return after fees, spreads, market impact, or short-borrow costs.
The decile values also show why the endpoint spread is informative: the comparison uses both a positive high-signal return and a negative low-signal return.
Treat the t-statistic as evidence against a zero mean under the paper’s setup, not as a guarantee of future performance.
**Cue:** Let the full bars register; point to D1, D10, then the spread. Transition: “The next question is whether standard risk controls absorb it.”

### Slide 10 — The spread remains positive across five factor models (0:55)
**Script:** The monthly alpha declines as the models add controls: from 0.917% under CAPM to 0.532% under the Fletcher five-factor model. Each of the five reported estimates remains positive, and each t-statistic is shown beside its estimate. This means those particular models do not absorb the entire average spread in the sample. It does not prove a risk-free return. The estimates remain exposed to model choice, omitted risks, and the unmeasured costs of constructing the long and short portfolios.
The shrinking estimate is a useful reminder that model controls change the magnitude even when the sign remains positive.
The plotted coefficients are estimates, and the printed t-statistics convey precision without implying an interval that was not reported.
**Cue:** Scan from the first to last model and avoid calling alpha arbitrage. Transition: “The factor tests make the comparison with HML more direct.”

### Slide 11 — NVF overlaps with HML but retains distinct pricing information (1:05)
**Script:** NVF and HML are related, with a reported correlation of 0.461, but they are not identical. In the spanning test, NVF’s intercept is 0.358% monthly with a t-statistic of 2.344. In the joint Fama–MacBeth result, NVF’s estimated price of risk is 0.466%, t-statistic 4.323; HML’s is 0.113%, t-statistic 1.576. Taken together, these tests support incremental information within the paper’s sample and setup. They do not identify whether the premium reflects risk, investor behavior, or another mechanism. The detailed GRS model comparisons are in Appendix A6.
A factor can be correlated with an established factor and still contribute conditional information; the reported tests quantify that distinction here.
Keep the mechanism question open: pricing evidence can be incremental without identifying why the premium exists.
**Cue:** Correlation first, spanning second, cross-sectional estimate last. Transition: “A constructive review asks what evidence would make this result investable.”

### Slide 12 — The evidence supports measurement improvement; net investability is untested (1:10)
**Script:** The paper provides a long UK sample, includes delisted firms where available, and checks several factor specifications. The next steps are designed to strengthen that evidence. First, measure turnover, spread, market impact, and borrow fees to obtain net returns. Second, use point-in-time reporting lags and a future holdout or rolling design to reduce sample-specific discovery. Third, test liquidity, microcap exposure, capacity, and short availability. Fourth, compare industry-neutral or intangible-aware definitions to see which part of the accounting signal matters. These are proposals, not tests the paper reports. The paper’s annual rebalance may limit some turnover, but frequency alone cannot quantify costs.
A credible next study would predefine these checks and report failures as well as successful specifications to limit selective reporting.
These proposals can be evaluated sequentially, but the most useful first result is a transparent gross-to-net decomposition.
**Cue:** Treat each row as a research extension, not a fault list. Transition: “That distinction gives us a concise conclusion.”

### Slide 13 — CBOP/M improves the UK value signal; net performance remains unknown (0:40)
**Script:** The paper’s strongest contribution is a measurement result: in this UK sample, CBOP/M produces a stronger value-related return signal than conventional book-to-market. Its factor also carries incremental information in the reported tests. Whether that result survives realistic costs, shorting limits, point-in-time data, and new observations remains unknown. The next decisive step is a transparent net-return replication. We’ll use Appendix A8 to route detailed questions to the formula, estimates, model comparison, or implementation design.
Our conclusion is deliberately bounded to the reported UK evidence and the tests shown in the paper.
Appendix A8 provides the route so the closing claim stays focused while detail remains available for discussion.
**Cue:** End on the evidence boundary; no extra closing slide.

**Q&A routes:** formula/construction → Speaker 2, A1–A2; estimates/asset-pricing tests → Speaker 3, A3/A6; lineage/novelty → Speaker 1, A4; implementation → Speaker 3, A5/A7; navigation → A8.

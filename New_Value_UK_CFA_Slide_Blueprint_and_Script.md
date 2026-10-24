# A NEW VALUE STRATEGY IN THE UK STOCK MARKET

**When Traditional Value Fades: Reconstructing the Evidence, Testing the Claims, and Designing the Next Experiment**

*Source study: Le Quy Duong (2025), “A new value strategy in the UK stock market,” Journal of Economic Studies, DOI: 10.1108/JES-03-2025-0190.*

**Format:** CFA-style quantitative research presentation | **Main deck:** 15 slides | **Target speaking time:** approximately 16–17 minutes including technical pauses (acceptable range: 12–18 minutes) | **Delivery:** academic English, approximately 130–150 spoken words per minute | **Audience:** students unfamiliar with the paper, followed by critical discussion with the author.

**Evidence rules:** All reported numerical findings below come from the supplied paper unless explicitly labelled *illustrative*, *calculated from reported numbers*, or *proposed experiment*. This document does **not** claim independent replication, access to the original security-level dataset, a completed trading backtest, causal identification, or verified net performance. Page references count pages in the provided 20-page PDF.

**Design specification:** 16:9; warm off-white background; deep navy for baseline B/M; restrained teal for CBOP/M or NVF; muted burgundy only for caveats; one conclusion-led headline per slide; approximately 34–42 pt titles and 20–26 pt key content; chart labels large enough for the back of a lecture hall. Footer navigation: **Problem → Construct & Design → Evidence → Critical Tests**. Source citation in lower-right footer. Never draw cumulative wealth, confidence intervals, or backtested Sharpe ratios from summary statistics alone.

---

## SLIDE 1 — Is Value Investing Dead, or Are We Measuring Value Incorrectly?

### 1. Nội dung hiển thị trên Slide

- **Core thesis:** The way we measure fundamental value may determine whether the value premium is detectable.
- **Question:** Does cash-based operating profitability reveal information missed by book-to-market?
- **Boundary:** Evidence of a priced return spread is not yet evidence of a frictionless investment strategy.
- **Paper:** Duong (2025), UK listed equities, July 2000–June 2024.

**Công thức:** None on the opening slide.

**Dữ liệu nổi bật:** Avoid juxtaposing B/M *post-2006* with CBOP/M *full-sample* figures as if they were a matched comparison.

**Visual/Chart:** Split-screen editorial visual: left “Traditional value: B/M”, right “New value: CBOP/M”, joined by a question mark. No faux performance lines. Hero headline occupies the top half; author citation discreetly below.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 0:40 | Cue: Make eye contact; pause after the opening question.]**
>
> Is value investing dead, or have we been measuring value incorrectly? This is the question behind Professor Le Quy Duong’s study of the UK equity market. For decades, investors used book-to-market to separate cheap stocks from expensive stocks. But the traditional value premium weakened substantially in more recent years. The paper asks whether a different accounting measure—cash-based operating profit relative to market value—can recover useful information. Today, I will reconstruct the research design, examine the empirical evidence, and identify precisely what we would need to test before calling the result an investable strategy.

---

## SLIDE 2 — The Research Gap Is Measurement, Not the Invention of Value Investing

### 1. Nội dung hiển thị trên Slide

- **Conventional benchmark:** Fama–French book-to-market factor, HML.
- **Accounting rationale:** Book equity may underrepresent economic resources, particularly internally generated intangibles.
- **Closest predecessor:** Wang (2024) tests a CBOP-to-price value strategy in US equities; Duong (2025) extends the empirical setting to the UK.
- **Research questions:** RQ1 — Does B/M weaken? RQ2 — Does CBOP/M sort returns more effectively? RQ3 — Does NVF add factor-pricing information?

**Dữ liệu:** Reported traditional UK B/M premium after 2006: **0.18% per month** (paper abstract and conclusion). This is a *period-specific* fact, not yet a matched comparison with the entire CBOP/M sample.

**Visual/Chart:** Horizontal three-node literature timeline: Fama–French (B/M and HML) → Ball et al. (2016: CBOP construct) and Wang (2024: US strategy) → Duong (2025: UK validation and asset-pricing tests). Each arrow states the exact contribution, avoiding a claim that CBOP/M was first invented by Duong.

**Source:** PDF pp. 1–3; Introduction and Literature Review.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 0:55 | Cue: Point to each node in the research lineage.]**
>
> The study builds on a well-established literature rather than proposing value investing from scratch. Fama and French made book-to-market a central valuation signal and introduced HML as a widely used value factor. More recent work questioned the strength of this premium and the informational completeness of book equity. Ball and colleagues developed the cash-based operating profitability measure, and Wang subsequently applied a cash-based profitability-to-price strategy to US stocks. Duong’s contribution is to investigate that approach in the UK and examine not just portfolio returns, but also whether the resulting new value factor adds explanatory power to asset-pricing models. These are three related, but distinct, research questions. Notice that a strong portfolio spread, an unexplained factor alpha, and a model-fit improvement are different pieces of evidence. We need to evaluate each on its own terms.

---

## SLIDE 3 — CBOP Changes the Numerator: It Is Not Simply Cash Flow

### 1. Nội dung hiển thị trên Slide

- **Traditional valuation ratio:** B/M = book equity ÷ market capitalization.
- **New valuation ratio:** CBOP/M = accrual-adjusted operating profit ÷ market capitalization.
- **Cash-based operating profit:** Adjust operating profit for selected changes in working-capital accounts.
- **Interpretation:** Two firms with identical reported operating profits may have different CBOP/M signals.

**Công thức (exact construct reported in the paper):**

$$
B/M_t=\frac{BookEquity_t}{MarketCap_t},\qquad CBOP/M_t=\frac{CBOP_t}{MarketCap_t}
$$

$$
OP_t = Revenue_t - COGS_t - SG\&A_t
$$

$$
\begin{aligned}
CBOP_t = OP_t
&+\Delta DeferredRevenue_t+\Delta AccruedExpenses_t\\
&+\Delta AccountsPayable_t-\Delta PrepaidExpense_t\\
&-\Delta Inventory_t-\Delta AccountsReceivable_t,\\
CBOP/M_t &= CBOP_t / MarketCap_t.
\end{aligned}
$$

**Giải thích ký hiệu:** $\Delta X_t=X_t-X_{t-1}$; $OP$: operating profit; $COGS$: cost of goods sold; $SG\&A$: selling, general and administrative expenses; $MarketCap$: market equity value. Changes in accounting accounts are signed according to the formula; **CBOP is not identical to reported cash flow from operations or free cash flow**.

**Illustrative teaching example (NOT paper data):**

| Illustrative inputs | Company A | Company B |
|---|---:|---:|
| Operating profit | 20 | 20 |
| Change in receivables | +12 | 0 |
| All other accrual adjustments | 0 | 0 |
| CBOP | 8 | 20 |
| Market capitalization | 200 | 200 |
| **CBOP/M** | **4%** | **10%** |

**Visual/Chart:** Accounting waterfall: Operating Profit → plus three adjustments → minus three adjustments → CBOP → divide by market capitalization. A smaller two-company card demonstrates the economic consequence. X-axis: components of the accounting bridge; Y-axis: illustrative accounting units. Insight: measured profitability changes even when reported OP is identical.

**Source:** PDF p. 4, Section 3.2; illustrative numbers are author-designed pedagogy.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:20 | Cue: Write “same OP, different CBOP” in the air or point to the two firms.]**
>
> Before interpreting any return, we must understand what the signal measures. Traditional book-to-market compares book equity with the market value of equity. The proposed signal instead scales cash-based operating profit by market capitalization. Operating profit starts with revenue minus cost of goods sold and selling, general, and administrative expenses. The author then adds changes in deferred revenue, accrued expenses, and accounts payable, and subtracts changes in prepaid expenses, inventory, and accounts receivable. These adjustments change the information contained in reported profits. Consider two hypothetical companies, each earning twenty units of operating profit and valued at two hundred units. If Company A’s receivables rise by twelve units while everything else stays constant, its CBOP falls to eight; Company B’s remains twenty. Their CBOP-to-market ratios become four and ten percent. The key lesson is not that one company must be a better investment. It is that the accounting definition changes the ranking. Importantly, CBOP is an accrual-adjusted profit measure, not literal free cash flow. Whether its ranking advantage reflects improved accounting measurement or a different exposure to firm characteristics is precisely what further controlled comparisons should investigate.

---

## SLIDE 4 — The UK Sample Supports Historical Testing, Not Yet Real-Time Replication

### 1. Nội dung hiển thị trên Slide

- **Universe:** Approximately 1,700 non-financial UK companies listed on the London Stock Exchange; foreign companies excluded.
- **Sources:** LSPD for monthly stock returns; Datastream for accounting fundamentals.
- **Accounting data window:** From June 1995; **return test:** July 2000–June 2024 = **288 monthly observations**.
- **Exclusions:** Missing accounting data; negative book equity. Delisted companies included where available.
- **Open detail:** The text does not document individual financial-statement publication timestamps or a field-by-field point-in-time data audit.

**Công thức (monthly count):** $24\text{ years}\times 12 = 288\text{ months}$.

**Visual/Chart:** Large timeline: 1995 (data history) → July 2000 (first test return) → June 2024 (last return). Beneath: two-row data-provenance strip. Use a dashed question marker between fiscal-year accounting observation and public release date; do not invent a lag.

**Source:** PDF pp. 3–4, Section 3.1 and Section 3.2.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:00 | Cue: Emphasize the distinction between accounting date and information availability.]**
>
> The empirical setting matters as much as the formula. The sample covers roughly seventeen hundred non-financial companies listed in the UK. Monthly returns come from the London Share Price Database, while accounting information comes from Datastream. The return analysis begins in July 2000 and ends in June 2024, giving twenty-four years, or two hundred eighty-eight monthly observations. The author excludes foreign and financial firms, missing-accounting observations, and firms with negative book equity; delisted stocks are included where available. This is a substantial historical sample. However, an accounting number dated at fiscal year-end is not necessarily public on that date. For an independent live-feasible replication, we would also require the exact dates when each accounting item became available. Without those dates, we can describe the published historical design, but we cannot certify that a new independent implementation would be free of look-ahead bias.

---

## SLIDE 5 — A Valuation Ratio Becomes a Strategy Through Portfolio Construction

### 1. Nội dung hiển thị trên Slide

- **Each July:** Sort eligible UK stocks into ten groups by the previous fiscal-year B/M or CBOP/M.
- **Returns:** Compute value-weighted monthly portfolio returns over the next 12 months; rebalance annually.
- **Decile spread:** Long highest-ratio decile, short lowest-ratio decile.
- **Different factor construct:** NVF is formed with a *2 × 3 size/CBOP-M double sort*, not by simply relabelling the decile spread.
- **Breakpoints for factor construction:** Size median and 30/70 valuation thresholds derived using the largest 350 stocks.

**Công thức:**

$$
R_{D,t}=\sum_{i\in D} w_{i,t}\,R_{i,t},\quad
R_{H-L,t}=R_{High,t}-R_{Low,t}
$$

$$
NVF_t=\frac{1}{2}\left(R_{BV,t}+R_{SV,t}-R_{BG,t}-R_{SG,t}\right)
$$

Here $B/S$ denote big/small, $V/G$ value/growth, and weights $w_{i,t}$ reflect the paper's value-weighted returns. **The paper specifies annual portfolio formation; execution-level share turnover and exact weight-drift conventions are not supplied.**

**Visual/Chart:** Left-to-right process diagram: previous fiscal-year signals → July sorting → decile portfolios → twelve monthly outcomes; bottom lane separately shows the 2×3 NVF factor construction. No dollar P&L unless security-level returns and costs are available.

**Source:** PDF pp. 4–6, Sections 3.2–3.3.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:10 | Cue: Trace the arrow from signal to holding-period return.]**
>
> A valuation ratio becomes a trading rule only after we specify portfolio construction. At the beginning of July, the author ranks stocks by the relevant accounting-to-market ratio, using prior fiscal-year information. Stocks enter ten portfolios, and their value-weighted monthly returns are observed over the following year. The headline strategy buys the highest-ratio decile and shorts the lowest-ratio decile. Its gross return is the high portfolio’s return minus the low portfolio’s return. But an important distinction follows: the new value factor, or NVF, is not exactly this decile spread. It is built from a separate two-by-three sort using size and CBOP-to-market. Confusing these constructions would cause us to misinterpret three different reported return statistics later in the presentation. In a quantitative presentation, the object being estimated must always be stated before its numerical result.

---

## SLIDE 6 — The Paper Tests Return Ordering, Risk Adjustment, and Pricing Information

### 1. Nội dung hiển thị trên Slide

- **Test 1 — Portfolio sorts:** Does return increase with CBOP/M?
- **Test 2 — Time-series factor regressions:** Does the spread retain an intercept after benchmark risk controls?
- **Test 3 — Spanning and Fama–MacBeth:** Does NVF provide information not contained in existing factors, and carry a cross-sectional price of risk?
- **Test 4 — GRS:** Do rival factor sets jointly explain returns on selected test assets?
- **Factor families tested:** CAPM; Fama–French 3-, 5-, 6-factor; Fletcher et al. (2024) UK 5-factor including market, HML, profitability, momentum, and behavioral financing.

**Công thức (time-series OLS):**

$$
R^{H-L}_{t}=\alpha_{H-L}+\sum_{k=1}^{K}\beta_k F_{k,t}+\varepsilon_t
$$

- $R^{H-L}_{t}$: gross monthly high-minus-low return.
- $F_{k,t}$: returns on the selected benchmark factors; $\beta_k$: exposure to factor $k$.
- $\alpha_{H-L}$: mean return not captured by those factor exposures **within that model**. Its statistical significance does not measure net trading profitability.

**Visual/Chart:** Four numbered questions with increasing evidentiary ambition; a ribbon underneath names CAPM, FF3, FF5, FF6, Fletcher5. X-axis: test sequence, not calendar time; Y-axis: none. Do not display GMM, Black–Scholes, instrumental variables, or causal treatment effects: **they are not analyses performed in this study.**

**Source:** PDF pp. 4–6, 13–17, Sections 3–5.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:20 | Cue: Reveal each question sequentially rather than all at once.]**
>
> The empirical design answers four progressively more demanding questions. First, when firms are sorted by the signal, do higher-ranked portfolios earn higher returns? Second, could a familiar set of risk factors explain the return difference? A time-series regression separates the strategy return into factor exposures and an intercept called alpha. If alpha is positive and statistically significant, the selected model has not fully explained the strategy’s historical average return. Third, the paper studies NVF as a pricing factor: spanning tests ask whether other factors make it redundant, while Fama–MacBeth regressions assess its price of risk across stocks. Finally, the GRS test checks whether a model’s portfolio alphas are jointly zero. None of these tests, by itself, proves that investors can capture the premium after transaction costs. Nor is this paper a causal identification study using instrumental variables or GMM. The meaning of each test comes from its null hypothesis and estimation setup; adding more tests does not automatically turn a predictive association into causality.

---

## SLIDE 7 — Conventional B/M Value Was Strong Early, but Weak After 2006

### 1. Nội dung hiển thị trên Slide

- **Full sample B/M decile long–short:** **+0.790% per month**, $t=2.312$.
- **Composition:** Highest B/M decile **+0.150%** ($t=0.386$); lowest decile **−0.640%** ($t=-1.670$).
- **Post-2006 premium:** About **+0.18% per month**, much weaker than the earlier regime.
- **Interpretation:** The entire 2000–2024 result should not be described as proof that B/M never worked or that its effect is literally zero.

**Dữ liệu/Bảng (Figure 1, monthly return %):**

| Period | B/M High–Low |
|---|---:|
| 2000–2005 | +3.08 |
| 2006–2010 | −0.54 |
| 2011–2015 | +0.28 |
| 2016–2020 | +0.60 |
| 2021–2024 | +0.47 |

**Visual/Chart:** Vertical bar chart. X-axis: five non-overlapping periods; Y-axis: average monthly B/M high-minus-low return (%), with a true zero line. Teal should be reserved for the *next slide's* CBOP/M results; this chart uses navy and neutral grey only. Insight: early-period dominance and subsequent weakening.

**Source:** PDF pp. 7–10, Tables 3–4 and Figure 1; pp. 1, 18 for post-2006 summary.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:10 | Cue: Point first to 2000–2005, then to the later periods.]**
>
> We begin with the conventional strategy. Across the full sample, buying the highest book-to-market decile and shorting the lowest produces an average spread of 0.790 percent per month, with a t-statistic of 2.312. But the composition is revealing. The high book-to-market portfolio itself earns only 0.150 percent per month, while the lowest decile has a negative average return of 0.640 percent. Much of the spread therefore comes from the short leg. The time profile is even more important: the spread averages 3.08 percent in 2000 to 2005, but the paper reports only about 0.18 percent per month after 2006. The careful conclusion is that conventional value weakened substantially, not that book-to-market was statistically worthless under every specification. This distinction matters because the full-sample premium remains positive and statistically different from zero. The apparent paradox largely disappears once we pay attention to the sample window.

---

## SLIDE 8 — CBOP/M Produces a 1.175% Monthly Gross Return Spread

### 1. Nội dung hiển thị trên Slide

- **High CBOP/M decile:** **+0.584% monthly** ($t=2.386$).
- **Low CBOP/M decile:** **−0.592% monthly** ($t=-2.097$).
- **High–Low spread:** **+1.175% monthly**, **$t=3.615$**, significant at the 1% level as reported.
- **Matched full-sample B/M comparison:** **+0.790% monthly**; the full-sample spread difference is **0.385 percentage points/month** (*calculated from reported headline numbers; not a separately tested difference*).

**Dữ liệu/Bảng (Table 6, value-weighted monthly decile returns %):**

| Decile | D1 High | D2 | D3 | D4 | D5 | D6 | D7 | D8 | D9 | D10 Low |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Return | +0.584 | +0.349 | +0.323 | +0.296 | +0.227 | +0.216 | −0.008 | −0.540 | −0.570 | −0.592 |

**Visual/Chart:** Hero bar chart. X-axis: CBOP/M-ranked deciles, D1 highest to D10 lowest; Y-axis: raw average monthly return (%); emphasize D1 in teal and D10 in burgundy, the others neutral. Add a horizontal bracket for the 1.175-point spread. Insight: return ordering is broadly monotonic; both long and short legs contribute. **Do not show cumulative P&L or investability from averages alone.**

**Source:** PDF p. 12, Table 6.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:10 | Cue: Allow the audience three seconds to inspect the ordered bars.]**
>
> This is the central empirical result. When the author ranks stocks by CBOP-to-market, the high-signal decile earns 0.584 percent per month, while the low-signal decile earns negative 0.592 percent. The reported long–short difference is 1.175 percent per month, with a t-statistic of 3.615. The pattern is broadly ordered across the ten portfolios, which gives the result more substance than a single extreme observation. Importantly, both sides of the trade contribute. On the same full-sample basis, the conventional book-to-market spread was 0.790 percent. That comparison favors the new signal descriptively, although the difference between the two headline averages is not itself presented as a separately tested statistical hypothesis. And all these are gross historical portfolio returns. A high-minus-low average is not what a retail investor can necessarily earn: short-sale permissions, borrowing fees, and the cost of reconstituting holdings have not yet been deducted.

---

## SLIDE 9 — Positive Alpha Survives Five Tested Risk Models

### 1. Nội dung hiển thị trên Slide

- **Alpha is model-dependent**, not an absolute measure of mispricing.
- The CBOP/M long–short strategy retains positive reported alphas under all five controls.
- The estimated alpha declines as the benchmark expands, but remains positive with $t>2$ in every reported case.
- **Model fit detail:** Fletcher 5-factor regression's $R^2 = 0.194$ for the strategy in Table 8; this is not an out-of-sample forecast score.

**Dữ liệu/Bảng (Table 7, high-minus-low monthly alpha %):**

| Model | Alpha (%/month) | t-statistic |
|---|---:|---:|
| CAPM | +0.917 | 4.012 |
| FF3 | +0.867 | 3.587 |
| FF5 | +0.716 | 3.119 |
| FF6 | +0.606 | 2.733 |
| Fletcher et al. (2024) 5-factor | +0.532 | 2.459 |

**Công thức:**

$$
\widehat\alpha = \overline{R^{H-L}}-\sum_{k=1}^{K}\widehat\beta_k\,\overline{F_k}
$$

This is the fitted OLS intercept identity for a common-sample regression with intercept. It shows why alpha differs from the raw mean return.

**Visual/Chart:** Horizontal dot plot, five models on Y-axis, alpha (% per month) on X-axis starting at zero, t-stat labels to the right. No fabricated standard-error bands. Insight: incremental factor controls reduce but do not fully remove the intercept.

**Source:** PDF pp. 13–14, Tables 7–8.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:10 | Cue: Read the decline from 0.917 to 0.532, not every table cell.]**
>
> A strong raw return could simply reflect exposure to familiar risk factors. The author therefore estimates time-series alphas using the capital asset pricing model, several Fama–French specifications, and the UK-oriented five-factor model of Fletcher and colleagues. The gross return spread produces a CAPM alpha of 0.917 percent per month. With broader controls, the estimate declines, reaching 0.532 percent under the Fletcher model, with a t-statistic of 2.459. That persistence is meaningful: the selected factor models do not fully account for the historical premium. But alpha should not be confused with net trading profit or proof of a particular behavioral explanation. It is the intercept of a statistical model, and its economic interpretation depends on the factors included. Table Eight also reports an R-squared of 0.194 for the Fletcher specification, meaning the chosen regressors explain only part of the strategy return variation, not that they predict future returns with nineteen-point-four-percent accuracy.

---

## SLIDE 10 — NVF Is Not the Decile Spread: It Adds Distinct Factor Evidence

### 1. Nội dung hiển thị trên Slide

- **NVF mean return (factor time series):** **+0.831% per month** (Table 2), distinct from the **+1.175%** decile-strategy mean (Table 6).
- **Correlation with HML:** **0.461** (Table 2): overlap, not equivalence.
- **Spanning regression NVF alpha:** **+0.358%/month**, $t=2.344$ (Table 9).
- **Fama–MacBeth, joint-factor model:** $\lambda_{NVF}=+0.466\%/month$, $t=4.323$; $\lambda_{HML}=+0.113\%/month$, $t=1.576$ (Table 10).

**Công thức (spanning OLS):**

$$
NVF_t = \alpha_{NVF} + \boldsymbol\beta^\top\mathbf F^{other}_t + \varepsilon_t
$$

**Công thức (Fama–MacBeth, schematic two-pass setup):**

$$
R_{i,t}=a_i+\boldsymbol\beta_i^\top\mathbf F_t+u_{i,t}
$$

$$
R_{i,t}=\lambda_{0,t}+\sum_{k=1}^{K}\lambda_{k,t}\widehat\beta_{i,k}+\eta_{i,t},\qquad
\widehat\lambda_k=\frac{1}{T}\sum_{t=1}^{T}\widehat\lambda_{k,t}
$$

Here $\widehat\beta_{i,k}$ estimates sensitivity to factor $k$, and $\widehat\lambda_k$ is the estimated average cross-sectional price of that exposure. The slide shows the conceptual equations; the article does not provide every implementation detail or inference adjustment.

**Visual/Chart:** Three aligned mini-panels, NOT a Venn diagram: (A) NVF vs HML mean/correlation; (B) spanning-alpha estimate +0.358 with t; (C) joint Fama–MacBeth risk prices +0.466 NVF vs +0.113 HML with t labels. For panel C X-axis = factor, Y-axis = estimated monthly risk price (%). Insight: distinctness is supported within the chosen models, not universal subsumption.

**Source:** PDF pp. 7, 15–16; Tables 2, 9 and 10.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:15 | Cue: Stress that 1.175, 0.831, and 0.466 are different statistics.]**
>
> The paper goes beyond a trading sort by constructing a new value factor, NVF. This factor has an average monthly return of 0.831 percent, which is not the same object as the 1.175 percent decile spread. NVF's correlation with the conventional HML factor is 0.461, suggesting shared information but not identity. In a spanning regression, NVF retains an intercept of 0.358 percent per month, with a t-statistic of 2.344, after controlling for other selected factors. The Fama–MacBeth exercise then asks whether exposure to NVF carries a price across stocks. In the joint model, the estimated NVF price is 0.466 percent per month and strongly significant; HML's estimate falls to 0.113 percent and is not significant at five percent. This supports incremental pricing information, conditional on the sample and methodology. It does not establish that HML is economically irrelevant in every portfolio, nor that the estimated risk price should be treated as a stand-alone investment return.

---

## SLIDE 11 — The CBOP/M Spread Is Not Confined to the Smallest Size Group

### 1. Nội dung hiển thị trên Slide

- Double sort on **size terciles × CBOP/M deciles** to examine size-related robustness.
- **Gross high-minus-low returns:** Small **+1.286%** ($t=3.390$), Neutral **+1.308%** ($t=3.556$), Big **+0.952%** ($t=2.953$).
- **FF6-adjusted high-minus-low alphas:** Small **+0.803%**, Neutral **+0.645%**, Big **+0.418%** per month.
- **Interpretation boundary:** A big-stock effect is not a substitute for bid–ask, borrow, turnover, or capacity measurement.

**Visual/Chart:** Grouped horizontal bars. Y-axis: Small, Neutral, Big; X-axis: high–low monthly return (%). Dark bar = raw; lighter bar = FF6-adjusted. Always label bars “gross mean return” versus “model alpha”. Insight: observed returns persist outside the smallest tercile, but weaken for large firms after factor adjustment.

**Source:** PDF p. 17, Table 11, Panels A–B.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:00 | Cue: Do not equate market capitalization with liquidity.]**
>
> A common concern with equity anomalies is that results may come mainly from very small stocks. The paper addresses this by repeating CBOP-to-market sorts inside three capitalization groups. The raw monthly high-minus-low returns are 1.286 percent for small firms, 1.308 percent for the middle group, and 0.952 percent for large firms. Even after the six-factor adjustment, the big-stock spread retains an estimated alpha of 0.418 percent. This makes the evidence broader than a microcap-only anomaly. However, size is an imperfect proxy for trading feasibility. These results do not directly tell us transaction costs, short availability, or how much capital the portfolios could absorb. For institutional implementation, average capitalization alone is not enough; we would need security-level volume, bid–ask data, and a transparent capacity assumption.

---

## SLIDE 12 — GRS Tests Favor NVF in These Test Assets, but Do Not Prove Universality

### 1. Nội dung hiển thị trên Slide

- **GRS null hypothesis:** all $N=25$ test-portfolio alphas jointly equal zero.
- **Test assets:** 25 size–B/M portfolios; $T=288$ months.
- **Reported pattern:** Replacing HML with NVF lowers GRS test statistics and increases p-values in four examined model families.
- **Do not claim:** A high p-value “proves” a model is correct or superior on all possible assets.

**Công thức (GRS as reported):**

$$
GRS=\frac{T-N-K}{N}\cdot
\frac{\widehat{\boldsymbol\alpha}^{\top}\widehat{\Sigma}^{-1}\widehat{\boldsymbol\alpha}}
{1+\overline{\mathbf F}^{\top}\widehat{\Omega}^{-1}\overline{\mathbf F}}
\sim F(N,T-N-K)
$$

$T$: months; $N$: test assets; $K$: factors; $\widehat{\boldsymbol\alpha}$: vector of intercepts; $\widehat\Sigma$: residual covariance; $\overline{\mathbf F}$: factor mean vector; $\widehat\Omega$: factor covariance. The null is assessed under the GRS test assumptions.

**Dữ liệu/Bảng (Table 12):**

| Model | HML GRS | HML p-value | NVF GRS | NVF p-value |
|---|---:|---:|---:|---:|
| FF3 | 1.934 | 0.006 | 1.668 | 0.027 |
| FF5 | 1.753 | 0.017 | 1.362 | 0.122 |
| FF6 | 1.424 | 0.092 | 1.090 | 0.354 |
| Fletcher 5-factor | 1.208 | 0.232 | 0.923 | 0.620 |

**Visual/Chart:** Paired dot plot of GRS statistic by model: X-axis = GRS statistic, Y-axis = model, color = HML vs NVF. Display p-values beside dots in small but readable labels. Insight: relative improvement is consistent for the selected 25 portfolios; FF3 with NVF still rejects at 5% ($p=0.027$).

**Source:** PDF pp. 16–18, Section 5 and Table 12.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:10 | Cue: Point to the FF3 p-value before celebrating the Fletcher result.]**
>
> The final asset-pricing test evaluates the models jointly, rather than one return series at a time. The GRS test asks whether all twenty-five test portfolios have zero alphas under the selected factor model. Replacing HML with NVF raises the reported p-values across all four model families. Under Fletcher's five-factor specification, the p-value increases from 0.232 to 0.620. That is consistent with a better fit on these assets. Yet this result requires careful interpretation. A high p-value means we have insufficient evidence to reject the model's joint zero-alpha restriction; it does not prove the model is true. Indeed, the NVF version of the three-factor model still has a p-value of 0.027 and remains rejected at the five-percent level. We should therefore describe the pattern as improvement in the reported diagnostics, rather than claiming the model has passed every statistical validation.

---

## SLIDE 13 — Three Evidence Boundaries Should Qualify the Investment Claim

### 1. Nội dung hiển thị trên Slide

| What the paper supports | What remains open | Why the boundary matters |
|---|---|---|
| Positive gross returns and factor alphas | Net returns after trade/borrow/impact costs | Gross signal ≠ implementable P&L |
| Returns based on prior fiscal-year fundamentals | Exact point-in-time availability and reporting lags | Timing error can overstate a backtest |
| UK historical asset-pricing evidence through June 2024 | Prospective holdout, alternate measures, and broader assets | In-sample fit ≠ universal economic mechanism |

- **Mechanism is not identified causally:** The role of intangible assets is a plausible explanation, not a separately identified causal estimate in this paper.
- **No causal endogeneity treatment claimed:** This is an empirical asset-pricing investigation, not a causal treatment-effect design.
- **Separate appendix-only audit question:** Some printed t-statistic signs and cross-column alpha arithmetic warrant checking against original regression outputs; do not announce a data error without a replication or author clarification.

**Visual/Chart:** An “Evidence → Unresolved assumption → Controlled test” three-column bridge, with each row connected by a thin rule. No generic red warning wall. Insight: critique must be traceable to a claim, not a list of unrelated limitations.

**Source:** PDF pp. 4, 12–18, 18–19; Sections 3–6. Critique is the presenter's analytical interpretation, not a claim made by the author.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:20 | Cue: Shift tone from reporting to constructive challenge.]**
>
> We can now ask the hardest question: what has actually been established? The paper provides substantial historical evidence that CBOP-to-market sorts UK returns and that NVF contributes to the selected pricing models. Three boundaries remain. First, the reported return advantage is gross; annual rebalancing does not, by itself, establish negligible execution and borrowing costs. Second, using last fiscal year's accounting information does not automatically guarantee that every field was public on the portfolio formation date. Third, evidence ending in June 2024 does not tell us whether the same rule will generalize to new periods or alternative accounting definitions. The paper also proposes an economic interpretation involving intangible assets, but does not causally isolate that mechanism. These are not reasons to dismiss the study. They are precise questions for the next research design. Critique is strongest when it changes a broad claim into a falsifiable proposition; simply adding a list of fashionable algorithms would not address the underlying uncertainty.

---

## SLIDE 14 — Three Controlled Experiments Can Separate Signal Quality from Implementability

### 1. Nội dung hiển thị trên Slide

**All items below are PROPOSED, NOT PERFORMED.**

| Test | Hypothesis | Treatment / comparison | Controls and evaluation |
|---|---|---|---|
| **E1 — Point-in-time validity** | $H_1$: CBOP/M remains predictive with public-data release lags | Fiscal-year-end alignment vs genuine availability-date alignment | Same eligible firms, signal formula, rebalancing; compare spreads and alphas |
| **E2 — Implementation costs** | $H_2$: Return survives execution constraints | Gross vs long–short after spread, turnover, impact, and borrow costs; plus long-only | Same date range and universe; compare net return, drawdown, capacity |
| **E3 — Measurement contribution** | $H_3$: CBOP adjustments add information over OP/M | B/M vs OP/M vs CBOP/M; industry-neutral robustness | Same formation dates and portfolio rules; compare out-of-sample spreads and incremental alphas |

**Công thức (planned net-return accounting identity, not a tested estimate):**

$$
R^{net}_t=R^{gross}_t-C^{trade}_t-C^{borrow}_t-C^{financing}_t-C^{other}_t
$$

**Decision rules:** Freeze ranking and filters before holdout; report both positive and negative results; benchmark *on identical dates and eligible universe*; report net and gross separately. Do not fit parameters on the test set and then report it as untouched holdout.

**Visual/Chart:** Three research protocol cards or a pre-analysis matrix, each with question → intervention → held-constant elements → metric. No equity curves, Sharpe numbers, or confidence bands until the data have been acquired and tested.

**Source:** Presenter's proposed extension based on unresolved questions in Duong (2025), Sections 3–6.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 1:20 | Cue: Announce clearly that these are research designs, not results.]**
>
> Our next step should not be to add more sophisticated machine learning immediately. It should be to design experiments that isolate the unanswered questions. First, we would rebuild the same CBOP-to-market signal using actual public availability dates and compare it with the paper-style fiscal-year alignment. Second, holding the signal and sample fixed, we would introduce realistic trading, financing, and borrowing costs, and separately evaluate a long-only implementation. Third, we would compare book-to-market, ordinary operating-profit-to-market, and CBOP-to-market on identical formation dates, including an industry-neutral version. Every comparison should use the same eligible universe and a pre-specified out-of-sample protocol. These tests allow either confirmation or rejection. Their purpose is to measure what the original signal genuinely adds, not to guarantee a prettier equity curve. A negative result from a well-designed test would still be informative: it would tell us where the historical evidence stops generalizing.

---

## SLIDE 15 — Conclusion: A Better Value Measure Is a Research Finding, Not Yet a Trading Product

### 1. Nội dung hiển thị trên Slide

- **Finding 1:** Conventional B/M weakened after 2006 in the studied UK market.
- **Finding 2:** CBOP/M formed a more persistent historical gross long–short spread and retained positive factor-adjusted alpha.
- **Finding 3:** NVF added pricing information and improved joint model-fit diagnostics in the examined tests.
- **Next research gate:** Point-in-time replication → cost-aware evaluation → controlled out-of-sample validation.
- **Bottom line:** **Better measurement deserves more testing; it does not eliminate implementation risk.**

**Visual/Chart:** Large one-sentence conclusion with three narrow evidence strips below: Strategy | Asset pricing | Next test. No unexplained new numbers or decorative logos.

**Source:** Duong (2025), Sections 4–6; tests proposed by the presenter.

### 2. Kịch bản thuyết trình (Speaker Notes)

> **[Estimated: 0:55 | Cue: Slow down; leave a brief pause before the last sentence.]**
>
> To conclude, the paper gives us three valuable results. Traditional book-to-market value became much weaker after 2006 in the UK sample. A strategy ranked by cash-based operating profitability relative to market value produced stronger historical gross spreads and remained positive after several factor adjustments. And the new value factor contributed information to cross-sectional pricing and joint model comparisons. The appropriate next step is therefore neither blind adoption nor blanket rejection. It is disciplined reconstruction: verify when information was available, measure realistic costs, and test the signal outside the environment in which its success was discovered. The broader lesson is simple: better accounting measurement can sharpen investment research, but a statistically persuasive factor is not automatically an investable product. Thank you.

---

# TECHNICAL APPENDIX — FOR LECTURER Q&A, NOT THE 15-SLIDE MAIN STORY

## APPENDIX A1 — Numerical evidence audit and source map

| Research claim / data | Source | Proper interpretation |
|---|---|---|
| Traditional B/M decile H−L: +0.790% monthly, t = 2.312 | Table 3, PDF p. 8 | Entire July 2000–June 2024 sample |
| B/M after 2006: +0.18% monthly | Abstract / Conclusion, PDF pp. 1, 18 | Different window: do not subtract directly from full-sample CBOP/M to quantify improvement |
| CBOP/M D1 +0.584%; D10 −0.592%; spread +1.175%, t = 3.615 | Table 6, PDF p. 12 | Gross decile strategy; D1 − D10 differs by 0.001 due to rounding |
| NVF factor mean: +0.831%; corr(NVF,HML) = 0.461 | Table 2, PDF p. 7 | Different factor construction from CBOP/M decile spread |
| Fletcher-5 alpha +0.532%, t = 2.459 | Table 7, PDF p. 13 | Model-specific alpha, not realized net return |
| NVF spanning alpha +0.358%, t = 2.344 | Table 9, PDF p. 15 | Incremental information conditional on regressors |
| Joint Fama–MacBeth λNVF +0.466%, t = 4.323 | Table 10, PDF p. 15 | Cross-sectional estimated risk price, not strategy mean |
| Big-size tercile raw H−L +0.952%, t = 2.953 | Table 11, PDF p. 17 | A size robustness check, not liquidity or capacity proof |
| Fletcher GRS p-value 0.232 (HML) vs 0.620 (NVF) | Table 12, PDF p. 18 | Joint model-fit evidence for selected test assets |

## APPENDIX A2 — Factors and economics of the models

| Factor | Economic feature / construction in the supplied paper |
|---|---|
| Market $R_m-R_f$ | FTSE All Share return less one-month UK Treasury Bill return |
| SMB | Small-minus-big factor derived from the three independent 2×3 sorts |
| HML | High-minus-low B/M from size × B/M double sorts |
| RMW | Profitability; paper follows UK implementation using gross profit margin |
| CMA | Conservative-minus-aggressive asset investment |
| WML | Winner-minus-loser prior stock performance, t−12 through t−2 |
| FIN | Behavioral financing factor based on CSI and NSI measures |
| NVF | High-minus-low cash-based OP to market factor, size × CBOP/M double sorts |

Selected additional factor definitions:

$$
HML_t=\tfrac12(R_{BH,t}+R_{SH,t}-R_{BL,t}-R_{SL,t})
$$

$$
SMB_t=\tfrac13(SMB_{HML,t}+SMB_{RMW,t}+SMB_{CMA,t})
$$

$$
WML_t=\tfrac12(R_{BW,t}+R_{SW,t}-R_{BL,t}-R_{SL,t})
$$

Subscripts $B/S$ denote large/small size groups; $H/L$ denote high/low value or winner/loser **within the relevant factor definition**. Variable symbols are overloaded across factors in the article; never use one abbreviation without stating its sort criterion.

**Theory distinction:** A factor return is constructed from portfolio returns; a factor-loading coefficient $\beta$ measures covariance exposure; a time-series alpha $\alpha$ is the intercept left unexplained by specified factor returns; a Fama–MacBeth $\lambda$ is an estimated average cross-sectional price of an exposure. These are not interchangeable.

## APPENDIX A3 — Focused referee audit: questions, not allegations

1. **Sign inconsistency in displayed t-statistics.** In Table 7, Fletcher model, decile 9 has alpha **−0.186** but a printed t-statistic of **(+1.539)**. In Table 11, Panel A, Neutral-decile 9 is **−0.596** with a printed t-statistic **(+1.578)**. Under an ordinary zero-null t-statistic computed as coefficient divided by positive standard error, signs should match. Ask whether these are transcription/formatting errors; do not infer that underlying estimation is wrong.
2. **Linearity/reconciliation question.** In Table 7 CAPM, high alpha **+0.511** and low alpha **−0.494** imply a simple difference of **1.005** percentage points, whereas the reported High−Low alpha is **+0.917**. With identical samples, factors, and OLS specifications applied to a spread exactly equal to high minus low, intercept additivity would normally hold. Clarify whether portfolio-return definitions, samples, estimation windows, or report formatting differ before labelling this an error.
3. **Statistical versus economic importance.** A significant return estimate does not demonstrate profit after trading costs. Table 6 does not provide individual stock turnover, spreads, market impact, security borrowing availability, or taxes.
4. **Causal mechanism.** The article's discussion of intangible assets is plausible but is not a separately identified empirical mechanism. A design explicitly testing intangible intensity would be needed to support a stronger mechanism claim.
5. **Outlier and standard-error details.** The paper states key sample exclusions but does not report a complete security-level winsorization/outlier-cleaning protocol or enough raw estimation outputs to reconstruct all standard errors. Do not state that winsorization, Newey–West adjustment, or GMM was performed without supporting text.

**Academic discussion wording:** “Could we clarify whether the stated regression specifications share exactly the same sample and spread construction? I noticed a small table-level reconciliation issue and would prefer to verify it before interpreting the result.”

## APPENDIX A4 — Likely lecturer questions and concise defenses

**Q: Why is the CBOP/M mean of 1.175% not the same as the NVF mean of 0.831%?**
A: The first is a high–low spread based on ten CBOP/M portfolios. NVF is a factor built from a separate 2×3 size-by-CBOP/M sort. Their weights, constituent portfolios, and return paths need not coincide.

**Q: Does a t-statistic above two prove the causal impact of CBOP/M?**
A: No. It supports a nonzero parameter estimate under the reported statistical assumptions. Observational portfolio sorts and factor regressions do not identify a causal intervention on firms' profitability or prices.

**Q: Is HML redundant?**
A: The paper reports that, after adding NVF, HML loses conventional statistical significance in certain spanning and Fama–MacBeth specifications. That is conditional redundancy in those tests, not universal irrelevance of HML.

**Q: Why does an increased GRS p-value matter?**
A: It weakens evidence against the joint zero-alpha restriction for these test assets. It does not certify that a model is true; FF3-with-NVF is still rejected at 5% in Table 12.

**Q: Is a strategy tradable because portfolios are rebalanced annually?**
A: Not necessarily. Annual formation may reduce turnover relative to faster strategies, but the magnitude of trade costs, turnover after firm exits, financing, and short-sale frictions must be measured, not assumed.

**Q: Is endogeneity solved?**
A: The article tests empirical return predictability and pricing relations; it does not report an instrumental-variables or other causal-identification design. “Endogeneity addressed” would therefore be an unsupported claim.

## APPENDIX A5 — Exact chart production brief and integrity checks

1. **Main slide 7:** Figure 1 period-by-period B/M bar chart. Show all five subperiods, all five values, zero baseline, unit = mean % per month. Do not make a line chart connecting category midpoints as though continuous monthly observations were provided.
2. **Main slide 8:** Table 6 D1–D10 bar chart. High-to-low sort order must remain left-to-right; D1 highest, D10 lowest. Numeric labels to three decimal places. Optional annotation: reported spread 1.175%; rounding explains 0.584−(−0.592)=1.176.
3. **Main slide 9:** Five horizontal alpha points. Do not include confidence intervals unless reconstructed using validated standard errors; label reported t-statistics instead.
4. **Main slide 10:** Separate panels for correlation, spanning alpha, and risk-price estimates. Avoid Venn-area graphics: correlation 0.461 does not define an area of overlap.
5. **Main slide 11:** Raw return and FF6 alpha side by side. The estimands differ; legend must say “Raw” and “FF6 alpha,” not two types of return.
6. **Main slide 12:** GRS levels plus p-values from Table 12. Do not present the *difference in p-values* as a formal significance test of one model against the other.
7. **Main slide 14:** Only experimental design, not synthetic backtest curves.
8. **Template hygiene:** Existing uploaded deck pp. 15–21 contain unrelated footer labels from another topic. Replace every footer, audit font sizes and units, and remove unsourced attractive but speculative investment claims.

## FINAL DELIVERY CHECKLIST

- [ ] Every reported number is labelled with time window, unit, construction (decile vs factor vs regression), and paper table.
- [ ] The audience can explain B/M, CBOP/M, high–low return, time-series alpha, Fama–MacBeth risk price, and GRS at an intuitive level.
- [ ] Every key equation is presented in LaTeX and every visible mathematical symbol is defined.
- [ ] No unperformed GMM, Black–Scholes, causal endogeneity remedy, trading backtest, or optimization is attributed to the paper.
- [ ] No invented outlier procedure, point-in-time publication lag, commission figure, borrow cost, or post-2024 performance is reported.
- [ ] Limitations explicitly distinguish what the author tested from what remains untested.
- [ ] Q&A appendix is available but is not spoken unless a question demands it.
- [ ] The 15-slide word-for-word script is rehearsed aloud and trimmed if it exceeds 18 minutes.

---

**Primary document:** Duong, Le Quy (2025). “A new value strategy in the UK stock market.” *Journal of Economic Studies*. DOI: **10.1108/JES-03-2025-0190**. All source references refer to the user-supplied 20-page paper PDF. Secondary research mentioned in the presentation is attributed to the paper's own literature review, not independently re-analyzed here.

# REVIVING THE VALUE PREMIUM IN A KNOWLEDGE ECONOMY: EMPIRICAL EVIDENCE FROM CASH-BASED OPERATING PROFITABILITY IN THE UK EQUITY MARKET

_Institutional Quantitative Equity Research Presentation | Based on Le Quy Duong (2025), Journal of Economic Studies_
_Thời lượng dự kiến: ~16 phút | Tốc độ nói: 135 - 145 từ/phút | Tổng số từ Script: ~2,250 từ (Tiếng Anh Học Thuật)_

---

## SLIDE 1: TITLE & EXECUTIVE SUMMARY — THE DEATH OF BOOK VALUE AND THE CASH-FLOW REVIVAL

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Core Thesis:** The traditional Fama-French Book-to-Market ($B/M$) value strategy has suffered severe structural decay in the UK post-2006 ($0.18\%$/month), driven by unrecorded intangible capital and accounting accrual distortions.
  - **The Quantitative Solution:** Replacing static book equity ($B$) with dynamic **Cash-Based Operating Profitability ($\text{CBOP}/M$)** restores the UK value premium to **$1.175\%$/month** ($t\text{-stat} = 3.615, p < 0.01$) across 1995–2024.
  - **Factor Dominance:** A $2 \times 3$ sorted New Value Factor ($\text{NVF}$) generates **$0.692\%$/month** ($t\text{-stat} = 4.442$), completely subsuming $\text{HML}$ in spanning regressions ($\alpha_{\text{NVF}} = 0.358\%, t = 2.344$) and improving portfolio Mean-Variance efficiency.
- **Công thức (Core Metric vs. Benchmark):**
  $$\text{Traditional Value} = \frac{\text{Book Equity}_{i, t-1}}{\text{Market Cap}_{i, t-1}} \quad \xrightarrow{\text{Paradigm Shift}} \quad \text{New Value} = \frac{\text{CBOP}_{i, t-1}}{\text{Market Cap}_{i, t-1}}$$
- **Dữ liệu/Bảng (Executive Performance Snapshot: July 1995 – June 2024):**

| Metric / Period                  | Conventional $B/M$ (H-L) | New Value $\text{CBOP}/M$ (H-L) | Factor $\text{HML}$ ($2\times3$) |   Factor $\text{NVF}$ ($2\times3$)   |
| :------------------------------- | :----------------------: | :-----------------------------: | :------------------------------: | :----------------------------------: |
| **Full Sample (1995–2024)**      | $0.790\%$ ($t = 2.312$)  |   **$1.175\%$ ($t = 3.615$)**   |     $0.273\%$ ($t = 1.384$)      |     **$0.692\%$ ($t = 4.442$)**      |
| **Post-2006 Regime (2006–2024)** |  $0.180\%$ (Collapsed)   |    **$0.920\%$ (Resilient)**    |          Insignificant           |       **Statistically Robust**       |
| **FF6 Risk-Adjusted $\alpha$**   | $0.353\%$ ($t = 1.981$)  |   **$0.606\%$ ($t = 3.249$)**   |    Redundant vs. $\text{NVF}$    | **$\alpha = 0.358\%$ ($t = 2.344$)** |

- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _Grouped Sub-period Bar Chart with Error Bars_ (So sánh hiệu suất High-Low theo 5 giai đoạn từ Hình 1 & Hình 2 trang 10, 14 của bài báo).
  - **Trục X:** 5 Giai đoạn lịch sử (`1995-2000`, `2000-2005`, `2006-2011`, `2012-2017`, `2018-2024`).
  - **Trục Y:** Lợi suất trung bình hàng tháng (%).
  - **Key Takeaway trực quan:** Làm nổi bật vùng từ năm 2006–2024 bằng khung đỏ: Đường/Cột $B/M$ sụp đổ về sát $0\%$ ($0.10\%$, $0.45\%$, $-0.02\%$), trong khi cột $\text{CBOP}/M$ giữ vững mức dương cao ổn định ($0.90\%$, $1.23\%$, $0.63\%$).

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 1.5 minutes]**
> **[Action/Cues]:** _[Stand center stage, maintain strong eye contact with Lecturer Le Quy Duong and the 100-student audience. Pause 2 seconds before starting.]_
>
> "Good morning/afternoon Professor Le Quy Duong, fellow researchers, and colleagues.
>
> For over three decades, the cornerstone of quantitative equity investing has been the Fama-French Book-to-Market ratio—buying stocks that appear statistically cheap relative to their accounting book value and shorting those that appear expensive. Yet, if you had deployed a conventional Book-to-Market strategy in the United Kingdom—Europe's largest equity market—anytime after 2006, your strategy would have flatlined. As shown on the right-hand chart of Slide 1, between 2006 and 2024, the conventional UK value premium collapsed from $3.08\%$ per month to a statistically indistinguishable $0.18\%$ per month.
>
> **[Cues: Point to the Core Metric equation in the center of the slide]**
> Does this mean value investing is dead? The seminal 2025 research by Dr. Le Quy Duong that we are examining today proves otherwise. Value is not dead; rather, our traditional accounting ruler—Book Equity—is broken.
>
> By replacing static Book Equity with a flow-based, accrual-purged metric—**Cash-Based Operating Profitability scaled by Market Capitalization ($\text{CBOP}/M$)**—this study demonstrates a remarkable revival of the UK value premium. Across a 29-year sample of roughly 1,700 London Stock Exchange firms from July 1995 to June 2024, the $\text{CBOP}/M$ long-short decile strategy delivers a highly significant **$1.175\%$ per month** with a $t\text{-statistic}$ of **$3.615$**, outperforming the traditional $B/M$ spread by nearly 40 basis points per month. Furthermore, when structured into a $2 \times 3$ Fama-French style factor—termed the **New Value Factor ($\text{NVF}$)**—it yields **$0.692\%$ per month** ($t = 4.442$), completely subsuming the traditional $\text{HML}$ factor. Today, we will dissect the econometric architecture behind this result, subject it to rigorous institutional critique, and propose a quantitative roadmap for live trading implementation."

---

## SLIDE 2: LITERATURE LINEAGE & RESEARCH MOTIVATION — WHY BOOK VALUE FAILS

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **The Intangible Economy Shift (Arnott et al., 2021;Lev & Srivastava, 2019):** Modern corporate value is driven by R&D, software, brand equity, and human capital—assets largely expensed rather than capitalized on balance sheets, rendering Book Equity ($B$) an incomplete measure of fundamental value.
  - **The Accrual Anomaly Distortion (Sloan, 1996; Ball et al., 2016):** GAAP/IFRS Operating Profit ($\text{OP}$) captures economic flow but is contaminated by working-capital accruals (e.g., uncollected receivables, bloated inventory) that negatively predict future stock returns.
  - **Research Lineage & The UK Gap:** Wang (2024) introduced $\text{CBOP}/M$ in the US market. However, the UK market exhibits unique institutional characteristics (e.g., weak post-2006 $B/M$ performance, distinct corporate governance, and absence of a dominant profitability premium under standard proxies).
- **Công thức (Decomposing Accounting Earnings into Cash vs. Accruals):**
  $$\text{Accounting Operating Profit } (\text{OP}_t) = \underbrace{\text{Cash-Based Operating Profit } (\text{CBOP}_t)}_{\text{True Fundamental Cash Generation}} + \underbrace{\text{Working Capital Accruals } (\Delta \text{WC}_t)}_{\text{Noise / Mean-Reverting Distortion}}$$
- **Dữ liệu/Bảng (Anatomy of the Post-2006 $B/M$ Failure — Table 3 Breakdown):**

| Decile / Leg                        | $B/M$ Average Ratio | Raw Return (% / month) | $t\text{-statistic}$ | Economic Interpretation                                     |
| :---------------------------------- | :-----------------: | :--------------------: | :------------------: | :---------------------------------------------------------- |
| **Decile 1 (High $B/M$ - Long)**    |       $2.212$       |       $0.858\%$        |      $1.807^*$       | Weak long-side return; fails $5\%$ significance threshold   |
| **Decile 10 (Low $B/M$ - Short)**   |       $0.145$       |       $0.068\%$        |       $0.165$        | Short leg does not lose money; expensive stocks keep rising |
| **Post-2006 Long Leg (D1 - $R_f$)** |          —          |     **$0.150\%$**      |     **$0.386$**      | **Complete collapse of the value long leg after 2006**      |

- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _2-Panel Diverging Horizontal Bar Chart + Timeline Flowchart_.
  - **Panel Trái:** Dòng chảy học thuật từ `Fama & French (1992, 1993) [B/M]` $\rightarrow$ `Ball et al. (2016) [CBOP/Assets]` $\rightarrow$ `Wang (2024) [US CBOP/M]` $\rightarrow$ `Le Quy Duong (2025) [UK Asset Pricing & Spanning Tests]`.
  - **Panel Phải:** Biểu đồ phân rã chân Long (D1: $+0.15\%, t=0.386$) và chân Short (D10: $-0.64\%, t=-1.690$) của $B/M$, chứng minh chiến lược $B/M$ truyền thống thực chất chỉ sống dựa vào chân bán khống (Short leg)!

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 1.5 minutes]**
> **[Action/Cues]:** _[Advance to Slide 2. Gesture toward the table on the bottom left.]_
>
> "To appreciate the contribution of this paper, we must first diagnose why the conventional Book-to-Market strategy failed. Look closely at the empirical breakdown of Table 3 from the paper. Over the entire 1995 to 2024 period, the top decile of high $B/M$ stocks generated a raw return of $0.858\%$ per month with a $t\text{-statistic}$ of $1.807$—failing even the standard $5\%$ statistical significance threshold. More alarmingly, when we isolate the excess return over the risk-free rate, the long leg of $B/M$ yields a mere $0.150\%$ per month ($t = 0.386$), while the short leg generates $-0.640\%$ ($t = -1.690$). In plain institutional terms: traditional $B/M$ in the UK was never a true long-value story; it was a disguised short-growth bet that imploded once knowledge-economy growth firms began compounding cash flows after 2006.
>
> **[Cues: Emphasize the decomposition formula]**
> Why does Book Equity fail? Because in a modern knowledge economy, intangible investments—patents, software, supply-chain networks—are expensed immediately on the income statement rather than recorded on the balance sheet. Consequently, Book Value severely understates the economic capital of modern enterprises.
>
> While Fama and French (2006, 2015) attempted to patch this by adding Operating Profitability ($\text{RMW}$), accounting operating profit includes working-capital accruals—such as surging accounts receivable or unsold inventory—which Sloan (1996) proved are mean-reverting and negatively correlated with future returns. Building upon Ball et al. (2016) and Wang (2024), Dr. Duong's study strips away these accrual distortions to isolate **Cash-Based Operating Profitability ($\text{CBOP}$)** and scales it by Market Capitalization ($M$), asking a fundamental question: _How much pure operating cash flow are we buying per pound of market equity?_"

---

## SLIDE 3: THE ACCOUNTING CONSTRUCT, DATA & PORTFOLIO DESIGN

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Exact Accounting Construction:** Converts accrual-based operating profit into actual operating cash inflows/outflows via 6 working-capital adjustments (Datastream codes in brackets).
  - **Sample & Survivorship-Bias Control:** All active and dead/delisted non-financial UK stocks on the London Stock Exchange (LSE) from **July 1995 to June 2024** ($\approx 1,700$ firms; $29$ years).
  - **Portfolio Formation & Look-Ahead Prevention:** Annual sorting at the beginning of **July of year $t$** using fiscal year-end accounting data from **year $t-1$**, matched with market cap $M$ at $t-1$, held for 12 months (July $t$ to June $t+1$).
- **Công thức (The $\text{CBOP}/M$ Mathematical Identity):**
  $$\text{OP}_{i,t} = \text{Revenue}_{i,t} [\text{WC01001}] - \text{COGS}_{i,t} [\text{WC01051}] - \text{SG\&A}_{i,t} [\text{WC01101}]$$
  $$\text{CBOP}_{i,t} = \text{OP}_{i,t} - \Delta \text{AR}_{i,t} - \Delta \text{INV}_{i,t} - \Delta \text{PREPAID}_{i,t} + \Delta \text{DR}_{i,t} + \Delta \text{AP}_{i,t} + \Delta \text{AE}_{i,t}$$
  $$\text{Value Signal}_{i,t} = \frac{\text{CBOP}_{i,t-1}}{\text{Market Capitalization}_{i,t-1} [\text{MV}]}$$
  _(Trong đó: $\Delta X_t = X_t - X_{t-1}$; $\text{AR}$: Khoản phải thu [WC02051]; $\text{INV}$: Hàng tồn kho [WC02101]; $\text{PREPAID}$: Chi phí trả trước [WC02140]; $\text{DR}$: Doanh thu chưa thực hiện [WC03263]; $\text{AP}$: Phải trả người bán [WC03040]; $\text{AE}$: Chi phí phải trả [WC03054]. Giá trị thay đổi bằng 0 nếu dữ liệu khuyết).\_
- **Dữ liệu/Bảng (Factor Summary Statistics & Correlation Matrix — Table 2, July 1995 – June 2024):**

| Factor                                | Mean (% / mo) | Std. Dev (%)  |   $t\text{-stat}$    | Corr w/ $\text{NVF}$ | Corr w/ $\text{HML}$ |
| :------------------------------------ | :-----------: | :-----------: | :------------------: | :------------------: | :------------------: |
| **$R_m - R_f$ (Market)**              |   $0.453\%$   |   $3.924\%$   |     $2.155^{**}$     |       $-0.095$       |       $0.145$        |
| **$\text{SMB}_{\text{NVF}}$ (Size)**  |   $0.119\%$   |   $3.164\%$   |       $0.701$        |       $-0.071$       |       $-0.044$       |
| **$\text{HML}$ (Conventional Value)** |   $0.273\%$   |   $3.679\%$   |       $1.384$        |       $0.461$        |       $1.000$        |
| **$\text{RMW}$ (Profitability)**      |   $0.234\%$   |   $2.625\%$   |      $1.662^*$       |       $0.076$        |       $-0.335$       |
| **$\text{CMA}$ (Investment)**         |   $0.171\%$   |   $2.238\%$   |       $1.425$        |       $0.323$        |       $0.460$        |
| **$\text{WML}$ (Momentum)**           |   $0.916\%$   |   $4.570\%$   |    $3.736^{***}$     |       $0.036$        |       $-0.440$       |
| **$\text{NVF}$ (New Value Factor)**   | **$0.692\%$** | **$2.905\%$** | **$4.442^{\***}$\*\* |     **$1.000$**      |     **$0.461$**      |

- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _Panel A: Waterfall Accounting Diagram_ (Từ Revenue $\rightarrow$ OP $\rightarrow$ Cộng/Trừ Working Capital $\rightarrow$ CBOP) kết hợp _Panel B: Heatmap Correlation Matrix_ (Trực quan hóa Bảng 2).
  - **Key Takeaway trực quan:** Trên Heatmap, làm nổi bật hệ số tương quan giữa $\text{HML}$ và $\text{WML}$ là **$-0.440$** (ngược chiều mạnh với Momentum), trong khi $\text{NVF}$ và $\text{WML}$ có tương quan **$+0.036$** (hoàn toàn trực giao/độc lập với Momentum!), đồng thời $\text{NVF}$ có độ lệch chuẩn thấp hơn hẳn $\text{HML}$ ($2.905\%$ vs $3.679\%$).

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 2.0 minutes]**
> **[Action/Cues]:** _[Move to Slide 3. Point to the three LaTeX equations in the middle.]_
>
> "Let us examine the exact mathematical engineering of $\text{CBOP}/M$ on Slide 3. We begin with standard Operating Profit: Revenue minus Cost of Goods Sold, minus Selling, General, and Administrative expenses. To convert this accounting figure into pure cash flow, we apply six working-capital adjustments from LSEG Datastream.
>
> Why do we subtract changes in Accounts Receivable ($\Delta \text{AR}$), Inventory ($\Delta \text{INV}$), and Prepaid Expenses ($\Delta \text{PREPAID}$)? Because if a company reports $£100$ million in revenue, but Accounts Receivable increases by $£40$ million, that $£40$ million is an uncollected IOUs sitting in customers' pockets—not cash in the firm's treasury. Conversely, we add back increases in Deferred Revenue ($\Delta \text{DR}$), Accounts Payable ($\Delta \text{AP}$), and Accrued Expenses ($\Delta \text{AE}$), as these represent real cash collected upfront or supplier credit effectively financing operations.
>
> **[Cues: Point to the Timeline and Table 2 Summary Statistics]**
> To ensure zero survivorship bias, the dataset encompasses both active and delisted non-financial firms on the London Stock Exchange from July 1995 to June 2024—approximately 1,700 firms. Following the Fama-French (1992) timing convention to eliminate look-ahead bias, portfolios are formed at the start of July in year $t$ using accounting data from fiscal year-end $t-1$, weighted by market capitalization.
>
> Look at the Summary Statistics from Table 2 at the bottom of the slide. This table contains a profound quantitative insight that most casual readers miss. First, the $2 \times 3$ sorted New Value Factor ($\text{NVF}$) delivers **$0.692\%$ per month** with a massive $t\text{-statistic}$ of **$4.442$**, more than doubling the $0.273\%$ ($t = 1.384$) of traditional $\text{HML}$, while exhibiting _lower_ monthly volatility ($2.905\%$ versus $3.679\%$). Second, look at the correlation with Momentum ($\text{WML}$): traditional $\text{HML}$ is heavily negatively correlated with Momentum at **$-0.440$**—meaning traditional value investors are constantly fighting negative momentum crashes. In contrast, $\text{NVF}$ has a near-zero correlation with Momentum (**$+0.036$**) and only a **$0.461$** correlation with $\text{HML}$. It captures a distinct, higher-quality dimension of value."

---

## SLIDE 4: ECONOMETRIC METHODOLOGY — THE FOUR-PILLAR TESTING ARCHITECTURE

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Pillar 1 — Time-Series Multi-Factor Regressions:** Evaluates whether decile returns ($R_{p,t} - R_{f,t}$) survive adjustment against 5 benchmark asset pricing models (CAPM, FF3, FF5, FF6, and Fletcher's 2021 UK 5-Factor model including $\text{CSI}$ and $\text{NSI}$).
  - **Pillar 2 — Factor Spanning Regressions:** Tests whether $\text{NVF}$ lies outside the mean-variance span of existing factors ($\alpha \neq 0$).
  - **Pillar 3 — Fama-MacBeth (1973) Two-Step Cross-Sectional Regressions:** Estimates the market price of risk ($\lambda_{\text{NVF}}$) across individual equities.
  - **Pillar 4 — Gibbons-Ross-Shanken (GRS, 1989) Efficiency Test:** Evaluates joint pricing errors across $25$ Size-Value test portfolios.
- **Công thức (Econometric Specifications):**
  - _1. Multi-Factor Time-Series Alpha (FF6 & Fletcher 5-Factor):_
    $$R_{p,t} - R_{f,t} = \alpha_p + \beta_{1}(R_{m,t} - R_{f,t}) + \beta_{2}\text{SMB}_t + \beta_{3}\text{HML}_t + \beta_{4}\text{RMW}_t + \beta_{5}\text{CMA}_t + \beta_{6}\text{WML}_t + \varepsilon_{p,t}$$
    $$R_{p,t} - R_{f,t} = \alpha_p + \beta_{1}(R_{m,t} - R_{f,t}) + \beta_{2}\text{SMB}_t + \beta_{3}\text{HML}_t + \beta_{4}\text{WML}_t + \beta_{5}\text{INV}_t + \varepsilon_{p,t} \quad (\text{where } \text{INV} \in \{\text{CSI}, \text{NSI}\})$$
  - _2. Spanning Regression:_
    $$\text{NVF}_t = \alpha_{\text{span}} + \sum_{k=1}^{K} \gamma_k F_{k,t} + u_t \quad \text{vs.} \quad \text{HML}_t = \alpha_{\text{span}}^* + \delta \text{NVF}_t + \sum_{k \neq \text{HML}} \gamma_k^* F_{k,t} + v_t$$
  - _3. Fama-MacBeth (1973) Cross-Sectional Pricing:_
    $$R_{i,t} - R_{f,t} = \lambda_{0,t} + \lambda_{1,t}\hat{\beta}_{i, m} + \lambda_{2,t}\hat{\beta}_{i, \text{SMB}} + \lambda_{3,t}\hat{\beta}_{i, \text{HML}} + \lambda_{4,t}\hat{\beta}_{i, \text{NVF}} + \dots + \eta_{i,t} \implies \bar{\lambda}_k = \frac{1}{T}\sum_{t=1}^{T} \lambda_{k,t}$$
  - _4. GRS Test Statistic:_
    $$\text{GRS} = \left(\frac{T}{N}\right)\left(\frac{T - N - L}{T - L - 1}\right) \left[\frac{\hat{\boldsymbol{\alpha}}' \hat{\boldsymbol{\Sigma}}^{-1} \hat{\boldsymbol{\alpha}}}{1 + \bar{\boldsymbol{\mu}}_f' \hat{\boldsymbol{\Omega}}^{-1} \bar{\boldsymbol{\mu}}_f}\right] \sim F_{N, \, T-N-L}$$
- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _4-Quadrant Architectural Flowchart_ kết nối 4 phương trình kinh tế lượng với câu hỏi tài chính tương ứng (như tinh thần của Slide 8 trong bản nháp của bạn nhưng bổ sung ký hiệu toán học).

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 2.0 minutes]**
> **[Action/Cues]:** _[Advance to Slide 4. Walk through the four econometric equations systematically.]_
>
> "In institutional quantitative research, a high raw return is meaningless unless it survives a gauntlet of econometric falsification tests. On Slide 4, we formalize the four-pillar econometric architecture employed in the study.
>
> **First**, in our time-series regressions, we regress the monthly excess returns of each decile portfolio against five asset pricing benchmarks: the CAPM, the Fama-French 3-factor, 5-factor, and 6-factor models, and—crucially for the UK—Fletcher's (2021) 5-factor model. Why Fletcher's model? Because Fletcher demonstrated that in the UK, investment is better captured through financing measures—specifically Composite Share Issuance ($\text{CSI}$) and Net Share Issuance ($\text{NSI}$)—rather than asset growth ($\text{CMA}$). Here, the intercept $\alpha_p$ measures the abnormal return unexplained by systematic risk exposures.
>
> **Second**, we execute factor spanning regressions following Fama and French (2018). We regress $\text{NVF}$ on all existing factors. Mathematically, the intercept $\alpha_{\text{span}}$ is nonzero if and only if adding $\text{NVF}$ significantly increases the maximum squared Sharpe ratio achievable from the factor tangency portfolio.
>
> **Third**, because portfolio sorts can mask individual stock idiosyncrasies, we run two-step Fama-MacBeth (1973) cross-sectional regressions across all individual stocks. In Step 1, we estimate factor loadings $\hat{\beta}_{i,k}$ for each stock. In Step 2, for each month $t$, we run a cross-sectional regression of stock excess returns on those estimated betas, averaging the slope coefficients $\lambda_{k,t}$ over all 348 months to test whether $\text{NVF}$ commands a statistically significant market price of risk, $\bar{\lambda}_{\text{NVF}}$.
>
> **Finally**, we compute the Gibbons, Ross, and Shanken (1989) $\text{GRS}$ $F\text{-statistic}$ across 25 double-sorted test portfolios. In the $\text{GRS}$ quadratic form, $\hat{\boldsymbol{\alpha}}' \hat{\boldsymbol{\Sigma}}^{-1} \hat{\boldsymbol{\alpha}}$ measures the aggregate pricing error across all 25 portfolios. Under the null hypothesis $H_0: \alpha_1 = \alpha_2 = \dots = \alpha_{25} = 0$, a **lower** $\text{GRS}$ statistic and a **higher** $p\text{-value}$ indicate a superior asset pricing model that approaches mean-variance efficiency."

---

## SLIDE 5: EMPIRICAL RESULTS I — DECILE MONOTONICITY & MULTI-FACTOR RISK-ADJUSTED ALPHAS

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Strict Monotonicity & Symmetric Two-Sided Alpha (Table 6):** Sorting on $\text{CBOP}/M$ creates a nearly monotonic return cascade from Decile 1 ($1.036\%$/mo) down to Decile 10 ($-0.140\%$/mo).
  - **Balanced Long & Short Contributions:** Unlike $B/M$ (where the long leg failed at $+0.150\%$), $\text{CBOP}/M$ generates symmetric, statistically significant excess returns on **both legs**: Long Decile 1 ($\text{High} - R_f = +0.584\%, t = 2.669$) and Short Decile 10 ($\text{Low} - R_f = -0.592\%, t = -1.787$).
  - **Survival Across All 5 Risk Models (Table 7):** The $\text{CBOP}/M$ High-Low spread remains economically large and statistically significant at the $1\%$ level across every multi-factor specification.
- **Dữ liệu/Bảng (Comparison of Decile Sorts & Risk-Adjusted Alphas — Tables 3, 4, 6 & 7):**

| Portfolio / Factor Model                      |         Decile 1 (High)          |     Decile 5      |       Decile 10 (Low)       |   **$\text{CBOP}/M$ (H-L Spread)**   |          _Benchmark: $B/M$ (H-L Spread)_          |
| :-------------------------------------------- | :------------------------------: | :---------------: | :-------------------------: | :----------------------------------: | :-----------------------------------------------: |
| **Average $\text{CBOP}/M$ Ratio**             |             $0.928$              |      $0.101$      |          $-0.454$           |               $+1.382$               |            _Avg $B/M$ Spread: $2.067$_            |
| **Average Market Cap ($ Billion)**            |        $\$0.958\text{B}$         | $\$2.752\text{B}$ |      $\$1.598\text{B}$      |                  —                   | _D1: $\$0.326\text{B}$ vs D10: $\$2.681\text{B}$_ |
| **Raw Monthly Return (%)**                    |         $1.036\%^{***}$          |  $0.888\%^{***}$  |         $-0.140\%$          | **$1.175\%^{\***}$ ($t = 3.615$)\*\* |          _$0.790\%^{**}$ ($t = 2.312$)_           |
| **Excess Return ($\text{Ret} - R_f$)**        | **$0.584\%^{\***}$ ($2.669$)\*\* |         —         | **$-0.592\%^*$ ($-1.787$)** | **$1.175\%^{\***}$ ($t = 3.615$)\*\* |          _$0.790\%^{**}$ ($t = 2.312$)_           |
| **CAPM $\alpha$ (%)**                         |    $0.278\%^{***}$ ($3.112$)     |    $0.144\%^*$    | $-0.640\%^{***}$ ($-3.175$) | **$0.917\%^{\***}$ ($t = 3.643$)\*\* |          _$0.713\%^{**}$ ($t = 2.093$)_           |
| **Fama-French 3-Factor $\alpha$**             |     $0.207\%^{**}$ ($2.495$)     |  $0.163\%^{**}$   | $-0.325\%^{***}$ ($-2.999$) | **$0.532\%^{\***}$ ($t = 2.912$)\*\* |           _$0.228\%^_$ ($t = 1.690$)\*            |
| **Fama-French 5-Factor $\alpha$**             |     $0.181\%^{**}$ ($2.148$)     |    $0.123\%^*$    | $-0.415\%^{***}$ ($-3.513$) | **$0.596\%^{\***}$ ($t = 3.176$)\*\* |          _$0.412\%^{**}$ ($t = 2.501$)_           |
| **Fama-French 6-Factor $\alpha$**             |     $0.219\%^{**}$ ($2.562$)     |  $0.146\%^{**}$   | $-0.388\%^{***}$ ($-3.164$) | **$0.606\%^{\***}$ ($t = 3.249$)\*\* |          _$0.353\%^{**}$ ($t = 1.981$)_           |
| **Fletcher 5-Factor ($\text{CSI}$) $\alpha$** |    $0.264\%^{***}$ ($2.969$)     |  $0.167\%^{**}$   | $-0.311\%^{**}$ ($-2.371$)  | **$0.576\%^{\***}$ ($t = 3.076$)\*\* |           _$0.311\%^_$ ($t = 1.855$)\*            |
| **Fletcher 5-Factor ($\text{NSI}$) $\alpha$** |    $0.258\%^{***}$ ($2.931$)     |  $0.175\%^{**}$   | $-0.296\%^{**}$ ($-2.292$)  | **$0.554\%^{\***}$ ($t = 2.948$)\*\* |           _$0.307\%^_$ ($t = 1.805$)\*            |

- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _Dual-Chart Layout_.
  - **Chart Trái:** _Decile Step-Bar Chart_ từ D1 đến D10 (Trục X: Deciles 1–10; Trục Y: Raw Return %). Vẽ đường ngang Risk-free rate ($R_f = 0.452\%$) để thấy rõ D1 vượt cao trên $R_f$ và D10 sụt sâu dưới $R_f$.
  - **Chart Phải:** _Paired Horizontal Forest Plot / Lollipop Chart_ so sánh $\alpha$ và khoảng tin cậy $95\%$ giữa $\text{CBOP}/M$ (màu xanh đậm) và $B/M$ (màu xám) qua 6 mô hình định giá tài sản.

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 2.5 minutes]**
> **[Action/Cues]:** _[Advance to Slide 5. Direct the audience's attention to the comprehensive comparison table.]_
>
> "Slide 5 presents our central empirical evidence, synthesizing Tables 3, 4, 6, and 7 from the paper. When we sort the UK equity universe into ten value-weighted deciles based on $\text{CBOP}/M$, three critical insights emerge.
>
> **First, look at the fundamental economics of the extreme deciles.** Firms in Decile 1 exhibit an average $\text{CBOP}/M$ ratio of **$+0.928$**—these are cash-gushing value machines. Firms in Decile 10 exhibit an average $\text{CBOP}/M$ of **$-0.454$**—these are cash-burning enterprises whose market valuations are detached from operating cash reality. Also notice the average market capitalization: Decile 1 firms average **$\$958\text{ million}$**—nearly three times larger than the $\$326\text{ million}$ average of traditional High $B/M$ firms—while Decile 10 firms average **$\$1.598\text{ billion}$**. This immediately tells us that $\text{CBOP}/M$ is not merely a micro-cap illiquidity anomaly.
>
> **[Cues: Highlight the Excess Return row]**
> **Second, observe the symmetry of the return generation.** While the raw High-minus-Low spread is **$1.175\%$ per month** ($t = 3.615$), look at how that spread is earned relative to the risk-free rate. The long leg ($\text{High} - R_f$) contributes **$+0.584\%$ per month** ($t = 2.669$), and the short leg ($\text{Low} - R_f$) contributes **$-0.592\%$ per month** ($t = -1.787$). Unlike traditional $B/M$, where the long leg was dead weight, $\text{CBOP}/M$ earns virtually **50% of its profit from the long leg and 50% from the short leg**. For long-only institutional asset managers, Decile 1 alone generates significant positive alpha across every single model!
>
> **[Cues: Point to the Multi-Factor Alpha rows at the bottom]**
> **Third, look at the multi-factor risk-adjusted alphas.** When we subject the traditional $B/M$ spread to the Fama-French 3-factor model or Fletcher's (2021) UK 5-factor models ($\text{CSI}$ and $\text{NSI}$), its alpha shrinks to $0.228\%$ ($t = 1.690$) and $0.307\%$ ($t = 1.805$)—losing statistical significance at the $5\%$ level. In stark contrast, the $\text{CBOP}/M$ spread survives every single benchmark with flying colors: delivering **$0.917\%$** ($t = 3.643$) under CAPM, **$0.532\%$** ($t = 2.912$) under FF3, **$0.596\%$** ($t = 3.176$) under FF5, **$0.606\%$** ($t = 3.249$) under FF6, and **$0.576\%$** ($t = 3.076$) under Fletcher's $\text{CSI}$ model. Every single alpha is statistically significant at the $1\%$ level."

---

## SLIDE 6: EMPIRICAL RESULTS II — FACTOR SPANNING, FAMA-MACBETH & MEAN-VARIANCE EFFICIENCY

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Spanning Regression Asymmetric Subsumption (Table 9):** Regressing $\text{NVF}$ on all FF6 factors yields a highly significant intercept $\alpha = 0.358\%$/mo ($t = 2.344$). Conversely, when $\text{HML}$ is regressed on $\text{NVF}$ and other factors, $\alpha_{\text{HML}}$ collapses to completeness ($-0.130\%, t = -1.215$). **$\text{NVF}$ renders $\text{HML}$ redundant.**
  - **Fama-MacBeth Cross-Sectional Price of Risk (Table 10):** Across individual stocks, $\hat{\beta}_{\text{NVF}}$ commands a monthly risk premium of $\lambda_{\text{NVF}} = 0.466\%$ ($t = 4.323$) alone and $\lambda_{\text{NVF}} = 0.378\%$ ($t = 3.285$) alongside $\text{HML}$, while $\lambda_{\text{HML}}$ becomes statistically insignificant ($0.113\%, t = 1.576$).
  - **Mean-Variance Frontier Expansion (Table 12 — GRS Test):** Replacing $\text{HML}$ with $\text{NVF}$ reduces GRS statistics across all models and lifts the FF5 $p\text{-value}$ from $0.017$ (rejected) to **$0.122$ (cannot reject zero pricing errors)**.
- **Công thức (Empirical Spanning Equations from Table 9):**
  $$\widehat{\text{NVF}}_t = \mathbf{0.358\%}^{**} \,(t=2.344) - 0.088(R_m - R_f)_t - 0.029\text{SMB}_t + \mathbf{0.440}^{***}\text{HML}_t + \mathbf{0.251}^{***}\text{RMW}_t + \mathbf{0.181}^{**}\text{CMA}_t + \mathbf{0.175}^{***}\text{WML}_t \quad (R^2 = 34.4\%)$$
  $$\widehat{\text{HML}}_t = -0.130\% \,(t=-1.215) + \mathbf{0.084}^{**}(R_m - R_f)_t + 0.015\text{SMB}_t + \mathbf{0.506}^{***}\text{NVF}_t - \mathbf{0.258}^{***}\text{RMW}_t + \mathbf{0.401}^{***}\text{CMA}_t - \mathbf{0.299}^{***}\text{WML}_t \quad (R^2 = 54.4\%)$$
- **Dữ liệu/Bảng (Fama-MacBeth Cross-Sectional Slopes [Table 10] & GRS Test [Table 12]):**

| Panel A: Fama-MacBeth (Table 10)                | Model (1): All excl. $\text{NVF}$ | Model (2): $\text{NVF}$ excl. $\text{HML}$ |     Model (3): Horse-Race (Both)     |
| :---------------------------------------------- | :-------------------------------: | :----------------------------------------: | :----------------------------------: |
| **$\lambda_{\text{HML}}$ (Conventional Value)** |   $0.252\%^{**}$ ($t = 2.092$)    |                     —                      | $0.113\%$ ($t = 1.576$ - **Insig.**) |
| **$\lambda_{\text{NVF}}$ (New Value Factor)**   |                 —                 |    **$0.466\%^{\***}$ ($t = 4.323$)\*\*    | **$0.378\%^{\***}$ ($t = 3.285$)\*\* |
| **$\lambda_{\text{WML}}$ (Momentum)**           |   $0.353\%^{**}$ ($t = 2.521$)    |       $0.374\%^{***}$ ($t = 2.671$)        |    $0.375\%^{***}$ ($t = 2.660$)     |
| **$\lambda_{\text{RMW}}$ (Profitability)**      |      $0.056\%$ ($t = 0.644$)      |          $0.019\%$ ($t = 0.218$)           |       $0.022\%$ ($t = 0.253$)        |

| Panel B: GRS Test (Table 12)                 | FF3 GRS ($p\text{-val}$) | FF5 GRS ($p\text{-val}$) | FF6 GRS ($p\text{-val}$) | Fletcher CSI ($p\text{-val}$) |
| :------------------------------------------- | :----------------------: | :----------------------: | :----------------------: | :---------------------------: |
| **With Original $\text{HML}$**               |    $1.751$ ($0.016$)     |    $1.753$ ($0.017$)     |    $1.976$ ($0.004$)     |       $2.033$ ($0.003$)       |
| **Replacing $\text{HML}$ with $\text{NVF}$** |  **$1.551$ ($0.048$)**   |  **$1.362$ ($0.122$)**   |  **$1.484$ ($0.067$)**   |     **$1.703$ ($0.022$)**     |

- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _2-Panel Head-to-Head Comparison Chart_.
  - **Panel Trái:** _Horse-Race Bar Chart_ của Fama-MacBeth $t\text{-statistics}$ từ Table 10 (Khi đứng riêng vs. Khi đối đầu trực tiếp: $t_{\text{NVF}} = 3.285$ vượt qua ngưỡng chuẩn $t=3.0$ của Harvey, Liu & Zhu (2016), trong khi $t_{\text{HML}} = 1.576$ gục ngã).
  - **Panel Phải:** _GRS $p\text{-value}$ Threshold Plot_ từ Table 12 với đường ranh giới đứt nét tại $p = 0.05$ và $p = 0.10$, cho thấy mô hình FF5 + $\text{NVF}$ vượt qua vạch $10\%$ ($p = 0.122$).

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 2.5 minutes]**
> **[Action/Cues]:** _[Advance to Slide 6. Point to the two Spanning Regression equations first.]_
>
> "Slide 6 brings us to the econometric climax of the paper: Does $\text{NVF}$ genuinely expand the investment opportunity set, or is it merely a repackaging of existing profitability, investment, and value factors?
>
> Look at the two Spanning Regression equations reproduced from Table 9. In the first equation, when we regress $\text{NVF}$ on the six Fama-French factors, it loads positively on $\text{HML}$ ($0.440$), $\text{RMW}$ ($0.251$), $\text{CMA}$ ($0.181$), and $\text{WML}$ ($0.175$), yet leaves a highly significant unexplained intercept of **$\alpha = 0.358\%$ per month** ($t = 2.344$), with an $R^2$ of only $34.4\%$. Now look at the reverse regression in the second equation: when we regress traditional $\text{HML}$ on $\text{NVF}$ and the remaining factors, $\text{HML}$'s intercept plunges into negative territory at **$-0.130\%$ per month** ($t = -1.215$). Notice also the factor loadings on $\text{RMW}$ and $\text{WML}$: $\text{HML}$ loads **negatively** on both profitability ($-0.258$) and momentum ($-0.299$), whereas $\text{NVF}$ loads **positively** on both! In short, $\text{NVF}$ captures the value premium without forcing investors to buy unprofitable, negative-momentum value traps.
>
> **[Cues: Gesture to Panel A (Fama-MacBeth) and Panel B (GRS Test)]**
> This dominance is confirmed at the individual stock level in Panel A via Fama-MacBeth cross-sectional regressions (Table 10). When $\text{NVF}$ replaces $\text{HML}$ in Model 2, the cross-sectional price of risk $\lambda_{\text{NVF}}$ is **$0.466\%$ per month** with a $t\text{-statistic}$ of **$4.323$**—comfortably clearing the stringent $t > 3.0$ hurdle proposed by Harvey, Liu, and Zhu (2016) for new factor discoveries. Even more decisively, in Model 3—the direct horse-race containing both factors—$\lambda_{\text{NVF}}$ remains highly significant at **$0.378\%$** ($t = 3.285$), while $\lambda_{\text{HML}}$ collapses to **$0.113\%$** ($t = 1.576$).
>
> Finally, look at Panel B from Table 12. Across 25 double-sorted size and value portfolios, replacing $\text{HML}$ with $\text{NVF}$ reduces the Gibbons-Ross-Shanken ($\text{GRS}$) statistic in every single model. Most notably, in the 5-factor model, the $\text{GRS}$ statistic drops from $1.753$ ($p = 0.017$) to **$1.362$**, pushing the $p\text{-value}$ up to **$0.122$**. At the $10\%$ significance level, we can no longer reject the null hypothesis that joint pricing errors are zero."

---

## SLIDE 7: ROBUSTNESS CHECKS & THE SIZE-STRATIFIED ANATOMY (TABLE 11)

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Double-Sorted Size Stratification (Table 11):** Independent $3 \times 10$ sorts on Market Cap (Small, Neutral, Big) and $\text{CBOP}/M$ (10 deciles) confirm positive High-Low spreads across all size segments.
  - **Severe Big-Cap Alpha Attenuation (The Hidden Vulnerability):** While raw H-L spreads are $1.084\%$/mo ($t = 3.245$) in Small caps and $1.239\%$/mo ($t = 3.745$) in Neutral caps, the Big-cap raw spread drops by more than half to **$0.562\%$/mo** ($t = 2.681$).
  - **Institutional Long-Leg Decay in Big Caps:** Under FF6 and Fletcher 5-factor adjustments, the **Big-cap Long Leg (High-1)** alpha shrinks to **$0.181\%$/mo ($t = 1.909^*$)** and **$0.207\%$/mo ($t = 1.911^*$)**—barely significant at the $10\%$ level!
- **Dữ liệu/Bảng (Size-Stratified Performance Anatomy — Extracted from Table 11, Page 17):**

| Metric / Model Specification                     |          **Small Tercile**           |      **Neutral (Mid) Tercile**       |    **Big Tercile (Institutional Universe)**     |
| :----------------------------------------------- | :----------------------------------: | :----------------------------------: | :---------------------------------------------: |
| **Raw Return: High-1 (Long Leg)**                |     $0.751\%^{**}$ ($t = 2.189$)     |    $1.031\%^{***}$ ($t = 3.081$)     |          $0.880\%^{***}$ ($t = 3.310$)          |
| **Raw Return: Low-10 (Short Leg)**               |      $-0.333\%$ ($t = -0.715$)       |      $-0.208\%$ ($t = -0.495$)       |             $0.318\%$ ($t = 1.076$)             |
| **Raw H-L Spread ($\text{CBOP}/M$)**             | **$1.084\%^{\***}$ ($t = 3.245$)\*\* | **$1.239\%^{\***}$ ($t = 3.745$)\*\* |      **$0.562\%^{\***}$ ($t = 2.681$)\*\*       |
| **FF6 $\alpha$: High-1 (Long Leg)**              |     $0.326\%^{**}$ ($t = 2.132$)     |    $0.336\%^{***}$ ($t = 2.712$)     |      **$0.181\%^*$ ($t = 1.909$ - Weak!)**      |
| **FF6 $\alpha$: Low-10 (Short Leg)**             |    $-0.478\%^{**}$ ($t = -2.519$)    |   $-0.531\%^{***}$ ($t = -3.195$)    |         $-0.237\%^{**}$ ($t = -2.012$)          |
| **FF6 $\alpha$: High-Low Spread**                | **$0.803\%^{\***}$ ($t = 3.556$)\*\* | **$0.867\%^{\***}$ ($t = 4.212$)\*\* | **$0.418\%^{**}$ ($t = 1.984$ - Borderline)\*\* |
| **Fletcher ($\text{NSI}$) $\alpha$: H-L Spread** |    $0.793\%^{***}$ ($t = 3.495$)     |    $0.848\%^{***}$ ($t = 4.132$)     | **$0.408\%^{**}$ ($t = 1.969$ - Borderline)\*\* |

- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _Clustered Bar Chart with Significance Threshold Line ($t = 1.96$ and $t = 2.58$)_ dựa trên dữ liệu Bảng 11 (Trang 17).
  - **Trục X:** 3 Nhóm Vốn hóa (`Small Cap`, `Neutral Mid-Cap`, `Big Cap`).
  - **Trục Y:** FF6 Risk-Adjusted Alpha (% / tháng) tách rõ đóng góp của **Long Leg (D1)** và **Short Leg (D10)**.
  - **Key Takeaway trực quan:** Cho thấy rõ sự sụt giảm mạnh (Alpha Decay) ở cột `Big Cap`: Cột Long Leg rơi xuống dưới ngưỡng $t = 1.96$ ($t = 1.909$), làm bàn đạp hoàn hảo để chuyển sang phần Phản biện học thuật (Slide 8)!

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 2.0 minutes]**
> **[Action/Cues]:** _[Advance to Slide 7. Pause and adopt a critical, analytical tone as you transition from summarizing the paper to stress-testing it.]_
>
> "Up to this point, we have presented the evidence on its strongest terms. Now, as quantitative researchers, we must put on our skeptical reviewer hats and ask: _Where are the structural cracks in this empirical edifice?_
>
> The bridge between the paper's academic narrative and our critical evaluation lies right inside **Table 11 on Page 17** of the study—reproduced here on Slide 7. To check whether the $\text{CBOP}/M$ premium is confined to tiny, illiquid stocks, the author double-sorts the universe into three size terciles—Small, Neutral, and Big—and ten $\text{CBOP}/M$ deciles.
>
> While the paper concludes that the strategy works across all size groups, a granular forensic reading of Table 11 reveals a critical vulnerability for institutional capital. Look at the **Small** and **Neutral** terciles: the Fama-French 6-factor High-Low alphas are massive at **$0.803\%$** ($t = 3.556$) and **$0.867\%$** ($t = 4.212$). Now look at the right-hand column—the **Big Tercile**, which represents the liquid, investable universe for institutional asset managers:
>
> 1. First, the raw High-Low spread drops by more than half, from $1.239\%$ down to **$0.562\%$ per month** ($t = 2.681$).
> 2. Second, notice that in the Big tercile, the Low-10 raw return is actually **positive** ($+0.318\%$ per month)—meaning shorting expensive large-cap stocks loses money on an unadjusted basis!
> 3. Third, and most importantly, when we control for the FF6 or Fletcher 5-factor models in the Big tercile, the **Long Leg (High-1) alpha shrinks to just $0.181\%$ per month with a $t\text{-statistic}$ of $1.909$** (and $0.207\%, t = 1.911$ under Fletcher's model)—failing the $5\%$ significance threshold! Meanwhile, the overall Big-cap High-Low FF6 alpha sits at **$0.418\%$ with a $t\text{-statistic}$ of $1.984$**—hovering just hair-thin above the $1.96$ cutoff _before_ a single basis point of transaction cost is deducted. This brings us directly to the five methodological limitations of the study."

---

## SLIDE 8: CONSTRUCTIVE CRITIQUE — FIVE METHODOLOGICAL & IMPLEMENTATION LIMITATIONS

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Limitation 1 — The Intangible Capital Paradox (Internal Contradiction):** The paper motivates $\text{CBOP}/M$ by arguing that $B/M$ ignores knowledge-economy intangibles (pp. 1–2). Yet, $\text{CBOP} = \text{Rev} - \text{COGS} - \mathbf{\text{SG\&A}} + \Delta\text{WC}$ deducts 100% of $\text{SG\&A}$ (which houses R&D, software, and human capital investment), penalizing knowledge-intensive firms!
  - **Limitation 2 — Weak Benchmark Specification for $\text{RMW}$ (Footnote 3 Bias):** Footnote 3 (p. 5) defines $\text{RMW}$ using _Gross Profit Margin_ ($\text{GP}/\text{Revenue}$) instead of Operating Profitability ($\text{OP}/\text{Book Equity}$, Fama-French 2015) or $\text{GP}/\text{Total Assets}$ (Novy-Marx 2013). Furthermore, no horse-race is run against accrual-based $\text{OP}/M$ to isolate whether the alpha comes from the _cash adjustment_ ($\Delta \text{WC}$) or simply replacing $B$ with _flow earnings_ ($\text{OP}$).
  - **Limitation 3 — Unconditional Sorting & Unintended Sector Bets:** Ranking $\text{CBOP}/M$ across all industries without sector neutralization conflates firm-level cash efficiency with structural working-capital differences across sectors (e.g., Retail vs. Heavy Manufacturing).
  - **Limitation 4 — Econometric Inference Gaps in Fama-MacBeth:** Step-2 cross-sectional regressions on individual stocks (Table 10) use estimated first-stage betas ($\hat{\beta}$) without **Shanken (1992) Errors-in-Variables (EIV) correction** or **Newey-West HAC standard errors**.
  - **Limitation 5 — Market Frictions, UK Stamp Duty & Stale Signals:** Ignores the **0.50% UK Stamp Duty Reserve Tax (SDRT)** on purchases, bid-ask spreads, short-borrowing fees on distressed Decile-10 stocks ($\text{CBOP}/M = -0.454$), and suffers from 11-month signal decay due to annual July rebalancing.
- **Công thức (Mathematical Formalization of the Intangibles & Decomposition Gaps):**
  $$\text{Identity Decomposition: } \frac{\text{CBOP}_{i,t}}{M_{i,t}} \equiv \underbrace{\frac{\text{OP}_{i,t}}{M_{i,t}}}_{\text{Earnings Yield Effect}} - \underbrace{\frac{\Delta \text{Net Working Capital Accruals}_{i,t}}{M_{i,t}}}_{\text{Pure Cash-Accrual Effect (Untested Separately)}}$$
  $$\text{Intangible-Adjusted CBOP}^*_{i,t} = \text{CBOP}_{i,t} + \text{R\&D}_{i,t} + \theta_{\text{int}} \cdot \text{SG\&A}_{i,t} \quad (\text{Peters \& Taylor, 2017: } \theta_{\text{int}} \approx 0.30)$$
- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _Diagnostic Gap Matrix (2x3 Grid)_ hoặc _Waterfall of Alpha Erosion_ (Bắt đầu từ Gross Spread $1.175\%$ $\rightarrow$ Trừ Size Effect ở Big Cap còn $0.562\%$ $\rightarrow$ Trừ UK Stamp Duty + Short Borrow Fee + Bid-Ask Spread $\rightarrow$ Net Realized Alpha).

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 2.5 minutes]**
> **[Action/Cues]:** _[Advance to Slide 8. Speak with respectful academic authority, addressing each of the 5 limitations clearly.]_
>
> "Building on that empirical observation, Slide 8 outlines five constructive critiques that bridge this academic paper to frontier quantitative research.
>
> **First is what we term the 'Intangible Capital Paradox.'** In the introduction, the study rightly critiques $B/M$ for failing to capture intangible investments in a knowledge economy. Yet, in constructing $\text{CBOP}$, the formula subtracts $100\%$ of Selling, General, and Administrative expenses ($\text{SG\&A}$). Under UK/IFRS and GAAP accounting, R&D expenditure, employee training, IT infrastructure, and brand building are embedded inside $\text{SG\&A}$! By subtracting $\text{SG\&A}$ in full, $\text{CBOP}$ inadvertently penalizes knowledge-intensive firms that invest heavily in intangible capital. As shown in our second equation, following Peters and Taylor (2017) and Eisfeldt et al. (2022), adding back R&D and roughly $30\%$ of $\text{SG\&A}$ as intangible investment is essential to align the formula with the paper's own theoretical motivation.
>
> **Second is the Benchmark Specification and Decomposition Gap.** As noted in Footnote 3 on Page 5, the paper constructs the Fama-French $\text{RMW}$ profitability factor using _Gross Profit Margin_ ($\text{Gross Profit} / \text{Revenue}$) rather than Operating Profitability ($\text{OP}/\text{BE}$) or Novy-Marx's $\text{GP}/\text{Total Assets}$. Profit margin measures pricing power, not return on capital—which explains why $\text{RMW}$ appears statistically weak in Table 2 ($t = 1.662$) and completely insignificant in Table 10 ($t = 0.218$). Moreover, look at our first mathematical identity: $\text{CBOP}/M$ is the sum of Operating Profit-to-Market ($\text{OP}/M$) minus Working Capital Accruals-to-Market ($\Delta \text{WC}/M$). Because the paper only compares $\text{CBOP}/M$ against $B/M$ and never runs a horse-race against $\text{OP}/M$, we cannot tell how much of the $1.175\%$ spread comes from the cash-flow adjustment versus simply replacing Book Equity with Operating Profit!
>
> **Third, the study relies on unconditional cross-sectional sorting without industry neutralization.** Working capital intensity varies structurally across sectors—a UK supermarket chain naturally runs negative working capital (high payables, fast inventory turnover), whereas an aerospace manufacturer carries massive inventory and receivables. Without sector Z-scoring, Deciles 1 and 10 carry unintended industry bets.
>
> **Fourth, on econometric rigor:** the Fama-MacBeth regressions on individual stocks in Table 10 do not apply the **Shanken (1992) correction** for errors-in-variables in first-stage beta estimates, nor Newey-West HAC standard errors.
>
> **Fifth, regarding live investability:** half of the strategy's return comes from shorting Decile 10 cash-burning firms, where equity borrowing fees are highest, while every UK long purchase incurs a mandatory **0.50% Stamp Duty Reserve Tax (SDRT)**, and annual July rebalancing leaves the signal stale for up to 11 months."

---

## SLIDE 9: QUANTITATIVE ENHANCEMENT & PORTFOLIO OPTIMIZATION FRAMEWORK (INTEGRATING ARXIV:2108.02838)

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Two-Layer Quantitative Upgrading Architecture:** Preserves Dr. Duong's core $\text{CBOP}/M$ insight in **Layer 1 (Signal Generation)** while upgrading **Layer 2 (Portfolio Construction & Risk Allocation)** from naive Value-Weighting to institutional optimization.
  - **Layer 1 Upgrades (Enhanced Alpha Signal $\tilde{S}_{i,t}$):**
    1. _Intangible Capitalization:_ Add back $\theta \cdot \text{SG\&A}_{i,t}$ ($\theta \in [0, 0.3]$) to $\text{CBOP}_{i,t}$.
    2. _Sector-Neutral Z-Score:_ Standardize within each industry $g$: $z_{i,t} = (\text{CBOP}^*_{i,t}/M_{i,t} - \mu_{g,t}) / \sigma_{g,t}$.
    3. _Point-in-Time Quarterly Rebalancing:_ Replace stale annual July sorts with trailing 12-month (TTM) quarterly updates.
  - **Layer 2 Upgrades (Portfolio Optimization via `arXiv:2108.02838` & Transaction-Cost Penalty):**
    - Replace raw market-cap weighting ($w_i \propto M_i$) inside the top deciles with an optimization objective that maximizes expected alpha exposure while penalizing covariance risk ($\boldsymbol{\Sigma}_t$), tail drawdown ($\text{CVaR}$), and turnover costs ($\Lambda \|\mathbf{w}_t - \mathbf{w}_{t-1}\|_1$).
- **Công thức (Transaction-Cost-Aware Portfolio Optimization Objective):**
  $$\max_{\mathbf{w}_t} \quad \mathbf{w}_t' \hat{\boldsymbol{\mu}}_t^{\text{CBOP}^*} - \frac{\gamma}{2} \mathbf{w}_t' \hat{\boldsymbol{\Sigma}}_t^{\text{LW}} \mathbf{w}_t - \kappa \cdot \text{CVaR}_{\alpha}(\mathbf{w}_t) - \sum_{i=1}^{N} c_i |w_{i,t} - w_{i,t-1}^+|$$
  $$\text{Subject to:} \quad \sum_{i=1}^{N} w_{i,t} = 1, \quad \mathbf{w}_t' \boldsymbol{\beta}_{m,t} = \beta_{\text{target}}, \quad w_{\min} \le w_{i,t} \le w_{\max} \quad (w_{i,t} \ge 0 \text{ for Long-Only Mandate})$$
- **Dữ liệu/Bảng (Architectural Comparison: Baseline Academic Paper vs. Proposed Live-Trading System):**

| System Dimension            | Baseline Study (Le Quy Duong, 2025)              | Upgraded Institutional Quant Framework                                                       |
| :-------------------------- | :----------------------------------------------- | :------------------------------------------------------------------------------------------- |
| **1. Signal Numerator**     | Raw $\text{CBOP} = \text{OP} - \Delta \text{WC}$ | **Intangible-Adjusted $\text{CBOP}^* = \text{CBOP} + \theta \text{SG\&A}$**                  |
| **2. Cross-Sectional Sort** | Unconditional Market-Wide Deciles                | **Industry-Neutral Cross-Sectional Z-Score ($z_{i,g,t}$)**                                   |
| **3. Rebalancing Horizon**  | Annual (Every July — 11-month lag)               | **Quarterly TTM with Turnover Buffer Rule**                                                  |
| **4. Weighting Scheme**     | Naive Market-Cap Weighting ($w_i \propto M_i$)   | **Mean-Variance-CVaR Optimization (`arXiv:2108.02838`)**                                     |
| **5. Friction Modeling**    | Zero Costs ($0\text{ bps}$)                      | **UK SDRT ($50\text{ bps}$) + Spread ($20\text{ bps}$) + Borrow Cost ($150\text{ bps/yr}$)** |

- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _2-Stage System Block Diagram (Signal Layer $\rightarrow$ Optimization Layer $\rightarrow$ Live Gradio/Bokeh Dashboard)_.
  - **Key Takeaway trực quan:** Cho thấy rõ sự tôn trọng tuyệt đối với đóng góp gốc của thầy Dương (giữ $\text{CBOP}/M$ ở trái tim của Tầng 1), nhưng bọc thêm lớp giáp التối ưu hóa Danh mục ở Tầng 2 để giải quyết bài toán suy giảm Alpha ở nhóm Big-cap (Table 11).

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 2.0 minutes]**
> **[Action/Cues]:** _[Advance to Slide 9. Gesture enthusiastically to the Two-Layer Architecture diagram and optimization equation.]_
>
> "How do we transform these five critiques into a constructive breakthrough for live quantitative trading? On Slide 9, we propose a **Two-Layer Quantitative Upgrading Framework** that bridges academic asset pricing and institutional portfolio management.
>
> In quantitative finance, we strictly separate **Alpha Signal Generation**—which answers _'Which stocks have higher expected returns?'_—from **Portfolio Construction**—which answers _'How should we weight those stocks to maximize net risk-adjusted wealth?'_ Dr. Duong's paper is a landmark achievement in Layer 1. Therefore, we preserve $\text{CBOP}/M$ as our core alpha engine, applying three targeted surgical refinements:
>
> 1. We introduce an intangible capitalization parameter $\theta$, adding back a fraction of $\text{SG\&A}$ and R&D so innovative firms are not unfairly penalized.
> 2. We apply **Industry-Neutral Z-scoring**, ranking each firm's $\text{CBOP}^*/M$ relative to its sector peers.
> 3. We transition from annual July rebalancing to **Quarterly Trailing-Twelve-Month (TTM)** updates with a turnover buffer.
>
> **[Cues: Point to the Optimization Equation in the center of the slide]**
> Next, in **Layer 2**, we address the Big-cap alpha decay we uncovered in Table 11. Why did the Big-cap long leg yield a $t\text{-statistic}$ of only $1.909$ under Value-Weighting? Because Market-Cap Weighting blindly allocates the largest portfolio weights to mega-cap stocks regardless of their return covariance, tail risk, or signal strength!
>
> Drawing on modern portfolio optimization literature—including `arXiv:2108.02838`—we replace naive market-cap weights inside the top deciles with the constrained optimization objective shown on the slide. Using a Ledoit-Wolf shrinkage covariance matrix $\hat{\boldsymbol{\Sigma}}_t^{\text{LW}}$ and Conditional Value-at-Risk ($\text{CVaR}_\alpha$), the optimizer maximizes expected $\text{CBOP}^*/M$ alpha while explicitly subtracting transaction costs $c_i$—incorporating the 50-basis-point UK Stamp Duty, bid-ask spreads, and short-borrowing fees—and supporting a **Long-Only constraint ($w_{i,t} \ge 0$)** for markets or mandates where shorting is restricted."

---

## SLIDE 10: LIVE TRADING SIMULATION DASHBOARD (GRADIO + BOKEH) & CONCLUSION

### 1. Nội dung hiển thị trên Slide:

- **Bullet points:**
  - **Interactive Research-to-Production Sandbox (Gradio + Bokeh):** Allows real-time stress-testing of the $\text{CBOP}/M$ strategy under varying institutional constraints:
    - _Parameter Sliders:_ Transaction Cost ($0 - 100\text{ bps}$), Short Borrow Fee ($0 - 300\text{ bps/yr}$), Intangible $\text{SG\&A}$ Capitalization ($\theta \in [0\%, 50\%]$), and Rebalancing Frequency (Annual vs. Quarterly).
    - _Mandate Toggle:_ Academic Long-Short ($100/100$) vs. Institutional $130/30$ vs. Long-Only Top Decile.
  - **Final Verdict & Core Takeaways:**
    1. **Measurement Matters:** $\text{CBOP}/M$ decisively rescues the UK value premium ($1.175\%$/mo, $t = 3.615$) where $B/M$ failed post-2006.
    2. **Asset Pricing Dominance:** $\text{NVF}$ ($0.692\%$/mo, $t = 4.442$) spans and subsumes $\text{HML}$ across time-series, Fama-MacBeth ($\lambda_{\text{NVF}} = 0.466\%$), and GRS tests.
    3. **From Paper to Production:** Combining $\text{CBOP}/M$ with intangible adjustments, sector neutralization, and covariance-aware portfolio optimization unlocks true net-of-cost investability.
- **Dữ liệu/Bảng (Q&A Defense Matrix — Quick Reference for Audience Discussion):**

| Potential Question from Lecturer / Audience                  | Core Empirical Anchor in Paper                                                                                       | Quantitative Extension Answer                                                                                             |
| :----------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------ |
| **1. Why does $\text{NVF}$ beat $\text{HML}$ so strongly?**  | Table 2 & Table 9: $\text{Corr}(\text{NVF}, \text{WML}) = +0.036$ vs $\text{Corr}(\text{HML}, \text{WML}) = -0.440$. | Purging accruals removes "value traps" with negative momentum and poor profitability.                                     |
| **2. Why did a _lower_ GRS mean a _better_ model?**          | Table 12 (p. 18): FF5 GRS drops $1.753 \rightarrow 1.362$ ($p: 0.017 \rightarrow 0.122$).                            | $H_0: \boldsymbol{\alpha} = \mathbf{0}$. Smaller GRS = smaller joint pricing errors = closer to Mean-Variance frontier.   |
| **3. Can we trade this in Vietnam (HOSE/HNX) or Long-Only?** | Table 6 & 7: Long leg D1 alone yields $+0.584\%$ excess return ($\alpha_{\text{FF6}} = +0.219\%, t = 2.562$).        | Yes! Unlike $B/M$, $\text{CBOP}/M$'s long leg is profitable standalone, and Layer-2 optimization boosts its Sharpe ratio. |

- **Gợi ý Visual/Chart:**
  - **Loại biểu đồ:** _Live Embedded Screenshot / Wireframe of the 4-Panel Bokeh Dashboard_ (Panel 1: Cumulative Log-Wealth Curve [Gross vs. Net vs. Optimized]; Panel 2: Underwater Drawdown Plot; Panel 3: Decile Monotonicity Bar Chart; Panel 4: Rolling 36-Month Sharpe & Information Ratio).

### 2. Kịch bản thuyết trình (Speaker Notes):

> **[Estimated Time: 1.5 minutes]**
> **[Action/Cues]:** _[Advance to Slide 10. Transition smoothly toward the live dashboard demonstration or concluding summary.]_
>
> "To bring these theoretical extensions to life, on Slide 10 we present our **Interactive Quantitative Sandbox**, built with Python, Gradio, and Bokeh. Rather than viewing backtest results as static tables on a page, our dashboard allows us to dynamically stress-test the $\text{CBOP}/M$ strategy in real time.
>
> When we dial in realistic UK market frictions—a 50-basis-point Stamp Duty, a 20-basis-point bid-ask spread, and a 150-basis-point annual short-borrowing fee on Decile 10—we can visually observe how the naive value-weighted strategy experiences significant alpha erosion, particularly in the large-cap segment. However, as soon as we activate our **Layer-1 Intangible & Sector-Neutral adjustments** alongside **Layer-2 Portfolio Optimization**, the net equity curve recovers its upward trajectory, Maximum Drawdown is compressed, and the Long-Only mandate becomes highly viable for emerging markets like Vietnam where short-selling is unavailable.
>
> **[Cues: Take a step forward, look at Professor Duong and the entire hall for the closing statement]**
> In conclusion, Dr. Le Quy Duong's (2025) study delivers a vital message to both academia and the asset management industry: **In a modern economy, how we measure fundamental value matters.** By purifying operating profitability of accounting accruals, $\text{CBOP}/M$ resurrects the UK value premium ($1.175\%$ per month, $t = 3.615$), spans and subsumes the classic Fama-French $\text{HML}$ factor ($\alpha = 0.358\%, t = 2.344$), and significantly reduces asset-pricing errors across the cross-section. By pairing this powerful fundamental signal with modern intangible accounting and quantitative portfolio optimization, we can successfully bridge the gap from empirical asset pricing to institutional live trading.
>
> Thank you very much for your attention. We now welcome your questions and critical feedback."

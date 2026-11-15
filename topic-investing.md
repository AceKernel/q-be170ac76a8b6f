# International returns, diversification and ADRs

Keywords: TSMC Nestle ADR underlying shares 1:5 bid ask investor return covariance correlation index futures home bias portfolio.

[Main index](INDEX.md) | [Question bank](QUESTIONS.md) | [Exam reuse map](PATTERNS.md)

Checked supplementary reference, not an official marking scheme. Original course sources and current official corrections take precedence.


For foreign-asset prices $P_F$, a dividend $D_F$ received at sale, and $S^{D/F}$:

$$1+R_D=\frac{(P_{F,1}+D_F)S_1}{P_{F,0}S_0}
=(1+R_F)\frac{S_1}{S_0}.$$

Convert separate dividends at their actual receipt-date rates if those differ. Buy stock at its ask and sell at its bid; execute the currency conversions on their appropriate dealer sides. Do not average bid and ask.

$$\mathbb E[R_p]=\sum_i w_i\mathbb E[R_i],\qquad
\sigma_p^2=\sum_i w_i^2\sigma_i^2+2\sum_{i<j}w_iw_j\rho_{ij}\sigma_i\sigma_j.$$

All returns/risks must use a common currency. The foreign-asset/FX volatility relation is the approximation in [VaR reference](topic-var.md). Tutorial 8 Q9 gives enough to calculate UK equity volatility in AUD, $\sqrt{0.15^2+0.05^2+2(0.2)(0.15)(0.05)}=16.7332\%$, **not** the total portfolio volatility: its AUD-return correlation with Australian stocks is missing.

An ADR representing $m$ underlying shares satisfies $P_{ADR,D}=mP_{share,F}S^{D/F}$, ignoring conversion costs. USD denomination does not remove the underlying FX exposure.

**S2 2025 / Tutorial 8 Q11 checks:** TSMC ADR USD151.40, one ADR = five shares, USD0.0308/TWD gives $P_{share}=151.40/(5\times0.0308)=\mathrm{TWD}\,983.12$. The ratio and price are image-based in the exam; the [checked data record](exam-tsmc-data.md) identifies that source.

Nestle: purchase CHF75 at CHF1.01/AUD; sale CHF112 at CHF0.99/AUD. Thus

$$R_{AUD}=\frac{112/0.99}{75/1.01}-1=52.3508\%.$$

Course ADR taxonomy: Level I OTC; Level II exchange-listed, no new public capital; Level III exchange-listed with new public capital. Historical regulatory details in the source slides are course material, not current legal advice.

International diversification exploits imperfect correlations; it does not eliminate systematic risk, transaction costs, political risk or crisis correlation increases. Index futures offer fast/liquid low-cash market exposure, but have margin/basis/contract-size issues and do not automatically eliminate currency risk.

**Worked routes:** [T08-CORE-Q01](question-t08-core-q01.md), [T08-CORE-Q04](question-t08-core-q04.md), [T08-CORE-Q05](question-t08-core-q05.md), [T08-CORE-Q09](question-t08-core-q09.md), [T08-CORE-Q10](question-t08-core-q10.md), [T08-CORE-Q11](question-t08-core-q11.md), [T08-EXTRA-Q15](question-t08-extra-q15.md), [T08-EXTRA-Q31](question-t08-extra-q31.md).

**Sources:** [L08 PDF p3](page-l08-003.md), [L08 PDF p4](page-l08-004.md), [L08 PDF p8](page-l08-008.md), [L08 PDF p9](page-l08-009.md), [L08 PDF p12](page-l08-012.md), [L08 PDF p21](page-l08-021.md), [L08 PDF p29](page-l08-029.md), [L08 PDF p30](page-l08-030.md), [L08 PDF p34](page-l08-034.md), [L08 PDF p36](page-l08-036.md).

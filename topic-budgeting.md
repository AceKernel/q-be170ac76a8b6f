# International capital budgeting and APV

Keywords: parent subsidiary FCF depreciation tax shields blocked funds remittance cannibalisation APV subsidy terminal value IC3 Xebec Thorwald BT.

[Main index](INDEX.md) | [Question bank](QUESTIONS.md) | [Exam reuse map](PATTERNS.md)

Checked supplementary reference, not an official marking scheme. Original course sources and current official corrections take precedence.


Specify parent/project perspective and cash-flow currency. Incremental cash flows include taxes, remittance restrictions, royalties/fees, cannibalisation and working-capital/capital expenditure effects where applicable.

$$FCF=EBIT(1-\tau)+\mathrm{Dep}-CapEx-\Delta NWC,$$
$$NPV_D=-I_{0,D}+\sum_{t=1}^N\frac{CF_{F,t}S_t^{D/F}}{(1+k_D)^t}.$$

Forecast $S_t^{D/F}=S_0[(1+\pi_D)/(1+\pi_F)]^t$ under PPP. Equivalently value foreign cash flows at a consistent foreign discount rate and convert foreign NPV at $S_0$, where the course imposes

$$1+k_F=(1+k_D)\frac{1+\pi_F}{1+\pi_D}.$$

This equivalence requires the course's currency/PPP/discount-rate consistency assumptions. Use an explicitly given foreign WACC in a case (e.g. IC3) rather than silently overriding it.

$$TV_N=\frac{FCF_N(1+g)}{k-g},\quad k>g.$$

Terminal value is at $N$, then discounted to zero; do not double-count year-$N$ cash flow or salvage.

$$APV=NPV_{\text{all-equity}}+PV(\text{interest tax shields})+PV(\text{other financing effects}).$$

Use an unlevered asset return for the base case, then value subsidies/issue costs/distress/tax shields separately without double-counting financing benefits already embedded in WACC. Lecture 10 p8 distinguishes fixed nominal debt (tax shields discounted at $r_D$) from a stable leverage ratio (asset-risk discounting in its simplified setup). Apply perpetual formulas only under their stated perpetual assumptions; finite debt needs dated cash flows.

**Worked routes:** [T10-CORE-Q01](question-t10-core-q01.md), [T10-CORE-Q03](question-t10-core-q03.md), [T10-CORE-Q04](question-t10-core-q04.md), [T10-CORE-Q06](question-t10-core-q06.md), [T10-CORE-Q07](question-t10-core-q07.md), [T10-EXTRA-Q12](question-t10-extra-q12.md), [T10-EXTRA-Q13](question-t10-extra-q13.md); [KrugerWales](exam-krugerwales.md).

**Incomplete source warning:** [T10-BT-FRAGMENT](question-t10-bt-fragment.md) is an unnumbered solution fragment whose original pro forma is absent. It is not a complete numerical practice case; do not invent the missing table or label it Q8.

**Sources:** [L10 PDF p4](page-l10-004.md), [L10 PDF p6](page-l10-006.md), [L10 PDF p7](page-l10-007.md), [L10 PDF p8](page-l10-008.md), [L10 PDF p9](page-l10-009.md), [L10 PDF p10](page-l10-010.md), [L10 PDF p15](page-l10-015.md), [L10 PDF p16](page-l10-016.md), [L10 PDF p19](page-l10-019.md), [L10 PDF p20](page-l10-020.md), [L10 PDF p21](page-l10-021.md), [L10 PDF p22](page-l10-022.md), [L10 PDF p23](page-l10-023.md).

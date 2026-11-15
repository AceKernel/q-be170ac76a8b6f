# Interest parity, Fisher effects and foreign borrowing

Keywords: IRP IFE Fisher CIA covered arbitrage uncovered carry forward unbiasedness Iberia loan indifference.

[Main index](INDEX.md) | [Question bank](QUESTIONS.md) | [Exam reuse map](PATTERNS.md)

Checked supplementary reference, not an official marking scheme. Original course sources and current official corrections take precedence.


Use horizon-matched rates. In $S^{A/B}$ units:

$$\frac{F_{0,T}}{S_0}=\frac{1+i_{A,T}}{1+i_{B,T}},\qquad
(1+i)=(1+r)(1+\pi).$$

For annual effective rates and $T$ years, the IFE forecast is

$$\frac{\mathbb E_0[S_T]}{S_0}=\frac{(1+i_A)^T}{(1+i_B)^T}.$$

Use simple proportional accrual for a short period if the stated p.a. quotation/question specifies it; do not substitute annual compounding indiscriminately.

For a domestic unit invested over one period, compare $1+i_A$ with $(F/S_0)(1+i_B)$. If unequal after spreads and borrowing/lending costs, borrow on the cheaper covered route, convert at the correct spot side, invest, and cover the **full maturity amount** forward. Tabulate cash flows at 0 and $T$ and show a positive residual after repayment.

Uncovered carry is risky, not riskless arbitrage. $F_{0,T}=\mathbb E_0[S_T]$ is an unbiasedness assumption, not a guarantee that realised spot equals forward.

**Iberia check (S2 2025 III.2 / Tutorial 4 Q9):** if $S_T$ is USD/EUR, indifference requires

$$\frac{13{,}500{,}000(1.06)^2}{S_T}=10{,}000{,}000(1.05)^2,
\qquad S_T=1.35\left(\frac{1.06}{1.05}\right)^2=1.3758367\ \mathrm{USD/EUR}.$$

This is a break-even exchange rate, not a forecast of actual spot. Compare repayments in the same currency to determine which loan is cheaper on either side.

**Worked routes:** [T04-CORE-Q01](question-t04-core-q01.md), [T04-CORE-Q03](question-t04-core-q03.md), [T04-CORE-Q05](question-t04-core-q05.md), [T04-CORE-Q06](question-t04-core-q06.md), [T04-CORE-Q09](question-t04-core-q09.md), [T09-CAPITAL-Q05](question-t09-capital-q05.md).

**Sources:** [L04 PDF p7](page-l04-007.md), [L04 PDF p9](page-l04-009.md), [L04 PDF p17](page-l04-017.md), [L04 PDF p18](page-l04-018.md), [L04 PDF p20](page-l04-020.md), [L04 PDF p27](page-l04-027.md), [L04 PDF p28](page-l04-028.md).

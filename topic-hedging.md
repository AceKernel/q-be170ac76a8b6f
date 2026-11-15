# Transaction-exposure hedge comparison

Keywords: receivable payable forward money market option WACC opportunity cost Coal River Airbus CSL Swedish Steel agency costs.

[Main index](INDEX.md) | [Question bank](QUESTIONS.md) | [Exam reuse map](PATTERNS.md)

Checked supplementary reference, not an official marking scheme. Original course sources and current official corrections take precedence.


First identify the foreign-currency amount $Q$, due date $T$, receivable/payable, quote units, rates, and premium convention. Compare alternatives **at the same date and in the same home currency**.

For $S,F,X$ quoted home/foreign:

| Strategy | Receivable | Payable |
|---|---|---|
| Unhedged at $T$ | $QS_T$ | $QS_T$ |
| Forward at $T$ | $QF_{\mathrm{bid}}$ | $QF_{\mathrm{ask}}$ |
| Option at $T$ | $Q\max(S_{T,\mathrm{bid}},X)-\mathrm{FV}_T(\text{put premium})$ | $Q\min(S_{T,\mathrm{ask}},X)+\mathrm{FV}_T(\text{call premium})$ |

For money-market hedging a receivable, borrow $Q/(1+i_{F,\mathrm{borrow}})$ foreign today, convert at spot bid, and invest/use the home proceeds. Repay using the receivable. For a payable, buy and invest $Q/(1+i_{F,\mathrm{deposit}})$ foreign today at spot ask, financing the home outlay at the appropriate funding rate.

The relevant home carry rate depends on the question. **Trident and Coal River use WACC/opportunity cost for the specified use of funds**; do not automatically use the domestic deposit rate instead. Match annual/period rates and quote inversion before substitution. A percentage option premium may be charged on the current home-currency equivalent; follow the stated source convention.

An option provides a floor for receipts/cap for payments while retaining favourable spot outcomes, at a premium. The exercise region is not an isolated 'bad strategy': it identifies the protected worst-case net proceeds/cost. Forward and money-market hedges coincide only under the relevant no-arbitrage/funding assumptions.

If a question evaluates an option using a forecast spot (as Airbus does), label the result a **forecast scenario**. In general, $\mathbb E[\max(S_T,X)]\ne\max(\mathbb E[S_T],X)$ without distributional assumptions.

Reasons for hedging in the course include distress costs, funding of investment and managerial agency/human-capital exposure. In frictionless markets shareholder diversification weakens the case; hedging does not create value automatically.

**Worked routes:** [T06-CORE-Q02](question-t06-core-q02.md), [T06-CORE-Q03](question-t06-core-q03.md), [T06-CORE-Q06](question-t06-core-q06.md), [T06-CORE-Q07](question-t06-core-q07.md), [T06-CORE-Q08](question-t06-core-q08.md), [T06-CORE-Q10](question-t06-core-q10.md), [T07-CORE-Q06](question-t07-core-q06.md).

**Sources:** [L06 PDF p11](page-l06-011.md), [L06 PDF p12](page-l06-012.md), [L06 PDF p20](page-l06-020.md), [L06 PDF p21](page-l06-021.md), [L06 PDF p23](page-l06-023.md), [L06 PDF p25](page-l06-025.md), [L06 PDF p28](page-l06-028.md), [L06 PDF p31](page-l06-031.md), [L06 PDF p32](page-l06-032.md), [L06 PDF p36](page-l06-036.md), [L06 PDF p38](page-l06-038.md).

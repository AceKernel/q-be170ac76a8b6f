# Currency options and futures

Keywords: call put strike X premium intrinsic time value American European long short futures marking to market Royal Doulton Bechtel contingent exposure.

[Main index](INDEX.md) | [Question bank](QUESTIONS.md) | [Exam reuse map](PATTERNS.md)

Checked supplementary reference, not an official marking scheme. Original course sources and current official corrections take precedence.


Declare a quote in home currency per foreign unit. The lecture denotes strike by $X$:

$$C_T=\max(S_T-X,0),\qquad P_T=\max(X-S_T,0).$$

These are **payoffs**, not profits. Long-option profit subtracts premium and fees; if comparing all cash flows at $T$, subtract their carried-forward value. Short-option payoffs have the opposite sign, plus received premium. A premium in cents per 100 yen must be converted before multiplying by yen notional.

| Exposure | Forward/futures hedge | Option hedge |
|---|---|---|
| Foreign-currency receivable | Sell foreign currency | Buy put on foreign currency |
| Foreign-currency payable | Buy foreign currency | Buy call on foreign currency |
| Bid/uncertain foreign revenue | An obligatory sale can create a new exposure if the bid fails | Put preserves the right not to transact |

Long put plus short call at the same strike is a synthetic short forward at expiry: $\max(X-S_T,0)-\max(S_T-X,0)=X-S_T$. It eliminates the contingency advantage of a standalone put (Bechtel).

Futures daily settlement: long gains $Q(F_t-F_{t-1})$; short gains its negative. Contract count is exposure divided by contract size (state any rounding). Futures are standardised/exchange-traded and marked to market; forwards are OTC and tailored. Option buyers have rights; writers have obligations if exercised. American options allow exercise before expiry; European options only at expiry.

**Royal Doulton course check:** GBP250,000 / GBP10,000 = 25 calls. At USD0.022/GBP plus USD1.50 per contract, total premium/fees are USD5,537.50. With strike USD1.50/GBP, the capped total is USD380,537.50, or USD1.52215/GBP, ignoring premium financing as in the source question.

**Worked routes:** [T05-OPTIONS-Q03](question-t05-options-q03.md), [T05-OPTIONS-Q04](question-t05-options-q04.md), [T05-OPTIONS-Q05](question-t05-options-q05.md), [T05-OPTIONS-Q06](question-t05-options-q06.md), [T05-FUTURES-Q03](question-t05-futures-q03.md), [T05-FUTURES-Q06](question-t05-futures-q06.md). [Graph conventions](GRAPH-STYLE.md).

**Sources:** [L05 PDF p6](page-l05-006.md), [L05 PDF p7](page-l05-007.md), [L05 PDF p8](page-l05-008.md), [L05 PDF p14](page-l05-014.md), [L05 PDF p17](page-l05-017.md), [L05 PDF p19](page-l05-019.md), [L05 PDF p23](page-l05-023.md), [L05 PDF p24](page-l05-024.md).

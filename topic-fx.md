# Exchange-rate quotations and arbitrage

Keywords: bid ask inverse cross rate triangular arbitrage swap points forward premium pip Bloomberg USDCHF.

[Main index](INDEX.md) | [Question bank](QUESTIONS.md) | [Exam reuse map](PATTERNS.md)

Checked supplementary reference, not an official marking scheme. Original course sources and current official corrections take precedence.


Write the currency units before calculating. $S_t^{A/B}$ means units of $A$ per unit of $B$; $B$ is the denominator/base currency. A Bloomberg ticker **AB** instead quotes units of **B per A**: GBPZAR 20 means ZAR20/GBP.

| Operation | Course convention |
|---|---|
| Dealer buys denominator currency | Bid |
| Dealer sells denominator currency | Ask |
| Invert a bid-ask quote | $[b,a]^{A/B}\mapsto[1/a,1/b]^{B/A}$ |
| Cross rate | Cancel currency units along the actual conversion route; apply the dealer's appropriate side at each step |
| Triangular arbitrage | Compare both closed currency routes with the starting amount; report the profitable route and net profit |

For a quote change $g=S_1/S_0-1$, the denominator currency appreciates by $g$ against the numerator. The inverse quote changes by $-g/(1+g)$, not simply $-g$.

$$\text{spread}=\frac{a-b}{a}\,100\%,\qquad
\text{annualised forward premium}=\frac{F-S}{S}\frac{360}{N}\,100\%.$$

Use the requested day count and annualise only when requested. A positive premium refers to the denominator currency. For unsigned swap-point pairs, ascending points are added; descending points are subtracted. Convert pips to quote units first (normally $0.0001$, JPY $0.01$); explicitly signed points retain their sign. Lecture 1 p29 contains an inconsistent numeric illustration: use the stated convention, Lecture 1 pp25-28 and Tutorial 1 Q6 rather than copying that table mechanically.

**Worked routes:** [T01-CORE-Q02](question-t01-core-q02.md), [T01-CORE-Q03](question-t01-core-q03.md), [T01-CORE-Q05](question-t01-core-q05.md), [T01-CORE-Q06](question-t01-core-q06.md), [T01-CORE-Q07](question-t01-core-q07.md).

**Sources:** [L01 PDF p9](page-l01-009.md), [L01 PDF p10](page-l01-010.md), [L01 PDF p18](page-l01-018.md), [L01 PDF p19](page-l01-019.md), [L01 PDF p25](page-l01-025.md), [L01 PDF p26](page-l01-026.md), [L01 PDF p28](page-l01-028.md), [L01 PDF p30](page-l01-030.md), [L01 PDF p32](page-l01-032.md).

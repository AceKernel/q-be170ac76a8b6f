# T08-CORE-Q09: Australian UK portfolio missing correlation

Source: Tutorial 8, Q9. Source block: **Main questions**.

[Original PDF p5](tutorial-08-solutions.pdf#page=5)

[Topic reference](topic-investing.md) | [Tutorial question index](questions-t08.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

**Source limitation:** The requested total portfolio risk is not numerically identified: the Australian/UK-in-AUD return correlation is missing. The foreign sleeve volatility is calculable.

## PDF page 5

```text
9.    (Past Exam Question from 2024)

    An Australian investor invests half her wealth in a portfolio of Australian stocks and

      half her wealth in UK stocks. The risk (standard deviation) of the UK portfolio is 15%

      in GBP, while risk of the Australian portfolio is 10% in AUD. The volatility of the spot

     rate (i.e., standard deviation of S(AUD/GBP)) is 5% and the correlation between the

     spot rate and returns of the UK market is 0.2. Can the standard deviation of the

      investor’s overall portfolio in AUD terms be estimated? If yes, show your calculations.

       If no, explain your reasoning.


The answer cannot be determined given the information.

1.   Need to convert VOLATILITY of the UK market into AUD terms.

                                 𝜎𝑈𝐾,$2  = 𝜎𝑈𝐾2 + 𝜎𝑆2 + 2𝜌𝑈𝐾,𝑆𝜎𝑈𝐾𝜎𝑆

              = 0.152 + 0.052 + 2 × 0.2 × 0.15 × 0.05 = 0.028

                                 𝜎𝑈𝐾,𝑆= 16.73%

2.   Then apply the classic portfolio formula. However, this CANNOT be estimated, as we need
      correlation between AUS and UK in $ terms (𝜌𝑈𝑆,𝑈𝐾$).


                                                                             5
```

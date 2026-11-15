# T06-CORE-Q11: Football club GBP investment volatility and VaR

Source: Tutorial 6, Q11. Source block: **Main questions**.

[Original PDF p14](tutorial-06-solutions.pdf#page=14)

[Topic reference](topic-var.md) | [Tutorial question index](questions-t06.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

**Source limitation:** The official solution uses a negligible/zero-mean approximation. See the checked VaR reference before carrying that convention into a new question.

## PDF page 14

```text
11.  You are working at the family office of an Australian billionaire. She is currently

     trying to buy a third division football club in the UK. She has made an investment

      of 2,000,000 GBP in the football club’s stock which trades on the London Stock

     Exchange. The daily mean and standard deviation of the club’s stock returns are

    0.002614% and 2.20% respectively. The daily mean and standard deviation of the

     dollar/pound exchange rate is 0 and 0.55% respectively. The current spot rate is

    S(AUD/GBP) = 1.878. The correlation between the club’s stock returns and the

     dollar/pound exchange rate is -0.06. The investor is very concerned about the risk

      of her foreign investment in the UK.

    You decided that Value at Risk (VaR) is a proper measure of risk to address your

      billionaire employer’s concern. Calculate the 1 day 5% VaR of her investment in

     the UK (in AUD terms) and explain carefully what your result would mean.

     [Useful information: You can assume that financial returns are normally distributed and

      the relevant critical statistic for 5% (1%) is 1.65 (2.33).]

                                                        2024 exam question (*)



      2p = 0.0222 + 0.00552 + 2 × (-0.06) × 0.022 × 0.0055 = 0.00049973

     p = 0.02235464

    VaR = 2,000,000 × 1.65 × 0.02235464 ×1.878 = $138,541

     There is a 5% probability that the investor would make a loss that exceeds $138,541 over

      the next day on her investment.





                                                                          14
```

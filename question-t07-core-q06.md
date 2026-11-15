# T07-CORE-Q06: CSL euro receivable put versus forward

Source: Tutorial 7, Q6. Source block: **Main questions**.

[Original PDF p4](tutorial-07-solutions.pdf#page=4) | [Original PDF p5](tutorial-07-solutions.pdf#page=5)

[Topic reference](topic-economic.md) | [Tutorial question index](questions-t07.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 4

```text
6.    It’s early March 2022 and the Commonwealth Serum Laboratories (CSL) has just

      started exporting COVID vaccines from its facilities in Melbourne to Europe. This

     has resulted in an accounts receivable of €5 million due in late June. Its treasury

     department which  is tasked with hedging the resultant exposure due to this

      transaction, gets the following information from Bloomberg. (*)

(Note: This is a question on Transaction Exposure. And if you read closely, you will notice a
similarity to the lecture example.)
   •   Spot rate: 158.34 cents per Euro (EUR).

   •  EUR 90-day interest rate: 0.40% p.a.

   •  AUD 90-day interest rate: 0.20% p.a.

   •   Forward rate (90 day): 158.05 cents per EUR.

             Exercise Price              Call Price           Put Price
                                     (cents/EUR)         (cents/EUR)
           158 cents/EUR               5.00                4.81
           159 cents/EUR               4.52                5.33
           160 cents/EUR               4.08                5.89





                                                                                          4
```

## PDF page 5

```text
(i)  What is the minimum net revenue the firm will receive if it uses options contracts?

Today: S(AUD/€) = AUD 158.34 cents/€

     Using strike price of the put option, X= 158 cents/€ (Closest to the current spot

      rate); premium for this option: 4.81 cents/€

     Premium paid today: €5,000,000×0.0481 = $240,500


In June 2022:

       If S(AUD/€) < $1.58/€, exercise the put option to sell €5,000,000 at the strike price of

     $1.58/€

   AUD received from selling euros: €5,000,000 × $1.58/€ = $7,900,000

       If S(AUD/€) > $1.58/€, sell €5,000,000 in the spot market.

     Revenue = €5,000,000 × 𝑆𝐽𝑢𝑛𝑒 2020 > $7,900,000


                                                                    0.2    90
    FV of Premium in June 2022 = $240,500×(1 +  ×   = $240,620.25                                                     100   360)

     The minimum net revenue is $7,900,000 – $240,620.25 = $7,659,379.75

      [Note, the actual cost of the June put option is 4.81 cents/€ × 1.0005= 4.812 cents/€]



(ii)  At what future exchange rate would the cashflow from using options exceed that

    from using forward contracts?

     Your answers to both parts should be detailed and include graphical aids if necessary.


                      𝑆∗−4.812 ¢/€ = 158.05 ¢/€

                     𝑆∗= 162.862405 ¢/€





                                                                                          5
```

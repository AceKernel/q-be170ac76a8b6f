# T01-CORE-Q05: EUR10m triangular arbitrage

Source: Tutorial 1, Q5. Source block: **Main questions**.

[Original PDF p5](tutorial-01-solutions.pdf#page=5)

[Topic reference](topic-fx.md) | [Tutorial question index](questions-t01.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 5

```text
5.  Triangular Arbitrage Question from Lecture Slide #22 (*)

    Find the arbitrage opportunity here if you start with €10,000,000:

     Citibank:            $1.7395/£  or £0.5749/$
     Barclays Bank:       €0.8408/$  or $1.1893/€


Cross-rate:
     Dresdner Bank:      €1.4381/£ or £0.6954/€

The first step is to check if the implied (or synthetic) quote is the SAME as the cross-rate that we
see on our Bloomberg screens.

               €    €    $Implied Cross Rate:   ⁄ = ⁄ × ⁄                   £     $    £

                   €0.8408    $1.7395     €1.4626      £0.6837                =       ⁄ ×       ⁄ =       ⁄  𝑜𝑟       ⁄                           $          £          £         €
For arbitrage (or riskless) profits to NOT be possible, the quoted cross-rate should be EQUAL to
the implied rate.
Here we notice that in the quoted cross-rate, the Euro buys more GBP (0.6954) than what the
two exchange rates say that it should buy (0.6837). Hence, your strategy should be one where
you are buying GBP with Euros.


STEP 1: Start with €10 million and buy GBP using the quoted exchange rate.

                           £0.6954        = €10,000,000 ×       ⁄ = £6,954,000                            €
STEP 2: Convert GBP into USD

                          $1.7395        = £6,954,000 ×       ⁄ = 𝑈𝑆𝐷12,096,483                                £
STEP 3: Last, we sell the USD for Euros

                             €0.8408        = 𝑈𝑆𝐷12,096,483 ×       ⁄ = €10,170,722                                     $
If you can make these transactions simultaneously, the profit you would have made is:

             = €10,170,722 − €10,000,000 = €170,722

The instantaneous return of such a transaction is
                      €10,170,722              =          ⁄        − 1 = 1.71%                                  €10,000,000





                                                                                             5
```

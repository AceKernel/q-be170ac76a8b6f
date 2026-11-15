# T04-CORE-Q06: Spot forward points and speculation exam case

Source: Tutorial 4, Q6. Source block: **Main questions**.

[Original PDF p5](tutorial-04-solutions.pdf#page=5) | [Original PDF p6](tutorial-04-solutions.pdf#page=6)

[Topic reference](topic-irp-ife.md) | [Tutorial question index](questions-t04.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 5

```text
6.  The following information on interest rates and exchange rates is available to all with

    access to any of the finance data providers:

  Currency        Spot       1 Month      3 Months     6 Months    12 Months
  Euro         2.0310/20      22/18          64/54       128/105      227/228
  GBP*        1.4890/00      55/22        160/156      302/289      560/523
  Yen          154.20/30        8/6           33/27        75/62       164/137

 *  The quote for the British Pound (GBP) is AUD per GBP. For the Euro and Yen it is
      foreign currency per AUD. For most currency pairs, a point is 1/100th of 1% (i.e.,
      0.0001); the Japanese Yen currency pair is the only exception to this rule. Swap points
      for Japanese Yen currency pairs (e.g., Yen per AUD) are quoted to two decimal places
      only, so one point is 1/100.
                                                      2021 exam question (*)

     The table below provides bid and ask interest rates on the Australian dollar (AUD), the
      Euro, the British Pound (GBP) and the Japanese Yen. These rates are quoted on a per
    annum basis.

     Currency     1 Month        3 Months       6 Months     12 Months
   AUD       5.6785-5.8125    5.5000-5.6250   5.5000-5.6250  5.6250-5.7500
     Euro       4.4375-4.5625    4.3125-4.4375   4.3125-4.4375  4.3125-4.4375
    GBP      10.0625-10.1875   9.8750-9.9375   9.6875-9.7500  9.6250-9.7500
    Yen        5.1250-5.1875    4.7500-4.8125   4.6250-4.6875  4.6250-4.6875


   COMMENTARY: Note that in financial markets, dealers will provide both bid and ask
      quotes and this applies to interest rates as well. The rate at which the bank/dealer will
     borrow from you (i.e., bid) is LESS than the rate at which they will lend to you (i.e., ask).

(a)  An investor who runs a family office expects the Japanese Yen to depreciate against the
      Australian dollar by 7% over the next three months. How can this investor try to profit
     from these expectations through (a) transactions in the spot market only (b) forward
     market transactions only? Assume that there are no regulatory restrictions whatsoever.

      Calculate the profit (or loss) on a $1 million position for each of the two cases. What
      other factors should this investor incorporate in his decision when he considers using spot
      versus forward markets to execute the transaction?


     The first part is SPECULATION – the investor is trading based on his opinion of what
      will happen in the future.

      1.   Borrow Yen 154,300,000 for 3 months at 4.8125%/4 = 1.2031% (0.012031)

      2.    Convert yen to dollars at 154.30. receive AUD 1m

      3.    Invest the dollars for 3 months at 5.5%/4 = 1.375%

         Have at the end of 3 months: AUD 1m × 1.01375 = 1,013,750

      4.   SPECULATING USING THE SPOT MARKET


                                                                                          5
```

## PDF page 6

```text
154.20
         Need to determine the expected future spot rate:    = 165.81
                                                         (1−0.07)
      5.   Repay YEN loan at the expected future spot rate.

       AUD needed to buy YEN = 154,300,000 × (1.012031) / 165.81 = 941,799.43

      6.   Expect the $ profit on the transaction to be (3) – (5)

         1,013,750 – 941,799.43 = 71,950.57


     Forward Transaction:

      1.    Sell yen forward and hope to buy in the spot market at a price lower than the
          forward sale price.

         The yen can be sold forward at 154.30 - 0.27 = 154.03 (i.e., selling 154m forward
             at 154.03).
      2.     If the yen depreciated by the predicted 7%, spot yen will be 165.81.

         The expected profit is $71,045 (154,030,000/154.03 – 154,030,000/165.81)


     The FACTORS the investors need to take into account include:

      (1)   Ability to close the deal at low transaction costs.

      (2)   Ability to borrow Yen and undertake the deal using forward markets for the
           maturity desired and for non-standard contract sizes.

      (3)  Borrowing could be affected by pre-payment penalties.
```

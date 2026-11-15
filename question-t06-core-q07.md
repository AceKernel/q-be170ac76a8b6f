# T06-CORE-Q07: GBP2m receivable bid-ask hedge exam case

Source: Tutorial 6, Q7. Source block: **Main questions**.

[Original PDF p9](tutorial-06-solutions.pdf#page=9) | [Original PDF p10](tutorial-06-solutions.pdf#page=10)

[Topic reference](topic-hedging.md) | [Tutorial question index](questions-t06.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 9

```text
7.  The following information on interest rates and exchange rates is available to all with
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

      [Recall Part (a) was covered in Topic 4]

(b)  Now suppose this investor expects a GBP 2 million payment in a month from client based
      in Glasgow. While he doesn’t have a strong opinion on how the exchange rate is likely to
     move, he is intent on eliminating the uncertainty around the value of the GBP. What
      options does he have and what are the costs of eliminating this risk? Which approach
     should he utilize? Provide your answer in dollar terms.


               𝑨𝑼𝑫𝟏. 𝟒𝟖𝟗𝟎−𝟏.     Spot Exchange rate:                  ⁄                        𝟒𝟗𝟎𝟎𝑮𝑩𝑷


     Here is the extract from Chapter 5, Eun & Resnick (i.e., the prescribed text) that
     explains how to arrive at the above quotation. Also, the way spot exchange rates have
     been presented here is no different to Question 5 in Tutorial 1.





                                                                           9
```

## PDF page 10

```text
MONEY MARKET HEDGE
     1.  Borrow the PV of £2,000,000 so that the receivable covers interest
                              2,000,000
        and principal:       = 𝐺𝐵𝑃1,983,164.
                             (1+(0.101875 ))
                                    12
     2.   This amount can be invested at 5.6875% for 30 days after converting
          into AUD (i.e., buying AUD at 1.4890).

            𝐺𝐵𝑃1,983,164 × 1.4890 × (1 + (0.056785 )) = $2,966,904.71
                                        12

     3.    If they are converted £2,000,000 at the current spot rate (i.e., today),
         they would have: 𝐺𝐵𝑃2,000,000 × 1.4890 = $2,978,000.00

     4.  The dollar cost is the difference between receiving £2,000,000 today
         versus receiving it in 30 days = ($11,095)


FORWARD HEDGE

    The outright forward rate is:

    BID: 1.4890 – 0.0055 = AUD 1.4835/GBP
    ASK: 1.4900 – 0.0022 = AUD 1.4878/GBP
    The dollar cost is: (1.4835 −1.4890) × 𝐺𝐵𝑃2,000,000 = −$11,000

      If IRP holds, the costs should be the same, which it is.





                                                                          10
```

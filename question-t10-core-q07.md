# T10-CORE-Q07: IC3 Japan FCF currency WACC valuation

Source: Tutorial 10, Q7. Source block: **Main questions**.

[Original PDF p7](tutorial-10-solutions.pdf#page=7) | [Original PDF p8](tutorial-10-solutions.pdf#page=8) | [Original PDF p9](tutorial-10-solutions.pdf#page=9)

[Topic reference](topic-budgeting.md) | [Tutorial question index](questions-t10.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 7

```text
7.   International Cuckoo Clock Corporation (IC3), a Switzerland based manufacturer
     of Cuckoo Clocks, is considering an expansion into Asia after its expansion into the
    US last summer was highly successful. Currently, IC3 does export clocks to Asia,
     but the increased Asian demand raises the question of an expansion in Asia. IC3 is
     trying to decide whether to establish a Cuckoo Clock manufacturing plant and office
     in Japan where the clocks would be built and then sold across Asia.

     The cost of the expansion is ¥80,000,000, which must be expended in the very, very near
      future. Moreover, IC3 would have to fund additional working capital of ¥5,000,000 at
      the time of the expansion. Further investment  in net working  capital would be
     ¥5,000,000, ¥8,000,000, and ¥10,000,000 in year 1, 2, and 3 respectively. If it builds the
      plant, IC3 will depreciate it at a rate of ¥5,000,000 per year (starting in year 1) and will
     have to fund additional capital expenditures of ¥8,000,000 per year to maintain and
     improve the plant. Although the project is assumed to have an infinite life, cash-flows
      are only projected up to three years and the terminal value of the project is computed
     based on the year 3 free cash-flow (FCF) assuming a growth rate that equals the
     Japanese long-run GDP growth rate.
     Other relevant data is given in the tables below. All taxes are paid in Japan in the year
      the income is earned. Tax treaties are in effect so that IC3 will have no tax obligations to
      the Swiss tax authorities.



                                     Japan               Switzerland
  Price inflation                    5%              4%
  Annual return on government bonds       9%              7%
  Corporate tax rate                   40%               30%
  Equity market risk premium CHF                               8.6%
  Spot rate—S(CHF/¥)                                0.01000
  Before tax cost of debt                                  10%
  Debt-to-value ratio (D/V)                                0.40
  Systematic risk (beta)                                      0.8
  Japanese long-run GDP growth rate               6%

Free Cash Flows for three years
                          Year 0        Year 1        Year 2        Year 3
 Net profit before Tax                       30.00         40.00         50.00
 Taxes                       0.00          -12.00         -16.00         -20.00
 Net profit after Tax           0.00          18.00         24.00         30.00
 Depreciation                 0.00           5.00           5.00           5.00
 CAPEX                     -80.00          -8.00           -8.00           -8.00
 NWC                        -5.00           -5.00           -8.00          -10.00
 FCF                        -85.00         10.00         13.00         17.00





                                                                          7
```

## PDF page 8

```text
(a)   Calculate the cost of capital, in Swiss francs (CHF), for the project.

Re   = Rf + ß × Market risk Premium
     = 7% + 0.8 × 8.6% = 13.88%


D/V × Rd × (1-T) + E/V × Re = 0.4×0.10× (1-0.3) + 0.6 × 13.88%
                      = 11.128%




(b)  Calculate the forward exchange rates, F1(CHF/¥) through F3(CHF/¥), for the years
      1,2, and 3 based on the spot rate and the interest rates given in the question.

F1   = Spot rate × (1+Swiss govt bond rate) / (1+Japan govt bond rate)
     = CHF0.01/¥ × (1.07)/(1.09) = 0.01 × 0.9817 = 0.009817 (CHF/¥)


F2   = 0.01 × (0.9817)2 = 0.009636 (CHF/¥)


F3   = 0.01 × (0.9817)3 = 0.009460 (CHF/¥)




(c)  Based on a perpetuity formula, the FCF in yen for year 3 and the Japanese growth
     rate assumption given in the question what is the terminal value as of year 3?
    Assume the yen WACC¥ is 12.7977%

   0      1      2      3         4            5            6    …
   -85     10     13     17      17×1.06      17×1.062      17×1.063   …

                                                                         (1 + g )
                         Terminal value = Et(FCF3) ×
                                                                         (r − g )
     Given: g = 6%

                                   (1.06)
                   17 ×           = ¥265.0897
                          (0.127977 −0.06)





                                                                          8
```

## PDF page 9

```text
(d)  Calculate the FCF for the years 0, 1, 2 and 3 and the terminal value in CHF using
     the forward rates calculated in (b).


                      Year 0         Year 1         Year 2         Year 3

       Forward rate F(CHF/¥)        0.009817       0.009636       0.009460

   FCF in Yen         -85.00           10.00          13.00          17.00

FCF in CHF: -0.85           0.098165         0.125273     0.160813 (mil)*
                    Spot rate: CHF0.01/¥)


  t     0     1        2        3        4        5        6    …
 JPY   -85   10       13       17       17×1.06  17×1.062  17×1.063 …
                                 265.0897
 F     0.01   0.009817  0.009636  0.009460
 CHF  -0.85  0.098165  0.125273  0.160813
                                  2.5077

= -0.85 + 0.098165/(1.11128) + 0.125273/(1.111282) + 0.160813/(1.111283) +
2.5076/(1.111283)

=1.284235


(e)  Should IC3 expand into the Asian market? Explain completely.

-0.85 + 0.098165/(1.11128) + 0.125273/(1.111282) + 0.160813/(1.111283) +
2.5076/(1.111283) = 1.284235 million CHF


EXPLANATION: Positive NPV Project – Yes they should expand





                                                                          9
```

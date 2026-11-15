# T04-CORE-Q01: USD GBP covered interest arbitrage

Source: Tutorial 4, Q1. Source block: **Main questions**.

[Original PDF p1](tutorial-04-solutions.pdf#page=1) | [Original PDF p2](tutorial-04-solutions.pdf#page=2)

[Topic reference](topic-irp-ife.md) | [Tutorial question index](questions-t04.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 1

```text
1.  Currently, the spot exchange rate is $1.50/£ and the three-month forward exchange

    rate is $1.52/£. The three-month interest rate is 8.0 percent per annum in the U.S.

   and 5.8 percent per annum in the U.K. Assume that you can borrow as much as $1.5

    million or £1 million.

(a)  Determine whether interest rate parity is currently holding.

        i$ = 2%, i£ = 1.45%, S = $1.5/£ and F = $1.52/£

     (1+ i$) = 1.02 (wealth from investing in the US)


     𝐹
     𝑆(1 + 𝑖£) = 1.0280 (wealth from investing in the UK)

     IRP does not hold.

      In this question, the pound is overvalued in the forward market.

     Note: Subtracting 1 from both sides of the IRP formula

                 𝐴𝐵⁄              𝐴𝐵⁄   𝐴𝐵⁄
                            𝐹𝑡,𝑡+1   1+𝑖𝐴            𝐹𝑡,𝑡+1 −𝑆𝑡      𝑖𝐴−𝑖𝐵
              =      gives us      =
                 𝐴𝐵⁄     1+𝑖𝐵         𝐴𝐵⁄        1+𝑖𝐵
                           𝑆𝑡                           𝑆𝑡

(b)   If IRP is not holding, how would you carry out covered interest arbitrage?
    Show all the steps and determine the arbitrage profit.

      (1) Borrow $1.5m – will have to repay $1.53m

      (2) Buy £1m using $1.5m at the prevailing spot rate



                                                                                          1
```

## PDF page 2

```text
(3) Invest £1m at the pound interest rate of 1.45% and the maturity value will be

         £1,014,500

      (4) Sell £1,014,500 forward for $1,542,040

      Arbitrage profit is $12,040


(c) Explain how IRP will be restored as a result of covered arbitrage activities.

     Following the arbitrage transactions described above:

     The $ interest rate will rise;

     The £ interest rate will fall;

     The spot exchange rate will rise;

     The forward rate will fall;

     The adjustments will continue until IRP holds.
```

# T06-CORE-Q08: Swedish Steel euro payable call versus forward

Source: Tutorial 6, Q8. Source block: **Main questions**.

[Original PDF p11](tutorial-06-solutions.pdf#page=11)

[Topic reference](topic-hedging.md) | [Tutorial question index](questions-t06.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 11

```text
8.   The Swedish Steel Company has debt of 100,000 Euros, which becomes due in 12
     months. The company’s financial controller, Freja Doe, is having trouble sleeping
      at night knowing that the debt is unhedged. Sweden’s currency is the Krona (Kr).
    The current Kr/Euro exchange rate is 20, and the per annum interest rates are 21
     percent on Krona and 10 percent on the Euro. Freja is considering a forward hedge.
     However, a friend tells her that he recently bought a call on 100,000 Euros with
      strike price of 20 and is willing to sell the call option to her at the historic cost of 1
    Kr per Euro or Kr 100,000 for the total contract. What should she do? Show your
     workings.

                                                      2023 exam question (*)



     The call premium asked by her friend is very tempting.
     The [fairly priced] forward rate for 12 months would be (using IRP):
       Ft,T = 20 x 1.21/1.10= Krona 22/Euro


     At expiration, Freja may exercise the call option and pay 20 Kr/Euro, which is less than

     22 Krona/Euro that she would pay based on the forward rate.



     Comparing Options versus Forward hedging -- in present value terms, this is worth:
      (22-20)/1.21 = 1.6529 Kr/Euro today > 1.0 Kr/Euro premium.


      Since, unlike the forward contract, Freja does not need to exercise if the future spot

     exchange rate is less than 20 Kr/Euro. Thus, the option is even more valuable than 1.6529

     Kr/Euro today (i.e., more flexibility)



     Recommendation: Freya Doe should buy the Euro call option from her friend.





                                                                          11
```

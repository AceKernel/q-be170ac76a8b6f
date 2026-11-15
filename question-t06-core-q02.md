# T06-CORE-Q02: The Row euro payable hedge comparison

Source: Tutorial 6, Q2. Source block: **Main questions**.

[Original PDF p2](tutorial-06-solutions.pdf#page=2) | [Original PDF p3](tutorial-06-solutions.pdf#page=3)

[Topic reference](topic-hedging.md) | [Tutorial question index](questions-t06.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 2

```text
2.   The Row owes €70 million in 30 days for a recent shipment of Spanish textiles. It

      faces the following interest and exchange rates:


   Spot rate:                                  Euros 130/$

   Forward rate (30 days)                      Euros 131/$

   30-day put option on dollars at €129/$    1% premium

   30-day call option on dollars at €131/$    3% premium

   U.S. dollar 30-day interest rate (annualized):   7.5%

   Euro 30-day interest rate (annualized):       15%


a.   What is the hedged cost of The Row's payable using a forward market hedge?

      In other words, what dollar cost of the payable can The Row lock in using the forward

      contract? By buying Euros forward, The Row can lock in a dollar cost of $534,351

      (70,000,000/131).


b.   What is the hedged cost of The Row's payable using a money market hedge?

     The Row can hedge its payable by borrowing the dollar equivalent of the present value

      of the €70 million payable, which equals €69,135,802 (70,000,000/1.0125), converting

      the dollars to Euros at the current spot rate, and investing the proceeds at the 1.25%

     monthly Euro interest rate (15%/12). The €69,135,802 amount translates into a dollar

     amount of $531,814  at the current spot  rate of €130/$ (€69,135,802/130). This

     investment is financed by borrowing these dollars at the monthly rate of 0.625%

      (7.5%/12). At the end of 30 days, The Row will pay off this dollar loan. The cost of

     doing so is $535,138 ($531,814 x 1.00625). The result from this money market hedge is

      the equivalent of buying forward the Ptas 70 million at a forward rate of €130.81

      (70,000,000/535,138). From the standpoint of the treasurer, this is a worse rate than

     could be realized directly in the forward market (as evidenced by the fact that the forward

     market hedge yields a cost that is $787 lower than the cost of the money market hedge).


c.   What is the hedged cost of The Row's payable using a put option?

    By buying a Euro put option, The Row can lock in a cost of $548,021 = the sum of the

    1% put premium of $5,385 (0.01 x 70,000,000/130) plus the $542,636 (70,000,000/129)

      cost of buying Euros through the put option at a rate of €129/$. (Notice that a put option

     on dollars with Euro receipt is exactly the same as a call option on Euros. Hence, the




                                                                           2
```

## PDF page 3

```text
terms can be used interchangeably as long as you bear in mind which currency is being

     bought and which is being sold).

     The PUT premium at t = T is $5,385 * (1+0.625%) = $5419.

     Although it looks as if the put option costs $13,704 more than the forward contract, these

      costs are not strictly comparable. The reason is that the put option gives The Row the

      option to buy Euros in the spot market in 30 days if the spot rate of the dollar at that time

     exceeds the exercise price of €129/$. Hence, the $548,055 (542,636 + 5,419) cost is the

    maximum cost of using a put option. On the other hand, with a forward contract, The

    Row must buy Euros at €131/$ even if the spot rate at time of settlement is lower at, say,

     €133/$. The value of this option accounts for the 1% premium that The Row must pay

      to acquire the put option.
```

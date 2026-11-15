# T01-CORE-Q06: Descending swap points to outright forward

Source: Tutorial 1, Q6. Source block: **Main questions**.

[Original PDF p6](tutorial-01-solutions.pdf#page=6)

[Topic reference](topic-fx.md) | [Tutorial question index](questions-t01.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 6

```text
6. Compute the implied forward rate if a dealer was quoting the USD against the AUD at

   0.7580/90 with 30-day forward margins of 40/30 points. (*)



To calculate the outright forward rate, the swap points are either added to or subtracted from the

spot rate. A point is 0.0001.

In this case, the bid swap point > ask swap point (i.e., the points are descending) indicating that

the forward rate is at a DISCOUNT and the points must be subtracted from the spot price to get

OUTRIGHT rate.

     Spot                 0.7580       0.7590

    Swap points          0.0040       0.0030

     Outright rate         0.7540       0.7560

The forward rate is trading at a discount (i.e., forward rate is < spot rate).



EXTRA EXPLANATION: Why does descending swap points imply subtraction?

Recall that a dealer’s (forward) quote must satisfy BID Price < ASK Price.

Suppose the market signals that the forward rate should be below the spot rate, then two things

must happen:

1.     Fbid < Sbid

2.    Fask < Sask

By subtracting, we ensure that bid/ask quotes are ordered correctly (i.e. bid < ask) with the larger

subtraction occurring on the bid side. The descending swap points quoting convention signals that

the outright forward rate must be below the spot.





                                                                                             6
```

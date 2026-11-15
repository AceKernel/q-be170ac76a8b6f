# T10-CORE-Q03: Spain perpetuity year-four expropriation threshold

Source: Tutorial 10, Q3. Source block: **Main questions**.

[Original PDF p1](tutorial-10-solutions.pdf#page=1) | [Original PDF p2](tutorial-10-solutions.pdf#page=2)

[Topic reference](topic-budgeting.md) | [Tutorial question index](questions-t10.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 1

```text
3.   Suppose a firm projects a $5 million perpetuity from an investment of $20 million

      in Spain. If the required return on this investment is 20% how large does the

     probability of expropriation in year 4 have to be before the investment has a

     negative NPV? Assume that all cash inflows occur at the end of each year and that

     the expropriation, if it occurs, will occur prior to the year 4 cash inflow or not at all.

     There is no compensation in the event of expropriation.


Let us look at this problem from by breaking the cash flow stream into two components – with

expropriation and without expropriation. The expected value of these streams is found by

multiplying the first component by the probability that expropriation will (or will not) take

place. All cash flows prior to year 4 are identical.



                                                                          1
```

## PDF page 2

```text
Year          0        1         2         3         4        5+

    CF with        -$20       $5        $5        $5        0         0
    expropriation
   CF without       -$20       $5        $5        $5        $5        $5
    expropriation


If the probability of expropriation in year 4 is p, then the expected cash flows are


      Year          0        1        2        3         4        5+

    CF with        -$20      $5       $5       $5      $5 (1-p)    $5 (1-p)
    expropriation


The NPV of these cash flows discounted at a 20% required return is
NPV  = - 20 + 5/1.2 + 5/(1.2)2 + 5/(1.2)3 + 5 * (1-p)/(1.2)4 + … + 5 * (1-p)/(1.2)t
     = -20 + 5/0.2 – (5p/0.2)/ (1.2)3

     = -20 + 25 – 14.468p

If this expression is set equal to 0, p = 34.6%. This means that the probability of expropriation

has to be 34.6% before the investment no longer has a positive NPV.

Note. The summation of the terms in the NPV equation uses the fact that the sum of an infinite
annuity (a perpetuity) is a/r, where a is the annuity and r is the discount rate. Recognize also
that the expected cash flow can be split into two annuities--one beginning in year 1 and equal
to 5 per annum and the other beginning in year 4 and equal to -5p per annum.
```

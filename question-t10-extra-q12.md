# T10-EXTRA-Q12: Terminal value timing and growth

Source: Tutorial 10, Q12. Source block: **Extra Questions**.

[Original PDF p12](tutorial-10-solutions.pdf#page=12) | [Original PDF p13](tutorial-10-solutions.pdf#page=13)

[Topic reference](topic-budgeting.md) | [Tutorial question index](questions-t10.md) | [All questions](QUESTIONS.md)

Automatic extract of the supplied question/official tutorial solution. Equations, tables and figure data can be misordered or omitted. **The linked original PDF is authoritative.**

## PDF page 12

```text
12. What is the terminal value of a project? How is it calculated?


The terminal value of a project is the present discounted value of all future free cash flows in

the years beyond an explicit forecasting horizon. If we generate explicit forecasts of free cash

flows for the next 10 years, the terminal value is the present discounted value of free cash flows

                                                                         12
```

## PDF page 13

```text
in years 11 to infinity. One typically assumes that future free cash flows will grow at the rate

g, and the discount rate for these perpetual cash flows is r. The starting value in year 11 is (1+

g) higher than the expected free cash flows in year 10. From the perpetuity formula for a

growing cash flow, we know that
                                 E t [FCF(t+10)] (1 + g )
                   Terminal value in year 10 =
                                                                       ( r - g )

After calculating the terminal value in year 10, that quantity must then be discounted to year 0
by multiplying by the appropriate discount factor, which is 1 / (1 + r)10:

                                          Terminal value in year 10
                  Terminal value in year 0 =                      10
                                                                    (1 + r )

The growth rate g should reflect the expected rate of inflation in the currency of the forecasts

because the project’s real capacity from its CAPX assumptions will be fully utilized, and new

real investments would have to be made for there to be additional real growth. These real

investments are typically not in the forecasts, so the only source of growth in nominal terms is

expected inflation.
```

# Course graph conventions

Use **TikZ** for diagrams; use LaTeX for labels and formulas. Follow the financial diagrams in [Lecture 5](lecture-05.pdf#page=14), PDF pp14-22, and [Lecture 6](lecture-06.pdf#page=15), PDF pp15,17,26,30: clean labelled axes, straight payoff segments, explicit strike/forward levels and only relevant curves. Avoid decorative plotting or misleading smooth curves.

| Requested graph | Vertical axis | Shape / check |
|---|---|---|
| Long call payoff | $\max(S_T-X,0)$ per foreign unit | Zero below strike, slope +1 above |
| Long put payoff | $\max(X-S_T,0)$ per foreign unit | Slope -1 below strike, zero above |
| Forward purchase/sale payoff | $S_T-F$ / $F-S_T$ | Straight line through $(F,0)$ |
| Option net profit | Payoff minus premium (carried if needed) | Shift payoff down; label break-even |
| Hedged receivable | Total net home-currency receipts | Unhedged $QS_T$; forward $QF$; put floor $QX-\mathrm{FV}(premium)$ |
| Hedged payable | Total home-currency cost | Call cap $QX+\mathrm{FV}(premium)$; unhedged $QS_T$ |
| Currency supply/demand | Explicit quote units | Label priced currency; original and shifted curves/equilibria |
| Diversification/efficient frontier | Expected common-currency return vs standard deviation | Distinguish efficient upper branch; correlations/data determine numerical shape |

Always identify the quote currency and scale, notional versus per-unit values, payoff versus profit, and the common valuation date. The strike $X$ is the kink, not necessarily the net-profit break-even. Do not invent numerical efficient-frontier points without a covariance matrix.

## Minimal TikZ template: receivable, schematic values only

The example uses $Q=1$, $X=1$, $F=1.1$ and maturity-value put premium $0.04$. Replace these **schematic** constants with the question's data before using it for a case.

```latex
\begin{tikzpicture}[x=3cm,y=2cm,>=stealth]
  \draw[->] (0,0)--(2.2,0) node[right] {$S_T^{D/F}$};
  \draw[->] (0,0)--(0,2.35) node[above] {Net receipts in $D$};
  \draw (0,0)--(2.05,2.05) node[above] {Unhedged};
  \draw[dashed] (0,1.1)--(2.05,1.1) node[right] {Forward: $QF$};
  \draw[thick] (0,0.96)--(1,0.96)--(2.05,2.01);
  \node[anchor=east] at (0,0.84) {$QX-\mathrm{FV}(premium)$};
  \node[above left] at (1.9,1.86) {Put hedge};
  \draw[dotted] (1,0)--(1,0.96);
  \node[below] at (1,0) {$X$};
\end{tikzpicture}
```

[Main index](INDEX.md) | [Options/futures](topic-derivatives.md) | [Hedge comparison](topic-hedging.md)

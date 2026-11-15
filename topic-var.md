# Foreign-currency return volatility and value at risk

Keywords: VaR 95% 1.65 football club market volatility exchange rate correlation normal distribution GBP zero mean.

[Main index](INDEX.md) | [Question bank](QUESTIONS.md) | [Exam reuse map](PATTERNS.md)

Checked supplementary reference, not an official marking scheme. Original course sources and current official corrections take precedence.


For a return in common home-currency units, the course uses the first-order volatility approximation

$$\sigma_D^2\approx\sigma_F^2+\sigma_{FX}^2+2\rho_{F,FX}\sigma_F\sigma_{FX}.$$

Use standard deviations and correlations for the **same horizon** and a quote measuring the foreign currency's return in home currency. This is not an exact variance identity for arbitrary products of simple returns.

For current home value $V$, normal returns and lower-tail probability $\alpha$:

$$\mathrm{VaR}_{1-\alpha}=V\bigl(z_{1-\alpha}\sigma_D-\mu_D\bigr).$$

Tutorial 6 Q11 neglects the tiny supplied mean, giving the course approximation $\mathrm{VaR}_{95\%}\approx1.65V\sigma_D$. State this zero-mean approximation rather than silently discarding a material mean. Use the critical value supplied in the question. Under the normal model, loss exceeds this threshold with probability 5%; VaR is **not the largest possible loss**.

**Worked route:** [T06-CORE-Q11](question-t06-core-q11.md); the sample/2024 VaR question is the same question family. For portfolio covariance that is not supplied, do not manufacture a correlation: [T08-CORE-Q09](question-t08-core-q09.md).

**Sources:** [L06 PDF p6](page-l06-006.md), [L06 PDF p7](page-l06-007.md), [L06 PDF p8](page-l06-008.md), [L08 PDF p29](page-l08-029.md). Extracted source arithmetic is not authoritative; recompute from the stated inputs.

# KrugerWales: foreign project and salvage expropriation

**Source question:** [S2 2025 PDF pp4-6](exam-s2-2025.pdf#page=4), Question II. **Checked supplementary derivation, not an official exam key.** Related tutorial methods are [T10 Q3](question-t10-core-q03.md) and [T10 Q7](question-t10-core-q07.md); these are analogues, not identical cases.

GBPZAR20 means ZAR20/GBP. Under PPP,

$$S_t^{ZAR/GBP}=20\left(\frac{1.05}{1.02}\right)^t,
\quad S_1=20.5882353,\ S_2=21.1937716,\ S_3=21.8171179.$$

Convert each ZAR cash flow by **dividing** by that year's quote; discount GBP cash flows at 9%:

$$NPV_{no}=-\frac{2{,}000{,}000}{20}
+\frac{800{,}000/S_1}{1.09}
+\frac{800{,}000/S_2}{1.09^2}
+\frac{1{,}800{,}000/S_3}{1.09^3}
=\mathrm{GBP}\,31{,}127.84.$$

The threatened cash flow is the ZAR1m **salvage only**. Year-3 operating cash flow ZAR0.8m remains:

$$L=\frac{1{,}000{,}000/S_3}{1.09^3}=\mathrm{GBP}\,35{,}393.47,
\qquad NPV_{ex}=NPV_{no}-L=-\mathrm{GBP}\,4{,}265.63.$$

$$\mathbb E[NPV]=NPV_{no}-pL,\qquad
p^*=\frac{31{,}127.841938}{35{,}393.468805}=0.87947983=87.9480\%.$$

Accept for $0\le p<p^*$, reject for $p^*<p\le1$, and be indifferent at $p=p^*$. The project has positive NPV without expropriation but negative NPV if salvage is certainly lost.

Cross-check: $k_{ZAR}=1.09(1.05/1.02)-1=12.2058824\%$. Discount all ZAR cash flows at this rate and divide their NPV by 20; this gives the same GBP result under the course's consistency assumptions.

[Capital-budgeting reference](topic-budgeting.md) | [Political-risk reference](topic-political.md)

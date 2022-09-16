# VaR-CVaR-SGLD

The paper "A fully data-driven approach to minimizing CVaR for portfolio of assets via SGLD with discontinuous updating" is from [1].

This is a class project for simulating VaR &amp; CVaR by using data driven SGLD method given in above paper.

The code given in this repo is asked for two main tasks:

First, implement the VaR-CVaR algorithm from Section 5.2. of the article with the same assumptions and parameter setting (single asset case) as per Table 1 & 2 of the
aforementioned article. And reproduce Table 1 & 2 (approximately).

Second, implement the VaR-CVaR algorithm for the case of three assets, i.e. for a portfolio which consists of three risky assets, as described in subsection 5.2.2., which is entitled "Minimizing CVaR of portfolios of assets" of the article by examining the following 5 different cases:
| Asset 1 | Asset 2 | Asset 3 |
|   ----  |   ----  |   ----  |
| $N(500,1)$| $N(0,10^{6})$ | $N(0,10^{-4})$ |
| $N(500,1)$  |  $N(0,10^{6})$  |  $N(0,1)$  |
| $N(0,10^3)$ | $N(0,1)$  | $N(0,4)$  |
| $N(0,1)$  | $N(1,4)$  |  $N(0,10^{-4})$ |
|  $N(0,1)$  | $N(1,4)$  |  $N(2,1)$  |


at a confidence level 95% following the style of presentation of Table 3 of the aforementioned article.


[1]:Sabanis S, Zhang Y. A fully data-driven approach to minimizing CVaR for portfolio of assets via SGLD with discontinuous updating[J]. arXiv preprint arXiv:2007.01672, 2020.

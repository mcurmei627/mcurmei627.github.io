---
title: "Monotonically Constrained Polynomial Regression: An Application of Sum of Squares Techniques and Semidefinite Programming"
collection: research
permalink: /research/thesis
excerpt:  '<i>Operations Research and Financial Engineering Senior Thesis, Winner of Procter & Gamble Prize for Outstanding Senior Thesis</i>'
date: 2017-06-01
venue: 'Princeton University Senior Thesis'
paperurl: 'http://arks.princeton.edu/ark:/88435/dsp01s4655k21r'
citation: ''
---
At Princeton I was fortunate to work with [Prof. Amir Ali Ahmadi](http://aaa.princeton.edu/) and [Prof. Georgina Hall](https://sites.google.com/view/georgina-hall). We were interested in developing a technique for incorporating strict monotonicity guarantees for polynomial regression on compact sets. Monotonicity is a common characteristic in practice, for example, it can be a way to incorporate prior knowledge, encode fairness criteria, and ensure robustness and generalization. We used constrained polynomial optimization to formulate the problem of learning feature-monotone functions. To provide theoretical validation, we proved a Weierstrass-like Polynomial Approximation theorem restricted to monotone multivariate functions. We showed that learning monotonically constrained polynomial functions is NP-hard. To address this complexity of we proposed a relaxation to a constrained Sum of Squares optimization problem, which we subsequently solved via Semidefinite Programming.

![](../../images/thesis.png)

Currently we are extending the framework to incorporate more complex shape constraints of the regressand. In practice, one of such
key constraints is convexity with respect to a set of variables. Currently we have a manuscript under review at Operations Research Journal which describes a general approach for “Shape Constrained Regression using Sum of Squares Polynomials”. See unpublished work [here](https://arxiv.org/abs/2004.03853).


[`thesis`](http://arks.princeton.edu/ark:/88435/dsp01s4655k21r)
[`MSJAR`](https://drive.google.com/file/d/1DQeItRRpwbtKIGad29YjfwU_uoDjuzWC/view)
[`arXiv`](https://arxiv.org/pdf/1806.06996.pdf)
[`code`](https://github.com/mcurmei627/dantzig)

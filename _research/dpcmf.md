---
title: "Private Matrix Factorization with Public Item Features"
collection: research
permalink: /research/dpcmf
date: 2022-09-14
venue: 'PProceedings of the 17th ACM Conference on Recommender Systems'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3604915.3608833'
citation: '<b>Mihaela Curmei</b>, Walid Krichene, Li Zhang, Mukund Sundararajan'
---
We consider the problem of training private recommendation models with access to public item features. Training with Differential Privacy (DP) offers strong privacy guarantees, at the expense of loss in recommendation quality. We show that incorporating public item features during training can help mitigate this loss in quality. We propose a general approach based on collective matrix factorization (CMF), that works by simultaneously factorizing two matrices: the user feedback matrix (representing sensitive data) and an item feature matrix that encodes publicly available (non-sensitive) item information.

The method is conceptually simple, easy to tune, and highly scalable. It can be applied to different types of public item data, including: (1) categorical item features; (2) item-item similarities learned from public sources; and (3) publicly available user feedback. Furthermore, these data modalities can be collectively utilized to fully leverage public data.

Evaluating our method on a standard DP recommendation benchmark, we find that using public item features significantly narrows the quality gap between private models and their non-private counterparts. As privacy constraints become more stringent, models rely more heavily on public side features for recommendation. This results in a smooth transition from collaborative filtering to item-based contextual recommendations

![](../../images/RecSys23.jpg)


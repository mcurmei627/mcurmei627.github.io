---
title: 'Quantifying Availability and Discovery in Recommender Systems
via Stochastic Reachability'
collection: research
permalink: /research/quantifying_reachability
excerpt: ''
date: 2021-06-30
venue: 'International Conference on Machine Learning; ICML'
paperurl: 'https://arxiv.org/pdf/2107.00833.pdf'
citation: 'Sarah Dean*, <b>Mihaela Curmei*</b>, Benjamin Recht'
---

In this work, we consider how preference models in interactive recommendation systems
determine the availability of content and users’ opportunities for discovery. We propose an
evaluation procedure based on stochastic reachability to quantify the maximum probability of
recommending a target piece of content to an user for a set of allowable strategic modifications.

Stochastic reachability can be used to detect
biases in the availability of content and diagnose limitations in the opportunities for discovery
granted to users.

We show that this metric can be computed efficiently as a convex program for
a variety of practical settings, and further argue that reachability is not inherently at odds with
accuracy.

We demonstrate evaluations of recommendation algorithms trained on large datasets
of explicit and implicit ratings. Our results illustrate how preference models, selection rules, and
user interventions impact reachability and how these effects can be distributed unevenly.

![Framework](../../images/Framework.gif)

See our [GitHub repository](https://github.com/modestyachts/stochastic-rec-reachability) for detailed experiments.

*Mihaela Curmei and Sarah Dean contributed equally to this work.*
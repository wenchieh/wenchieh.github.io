---
title: "SpecGreedy: Unified Dense Subgraph Detection"
collection: publications
permalink: /publication/SPECGREEDY
date: 2020-09-14
venue: 'European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases. (ECML-PKDD) 2020'
citation: 'Feng, W., Liu, S., Danai, K., Shen, H., & Cheng, X. (2020). &quot; SpecGreedy: Unified Dense Subgraph Detection &quot;.<i>In European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases. </i>'
---

## Abstract
How can we effectively detect fake reviews or fraudulent connections on a website?
How can we spot communities that suddenly appear based on users’ interaction?
And how can we efficiently find the minimum cut in a big graph?
All of these are related to the problem of finding dense subgraphs,
an important primitive problem in graph data analysis with
extensive applications across various domains.

We focus on formulating the problem of detecting the densest subgraph in real-world large graphs,
and we theoretically compare and contrast several closely related problems.
Moreover, we propose a unified framework for the densest subgraph detection (**GenDS**) and
devise a simple and computationally efficient algorithm, **SpecGreedy**,
to solve it by leveraging the graph spectral properties with a greedy approach.
We conduct thorough experiments on 40 real-world networks with up to 1.47 billion edges from various domains,
and demonstrate that our algorithm yields up to 58.6 × speedup and achieves better or approximately
equal-quality solutions for the densest subgraph detection compared to the baselines.
Moreover, SpecGreedy scales linearly with the graph size and is proved effective in applications,
such as finding collaborations that appear suddenly in a big, time-evolving co-authorship network.


---
---

[**ECML-PKDD 2020**](https://ecmlpkdd2020.net/)
[
[paper](http://wenchieh.github.io/files/pdf/specgreedy.pdf) |
[appendix](http://wenchieh.github.io/files/pdf/specgreedy_supple.pdf) |
[code](https://github.com/wenchieh/specgreedy) |
[slide](http://wenchieh.github.io/files/slide/specgreedyECMLPKDD2020.pptx) |
bib
]

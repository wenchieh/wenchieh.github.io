---
title: "EigenPulse: Detecting Surges in Large Streaming Graphs with Row Augmentation"
collection: publications
permalink: /publication/EIGENPULSE
date: 2019-04-17
venue: 'In Pacific-Asia Conference on Knowledge Discovery and Data Mining. (PAKDD) 2019'
paperurl: 'http://wenchieh.github.io/files/pdf/eigenpulse.pdf'
citation: 'Zhang, J., Liu, S., Yu, W., Feng, W., & Cheng, X. (2019). &quot;EigenPulse: Detecting Surges in Large Streaming Graphs with Row Augmentation&quot;. <i>In Pacific-Asia Conference on Knowledge Discovery and Data Mining. Springer, Cham.</i> (pp. 501-513).'
---

## Abstract
How can we spot dense blocks in a large streaming graph efficiently? Anomalies such as fraudulent attacks,
spamming, and DDoS attacks, can create dense blocks in a short time window, emerging a surge of density
in a streaming graph. However, most existing methods detect dense blocks in a static graph or
a snapshot of dynamic graphs, which need to inefficiently rerun the algorithms for a streaming graph.
Moreover, some works on streaming graphs are either consuming much time on updating algorithm for
every incoming edge, or spotting the whole snapshot of a graph instead of the attacking sub-block.

Therefore, we propose a row-augmented matrix with sliding window to model a streaming graph,
and design the AugSVD algorithm for computation- and memory-efficient singular decomposition.
**EigenPulse** is then proposed to spot the density surges in streaming graphs based
on the singular spectrum. We theoretically analyze the robustness of our method.
Experiments on real datasets with injections show our performance and
efficiency compared with the state-of-the-art baseline.

---
---

[**PAKDD 2019**](http://pakdd2019.medmeeting.org)
[
[paper](http://wenchieh.github.io/files/pdf/eigenpulse.pdf) |
code |
[slide](http://wenchieh.github.io/files/slide/eaglepulse.pptx) |
[bib](https://dblp.uni-trier.de/rec/bibtex/conf/pakdd/ZhangLYFC19)
]

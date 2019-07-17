---
title: "Beyond outliers and on to micro-clusters: Vision-guided Anomaly Detection"
collection: publications
permalink: /publication/EAGLEMINE
date: 2019-04-15
venue: 'In Pacific-Asia Conference on Knowledge Discovery and Data Mining. (PAKDD) 2019'
citation: 'Feng, W., Liu, S., Faloutsos, C., Hooi, B., Shen, H., & Cheng, X. (2019). &quot;Beyond outliers and on to micro-clusters: Vision-guided Anomaly Detection&quot;. <i>In Pacific-Asia Conference on Knowledge Discovery and Data Mining. Springer, Cham.</i> (pp. 541-554).'
---

## Abstract
Given a heatmap for millions of points, what patterns exist in the distributions of point
characteristics, and how can we detect them and separate anomalies in a way similar to human vision?
In this paper, we propose a vision guided algorithm, **EagleMine**, to recognize and summarize
point groups in the feature spaces. EagleMine utilizes a water-level tree to capture group structures
according to vision-based intuition at multiple resolutions, and adopts statistical
hypothesis tests to determine the optimal groups along the tree. Moreover,
EagleMine can identify anomalous micro-clusters (i.e., micro-size groups),
which exhibit very similar behavior but deviate away from the majority.
Extensive experiments are conducted for large graph scenario, and show that our method can
recognize intuitive node groups as human vision does, and achieves the best performance
in summarization compared to baselines. In terms of anomaly detection,
EagleMine also outperforms state-of-the-art graph-based methods by significantly
improving accuracy in synthetic and microblog datasets.

---
---

[**PAKDD 2019**](http://pakdd2019.medmeeting.org)
[
[paper](http://wenchieh.github.io/files/pdf/eaglemine.pdf) |
[appendix](http://wenchieh.github.io/files/pdf/eaglemine_supple.pdf) |
[code](https://github.com/wenchieh/eaglemine) |
[slide](http://wenchieh.github.io/files/slide/eaglemine.pptx) |
[bib](https://dblp.uni-trier.de/rec/bibtex/conf/pakdd/FengLFHSC19)
]

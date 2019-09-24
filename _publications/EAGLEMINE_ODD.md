---
title: "EagleMine: Vision-Guided Mining in Large Graphs"
collection: publications
permalink: /publication/EAGLEMINE_ODD
date: 2018-08-20
venue: 'KDD Outlier Detection De-constructed (ODD v5.0) Workshop 2018.'
citation: 'Feng, W., Liu, S., Faloutsos, C., Hooi, B., Shen, H., & Cheng, X. (2019). &quot;EagleMine: Vision-Guided Mining in Large Graphs&quot;. <i>KDD Outlier Detection De-constructed (ODD v5.0) Workshop 2018.</i>'
---

## Abstract
Given a graph with millions of nodes, what patterns exist in the distributions of node characteristics,
and how can we detect them and separate anomalous nodes in a way similar to human vision?

In this paper, we propose a vision-guided algorithm, **EagleMine**, to recognize and summarize
graph node groups in feature spaces. EagleMine hierarchically discovers node groups,
and each group is an internally connected dense area in some feature space.
EagleMine utilizes a water-level tree to capture group structures according
to vision-based intuition at multiple resolutions. EagleMine traverses the water-level tree,
applying statistical hypothesis test to determine the optimal node groups that should
be fitted along the path. Moreover, EagleMine can identify anomalous micro-clusters
(i.e., micro-size groups), who exhibit very similar behavior in some feature space,
and deviate away from the majority. Experiments on real-world data show that our method can
recognize intuitive groups as human vision does, and achieve the best performance
in summarization compared to baselines. In terms of anomaly detection,
EagleMine also outperforms well-known state-of-the-art graph-based methods by
significantly improving accuracy in a microblog dataset.

---
---

[**KDD ODD v5.0 2018**](https://www.andrew.cmu.edu/user/lakoglu/odd/)
[
[paper](http://wenchieh.github.io/files/pdf/eaglemine_ODDv5.pdf) |
[appendix](http://wenchieh.github.io/files/pdf/eaglemine_supple_ODDv5.pdf) |
[poster](http://wenchieh.github.io/files/pdf/eaglemine_poster.pdf) |
[code](https://github.com/wenchieh/eaglemine) |
[slide](http://wenchieh.github.io/files/slide/eaglemineSIGKDDODDv5.pdf)
]

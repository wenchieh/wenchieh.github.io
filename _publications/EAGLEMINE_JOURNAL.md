---
title: "EagleMine: Vision-guided Micro-clusters recognition and collective anomaly detection"
collection: publications
permalink: /publication/EAGLEMINE_JOURNAL
date: 2020-08-13
venue: 'Future Generation Computer Systems'
citation: 'Feng, W., Liu, S., Faloutsos, C., Hooi, B., Shen, H., & Cheng, X.
&quot; EagleMine: Vision-guided Micro-clusters recognition and collective anomaly detection.&quot;. <i>Future Generation Computer Systems</i> 115: 236-250.'
---

## Abstract
Given a graph with millions of nodes, what patterns exist in the distributions of node characteristics?
How can we detect them and separate anomalous nodes in a way similar to human visual perception?
More generally, how can we identify micro-clusters in a histogram and spot some interesting patterns?
In this paper, we propose a vision-guided algorithm, EagleMine, to recognize and
summarize node groups in a histogram constructed from some correlated features.
EagleMine hierarchically discovers node groups, which form internally connected dense areas in the histogram,
by utilizing a water-level tree with multiple resolutions according to the rule of the visual recognition.
EagleMine uses the statistical hypothesis test to determine the optimal groups while exploring the tree and
simultaneously performs vocabulary-based summarization.
Moreover, EagleMine can identify anomalous micro-clusters, consisting of nodes that exhibit very similar and
suspicious behavior, deviate away from the majority.
Experiments on the real-world datasets show that our method can recognize intuitive node groups as human vision does;
it achieves the best summarization performance compared to baselines. In terms of anomaly detection,
EagleMine also outperforms the state-of-the-art graph-based methods with significantly
improving accuracy in a micro-blog dataset. Moreover, EagleMine can be used for other applications,
e.g., to detect the synchronized patterns in the temporal retweet event.

---
---

[
[paper (J)](http://wenchieh.github.io/files/pdf/eaglemine_journal.pdf) |
[code](https://github.com/wenchieh/eaglemine) |
[bib](http://wenchieh.github.io/files/bib/EAGLEMINE)
]

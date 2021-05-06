---
title: "CatchCore: Catching Hierarchical Dense Subtensor"
collection: publications
permalink: /publication/CATCHCORE
date: 2019-09-16
venue: 'European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases. (ECML-PKDD) 2019'
citation: 'Feng, W., Liu, S., Shen, H., & Cheng, X. (2019). &quot;CatchCore: Catching Hierarchical Dense Subtensor&quot;.<i>In European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases. </i>'
---

## Abstract
Dense subtensor detection gains remarkable success in spotting anomaly and fraudulent
behaviors for the multi-aspect data (i.e., tensors), like in social media and event streams.
Existing methods detect the densest subtensors flatly and separately, with an underlying assumption
that those subtensors are exclusive. However, many real-world tensors usually present hierarchical properties,
e.g., the core-periphery structure or dynamic communities in networks. In this paper,
we propose, **CatchCore**, a novel framework to  effectively and the hierarchical dense subtensors.
We first design a unified metric for dense subtensor detection, which can be optimized with
gradient-based methods. With the proposed metric, CatchCore detects hierarchical dense subtensors
through the hierarchy-wise alternative optimization. Finally, we utilize the minimum description
length principle to measure the quality of detection result and select the optimal hierarchical dense subtensors.
Extensive experiments on synthetic and real-world datasets demonstrate that CatchCore
outperforms the top competitors in accuracy for detecting dense subtensors and anomaly patterns.
Additionally, CatchCore successfully  identified a hierarchical researcher co-authorship group with
intense interactions in DBLP dataset. Meanwhile, CatchCore also scales linearly with all aspects of tensors.

---
---

[**ECML-PKDD 2019**](http://ecmlpkdd2019.org)
[
[paper](http://wenchieh.github.io/files/pdf/catchcore.pdf) |
[appendix](http://wenchieh.github.io/files/pdf/catchcore_supple.pdf) |
[poster](http://wenchieh.github.io/files/pdf/catchcore_poster.pdf) |
[code](https://github.com/wenchieh/catchcore) |
[slide](http://wenchieh.github.io/files/slide/catchcoreECMLPKDD2019.pptx) |
[bib](https://dblp.uni-trier.de/rec/bibtex/conf/pkdd/FengLC19)
]

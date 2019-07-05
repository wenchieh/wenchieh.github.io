---
title: "Visual Domain Adaptation with Manifold Embedded Distribution Alignment"
collection: publications
permalink: /publication/MEDA
date: 2018-10-05
venue: 'ACM International Conference on Multimedia (ACM MM) 2018'
paperurl: 'http://wenchieh.github.io/files/pdf/meda.pdf'
citation: 'Wang, J., Feng, W., Chen, Y., Yu, H., Huang, M., & Yu, P. S. (2018). &quot;Visual domain adaptation with manifold embedded distribution alignment&quot;. <i>In 2018 ACM Multimedia Conference on Multimedia Conference. ACM.</i> (pp. 402-410).'
---

## Abstract
Visual domain adaptation aims to learn robust classifiers for the target domain by
leveraging knowledge from a source domain. Existing methods either attempt to align the
cross-domain distributions, or perform manifold subspace learning. However,
there are two significant challenges:
(1) degenerated feature transformation, which means that distribution alignment is
often performed in the original feature space, where feature distortions are hard to overcome.
On the other hand, subspace learning is not sufficient to reduce the distribution divergence.
(2) unevaluated distribution alignment, which means that existing distribution alignment
methods only align the marginal and conditional distributions with equal importance,
while they fail to evaluate the different importance of these two distributions in
real applications.
In this paper, we propose a **Manifold Embedded Distribution Alignment (MEDA)** approach to
address these challenges. MEDA learns a domain-invariant classifier in Grassmann manifold
with structural risk minimization, while performing dynamic distribution alignment to
quantitatively account for the relative importance of marginal and conditional distributions.
To the best of our knowledge, MEDA is the first attempt to perform dynamic distribution
alignment for manifold domain adaptation. Extensive experiments demonstrate that MEDA shows
significant improvements in classification accuracy compared to state-of-the-art traditional
and deep methods.

---
---

[**ACM MM 2018**](http://www.acmmm.org/2018/)
[
[paper](http://wenchieh.github.io/files/pdf/meda.pdf) |
[appendix](http://wenchieh.github.io/files/pdf/meda_supple.pdf) |
[poster](http://wenchieh.github.io/files/pdf/meda_poster.pdf) |
[code](https://github.com/wenchieh/MEDA) |
[bib](https://dblp.uni-trier.de/rec/bibtex/conf/mm/WangFCYHY18)
]

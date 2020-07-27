---
title: "Scalable demand-aware recommendation"
collection: publications
permalink: /publication/scalable-demand-aware-recommendation
excerpt: ''
date: 2017
venue: ''
paperurl: 'https://papers.nips.cc/paper/6835-scalable-demand-aware-recommendation.pdf'
citation: 'J Yi, CJ Hsieh, KR Varshney, L Zhang, Y Li - Advances in Neural Information Processing Systems, 2017.'
---
Recommendation for e-commerce with a mix of durable and nondurable goods has characteristics that distinguish it from the well-studied media recommendation problem. The demand for items is a combined effect of form utility and time utility, ie, a product must both be intrinsically appealing to a consumer and the time must be right for purchase. In particular for durable goods, time utility is a function of inter-purchase duration within product category because consumers are unlikely to purchase two items in the same category in close temporal succession. Moreover, purchase data, in contrast to rating data, is implicit with non-purchases not necessarily indicating dislike. Together, these issues give rise to the positive-unlabeled demand-aware recommendation problem that we pose via joint low-rank tensor completion and product category inter-purchase duration vector estimation. We further relax this problem and propose a highly scalable alternating minimization approach with which we can solve problems with millions of users and millions of items in a single thread. We also show superior prediction accuracies on multiple real-world datasets.

[Download paper here](https://papers.nips.cc/paper/6835-scalable-demand-aware-recommendation.pdf)

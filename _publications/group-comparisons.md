---
title: "Learning from Group Comparisons: Exploiting Higher Order Interactions"
collection: publications
permalink: /publication/group-comparisons
date: 2018-12-01
venue: 'NeurIPS'
---
We study the problem of learning from group comparisons, with applications in predicting outcomes of sports and online games. Most of the previous works in this area focus on learning individual effects---they assume each player has an underlying score, and the''ability''of the team is modeled by the sum of team members' scores. Therefore, all the current approaches cannot model deeper interaction between team members: some players perform much better if they play together, and some players perform poorly together. In this paper, we propose a new model that takes the player-interaction effects into consideration. However, under certain circumstances, the total number of individuals can be very large, and number of player interactions grows quadratically, which makes learning intractable. In this case, we propose a latent factor model, and show that the sample complexity of our model is bounded under mild assumptions. Finally, we show that our proposed models have much better prediction power on several E-sports datasets, and furthermore can be used to reveal interesting patterns that cannot be discovered by previous methods.

[Download paper here](https://papers.nips.cc/paper/7746-learning-from-group-comparisons-exploiting-higher-order-interactions.pdf)

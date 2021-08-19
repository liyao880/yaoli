---
title: "Detecting Adversarial Examples with Bayesian Neural Network"
collection: publications
permalink: /publication/bayesian_detection
date: 2021-05-18
venue: 'arXiv'
---
In this paper, we propose a new framework to detect adversarial examples motivated by the observations that random components can improve the smoothness of predictors and make it easier to simulate output distribution of deep neural network. With these observations, we propose a novel Bayesian adversarial example detector, short for BATer, to improve the performance of adversarial example detection. In specific, we study the distributional difference of hidden layer output between natural and adversarial examples, and propose to use the randomness of Bayesian neural network (BNN) to simulate hidden layer output distribution and leverage the distribution dispersion to detect adversarial examples. The advantage of BNN is that the output is stochastic while neural networks without random components do not have such characteristics. Empirical results on several benchmark datasets against popular attacks show that the proposed BATer outperforms the state-of-the-art detectors in adversarial example detection.

[Download paper here](https://arxiv.org/pdf/2105.08620.pdf)

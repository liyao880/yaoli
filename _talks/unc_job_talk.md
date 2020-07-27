---
title: " On the Robustness of Machine Learning Systems"
collection: talks
type: "Job talk"
permalink: /talks/unc_job_talk
venue: "UNC Chapel Hill"
date: 2020-01-10
location: "Chapel Hill, NC"
---

Deep neural networks (DNNs) are one of the most prominent technologies of our time, as they achieve state-of-the-art performance in many machine learning tasks, including but not limited to image classification, text mining, and speech processing. However, recent studies have demonstrated the vulnerability of deep neural networks against adversarial examples, i.e., examples that are carefully crafted to fool a well-trained deep neural network while being indistinguishable from the natural images to humans. This makes it unsafe to apply neural networks in security-critical applications.
We present two algorithms, Adversarial Bayesian Neural Network (Adv-BNN) and Embedding Regularized Classifier (ER-Classifier), to train robust neural networks against adversarial examples. Motivated by the ideas that randomness and adversarial training can improve the robustness of neural networks, we formulate the min-max problem in Bayesian Neural Network to learn the best model distribution under adversarial attacks, leading to an adversarial-trained Bayesian neural network. Another algorithm, ER-Classifier, is inspired by the observation that the intrinsic dimension of image data is much smaller than its pixel space dimension and the vulnerability of neural networks grows with the input dimension. We propose to embed high-dimensional input images to a low-dimensional space to perform classification and regularize the embedding space in training process. Experimental results on several benchmark datasets show that our proposed frameworks achieve state-of-the-art performances against strong adversarial attack methods.

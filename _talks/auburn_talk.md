---
title: "ER-Classifier and BATer"
collection: talks
type: "Presentation"
permalink: /talks/auburn_talk
venue: "Auburn University"
date: 2021-10-21
location: "Virtual"
---

Deep neural networks (DNNs) are one of the most prominent technologies of our time, as they achieve state-of-the-art performance in many machine learning tasks, including but not limited to image classification, text mining, and speech processing. However, recent studies have demonstrated the vulnerability of DNNs against adversarial examples, i.e., examples that are carefully crafted to fool a well-trained DNN while being indistinguishable from the natural images to humans. This makes it unsafe to apply neural networks in security-critical applications.
We present two algorithms, Embedding Regularized Classifier (ER-Classifier) and Bayesian Adversarial Detector (BATer), to train robust neural networks against adversarial examples. Inspired by the observation that adversarial examples often lie outside the natural image data manifold and the intrinsic dimension of image data is much smaller than its pixel space dimension, we propose to embed high-dimensional input images into a low-dimensional space and apply regularization on the embedding space to push the adversarial examples back to the manifold. Another algorithm, BATer, is motivated by the observations that random components can improve the smoothness of predictors and make it easier to simulate output distribution of DNN. Experimental results on several benchmark datasets show that our proposed frameworks achieve state-of-the-art performances against strong adversarial attack methods.

---
title: "Defending Against Adversarial Attacks by Regularized Deep Embedding"
collection: talks
type: "Talk"
permalink: /talks/sdss
venue: "2019 Symposium on Data Science & Statistics"
date: 2019-05-31
location: "Bellevue, Washington"
---

Recent studies have demonstrated the vulnerability of deep convolutional neural networks against adversarial examples. Inspired by the observation that the intrinsic dimension of image data is much smaller than its pixel space dimension and the vulnerability of neural networks grows with the input dimension, we propose to embed high-dimensional input images into a low-dimensional space to perform classification. However, arbitrarily projecting the input images to a low-dimensional space without regularization will not improve the robustness of deep neural networks. Leveraging optimal transport theory, we propose a new framework, Optimal Transport Classifier (OT-Classifier), and derive an objective that minimizes the discrepancy between the distribution of the true label and the distribution of the OT-Classifier output. Experimental results on several benchmark datasets show that, our proposed framework achieves state-of-the-art performance against strong adversarial attack methods.

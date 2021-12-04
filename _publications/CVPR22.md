---
title: "Learning Discriminative Shrinkage Deep Networks for Image Deconvolution"
#collection: publications
#permalink: /publication/CVPR22
excerpt: 'Pin-Hung Kuo, Jinshan Pan, Shao-Yi Chien, Ming-Hsuan Yang'
date: 2021-12-04
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/pdf/2111.13876'
---

Non-blind deconvolution is an ill-posed problem. Most existing methods usually formulate this problem into a maximum-a-posteriori framework and address it by designing kinds of regularization terms and data terms of the latent clear images. In this paper, we propose an effective non-blind deconvolution approach by learning discriminative shrinkage functions to implicitly model these terms. In contrast to most existing methods that use deep convolutional neural networks (CNNs) or radial basis functions to simply learn the regularization term, we formulate both the data term and regularization term and split the deconvolution model into data-related and regularization-related sub-problems according to the alternating direction method of multipliers. We explore the properties of the Maxout function and develop a deep CNN model with a Maxout layer to learn discriminative shrinkage functions to directly approximate the solutions of these two sub-problems. Moreover, given the fast Fourier transform based image restoration usually leads to ringing artifacts while conjugate gradient-based image restoration is time-consuming, we develop the conjugate gradient network to restore the latent clear images effectively and efficiently. Experimental results show that the proposed method performs favorably against the state-of-the-art ones in terms of efficiency and accuracy.

[Download paper here](https://arxiv.org/abs/2111.13876)

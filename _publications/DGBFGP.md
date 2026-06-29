---
title: "Bayesian Basis Function Approximation for Scalable Gaussian Process Priors in Deep Generative Models"
collection: publications
category: conferences
permalink: /publication/DGBFGP
excerpt: 'We propose a new way of utlizing Gaussian process priors in deep generative models, specifically variational autoencoders, with global parameterization that avoids explicit kernels, runs in linear time, eliminates the amortization gap, overcomes the limitations of categorical inducing point optimization, enhances interpretability in the latent space by quantifying the contributions of different covariates/effects using Sobol indices, allows for standard mini‑batch training, and treats kernel hyperparameters probabilistically.'
date: 2025-05-01
venue: 'Proceedings of the 42nd International Conference on Machine Learning (ICML)'
paperurl: 'https://openreview.net/pdf?id=dewZTXKwli'
slidesurl: 'https://slideslive.com/39039622/bayesian-basis-function-approximation-for-scalable-gaussian-process-priors-in-deep-generative-models'
bibtexurl: 'https://scholar.googleusercontent.com/scholar.bib?q=info:BXNj0i73lfIJ:scholar.google.com/&output=citation&scisdr=CgIVKXv8ELPW5qmVwIQ:AAZF9b8AAAAAaGqT2ITNKjY_5au2Ma702vXnmhI&scisig=AAZF9b8AAAAAaGqT2KLyYsn1H4Kchck7NRyMi8s&scisf=4&ct=citation&cd=-1&hl=en'
image: "DGBFGP.png"
authors: "<u>M. Y. Balık</u>, M. Sinelnikov, P. Ong, H. Lähdesmäki"
codeurl: "https://github.com/YigitBalik/DGBFGP"
---

High-dimensional time-series datasets are common in domains such as healthcare and economics. Variational autoencoder (VAE) models, where latent variables are modeled with a Gaussian process (GP) prior, have become a prominent model class to analyze such correlated datasets. However, their applications are challenged by the inherent cubic time complexity that requires specific GP approximation techniques, as well as the general challenge of modeling both shared and individual-specific correlations across time. Though inducing points enhance GP prior VAE scalability, optimizing them remains challenging, especially since discrete covariates resist gradient‑based methods. In this work, we propose a scalable basis function approximation technique for GP prior VAEs that mitigates these challenges and results in linear time complexity, with a global parametrization that eliminates the need for amortized variational inference and the associated amortization gap, making it well-suited for conditional generation tasks where accuracy and efficiency are crucial. Empirical evaluations on synthetic and real-world benchmark datasets demonstrate that our approach not only improves scalability and interpretability but also drastically enhances predictive performance.

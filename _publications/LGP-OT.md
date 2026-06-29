---
title: "Modeling Temporal scRNA-seq Data with Latent Gaussian Process and Optimal Transport"
collection: publications
category: conferences
permalink: /publication/LGP-OT
date: 2026-03-30
venue: 'Proceedings of the 43rd International Conference on Machine Learning (ICML)'
paperurl: 'https://openreview.net/forum?id=8RE5i7g4uB'
# slidesurl: 'https://slideslive.com/39039622/bayesian-basis-function-approximation-for-scalable-gaussian-process-priors-in-deep-generative-models'
# bibtexurl: 'https://scholar.googleusercontent.com/scholar.bib?q=info:BXNj0i73lfIJ:scholar.google.com/&output=citation&scisdr=CgIVKXv8ELPW5qmVwIQ:AAZF9b8AAAAAaGqT2ITNKjY_5au2Ma702vXnmhI&scisig=AAZF9b8AAAAAaGqT2KLyYsn1H4Kchck7NRyMi8s&scisf=4&ct=citation&cd=-1&hl=en'
image: "LGP-OT.png"
authors: "<u>M. Y. Balık</u>, H. Lähdesmäki"
codeurl: "https://github.com/YigitBalik/LGP-OT"
---

Single-cell RNA sequencing provides insights into gene expression at single-cell resolution, yet inferring temporal processes from these static snapshot measurements remains a fundamental challenge. Current approaches utilizing neural differential equations and flows are sensitive to overfitting and lack careful considerations of biological variability. In this work, we propose a generative framework that models population trends using a latent heteroscedastic Gaussian process (GP) approximated by Hilbert space methods. To address the absence of genuine cell trajectories, we leverage an optimal transport (OT) objective that aligns generated and observed population distributions. Our method explicitly captures biological heterogeneity by incorporating cell-specific latent time and cell type conditioning to disentangle temporal asynchrony and trajectories to different cell types. We demonstrate state-of-the-art performance on complex interpolation and extrapolation benchmarks and introduce a novel gradient-based strategy for inferring perturbation trajectories.

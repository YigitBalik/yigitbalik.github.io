---
title: "Investigating the Predictive Reproducibility of Federated Graph Neural Networks Using Medical Datasets"
collection: publications
category: conferences
permalink: /publication/reproducibleFedGNN
excerpt: 'In this work, we investigate the predictive reproducibility of federated graph neural networks (GNNs) using medical datasets. We evaluate the performance of various GNN models in a federated learning setting and analyze their performance.'
date: 2022-09-16
venue: 'Predictive Intelligence in Medicine: 5th International Workshop, PRIME 2022, Held in Conjunction with MICCAI'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-16919-9_15'
slidesurl: 'https://www.youtube.com/watch?v=pnattjt981k'
bibtexurl: 'https://scholar.googleusercontent.com/scholar.bib?q=info:RiBzS_ZF0loJ:scholar.google.com/&output=citation&scisdr=CgIVKQ1cELPW5lOJbdA:AAZF9b8AAAAAaJCPddDp7JNe4ejoYagRhy2Cg5E&scisig=AAZF9b8AAAAAaJCPdVA27gfJ3HE6Iej2vhWpVX8&scisf=4&ct=citation&cd=-1&hl=en'
image: "reproducibleFedGNN.png"
authors: "<u>M. Y. Balık</u>, A. Rekik, I. Rekik"
codeurl: "https://github.com/basiralab/reproducibleFedGNN"
---

Graph neural networks (GNNs) have achieved extraordinary enhancements in various areas including the fields medical imaging and network neuroscience where they displayed a high accuracy in diagnosing challenging neurological disorders such as autism. In the face of medical data scarcity and high-privacy, training such data-hungry models remains challenging. Federated learning brings an efficient solution to this issue by allowing to train models on multiple datasets, collected independently by different hospitals, in fully data-preserving manner. Although both state-of-the-art GNNs and federated learning techniques focus on boosting classification accuracy, they overlook a critical unsolved problem: investigating the reproducibility of the most discriminative biomarkers (i.e., features) selected by the GNN models within a federated learning paradigm. Quantifying the reproducibility of a predictive medical model against perturbations of training and testing data distributions presents one of the biggest hurdles to overcome in developing translational clinical applications. To the best of our knowledge, this presents the first work investigating the reproducibility of federated GNN models with application to classifying medical imaging and brain connectivity datasets. We evaluated our framework using various GNN models trained on medical imaging and connectomic datasets. More importantly, we showed that federated learning boosts both the accuracy and reproducibility of GNN models in such medical learning tasks. Our source code is available at <a href="https://github.com/basiralab/reproducibleFedGNN">https://github.com/basiralab/reproducibleFedGNN</a>.

---
title: "Interpretable Deep Learning for Myocardial Infarction Detection from ECG Signals"
collection: publications
category: conferences
permalink: /publication/IDLMID
excerpt: 'In this study, we show that deep learning models can be trained to detect myocardial infarction (MI) from 12-lead ECG signals. We also show that the model can be made interpretable by using gradient class activation maps (Grad-CAMs) to highlight the segments of the ECG that contribute most to the decision.'
date: 2023-08-28
venue: '31st Signal Processing and Communications Applications Conference (SIU)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10223856'
bibtexurl: 'https://scholar.googleusercontent.com/scholar.bib?q=info:d3qocV69vZwJ:scholar.google.com/&output=citation&scisdr=CgIVKQ1cELPW5lOLqcU:AAZF9b8AAAAAaJCNscWbiaPMr-OuVZGtIBxBr78&scisig=AAZF9b8AAAAAaJCNsZB2xMywDkQsahU0fluwhGA&scisf=4&ct=citation&cd=-1&hl=en'
image: "ecgd.png"
authors: "<u>M. Y. Balık</u>, K. Gökçe, S. Atmaca, E. Aslanger, A. Güler, I. Öksüz"
---

Acute heart attacks such as myocardial infarction (MI) are the main reasons for global deaths. Additionally, approximately half of the deaths occur before the treatment. Hence, it is crucial to diagnose MI fast and cheaply. 12-lead electrocardiogram (ECG) is noninvasive and fast compared to alternative devices. In this work, we aimed to train and validate a residual network model that can distinguish MI and healthy 12-lead ECG records. Moreover, we investigated the contribution of patient information such as age and sex to the decision. Additionally, we compared the performances of models trained with two different loss functions which are binary cross-entropy and pinball loss. We observed the highest accuracy, recall, and F1 score which are 97.86%, 98.73%, and 98.66%, respectively. Furthermore, since we used a convolutional neural network-based architecture, we obtained explainable results using gradient class activation maps by highlighting the ECG segments that contribute the most to the decision.

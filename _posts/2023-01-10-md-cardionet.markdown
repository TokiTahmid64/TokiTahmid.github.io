---
layout: post
title:  "MD-CardioNet: A Multi-Dimensional Deep Neural Network for Cardiovascular Disease Diagnosis from Electrocardiogram"
date:   2023/01/10
image: ../images/J_2.png
categories: journal
authors: "Md Toki Tahmid, Muhammad Ehsanul Kader, Tanvir Mahmud, Shaikh Anowarul Fattah"
venue: "IEEE Journal of Biomedical and Health Informatics"
arxiv: N/A
code: N/A
doi: https://doi.org/10.1109/JBHI.2023.3308856
excerpt: "Automated classification of cardiovascular diseases from electrocardiogram (ECG) signals using deep learning has gained significant interest due to its wide range of applications. However, existing deep learning approaches often overlook inter-channel shared information or lose time-sequence dependent information when considering 1D and 2D ECG representations, respectively. Moreover, besides considering spatial dimension, it is necessary to understand the context of the signals from a global feature space. We propose MD-CardioNet, an efficient deep learning architecture that captures temporal, spatial, and volumetric features from multi-lead ECG signals using multidimensional (1D, 2D, and 3D) convolutions to address these challenges. Sequential feature extractors capture time-dependent information, while a 2D convolution is applied to form an image representation from the multi-channel ECG signal, extracting inter-channel features. Additionally, a volumetric feature extraction network is designed to incorporate intra-channel, inter-channel, and inter-filter global space information. To reduce computational complexity, we introduce a practical knowledge distillation framework that reduces the number of trainable parameters by up to eight times (from 4,304,910 parameters to 94,842 parameters) while maintaining satisfactory performance compatible with the other existing approaches. The proposed architecture is evaluated on a large publicly available dataset containing ECG signals from over 10,000 patients, achieving an accuracy of 97.3% in classifying six heartbeat rhythms. Our results surpass the performance of some state-of-the-art approaches. This paper presents a novel deep-learning approach for ECG classification that addresses the limitations of existing methods. The experimental results highlight the robustness and accuracy of MD-CardioNet in cardiovascular disease classification, offering valuable insights for future research in this field.
"
---

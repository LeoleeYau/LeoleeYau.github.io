---
title: "JOWMDroid: Android malware detection based on feature weighting with joint optimization of weight-mapping and classifier parameters"
collection: publications
category: manuscripts
permalink: /publication/2021-01-01-JOWMDroid
date: 2021-01-01
venue: 'Computers & Security'
paperurl: 'https://doi.org/10.1016/j.cose.2020.102086'
citation: 'Cai, Lingru & Li, Yao & Xiong, Zhi. (2021). JOWMDroid: Android malware detection based on feature weighting with joint optimization of weight-mapping and classifier parameters. Computers & Security.'
---

Android malware detection is an important problem that must be urgently studied and solved. Machine learning-based methods first extract features from applications and then build a classifier using machine learning algorithms to distinguish malicious and benign applications. In most of the existing work, the difference in feature importance has been ignored, or the calculation of feature weights is irrelevant to the classification model. To address these issues, this paper proposes a novel Android malware detection scheme based on feature weighting with the joint optimization of weight-mapping and classifier parameters, called JOWMDroid. First, features of eight categories are extracted from the Android application package and then a certain number of the most important features are selected using information gain for malware detection. Next, an initial weight is calculated for each selected feature via three machine learning models and then five weight-mapping functions are designed to map the initial weights to the final weights. Finally, the parameters of the weight-mapping function and classifier are jointly optimized by the differential evolution algorithm. The experimental results reveal that the proposed method outperforms four state-of-the-art feature weighting methods and makes the weight-aware classifiers more competitive.

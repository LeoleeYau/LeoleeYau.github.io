---
title: "Meta-Learning for Multi-Family Android Malware Classification"
collection: publications
category: manuscripts
permalink: /publication/2024-08-26-MAMC
date: 2024-08-26
venue: 'ACM Transactions on Software Engineering and Methodology'
paperurl: 'https://doi.org/10.1145/3664806'
citation: 'Yao Li, Dawei Yuan, Tao Zhang, Haipeng Cai, David Lo, Cuiyun Gao, Xiapu Luo, and He Jiang. 2024. Meta-Learning for Multi-Family Android Malware Classification. ACM Trans. Softw. Eng. Methodol. 33, 7, Article 174 (September 2024), 27 pages.'
---

With the emergence of smartphones, Android has become a widely used mobile operating system. However, it is vulnerable when encountering various types of attacks. Every day, new malware threatens the security of users’ devices and private data. Many methods have been proposed to classify malicious applications, utilizing static or dynamic analysis for classification. However, previous methods still suffer from unsatisfactory performance due to two challenges. First, they are unable to address the imbalanced data distribution problem, leading to poor performance for malware families with few members. Second, they are unable to address the zero-day malware (zero-day malware refers to malicious applications that exploit unknown vulnerabilities) classification problem. In this article, we introduce an innovative meta-learning approach for multi-family Android malware classification named Meta-MAMC, which uses meta-learning technology to learn meta-knowledge (i.e., the similarities and differences among different malware families) of few-family samples and combines new sampling algorithms to solve the above challenges. Meta-MAMC integrates (i) the meta-knowledge contained within the dataset to guide models in learning to identify unknown malware; and (ii) more accurate and diverse tasks based on novel sampling strategies, as well as directly adapting meta-learning to a new few-sample and zero-sample task to classify families. We have evaluated Meta-MAMC on two popular datasets and a corpus of real-world Android applications. The results demonstrate its efficacy in accurately classifying malicious applications belonging to certain malware families, even achieving 100% classification in some families.

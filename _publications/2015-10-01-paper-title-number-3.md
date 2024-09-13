---
title: "Do pre-trained language models indeed understand software engineering tasks?"
collection: publications
category: manuscripts
permalink: /publication/2023-08-28-paper-title-number-3
date: 2024-08-28
venue: 'IEEE Transactions on Software Engineering'
paperurl: 'https://doi.org/10.1109/TSE.2023.3308952'
citation: 'Yao Li, Tao Zhang, Xiapu Luo, Haipeng Cai, Sen Fang, and Dawei Yuan. 2023. Do Pretrained Language Models Indeed Understand Software Engineering Tasks? IEEE Trans. Softw. Eng. 49, 10 (Oct. 2023), 4639–4655.'
---

Artificial intelligence (AI) for software engineering (SE) tasks has recently achieved promising performance. In this article, we investigate to what extent the pre-trained language model truly understands those SE tasks such as code search, code summarization, etc. We conduct a comprehensive empirical study on a board set of AI for SE (AI4SE) tasks by feeding them with variant inputs: 1) with various masking rates and 2) with sufficient input subset method. Then, the trained models are evaluated on different SE tasks, including code search, code summarization, and duplicate bug report detection. Our experimental results show that pre-trained language models are insensitive to the given input, thus they achieve similar performance in these three SE tasks. We refer to this phenomenon as <italic>overinterpretation</italic>, where a model confidently makes a decision without salient features, or where a model finds some irrelevant relationships between the final decision and the dataset. Our study investigates two approaches to mitigate the overinterpretation phenomenon: whole word mask strategy and ensembling. To the best of our knowledge, we are the <italic>first</italic> to reveal this overinterpretation phenomenon to the AI4SE community, which is an important reminder for researchers to design the input for the models and calls for necessary future work in understanding and implementing AI4SE tasks.

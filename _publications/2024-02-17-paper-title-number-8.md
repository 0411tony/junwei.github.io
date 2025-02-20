---
title: "Pre-training by Predicting Program Dependencies for Vulnerability Analysis Tasks"
collection: publications
category: conferences
permalink: 
excerpt: 'This work proposes two novel pre-training objectives, namely Control Dependency Prediction (CDP) and Data Dependency Prediction (DDP), which aim to
predict the statement-level control dependencies and token-level data dependencies, respectively, in a code snippet only based on
its source code.'
date: 2024-04-14
venue: 'ICSE 2024.'
paperurl: 'https://github.com/0411tony/junwei.github.io/blob/master/files/ICSE2024-paper.pdf'
citation: 'Zhongxin Liu, Zhijie Tang, Junwei Zhang, Xin Xia, and Xiaohu Yang. (2024). &quot;Pre-training by Predicting Program Dependencies for Vulnerability Analysis Tasks.&quot; <i>ICSE 2024.</i>. 546(2024).'
---

Vulnerability analysis is crucial for software security. Inspired by the success of pre-trained models on software engineering tasks,
this work focuses on using pre-training techniques to enhance the understanding of vulnerable code and boost vulnerability analysis.
The code understanding ability of a pre-trained model is highly related to its pre-training objectives. The semantic structure, e.g.,
control and data dependencies, of code is important for vulnerability analysis. However, existing pre-training objectives either ignore
such structure or focus on learning to use it. The feasibility and benefits of learning the knowledge of analyzing semantic structure
have not been investigated. To this end, this work proposes two novel pre-training objectives, namely Control Dependency Prediction (CDP) and Data Dependency Prediction (DDP), which aim to
predict the statement-level control dependencies and token-level data dependencies, respectively, in a code snippet only based on
its source code. During pre-training, CDP and DDP can guide the model to learn the knowledge required for analyzing fine-grained
dependencies in code. After pre-training, the pre-trained model can boost the understanding of vulnerable code during fine-tuning
and can directly be used to perform dependence analysis for both partial and complete functions. To demonstrate the benefits of our
pre-training objectives, we pre-train a Transformer model named PDBERT with CDP and DDP, fine-tune it on three vulnerability
analysis tasks, i.e., vulnerability detection, vulnerability classification, and vulnerability assessment, and also evaluate it on program
dependence analysis. Experimental results show that PDBERT benefits from CDP and DDP, leading to state-of-the-art performance
on the three downstream tasks. Also, PDBERT achieves F1-scores of over 99% and 94% for predicting control and data dependencies,
respectively, in partial and complete functions.


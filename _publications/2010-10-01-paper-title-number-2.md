---
title: "Dual Prompt-Based Few-Shot Learning for Automated Vulnerability Patch Localization"
collection: publications
category: manuscripts
permalink: 
excerpt: 'This paper proposes a novel security patch localization approach named PromVPat, which utilizes the dual prompt tuning channel to capture the semantic correlation between vulnerability descriptions and commits, especially in data scarcity (i.e., few-shot) scenarios.'
date: 2024-03-12
venue: '940--951'
paperurl: 'https://github.com/0411tony/junwei.github.io/blob/master/files/SANER2024.pdf'
citation: 'Junwei Zhang, Xing Hu*, Lingfeng Bao, Xin Xia, Shanping Li. International Conference on Software Analysis, Evolution and Reengineering (SANER 2024). &quot; Dual Prompt-Based Few-Shot Learning for Automated Vulnerability Patch Localization &quot; <i>940--951</i>. 1(2).'
---

In this paper, we propose a novel security patch localization approach named PromVPat, which utilizes the dual prompt tuning channel to capture the
semantic correlation between vulnerability descriptions and commits, especially in data scarcity (i.e., few-shot) scenarios. We first input the commit message and code changes with the
vulnerability description into the prompt generator to generate two new inputs with prompt templates. Then, we adopt a pretrained language model (i.e., PLM) as the encoder, utilize the
prompt tuning method to fine-tune the encoder, and generate two correlation probabilities as the semantic features. In addition, we extract 26 handcrafted features from the vulnerability descriptions
and the code commits. Finally, we utilize the attention mechanism to fuse the handcrafted and semantic features, which are fed into the classifier to predict the correlation probability and locate
the security patch. To evaluate the performance of PromVPat, we compare it with five baselines on two datasets. Experimental results demonstrate that PromVPat performs best in the security
patch localization task, improving the best baseline by 14.42% and 86.57% on two datasets regarding Recall@1. Moreover, PromVPat has proven to be effective even in data scarcity scenarios.

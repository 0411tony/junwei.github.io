---
title: "Path-based reasoning over heterogeneous networks for recommendation via bidirectional modeling"
collection: publications
category: conferences
permalink: 
excerpt: 'This paper proposes a novel path-based reasoning approach for recommendation over HIN'
date: 2021-07-20
venue: 'Neurocomputing.'
paperurl: 'https://github.com/0411tony/junwei.github.io/blob/master/files/Neurocomputing.pdf'
citation: 'Junwei Zhang, Min Gao, Junliang Yu, Linda Yang, Zongwei Wang, Qingyu Xiong. (2021). &quot;Path-based reasoning over heterogeneous networks for recommendation via bidirectional modeling.&quot; <i>Neurocomputing</i>. 461(2021).'
---

Heterogeneous Information Network (HIN) is a natural and general representation of data in recommender systems. Combining HIN and recommender systems can not only help model user behaviors but also make the recommendation results explainable by aligning the users/items with various types of entities in the network. Over the past few years, path-based reasoning models have shown great capacity in HIN-based recommendation. The basic idea of these models is to explore HIN with predefined
path schemes. Despite their effectiveness, these models are often confronted with the following limitations: (1) Most prior path-based reasoning models only consider the influence of the predecessors on
the subsequent nodes when modeling the sequences, and ignore the reciprocity between the nodes in a path; (2) The weights of nodes in the same path instance are usually assumed to be constant, whereas
varied weights of nodes can bring more flexibility and lead to expressive modeling; (3) User-item interactions are noisy, but they are often indiscriminately exploited. To overcome the aforementioned issues,
in this paper, we propose a novel path-based reasoning approach for recommendation over HIN. Concretely, we use a bidirectional LSTM to enable the two-way modeling of paths and capture the
reciprocity between nodes. Then an attention mechanism is employed to learn the dynamical influence of nodes in different contexts. Finally, the adversarial regularization terms are imposed on the loss function of the model to mitigate the effects of noise and enhance HIN-based recommendation. Extensive experiments conducted on three public datasets show that our model outperforms the state-of-the-art baselines. The case study further demonstrates the feasibility of our model on the explainable recommendation task.

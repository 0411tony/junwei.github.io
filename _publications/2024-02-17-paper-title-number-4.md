---
title: "Vulnerability Detection by Learning From Syntax-Based Execution Paths of Code"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This work proposed to decompose the syntax-based Control Flow Graph (CFG) of the code snippet into multiple execution paths to detect the vulnerability'
date: 2024-02-17
venue: 'IEEE Trans. Software Eng.'
paperurl: 'https://github.com/0411tony/junwei.github.io/blob/master/files/TSE.pdf'
citation: 'Junwei Zhang, Zhongxin Liu, Xing Hu, Xin Xia, Shanping Li. (2024). &quot;Vulnerability Detection by Learning From Syntax-Based Execution Paths of Code.&quot; <i>IEEE Trans. Software Eng</i>. 1(3).'
---

Vulnerability detection is essential to protect software systems. Various approaches based on deep learning have been proposed to learn the pattern of vulnerabilities and identify them.
Although these approaches have shown vast potential in this task, they still suffer from the following issues: (1) It is difficult for them to distinguish vulnerability-related information from a large
amount of irrelevant information, which hinders their effectiveness in capturing vulnerability features. (2) They are less effective in
handling long code because many neural models would limit the input length, which hinders their ability to represent the long
vulnerable code snippets. To mitigate these two issues, in this work, we proposed to decompose the syntax-based Control Flow Graph
(CFG) of the code snippet into multiple execution paths to detect the vulnerability. Specifically, given a code snippet, we first build its
CFG based on its Abstract Syntax Tree (AST), refer to such CFG as syntax-based CFG, and decompose the CFG into multiple paths
from an entry node to its exit node. Next, we adopt a pre-trained code model and a convolutional neural network to learn the path
representations with intra- and inter-path attention. The feature vectors of the paths are combined as the representation of the
code snippet and fed into the classifier to detect the vulnerability. Decomposing the code snippet into multiple paths can filter out
some redundant information unrelated to the vulnerability and help the model focus on the vulnerability features. Besides, since
the decomposed paths are usually shorter than the code snippet, the information located in the tail of the long code is more likely
to be processed and learned. To evaluate the effectiveness of our model, we build a dataset with over 231 k code snippets, in which
there are 24 k vulnerabilities. Experimental results demonstrate that the proposed approach outperforms state-of-the-art baselines
by at least 22.30%, 42.92%, and 32.58% in terms of Precision, Recall, and F1-Score, respectively.Our further analysis investigates
the reason for the proposed approach’s superiority.

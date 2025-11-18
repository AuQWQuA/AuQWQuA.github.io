---
title: "GramTrans: A Better Code Representation Approach in Code Generation"
collection: publications
permalink: /publication/2025-10-03-gramtrans
excerpt: '<strong>Zhao Zhang</strong>, Qingyuan Liang, Zeyu Sun, Yizhou Chen, Guoqing Wang, Yican Sun, Lu Zhang, Ge Li, Yingfei Xiong'
date: 2025-10-03
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2510.02887'
---
Code generation has shown great promise in assisting software development. A fundamental yet underexplored question is how the choice of code representation affects model performance. While existing studies employ various representations, such as treating code as plain text, grammar rule sequences, or syntax tree sequences, they lack a principled understanding of the relationship between parsing difficulty and model effectiveness. 

This paper proposes a conjecture: the easier a representation is to parse, the better performance the model achieves. We formalize this idea using grammar classes, where representations in simpler classes (e.g., LL(1)) are easier to parse. Through a controlled experiment on a Python-based DSL, we show that parsing difficulty strongly correlates with model performance. Motivated by this finding, we present GramTrans, a general approach that automatically transforms a context-free language into a representation within the LL(1) class. GramTrans introduces a novel hierarchical conflict elimination algorithm, enabling a flexible trade-off between syntactic simplicity and token efficiency. We evaluate GramTrans on both Python and Java using three code generation models: StarCoder 1B, DeepSeek-Coder 1.3B, and Qwen2.5 1.5B. Across multiple benchmarks, GramTrans consistently delivers significant improvements over baseline representations.

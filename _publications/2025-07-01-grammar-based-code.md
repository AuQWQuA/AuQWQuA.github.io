---
title: "Grammar-based code representation: Is it a worthy pursuit for llms?"
collection: publications
category: conferences
permalink: /publication/2025-07-01-grammar-based-code
excerpt: 'We develop a series of billion-scale GrammarCoder models, incorporating grammar rules in the code generation process, showing that grammar-based representations remain valuable even in billion-scale models.'
date: 2025-07-01
venue: 'Findings of the Association for Computational Linguistics: ACL 2025'
paperurl: 'https://aclanthology.org'
citation: 'Qingyuan Liang, Zhao Zhang, Zeyu Sun, Zheng Lin, Qi Luo, Xiao Yueyi, Yizhou Chen, Yuqun Zhang, Haotian Zhang, Lu Zhang, Chenbin Chenbin, Yingfei Xiong. (2025). &quot;Grammar-based code representation: Is it a worthy pursuit for llms?&quot; <i>Findings of ACL 2025</i>. pp. 15640-15653.'
---
Grammar serves as a cornerstone in programming languages and software engineering, providing frameworks to define the syntactic space and program structure. Existing research demonstrates the effectiveness of grammar-based code representations in small-scale models, showing their ability to reduce syntax errors and enhance performance. However, as language models scale to the billion level or beyond, syntax-level errors become rare, making it unclear whether grammar information still provides performance benefits. 

To explore this, we develop a series of billion-scale GrammarCoder models, incorporating grammar rules in the code generation process. Experiments on HumanEval (+) and MBPP (+) demonstrate a notable improvement in code generation accuracy. Further analysis shows that grammar-based representations enhance LLMs' ability to discern subtle code differences, reducing semantic errors caused by minor variations. These findings suggest that grammar-based code representations remain valuable even in billion-scale models, not only by maintaining syntax correctness but also by improving semantic differentiation.

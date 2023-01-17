---
layout: default
title: Execution Model
parent: Runtime Related Terms
nav_order: 1
---

# Execution Model
{: .fs-9 }
The model which governs the execution of a program.
{: .fs-6 .fw-300 }

Classical
{: .label }

Quantum
{: .label .label-green}


## Full Definition
The execution model defines the behavior between different components in the programming language, the interaction between the classical computer and the quantum computer (intermediate or non-intermediate) including scheduling.
The execution model is enforced by the runtime environment. 
The program execution can be defined by operational semantics.
In quantum computing three models have been defined <sup>[1](#src_1)<sup>:
1. The QRAM Model
2. The Restricted HQCC Model
3. The Refined HQCC Model


<!-- ## Examples -->

<!-- ## Synonyms

- -->

## Related Terms
- [Runtime Environment]


## Sources
1. X. Fu, Jintao Yu, Xing Su, Hanru Jiang, Hua Wu, Fucheng Cheng, Xi Deng, Jinrong Zhang, Lei Jin, Yihang Yang, Le Xu, Chunchao Hu, Anqi Huang, Guangyao Huang, Xiaogang Qiang, Mingtang Deng, Ping Xu, Weixia Xu, Wanwei Liu, Yu Zhang, Yuxin Deng, Junjie Wu, and Yuan Feng. 2021. Quingo: A Programming Framework for Heterogeneous Quantum-Classical Computing with NISQ Features. ACM Transactions on Quantum Computing 2, 4, Article 19 (December 2021), 37 pages. [doi](https://doi.org/10.1145/3483528)<a href="src_1"></a>


[Runtime Environment]: {{ site.baseurl }}{% link glossary/runtime-related/runtime-environment.md %}

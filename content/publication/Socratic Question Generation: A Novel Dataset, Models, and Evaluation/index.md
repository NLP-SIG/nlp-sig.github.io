---
title: Socratic Question Generation\: A Novel Dataset, Models, and Evaluation
publication_types:
  - "1"
authors:
  - Xiaoqiang Lin*
  - Zhaoxuan Wu*
  - Zhongxiang Dai
  - Wenyang Hu
  - Yao Shu
  - See-Kiong Ng
  - Patrick Jaillet
  - Bryan Kian Hsiang Low
publication: "NeurIPS"
publication_short: NeurIPS
abstract: Large language models (LLMs) have shown remarkable instruction-following capabilities and achieved impressive performances in various applications. However, the performances of LLMs depend heavily on the instructions given to them, which are typically manually tuned with substantial human efforts. Recent work has used the query-efficient Bayesian optimization (BO) algorithm to automatically optimize the instructions given to black-box LLMs. However, BO usually falls short when optimizing highly sophisticated (e.g., high-dimensional) objective functions, such as the functions mapping an instruction to the performance of an LLM. This is mainly due to the limited expressive power of the Gaussian process (GP) model which is used by BO as a surrogate to model the objective function. Meanwhile, it has been repeatedly shown that neural networks (NNs), especially pre-trained transformers, possess strong expressive power and can model highly complex functions. So, we adopt a neural bandit algorithm which replaces the GP in BO by an NN surrogate to optimize instructions for black-box LLMs. More importantly, the neural bandit algorithm allows us to naturally couple the NN surrogate with the hidden representation learned by a pre-trained transformer (i.e., an open-source LLM), which significantly boosts its performance. These motivate us to propose our INSTruction optimization usIng Neural bandits Coupled with Transformers} (INSTINCT) algorithm. We perform instruction optimization for ChatGPT and use extensive experiments to show that our INSTINCT consistently outperforms the existing methods in different tasks, such as in various instruction induction tasks and the task of improving the zero-shot chain-of-thought instruction.

date: '2023-10-02T00:00:00Z'
---
Link: https://arxiv.org/abs/2310.02905
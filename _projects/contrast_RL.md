---
title: "Contrastive Offline Reinforcement Learning"
excerpt: "Contrastive learning for Offline RL"
collection: projects
---
[proposal PDF](https://www.yuewu.ml/files/other/proposal.pdf)
# Abstract
Offline Reinforcement Learning promises to learn effective policies from previously-collected, static datasets without the need for exploration. However, existing Q-learning and actor-critic based off-policy RL algorithms fail when bootstrapping from out-of-distribution (OOD) actions or states. We hypothesize that a training curriculum motivated through contrastive learning can improve the models' robustness against OOD backups. 
The goal of this project is to invent a contrastive training curriculum that is robust against OOD samples for actor-critic algorithms in the context of offline reinforcement learning. Achieving this goal will enable RL agents to better learn from demonstrations and improve the sample efficiency of online RL in general.

# Research Questions
We aim to answer the following specific research questions from both empirical and theoretical perspectives:
- Can we design an efficient model and training curriculum that makes best use of contrastive learning to help reduce the effect of OOD samples in offline RL?
- Can we mathematically show better convergence properties with our contrastive framework?
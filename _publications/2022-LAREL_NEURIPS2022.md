---
title: "Tackling AlfWorld with Action Attention and Common Sense from Language Models"
collection: publications
permalink: /publication/AlfWorld
excerpt: 'We present (1) a novel question answering framework to simplify observation and (2) an action attention framework to handle large and variable size action space for the AlfWorld simulator.'
date: 2022-09-30
venue: 'Language and Reinforcement Learning Workshop, NeurIPS'
paperurl: 'https://openreview.net/pdf?id=AqkPRUZ-YkO'
authors: 'Yue Wu, So Yeon Min, Yonatan Bisk, Ruslan Salakhutdinov, Shrimai Prabhumoye'
img: 'https://alfworld.github.io/images/butler_pipeline.png'
submitted: false
---
[View full text here](https://openreview.net/pdf?id=AqkPRUZ-YkO)

<!-- <img src="https://www.yuewu.ml/files/demos/UWAC.gif"
     alt="Figure Illustration"/> -->
### Abstract
Pre-trained language models (LMs) capture strong prior knowledge about the world. This common sense knowledge can be used in control tasks. However, directly generating actions from LMs may result in a reasonable narrative, but not executable by a low level agent. We propose to instead use the knowledge in LMs to simplify the control problem, and assist the low-level actor training. We implement a novel question answering framework to simplify observations and an agent that handles arbitrary roll-out length and action space size based on action attention. On the Alfworld benchmark for indoor instruction following, we achieve a significantly higher success rate (50% over the baseline) with our novel object masking - action attention method.

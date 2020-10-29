---
title: "Improving GAN Training with Probability Ratio Clipping and Sample Reweighting"
collection: publications
permalink: /publication/PPOGAN
excerpt: 'GAN formulation through variational inference and constrained reinforcement learning that leads to probability ratio clipping and discriminator re-weighting.'
date: 2020-12-12
venue: 'NeurIPS'
paperurl: 'https://arxiv.org/pdf/2006.06900.pdf'
published: true
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
[View full text here](https://arxiv.org/pdf/2006.06900.pdf)
### Abstract
Despite success on a wide range of problems related to vision, generative adversarial networks (GANs) often suffer from inferior performance due to unstable training, especially for text generation. To solve this issue, we propose a new variational GAN training framework which enjoys superior training stability. Our approach is inspired by a connection of GANs and reinforcement learning under a variational perspective. The connection leads to (1) probability ratio clipping that regularizes generator training to prevent excessively large updates, and (2) a sample re-weighting mechanism that improves discriminator training by downplaying bad-quality fake samples. Moreover, our variational GAN framework can provably overcome the training issue in many GANs that an optimal discriminator cannot provide any informative gradient to training generator. By plugging the training approach in diverse state-of-the-art GAN architectures, we obtain significantly improved performance over a range of tasks, including text generation, text style transfer, and image generation.
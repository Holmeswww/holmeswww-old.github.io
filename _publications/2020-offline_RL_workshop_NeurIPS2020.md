---
title: "Uncertainty Weighted Offline Reinforcement Learning"
collection: publications
permalink: /publication/UWAC
excerpt: 'Uncertainty estimation to stabilize actor-critic based offline reinforcement learning.'
date: 2020-12-12
venue: 'Offline RL Workshop, NeurIPS'
paperurl: 'https://www.yuewu.ml/files/paper/Offline_RL_Workshop.pdf'
submitted: true
---
[View full text here](https://www.yuewu.ml/files/paper/Offline_RL_Workshop.pdf)

<img src="https://www.yuewu.ml/files/demos/UWAC.gif"
     alt="Figure Illustration"/>
### Abstract
Offline Reinforcement Learning promises to learn effective policies from previously-collected, static datasets without the need for exploration. However, existing Q-learning and actor-critic based off-policy RL algorithms fail when bootstrapping from out-of-distribution (OOD) actions or states. We hypothesize that a key missing ingredient from the existing methods is a proper treatment of uncertainty in the offline setting. We propose Uncertainty Weighted Actor-Critic (UWAC), an algorithm that models the epistemic uncertainty to detect OOD state-action pairs and down-weights their contribution in the training objectives accordingly. Implementation-wise, we adopt a practical and effective dropout-based uncertainty estimation method that introduces very little overhead over existing RL algorithms. Empirically, we observe that UWAC substantially improves model stability during training. In addition, UWAC out-performs existing offline RL methods on a variety of competitive tasks, and achieves significant performance gains over the state-of-the-art baseline on datasets with sparse demonstrations collected from human experts.

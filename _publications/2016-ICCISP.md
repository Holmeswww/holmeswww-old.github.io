---
title: "License plate recognition using deep FCN"
collection: publications
permalink: /publication/ICCSIP2016
excerpt: 'Deep residual Fully Convolutional Network for car license plate recognition.'
date: 2016-12-10
venue: 'International Conference on Cognitive Systems and Signal Processing, ICCSIP'
submitted: false
---
### Abstract
In our work, we concentrate on the problem of car license plate recognition after the plate has been extracted from an image. Traditional methods approach this problem as three separate steps: preprocessing, segmentation, and recognition. In this paper, we propose a unified approach that integrates these steps using a fully convolutional network. We train a 36-class FCN on a dataset of single characters and apply it to height-normalized license plates. The architecture of this model successfully reduces the loss in detail during end-to-end convolution. Finally, we extract the results from the output sequences of probabilities using a variant of the NMS algorithm. The experiments on public license plate datasets show that our approach outperforms the state-of-the-art methods.
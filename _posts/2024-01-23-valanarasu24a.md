---
title: On-the-Fly Test-time Adaptation for Medical Image Segmentation
abstract: One major problem in deep learning-based solutions for medical imaging is
  the drop in performance when a model is tested on a data distribution different
  from the one that it is trained on. Adapting the source model to target data distribution
  at test-time is an efficient solution for the data-shift problem. Previous methods
  solve this by adapting the model to target distribution by using techniques like
  entropy minimization or regularization. In these methods, the models are still updated
  by back-propagation using an unsupervised loss on complete test data distribution.
  In real-world clinical settings, it makes more sense to adapt a model to a new test
  image on-the-fly and avoid model update during inference due to privacy concerns
  and lack of computing resource at deployment. To this end, we propose a new setting
  - On-the-Fly Adaptation which is zero-shot and episodic i.e., the model is adapted
  to a single image at a time and also does not perform any back-propagation during
  test-time). To achieve this, we propose a new framework called Adaptive UNet where
  each convolutional block is equipped with an adaptive batch normalization layer
  to adapt the features with respect to a domain code. The domain code is generated
  using a pre-trained encoder trained on a large corpus of medical images. During
  test-time, the model takes in just the new test image and generates a domain code
  to adapt the features of source model according to the test data. We validate the
  performance on both 2D and 3D data distribution shifts where we get a better performance
  compared to previous test-time adaptation methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: valanarasu24a
month: 0
tex_title: On-the-Fly Test-time Adaptation for Medical Image Segmentation
firstpage: 586
lastpage: 598
page: 586-598
order: 586
cycles: false
bibtex_author: Valanarasu, Jeya Maria Jose and Guo, Pengfei and VS, Vibashan and Patel,
  Vishal M.
author:
- given: Jeya Maria Jose
  family: Valanarasu
- given: Pengfei
  family: Guo
- given: Vibashan
  family: VS
- given: Vishal M.
  family: Patel
date: 2024-01-23
address:
container-title: Medical Imaging with Deep Learning
volume: '227'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 1
  - 23
pdf: https://proceedings.mlr.press/v227/valanarasu24a/valanarasu24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

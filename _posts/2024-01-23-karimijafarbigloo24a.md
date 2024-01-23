---
title: 'MS-Former: Multi-Scale Self-Guided Transformer for Medical Image Segmentation'
abstract: Multi-scale representations have proven to be a powerful tool since they
  can take into account both the fine-grained details of objects in an image as well
  as the broader context. Inspired by this, we propose a novel dual-branch transformer
  network that operates on two different scales to encode global contextual dependencies
  while preserving local information. To learn in a self-supervised fashion, our approach
  considers the semantic dependency that exists between different scales to generate
  a supervisory signal for inter-scale consistency and also imposes a spatial stability
  loss within the scale for self-supervised content clustering. While intra-scale
  and inter-scale consistency losses aim to increase features similarly within the
  cluster, we propose to include a cross-entropy loss function on top of the clustering
  score map to effectively model each cluster distribution and increase the decision
  boundary between clusters. Iteratively our algorithm learns to assign each pixel
  to a semantically related cluster to produce the segmentation map. Extensive experiments
  on skin lesion and lung segmentation datasets show the superiority of our method
  compared to the state-of-the-art (SOTA) approaches.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karimijafarbigloo24a
month: 0
tex_title: 'MS-Former: Multi-Scale Self-Guided Transformer for Medical Image Segmentation'
firstpage: 680
lastpage: 694
page: 680-694
order: 680
cycles: false
bibtex_author: Karimijafarbigloo, Sanaz and Azad, Reza and Kazerouni, Amirhossein
  and Merhof, Dorit
author:
- given: Sanaz
  family: Karimijafarbigloo
- given: Reza
  family: Azad
- given: Amirhossein
  family: Kazerouni
- given: Dorit
  family: Merhof
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
pdf: https://proceedings.mlr.press/v227/karimijafarbigloo24a/karimijafarbigloo24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

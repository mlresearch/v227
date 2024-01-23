---
title: Domain adaptation using optimal transport for invariant learning using histopathology
  datasets
abstract: Histopathology is critical for the diagnosis of many diseases, including
  cancer. These protocols typically require pathologists to manually evaluate slides
  under a microscope, which is time-consuming and subjective, leading to interest
  in machine learning to automate analysis. However, computational techniques are
  limited by batch effects, where technical factors like differences in preparation
  protocol or scanners can alter the appearance of slides, causing models trained
  on one institution or patient to fail when generalizing to others. Here, we propose
  a domain adaptation method that improves the generalization of histopathological
  models to data from unseen institutions, without the need for labels or retraining
  in these new settings. Our approach introduces an optimal transport (OT) loss, that
  extends adversarial methods that penalize models if images from different institutions
  can be distinguished in their representation space. Unlike previous methods, which
  operate on single samples, our loss accounts for distributional differences between
  batches of images. We show that on the Camelyon17 dataset, while both methods can
  adapt to global differences in color distribution, only our OT loss can reliably
  classify a cancer phenotype unseen during training. Together, our results suggest
  that OT improves generalization on rare but critical phenotypes that may only make
  up a small fraction of the total tiles and variation in a slide.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: falahkheirkhah24a
month: 0
tex_title: Domain adaptation using optimal transport for invariant learning using
  histopathology datasets
firstpage: 1765
lastpage: 1782
page: 1765-1782
order: 1765
cycles: false
bibtex_author: Falahkheirkhah, Kianoush and Lu, Alex Xijie and Alvarez-Melis, David
  and Huynh, Grace
author:
- given: Kianoush
  family: Falahkheirkhah
- given: Alex Xijie
  family: Lu
- given: David
  family: Alvarez-Melis
- given: Grace
  family: Huynh
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
pdf: https://proceedings.mlr.press/v227/falahkheirkhah24a/falahkheirkhah24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

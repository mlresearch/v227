---
title: MultiTask Learning for accelerated-MRI Reconstruction and Segmentation of Brain
  Lesions in Multiple Sclerosis
abstract: This work proposes MultiTask Learning for accelerated-MRI Reconstruction
  and Segmentation (MTLRS). Unlike the common single-task approaches, MultiTask Learning
  identifies relations between multiple tasks to improve the performance of all tasks.
  The proposed MTLRS consists of a unique cascading architecture, where a recurrent
  reconstruction network and a segmentation network inform each other through hidden
  states. The features of the two networks are shared and implicitly enforced as inductive
  bias. To evaluate the benefit of MTLRS, we compare performing the two tasks of accelerated-MRI
  reconstruction and MRI segmentation with pre-trained, sequential, end-to-end, and
  joint approaches. A synthetic multicoil dataset is used to train, validate, and
  test all approaches with five-fold cross-validation. The dataset consists of 3D
  FLAIR brain data of relapsing-remitting Multiple Sclerosis patients with known white
  matter lesions. The acquisition is prospectively undersampled by approximately 7.5
  times compared to clinical standards. Reconstruction performance is evaluated by
  Structural Similarity Index Measure (SSIM) and Peak Signal-to-Noise Ratio (PSNR).
  Segmentation performance is evaluated by Dice score for combined brain tissue and
  white matter lesion segmentation and by per lesion Dice score. Results show that
  MTLRS outperforms other evaluated approaches, providing high-quality reconstructions
  and accurate white matter lesion segmentation. A significant correlation was found
  between the performance of both tasks (SSIM and per lesion Dice score, $\rho=0.92$,
  $p=0.0005$). Our proposed MTLRS demonstrates that accelerated-MRI reconstruction
  and MRI segmentation can be effectively combined to improve performance on both
  tasks, potentially benefiting clinical settings.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karkalousos24a
month: 0
tex_title: MultiTask Learning for accelerated-MRI Reconstruction and Segmentation
  of Brain Lesions in Multiple Sclerosis
firstpage: 991
lastpage: 1005
page: 991-1005
order: 991
cycles: false
bibtex_author: Karkalousos, Dimitrios and Isgum, Ivana and Marquering, Henk and Caan,
  Matthan W. A.
author:
- given: Dimitrios
  family: Karkalousos
- given: Ivana
  family: Isgum
- given: Henk
  family: Marquering
- given: Matthan W. A.
  family: Caan
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
pdf: https://proceedings.mlr.press/v227/karkalousos24a/karkalousos24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

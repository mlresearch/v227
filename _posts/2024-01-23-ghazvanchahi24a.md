---
title: Effect of Intensity Standardization on Deep Learning for WML Segmentation in
  Multi-Centre FLAIR MRI
abstract: 'Deep learning (DL) methods for white matter lesion (WML) segmentation in
  MRI suffer a reduction in performance when applied on data from a scanner or centre
  that is out-of-distribution (OOD) from the training data. This is critical for translation
  and widescale adoption, since current models cannot be readily applied to data from
  new institutions. In this work, we evaluate several intensity standardization methods
  for MRI as a preprocessing step for WML segmentation in multi-centre Fluid-Attenuated
  Inversion Recovery (FLAIR) MRI. We evaluate a method specifically developed for
  FLAIR MRI called IAMLAB along with other popular normalization techniques such as
  White-strip, Nyul and Z-score. We proposed an Ensemble model that combines predictions
  from each of these models. A skip-connection UNet (SC UNet) was trained on the standardized
  images, as well as the original data and segmentation performance was evaluated
  over several dimensions. The training (in-distribution) data consists of a single
  study, of 60 volumes, and the test (OOD) data is 128 unseen volumes from three clinical
  cohorts. Results show IAMLAB and Ensemble provide higher WML segmentation performance
  compared to models from original data or other normalization methods. IAMLAB & Ensemble
  have the highest dice similarity coefficient (DSC) on the in-distribution data (0.78
  & 0.80) and on clinical OOD data. DSC was significantly higher for IAMLAB compared
  to the original data (p<0.05) for all lesion categories (LL>25mL: 0.77 vs. 0.71;
  10mL<= LL<25mL: 0.66 vs. 0.61; LL<10mL: 0.53 vs. 0.52). The IAMLAB and Ensemble
  normalization methods are mitigating MRI domain shift and are optimal for DL-based
  WML segmentation in unseen FLAIR data.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ghazvanchahi24a
month: 0
tex_title: Effect of Intensity Standardization on Deep Learning for WML Segmentation
  in Multi-Centre FLAIR MRI
firstpage: 1923
lastpage: 1940
page: 1923-1940
order: 1923
cycles: false
bibtex_author: Ghazvanchahi, Abdollah and Maralani, Pejman Jahbedar and Moody, Alan
  R. and Khademi, April
author:
- given: Abdollah
  family: Ghazvanchahi
- given: Pejman Jahbedar
  family: Maralani
- given: Alan R.
  family: Moody
- given: April
  family: Khademi
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
pdf: https://proceedings.mlr.press/v227/ghazvanchahi24a/ghazvanchahi24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

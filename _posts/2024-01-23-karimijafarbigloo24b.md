---
title: 'MMCFormer: Missing Modality Compensation Transformer for Brain Tumor Segmentation'
abstract: Human brain tumours and more specifically gliomas are amongst the most life-threatening
  cancers which usually arise from abnormal growth of the glial stem cells. In practice,
  Magnetic Resonance Imaging (MRI) modalities, which offer different contrasts to
  elucidate tissue properties, provide comprehensive information regarding the brain’s
  structure and also potential clues for detecting tumors. Hence, multi-modal MRI
  is commonly utilized for the diagnosis of brain tumors. However, since the set of
  acquired modalities may vary between clinical sites, brain tumor studies may miss
  one or two MRI modalities. To address missing information in an end-to-end manner,
  we propose MMCFormer, a novel missing modality compensation network. Our strategy
  builds upon 3D efficient transformer blocks and uses a co-training strategy to effectively
  train a missing modality network. To ensure feature consistency in a multi-scale
  fashion, MMCFormer utilizes global contextual agreement modules in each scale of
  the encoders. Furthermore, to transfer modality-specific representations, we propose
  to incorporate auxiliary tokens in the bottleneck stage to model interaction between
  full and missing-modality paths. On top of that, we include feature consistency
  losses to reduce the domain gap in network prediction and increase the prediction
  reliability for the missing modality path. Extensive experiments on the BraTS 2018
  dataset demonstrate the benefits of our approach compared to competing approaches.
  The implementation code will be publicly available after the paper acceptance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karimijafarbigloo24b
month: 0
tex_title: 'MMCFormer: Missing Modality Compensation Transformer for Brain Tumor Segmentation'
firstpage: 1144
lastpage: 1162
page: 1144-1162
order: 1144
cycles: false
bibtex_author: Karimijafarbigloo, Sanaz and Azad, Reza and Kazerouni, Amirhossein
  and Ebadollahi, Saeed and Merhof, Dorit
author:
- given: Sanaz
  family: Karimijafarbigloo
- given: Reza
  family: Azad
- given: Amirhossein
  family: Kazerouni
- given: Saeed
  family: Ebadollahi
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
pdf: https://proceedings.mlr.press/v227/karimijafarbigloo24b/karimijafarbigloo24b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

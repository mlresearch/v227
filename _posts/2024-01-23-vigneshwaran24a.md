---
title: Improved multi-site Parkinson’s disease classification using neuroimaging data
  with counterfactual inference
abstract: 'Deep learning has led to many advances in medical image analysis for various
  clinical problems. However, most deep learning models are known to be sensitive
  to differences in the training and test data distributions, which can lead to a
  decrease in accuracy when applied in real-life scenarios. Thus far, various techniques
  have been developed to tackle this problem, primarily focusing on harmonizing feature
  representations from different datasets. Due to the recent increased interest in
  causal approaches in deep learning, explainable harmonization techniques have gained
  momentum lately but have not been applied broadly yet. Our study proposes a causal
  flow-based technique to overcome the problem of different feature distributions
  in multi-site data used for Parkinson’s disease (PD) classification. Feature distributions
  from six different sites, with a total of 415 subjects (PD: 263, healthy controls:
  152), were used for the experiments. A counterfactual approach to answer the question,
  How would brain MRI features appear if they were obtained at a different site?"
  was developed using a causal normalizing flow. When tested on features from a previously
  unseen site, the counterfactual-based classifier demonstrated superior performance
  (weighted f1 = 0.68) compared to a classifier trained on purely observational data
  (weighted f1 = 0.36) and improved accuracy compared to a harmonization technique
  typically used in neurological settings (weighted f1 = 0.5). These results show
  that the proposed technique can effectively correct differences in multi-site feature
  distributions to facilitate generalizable deep-learning models.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vigneshwaran24a
month: 0
tex_title: Improved multi-site Parkinson’s disease classification using neuroimaging
  data with counterfactual inference
firstpage: 1304
lastpage: 1317
page: 1304-1317
order: 1304
cycles: false
bibtex_author: Vigneshwaran, Vibujithan and Wilms, Matthias and Camacho, Milton Ivan
  Camacho and Souza, Raissa and Forkert, Nils
author:
- given: Vibujithan
  family: Vigneshwaran
- given: Matthias
  family: Wilms
- given: Milton Ivan Camacho
  family: Camacho
- given: Raissa
  family: Souza
- given: Nils
  family: Forkert
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
pdf: https://proceedings.mlr.press/v227/vigneshwaran24a/vigneshwaran24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

---
title: Towards Agnostic and Holistic Universal Image Segmentation with Bit Diffusion
openreview: C11afeqaV7
software: https://github.com/JakobLC/TowardsDiff
abstract: This paper introduces a diffusion-based framework for universal image segmentation,
  making agnostic segmentation possible without depending on mask-based frameworks
  and instead predicting the full segmentation in a holistic manner. We present several
  key adaptations to diffusion models, which are important in this discrete setting.
  Notably, we show that a location-aware palette with our 2D gray code ordering improves
  performance. Adding a final tanh activation function is crucial for discrete data.
  On optimizing diffusion parameters, the sigmoid loss weighting consistently outperforms
  alternatives, regardless of the prediction type used, and we settle on x-prediction.
  While our current model does not yet surpass leading mask-based architectures, it
  narrows the performance gap and introduces unique capabilities, such as principled
  ambiguity modeling, that these models lack. All models were trained from scratch,
  and we believe that combining our proposed improvements with large-scale pretraining
  or promptable conditioning could lead to competitive models.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: christensen26a
month: 0
tex_title: Towards Agnostic and Holistic Universal Image Segmentation with Bit Diffusion
firstpage: 49
lastpage: 56
page: 49-56
order: 49
cycles: false
bibtex_author: Christensen, Jakob L{\o}nborg and Hannemose, Morten Rieger and Dahl,
  Anders and Dahl, Vedrana Andersen
author:
- given: Jakob Lønborg
  family: Christensen
- given: Morten Rieger
  family: Hannemose
- given: Anders
  family: Dahl
- given: Vedrana Andersen
  family: Dahl
date: 2026-01-19
address:
container-title: Proceedings of the 7th Northern Lights Deep Learning Conference (NLDL)
volume: '307'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 1
  - 19
pdf: https://raw.githubusercontent.com/mlresearch/v307/main/assets/christensen26a/christensen26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

---
title: 'Extremal Contours: Gradient-driven contours for compact visual attribution'
openreview: EiX4I37Xmr
software: https://github.com/rezakarimzadeh/extremal-contours
abstract: "Faithful yet compact explanations for vision models remain a challenge,
  as commonly used dense perturbation masks are often fragmented and overfitted, needing
  careful post-processing.\r Here, we present a training-free explanation method that
  replaces dense masks with smooth tunable contours.\r A star-convex region is parameterized
  by a truncated Fourier series and optimized under an extremal preserve/delete objective
  using the classifier gradients.\r The approach guarantees a single, simply connected
  mask, cuts the number of free parameters by orders of magnitude, and yields stable
  boundary updates without cleanup.\r Restricting solutions to low-dimensional, smooth
  contours makes the method robust to adversarial masking artifacts.\r On ImageNet
  classifiers, it matches the extremal fidelity of dense masks while producing compact,
  interpretable regions with improved run-to-run consistency.\r Explicit area control
  also enables importance contour maps, yielding a transparent fidelity area profiles.\r
  Finally, we extend the approach to multi-contour and show how it can localize multiple
  objects within the same framework.\r Across benchmarks, the method achieves higher
  relevance mass and lower complexity than gradient and perturbation based baselines,
  with especially strong gains on self-supervised DINO models where it improves relevance
  mass by over 15% and maintains positive faithfulness correlations."
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karimzadeh26a
month: 0
tex_title: 'Extremal Contours: Gradient-driven contours for compact visual attribution'
firstpage: 201
lastpage: 210
page: 201-210
order: 201
cycles: false
bibtex_author: Karimzadeh, Reza and Alonso, Albert and Zdyb, Frans and Kirkegaard,
  Julius B. and Ibragimov, Bulat
author:
- given: Reza
  family: Karimzadeh
- given: Albert
  family: Alonso
- given: Frans
  family: Zdyb
- given: Julius B.
  family: Kirkegaard
- given: Bulat
  family: Ibragimov
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
pdf: https://raw.githubusercontent.com/mlresearch/v307/main/assets/karimzadeh26a/karimzadeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

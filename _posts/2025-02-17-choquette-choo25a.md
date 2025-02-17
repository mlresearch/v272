---
title: Near-Optimal Rates for O(1)-Smooth DP-SCO with a Single Epoch and Large Batches
abstract: 'In this paper we revisit the DP stochastic convex optimization (SCO) problem.
  For convex smooth losses, it is well-known that the canonical DP-SGD (stochastic
  gradient descent) achieves the optimal rate of $O\left(\frac{LR}{\sqrt{n}} + \frac{LR
  \sqrt{p \log(1/\delta)}}{\epsilon n}\right)$ under $(\epsilon, \delta)$-DP (Bassily
  et al. 2014), and also well-known that variants of DP-SGD can achieve the optimal
  rate in a single epoch (Feldman et al. 2019). However, the batch gradient complexity
  (i.e., number of adaptive optimization steps), which is important in applications
  like federated learning, is less well-understood. In particular, all prior work
  on DP-SCO requires $\Omega(n)$ batch gradient steps, multiple epochs, or convexity
  for privacy. We propose an algorithm, Accelerated-DP-SRGD (stochastic recursive
  gradient descent), which bypasses the limitations of past work: it achieves the
  optimal rate for DP-SCO (up to polylog factors), in a single epoch using  $\sqrt{n}$
  batch gradient steps with batch size $\sqrt{n}$, and can be made private for arbitrary
  (non-convex) losses via clipping. If the global minimizer is in the constraint set,
  we can further improve this to $n^{1/4}$ batch gradient steps with batch size $n^{3/4}$.
  To achieve this, our algorithm combines three key ingredients, a variant of stochastic
  recursive gradients (SRG), accelerated gradient descent, and correlated noise generation
  from DP continual counting.'
openreview: nIBYq3O2HG
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: choquette-choo25a
month: 0
tex_title: Near-Optimal Rates for O(1)-Smooth DP-SCO with a Single Epoch and Large
  Batches
firstpage: 315
lastpage: 348
page: 315-348
order: 315
cycles: false
bibtex_author: Choquette-Choo, Christopher A. and Ganesh, Arun and Thakurta, Abhradeep
  Guha
author:
- given: Christopher A.
  family: Choquette-Choo
- given: Arun
  family: Ganesh
- given: Abhradeep Guha
  family: Thakurta
date: 2025-02-17
address:
container-title: Proceedings of The 36th International Conference on Algorithmic Learning
  Theory
volume: '272'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 2
  - 17
pdf: https://raw.githubusercontent.com/mlresearch/v272/main/assets/choquette-choo25a/choquette-choo25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

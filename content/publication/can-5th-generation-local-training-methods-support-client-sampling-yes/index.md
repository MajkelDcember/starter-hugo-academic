---
title: Can 5th Generation Local Training Methods Support Client Sampling? Yes!
subtitle: ""
publication_types:
  - "1"
authors:
  - Michał Grudzień
  - Grigory Malinovsky
  - Peter Richtárik
doi: ""
publication: Proceedings of The 26th International Conference on Artificial
  Intelligence and Statistics
publication_short: https://proceedings.mlr.press/v206/grudzien23a/grudzien23a.pdf
abstract: "he celebrated FedAvg algorithm of McMahan et al.(2017) is based on
  three components: client sampling (CS), data sampling (DS) and local training
  (LT). While the first two are reasonably well understood, the third component,
  whose role is to reduce the number of communication rounds needed to train the
  model, resisted all attempts at a satisfactory theoretical explanation.
  Malinovsky et al.(2022) identified four distinct generations of LT methods
  based on the quality of the provided theoretical communication complexity
  guarantees. Despite a lot of progress in this area, none of the existing works
  were able to show that it is theoretically better to employ multiple local
  gradient-type steps (ie, to engage in LT) than to rely on a single local
  gradient-type step only in the important heterogeneous data regime. In a
  recent breakthrough embodied in their ProxSkip method and its theoretical
  analysis, Mishchenko et al.(2022) showed that LT indeed leads to provable
  communication acceleration for arbitrarily heterogeneous data, thus
  jump-starting the 5th generation of LT methods. However, while these latest
  generation LT methods are compatible with DS, none of them support CS. We
  resolve this open problem in the affirmative. In order to do so, we had to
  base our algorithmic development on new algorithmic and theoretical
  foundations."
draft: false
featured: false
tags: []
image:
  filename: ""
  focal_point: ""
  preview_only: false
date: 2023-06-28T08:11:41.228Z
---

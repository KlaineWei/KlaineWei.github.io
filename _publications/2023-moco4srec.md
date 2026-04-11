---
title: "MoCo4SRec: A Momentum Contrastive Learning Framework for Sequential Recommendation"
collection: publications
category: manuscripts
permalink: /publication/2023-moco4srec
date: 2023-08-01
venue: 'Expert Systems with Applications'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0957417423004128'
doi: '10.1016/j.eswa.2023.119911'
code: 'https://github.com/KlaineWei/MoCo4SRec'
citation: 'Z. Wei, N. Wu, F. Li, K. Wang, W. Zhang. (2023). &quot;MoCo4SRec: A Momentum Contrastive Learning Framework for Sequential Recommendation.&quot; <i>Expert Systems with Applications</i>, 223, 119911.'
header:
  teaser: publications/moco4srec.png
bibtex: |
  @article{wei2023moco4srec,
    title   = {MoCo4SRec: A Momentum Contrastive Learning Framework for Sequential Recommendation},
    author  = {Wei, Zihan and Wu, Ning and Li, Fengxia and Wang, Ke and Zhang, Wei},
    journal = {Expert Systems with Applications},
    volume  = {223},
    pages   = {119911},
    year    = {2023},
    doi     = {10.1016/j.eswa.2023.119911},
  }
---

## Abstract

Contrastive self-supervised learning has shown promise for sequential recommendation, but existing approaches suffer from data sparsity, noisy user behaviors, and sampling bias — particularly false negatives that hurt representation quality. We propose **MoCo4SRec**, a momentum contrastive learning framework that adapts MoCo-style training to sequential recommendation. MoCo4SRec maintains a **dynamic queue of negatives** updated by a **momentum-averaged encoder**, enabling large and consistent negative pools without expensive batch scaling. We introduce two-level (sequence-level and embedding-level) augmentations for robust contrast, and design an **instance weighting** mechanism that penalizes likely false negatives in the queue. Training jointly optimizes the recommendation objective, a standard contrastive objective, and the momentum contrastive objective. Across eight real-world datasets, MoCo4SRec yields consistent improvements over competitive sequential-recommendation baselines.

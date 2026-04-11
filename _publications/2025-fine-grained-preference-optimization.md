---
title: "Fine-Grained Preference Optimization with Differentiated Token Weighting for LLM-based Recommendations"
collection: publications
category: manuscripts
permalink: /publication/2025-fine-grained-preference-optimization
date: 2026-01-03
venue: 'Knowledge-Based Systems'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S095070512501843X'
doi: '10.1016/j.knosys.2025.114805'
citation: 'Z. Wei, Q. Zhang, F. Li, K. Wang. (2025). &quot;Fine-Grained Preference Optimization with Differentiated Token Weighting for LLM-based Recommendations.&quot; <i>Knowledge-Based Systems</i>, 114805.'
header:
  teaser: publications/fgpo.png
bibtex: |
  @article{wei2026fgpo,
    title   = {Fine-Grained Preference Optimization with Differentiated Token Weighting for LLM-based Recommendations},
    author  = {Wei, Zihan and Zhang, Qi and Li, Fengxia and Wang, Ke},
    journal = {Knowledge-Based Systems},
    volume  = {331},
    pages   = {114805},
    year    = {2026},
    doi     = {10.1016/j.knosys.2025.114805},
  }
---

## Abstract

Existing preference optimization methods for LLM-based recommendation systems typically treat each candidate response as a single unit, overlooking the fact that LLMs generate output token by token. This coarse-grained view limits their effectiveness when aligning recommendation models with user preferences. We propose **Fine-Grained Preference Optimization (FGPO)**, which operates at the token level: a lightweight network assigns differentiated importance weights to tokens based on their contribution to user preferences, and multiple negative samples are incorporated to provide richer contrastive learning signals. FGPO is instantiated in two variants, **FGDPO** and **FGSimPO**, built on top of DPO and SimPO respectively. Experiments on three public benchmarks show that both variants consistently outperform prior preference-optimization baselines, confirming the value of fine-grained token-level alignment for LLM-based recommendation.

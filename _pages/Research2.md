---
title: "Research Experience"
layout: single
permalink: /research2/
author_profile: true
---



## Research Line I: Out-of-Distribution Detection  
**When should a model abstain?**

### Out-of-Distribution Detection via Self-Supervised Geometry Learning  
Related: [[arXiv]](https://arxiv.org/abs/2511.13539)

- **Problem.** Existing OOD detection methods often rely on external outlier data or lack explicit geometric separation between in-distribution and OOD samples.
- **Method.** Proposed a self-supervised OOD training framework guided by Neural Collapse, combining geometry-aware regularization with feature-space pseudo-OOD generation.
- **Contribution.** Enabled effective OOD detection without external outliers while explicitly shaping feature norm and angular geometry, achieving consistent improvements over strong post-hoc and outlier-free baselines.



## Research Line II: Out-of-Distribution Generalization  
**When can a model generalize reliably?**

### Distributionally Robust Invariant Learning for OOD Generalization  
Related: [[arXiv]](https://arxiv.org/abs/2511.13539)

- **Problem.** Invariant learning methods mitigate correlation shift but remain vulnerable to diversity shift and support mismatch under severe OOD settings.
- **Method.** Unified invariant risk minimization with sample-level Distributionally Robust Optimization (DRO) via a learnable adversarial reweighting mechanism.
- **Contribution.** Formulated a primal–dual–adversarial training objective that improves worst-case generalization across both classification and regression benchmarks.

### Out-of-Distribution Generalization for Invariant Risk Minimization  
Related: [[ICLR 2025 Poster]](https://iclr.cc/virtual/2025/poster/29073)

- **Problem.** Fixed regularization strength in IRM-based methods limits adaptability across heterogeneous environments.
- **Method.** Introduced an autonomous Total Variation penalty optimized through a minimax adversarial learning scheme.
- **Contribution.** Improved both average and worst-case OOD generalization over IRM-TV baselines on multiple simulated and real-world datasets.



## Early Research Projects

### Learning Attention Behaviors with Decision Trees  
Related: [[arXiv]](https://arxiv.org/pdf/2110.03879)

- **Focus.** Interpreting temporal dynamics of attention mechanisms in end-to-end speech recognition models.
- **Contribution.** Provided an early, model-agnostic analysis of attention behavior using decision trees, revealing strong temporal dependence and high predictability of attention states.

### Modular Cross-lingual Speech-to-Text Framework

- **Focus.** Cross-lingual speech recognition under structural and phonetic mismatch.
- **Contribution.** Designed a modular attention-based alignment framework and constructed an early Mandarin-to-English speech-to-text benchmark with improved efficiency and accuracy.


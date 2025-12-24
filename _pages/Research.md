---
title: "Research Experience"
layout: single
permalink: /research/
author_profile: true
---



### Out-of-Distribution Detection via Self-Supervised Geometry Learning
Related: [[arXiv PDF]](https://arxiv.org/abs/2511.13539))

- **Neural-Collapse-guided training framework.** Built a two-phase OOD detection pipeline: (i) train an in-distribution classifier (e.g., ResNet-18) to reach stable collapsed geometry, then (ii) apply geometry-aware regularization at the feature level for OOD separation.
- **Self-supervised pseudo-OOD generation without external data.** Proposed a feature-space pseudo-OOD strategy using class-wise mixup with \( \lambda \sim \mathrm{Beta}(\alpha,\alpha) \) to generate challenging near-OOD samples while avoiding decision-boundary distortion.
- **Radius-based and directional feature regularization.** Introduced joint feature-norm shaping via K-bin radius classification/regression with a fractional margin, plus directional separation loss that discourages pseudo-OOD features from aligning with class prototypes.



### Distributionally Robust Invariant Learning for OOD Generalization
Related: [[arXiv PDF]](https://arxiv.org/abs/2511.13539))

- **Unified OOD view via DRO and invariant learning.** Extended an OOD-TV-IRM style framework by integrating sample-level distributionally robust optimization (DRO) to address both correlation shift (invariance) and diversity shift (adversarial reweighting).
- **Sample-level adversarial reweighting.** Designed a learnable sample adversary to upweight high-loss and underrepresented samples, approximating worst-case risk under constrained distributional neighborhoods.
- **Primal–dual–adversarial optimization.** Formulated training as a one-vs-two min–max objective: optimizing the invariant feature extractor against (i) a dual network enforcing TV-based invariance and (ii) a DRO-based sample adversary.
- **Empirical validation.** Evaluated on multiple benchmark datasets (classification + regression) and observed improvements in worst-case performance under challenging OOD settings.



### Out-of-distribution Generalization for Invariant Risk Minimization
Related: [[ICLR 2025 Poster]](https://iclr.cc/virtual/2025/poster/29073)

- **Autonomous TV penalty.** Proposed an autonomous total-variation penalty whose strength adapts to the invariant feature extractor parameters, improving robustness across environments.
- **Adversarial learning scheme.** Developed a minimax-style alternating optimization between feature extractor and TV penalty parameters.
- **Evaluation.** Demonstrated improvements over IRM-TV baselines on simulated and real-world OOD benchmarks, with gains in average and worst-case accuracy.


### Supply Chain Optimization Using Machine Learning Techniques

- Built ML models for logistics/warehouse operations, including risk identification for shipments and user segmentation based on delivery preferences.
- Collected and cleaned multi-source datasets (transportation data, traffic/closure alerts, manufacturer production records) and performed feature engineering.
- Developed CNN/LSTM forecasting models and compared against ARIMA/ETS, reporting improvements in delivery accuracy and reduced forecasting error and logistics cost.



### Learning Attention Behaviors with Decision Trees
Related: [[arXiv PDF]](https://arxiv.org/pdf/2110.03879)

- Studied attention behavior in speech recognition via decision-tree-based analysis of attention states.
- Found that current attention is strongly influenced by the previous four attention states rather than encoder–decoder configuration.
- Trained a decision tree predictor achieving >80% accuracy for attention level prediction.



### Modular Cross-lingual Speech-to-text Framework

- Proposed a modular cross-lingual speech-to-text framework with attention-based sequence alignment to handle cross-language expression variance.
- Incorporated tonal information into Chinese Pinyin phoneme modeling, yielding a compact 212-phoneme set; accelerated training and improved accuracy.
- Constructed an early benchmark dataset for Chinese speech-to-English conversion

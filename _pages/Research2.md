---
title: "Research Experience"
layout: single
permalink: /research2/
author_profile: true
---

## Research Line I: Out-of-Distribution Detection  
**When should a model abstain?**

<div style="display:flex; gap:1.5em; align-items:flex-start; margin-bottom:2.2em;">

  <div style="flex:0 0 32%;">
    <img src="/images/Research/BootOOD.jpg"
         alt="OOD Detection via Self-Supervised Geometry Learning"
         style="width:100%; border-radius:8px;">
  </div>

  <div style="flex:1;">
    <h3 style="margin-top:0;">Out-of-Distribution Detection via Self-Supervised Geometry Learning</h3>
    <p>Related: <a href="https://arxiv.org/abs/2511.13539">arXiv</a></p>
    <ul>
      <li><strong>Problem.</strong> Existing OOD detection methods often rely on external outlier data or lack explicit geometric separation between in-distribution and OOD samples.</li>
      <li><strong>Method.</strong> Proposed a self-supervised OOD training framework guided by Neural Collapse, combining geometry-aware regularization with feature-space pseudo-OOD generation.</li>
      <li><strong>Contribution.</strong> Enabled effective OOD detection without external outliers while explicitly shaping feature norm and angular geometry, achieving consistent improvements over strong post-hoc and outlier-free baselines.</li>
    </ul>
  </div>

</div>

---

## Research Line II: Out-of-Distribution Generalization  
**When can a model generalize reliably?**

<div style="display:flex; gap:1.5em; align-items:flex-start; margin-bottom:2.2em;">

  <div style="flex:0 0 32%;">
    <img src="/images/Research/2026.jpg"
         alt="Distributionally Robust Invariant Learning"
         style="width:100%; border-radius:8px;">
  </div>

  <div style="flex:1;">
    <h3 style="margin-top:0;">Distributionally Robust Invariant Learning for OOD Generalization</h3>
    <p>Related: <a href="https://arxiv.org/abs/2511.13539">arXiv</a></p>
    <ul>
      <li><strong>Problem.</strong> Invariant learning methods mitigate correlation shift but remain vulnerable to diversity shift and support mismatch under severe OOD settings.</li>
      <li><strong>Method.</strong> Unified invariant risk minimization with sample-level Distributionally Robust Optimization (DRO) via a learnable adversarial reweighting mechanism.</li>
      <li><strong>Contribution.</strong> Formulated a primal–dual–adversarial training objective that improves worst-case generalization across both classification and regression benchmarks.</li>
    </ul>
  </div>

</div>

<div style="display:flex; gap:1.5em; align-items:flex-start; margin-bottom:2.2em;">

  <div style="flex:0 0 32%;">
    <img src="/images/Research/2025.jpg"
         alt="Invariant Risk Minimization under OOD"
         style="width:100%; border-radius:8px;">
  </div>

  <div style="flex:1;">
    <h3 style="margin-top:0;">Out-of-Distribution Generalization for Invariant Risk Minimization</h3>
    <p>Related: <a href="https://iclr.cc/virtual/2025/poster/29073">ICLR 2025 Poster</a></p>
    <ul>
      <li><strong>Problem.</strong> Fixed regularization strength in IRM-based methods limits adaptability across heterogeneous environments.</li>
      <li><strong>Method.</strong> Introduced an autonomous Total Variation penalty optimized through a minimax adversarial learning scheme.</li>
      <li><strong>Contribution.</strong> Improved both average and worst-case OOD generalization over IRM-TV baselines on multiple simulated and real-world datasets.</li>
    </ul>
  </div>

</div>

---

## Early Research Projects

<div style="display:flex; gap:1.5em; align-items:flex-start; margin-bottom:2.2em;">

  <div style="flex:0 0 32%;">
    <img src="/images/Research/Tree.jpg"
         alt="Learning Attention Behaviors with Decision Trees"
         style="width:100%; border-radius:8px;">
  </div>

  <div style="flex:1;">
    <h3 style="margin-top:0;">Learning Attention Behaviors with Decision Trees</h3>
    <p>Related: <a href="https://arxiv.org/pdf/2110.03879">arXiv</a></p>
    <ul>
      <li><strong>Focus.</strong> Interpreting temporal dynamics of attention mechanisms in end-to-end speech recognition models.</li>
      <li><strong>Contribution.</strong> Provided an early, model-agnostic analysis of attention behavior using decision trees, revealing strong temporal dependence and high predictability of attention states.</li>
    </ul>
  </div>

</div>

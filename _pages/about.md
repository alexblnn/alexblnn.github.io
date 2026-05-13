---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="intro-block">
  <p>
    I am a Research Scientist at <a href="https://www.surge.care">SurgeCare</a>, a spinoff from
    <a href="https://gaudillierelab.stanford.edu">Brice Gaudillière's lab</a> at Stanford University.
    I'm working on building <strong>ImmuneMind</strong>, a foundation model trained on billions of single cells,
    and developing interpretability methods for biomarker discovery.
  </p>
  <p>
    I previously studied at <a href="https://www.ensae.fr/en">ENSAE Paris</a> and completed the
    <a href="https://www.master-mva.com/">Master MVA</a> (Mathematics, Vision and Learning)
    at <a href="https://ens-paris-saclay.fr/en">École Normale Supérieure Paris-Saclay</a>.
  </p>
  <p>
    I hold a PhD in Machine Learning and Statistics from
    <a href="https://team.inria.fr/parietal/">INRIA Parietal</a>, advised by
    <a href="https://pages.saclay.inria.fr/bertrand.thirion/">Bertrand Thirion</a> and
    <a href="https://www.math.univ-toulouse.fr/~pneuvial/">Pierre Neuvial</a>.
    I am interested in interpretability and foundation models for healthcare data (clinical and biological).
  </p>
</div>

---

## Updates

<ul class="update-list">
  <li class="update-item">
    <span class="update-date">Feb 2026</span>
    <span class="update-dot"></span>
    <span class="update-text"><a href="https://www.entreprises.gouv.fr/la-dge/actualites/appel-projets-pionniers-de-lia-les-23-premiers-laureats-connus">ImmuneMind awarded the AI Trailblazer Grant</a> as part of the France 2030 plan!</span>
  </li>
  <li class="update-item">
    <span class="update-date">May 2025</span>
    <span class="update-dot"></span>
    <span class="update-text"><em>False Coverage Proportion control for Conformal Prediction</em> accepted at <strong>ICML 2025</strong>.</span>
  </li>
  <li class="update-item">
    <span class="update-date">Jan 2025</span>
    <span class="update-dot"></span>
    <span class="update-text">Excited to join <strong>SurgeCare</strong> as Research Scientist. I will be working on foundation models for single-cell cytometry data!</span>
  </li>
  <li class="update-item">
    <span class="update-date">Dec 2024</span>
    <span class="update-dot"></span>
    <span class="update-text">Successfully defended my <a href="https://theses.hal.science/tel-04935172">PhD thesis</a> in Machine Learning and Statistics at INRIA.</span>
  </li>
  <li class="update-item">
    <span class="update-date">May 2024</span>
    <span class="update-dot"></span>
    <span class="update-text">New preprint — <em>When Knockoffs fail: diagnosing and fixing non-exchangeability of Knockoffs</em>.</span>
  </li>
  <li class="update-item">
    <span class="update-date">Dec 2023</span>
    <span class="update-dot"></span>
    <span class="update-text"><em>False Discovery Proportion control for aggregated Knockoffs</em> accepted at <strong>NeurIPS 2023</strong>.</span>
  </li>
</ul>

---

## Publications

<div class="pub-entry">
  <div class="pub-title">
    False Coverage Proportion control for Conformal Prediction
    <span class="venue-badge venue-icml">ICML 2025</span>
  </div>
  <div class="pub-authors">A. Blain, B. Thirion, P. Neuvial</div>
  <div class="pub-desc">Distribution-free uncertainty quantification with improved statistical guarantees, applicable to any black-box model including neural networks.</div>
  <div class="pub-links">
    <a href="https://proceedings.mlr.press/v267/blain25a.html">Paper</a> &middot;
    <a href="https://github.com/alexblnn/CoJER">Code</a>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-title">
    When Knockoffs fail: diagnosing and fixing non-exchangeability of Knockoffs
    <span class="venue-badge venue-preprint">Preprint</span>
  </div>
  <div class="pub-authors">A. Blain, A. Reyero Lobo, J. Linhart, B. Thirion, P. Neuvial</div>
  <div class="pub-desc">A diagnostic tool based on Classifier Two-Sample Tests that detects violations of the knockoff exchangeability assumption — which cause massive false positive inflation — and an alternative construction that restores error control.</div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2407.06892">arXiv</a>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-title">
    False Discovery Proportion control for aggregated Knockoffs
    <span class="venue-badge venue-neurips">NeurIPS 2023</span>
  </div>
  <div class="pub-authors">A. Blain, B. Thirion, O. Grisel, P. Neuvial</div>
  <div class="pub-desc">Controls the actual proportion of false discoveries (FDP) — beyond the usual FDR guarantee — for Knockoff-based variable selection in high dimension, with a new aggregation scheme that removes the randomness of classical Knockoff inference. Demonstrated on brain imaging and genomic data.</div>
  <div class="pub-links">
    <a href="https://neurips.cc/virtual/2023/poster/70300">Paper</a> &middot;
    <a href="https://arxiv.org/abs/2310.10373">arXiv</a> &middot;
    <a href="https://github.com/alexblnn/KOPI">Code</a>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-title">
    Notip: Non-parametric True Discovery Proportion control for brain imaging
    <span class="venue-badge venue-journal">NeuroImage</span>
  </div>
  <div class="pub-authors">A. Blain, B. Thirion, P. Neuvial</div>
  <div class="pub-desc">Distribution-free method for detecting statistically significant activations in high-dimensional data, with applications to fMRI. Oral at OHBM 2022 and MCP 2022.</div>
  <div class="pub-links">
    <a href="https://doi.org/10.1016/j.neuroimage.2022.119492">Full text</a> &middot;
    <a href="https://github.com/alexblnn/Notip">Code</a>
  </div>
</div>

---

## Software

<div class="software-grid">
  <a class="software-item" href="https://github.com/alexblnn/Notip">
    <div class="software-name">Notip</div>
    <div class="software-desc">Non-parametric True Discovery Proportion control for brain imaging.</div>
  </a>
  <a class="software-item" href="https://github.com/alexblnn/KOPI">
    <div class="software-name">KOPI</div>
    <div class="software-desc">Knockoffs with FDP control and derandomization.</div>
  </a>
  <a class="software-item" href="https://github.com/pneuvial/sanssouci.python">
    <div class="software-name">sanssouci.python</div>
    <div class="software-desc">Python implementation of the SansSouci post-hoc inference framework.</div>
  </a>
</div>

---

## Selected Talks

- **False Discovery Proportion control for aggregated Knockoffs**, November 2023, [INRIA Parietal](https://team.inria.fr/parietal/) team meeting, Paris
- **False Discovery Proportion control for aggregated Knockoffs**, September 2023, [ANR Fast-Big workshop](https://project.inria.fr/fastbig/stats-workshop-october-19th-2023/) @ [Institut Henri Poincaré](http://www.ihp.fr/en), Paris
- **Notip**, December 2022, [International Seminar on Selective Inference](https://www.selectiveinferenceseminar.com/) *(organized by E. Candès' group, Stanford)*
- **Notip**, August 2022, [MCP Conference](https://www.mcp-conference.org/), Bremen, Germany *(oral)*
- **Notip**, June 2022, [OHBM 2022](https://www.humanbrainmapping.org/) *(oral)*

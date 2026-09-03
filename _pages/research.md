---
title: Research
permalink: /research/
---

# Research

My research asks how **geochemical, geological, spatial, and remote-sensing evidence can be converted into robust mineral-exploration inference without losing geological meaning**.

The central themes are mineral-system discrimination, geochemical intelligence, prospectivity, interpretable machine learning, uncertainty, and reproducible scientific software.

## Selected research impact

<div class="metric-grid">
  <div class="metric-card"><strong>5,200+ analyses</strong><span>Global pyrite dataset spanning 138 deposits and multiple ore systems.</span></div>
  <div class="metric-card"><strong>AUC &gt; 0.99</strong><span>Reported in selected pyrite discrimination workflows under project-specific validation.</span></div>
  <div class="metric-card"><strong>37 Pb-Zn deposits</strong><span>Galena geochemistry evaluated using RF, GB, MLP, and SVM workflows.</span></div>
  <div class="metric-card"><strong>43 global locations</strong><span>Sedimentary pyrite tectonic-setting research using CNN/XGBoost and interpretable analysis.</span></div>
</div>

<div class="notice">Performance values are study-specific validation results, not universal model guarantees. Their interpretation depends on cohort definition, validation design, label quality, feature availability, and transfer domain.</div>

## Research directions

### 1. Mineral geochemistry & metallogenic discrimination

Global and deposit-scale pyrite, galena, and sphalerite geochemistry are used to test whether mineral chemistry retains reproducible information about ore system, tectonic environment, mineralization style, and critical-metal enrichment.

Methods include LA-ICP-MS trace elements, S-Pb isotopes, geochemical ratios, deposit-aware labels, imbalance treatment, and geological interpretation.

### 2. GeoAI & interpretable machine learning

I use Random Forest, XGBoost, SVM, gradient boosting, MLP/CNN workflows, clustering, PCA, t-SNE/UMAP, Isolation Forest, SHAP, LIME, and related methods where scientifically justified.

The main emphasis is not algorithm novelty by itself, but **defensible validation and geological interpretability**.

### 3. Geochemical anomaly intelligence

Research and professional R&D include multivariate anomaly detection, correlation structure, outlier diagnostics, clustering, manifold learning, anomaly scores, spatial confidence, threshold sensitivity, and target ranking.

### 4. Mineral prospectivity & multimodal evidence integration

I work with geological, geochemical, geophysical, structural, terrain, remote-sensing, field, trench, drilling, and uncertainty evidence. These inputs are integrated for prospect screening and decision support while retaining provenance and spatial context.

### 5. Geostatistics & spatial uncertainty

Work includes variography, kriging, sequential Gaussian simulation, uncertainty products, spatial validation, target sensitivity, and GPU/CUDA-oriented experimentation for scalable simulation workflows.

## Validation principles

My preferred scientific controls include:

- group-aware or deposit-aware validation where observations are clustered by site;
- spatial or geological validation where random splitting would leak context;
- strict separation of training, threshold selection, calibration, and holdout evaluation;
- sensitivity analysis for thresholds, cohorts, missing data, outliers, and feature choices;
- external or prospective validation where feasible;
- explicit separation of prediction, association, interpretation, and causal claims;
- reporting of failure, instability, non-transferability, and negative results.

## Computational methods

<div class="tag-list">
<span class="tag">Python</span><span class="tag">scikit-learn</span><span class="tag">XGBoost</span><span class="tag">PyTorch/CUDA</span><span class="tag">Random Forest</span><span class="tag">SVM</span><span class="tag">MLP/CNN</span><span class="tag">SHAP</span><span class="tag">LIME</span><span class="tag">PCA</span><span class="tag">t-SNE</span><span class="tag">UMAP</span><span class="tag">Isolation Forest</span><span class="tag">SMOTE/RUC</span><span class="tag">LOGO CV</span><span class="tag">GIS</span><span class="tag">Remote sensing</span><span class="tag">Geostatistics</span>
</div>

## Research outputs

See [Publications](/publications/) for selected papers and [Projects](/projects/) for public repositories and professional R&D summaries.

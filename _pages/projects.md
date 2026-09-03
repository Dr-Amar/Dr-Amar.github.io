---
title: Projects
permalink: /projects/
description: "Research repositories and selected GeoAI R&D by Dr. Muhammad Amar Gul, spanning mineral geochemistry, metallogenic discrimination, anomaly intelligence, prospectivity, remote sensing, target detection, and geostatistics."
---

# Projects

This portfolio separates **intentionally public research** from **professional or proprietary R&D**. Public projects link to released code, figures, workflows, or research assets. Professional systems are described at capability level only unless ownership and release permissions are explicit.

## Public research portfolio

### Artificial intelligence-driven metallogenic typing of pyrite

**Type:** Published research · public-safe repository  
**Publication:** *Journal of Geochemical Exploration* (2026), 289, 108138  
**Scale:** ~5,200 pyrite analyses · 138 global deposits/settings · six ore-system classes  
**Methods:** RF, SVM, gradient boosting, MLP, class-balance experiments, blind testing, deposit-scale LOGO validation, feature/permutation importance, t-SNE  
**Public release:** notebooks, figures, workflow documentation, reproducibility notes, citation metadata; full compiled global dataset is not publicly released

This project tests whether multielement pyrite geochemistry can discriminate major metallogenic environments more reliably than conventional low-dimensional discrimination diagrams. A key methodological component is **deposit-scale validation**, designed to reduce optimistic performance from splitting analyses from the same deposit across training and testing.

[Repository](https://github.com/Dr-Amar/Pyrite-AI-metallogenic-typing) · [DOI](https://doi.org/10.1016/j.gexplo.2026.108138)

### Big-data galena geochemistry for metallogenic discrimination

**Type:** Published research · public repository  
**Publication:** *Mathematical Geosciences* (2026), Early Access  
**Scale:** galena from 37 Pb-Zn deposits and multiple metallogenic classes  
**Methods:** Random Forest, Gradient Boosting, MLP, SVM, standardization, SMOTE, undersampling experiments, blind testing, cross-validation, feature importance, t-SNE  
**Public release:** model notebooks, figures, reproducible workflow; the publisher-protected article is not distributed through the repository

This study evaluates how far galena trace-element chemistry can support data-driven metallogenic classification and which elements contribute most strongly to discrimination across deposit classes.

[Repository](https://github.com/Dr-Amar/Galena-Geochemistry-ML-Metallogenic-Discrimination) · [DOI](https://doi.org/10.1007/s11004-026-10274-0)

### Gunga Pb-Zn pyrite machine learning

**Type:** Published research · public repository  
**Publication:** *Journal of Geochemical Exploration* (2025)  
**Scientific scope:** pyrite trace elements + S-Pb isotopes + global comparison data  
**Methods:** RF, GB, SVM, MLP, deposit-aware/LOGO validation, geochemical and isotopic interpretation  
**Purpose:** test Pb-Zn mineralization and geological-class discrimination while retaining deposit-level geological context

The project connects local Gunga mineral chemistry and isotope data with broader global pyrite patterns to evaluate metallogenic interpretation using both geochemical evidence and machine learning.

[Repository](https://github.com/Dr-Amar/Pyrite-Gunga-Pb-Zn-Deposit--Machine-Learning) · [DOI](https://doi.org/10.1016/j.gexplo.2025.107693)

### Gunga sphalerite deep learning & critical-metal research

**Type:** Published research · public repository  
**Publication:** *Journal of Geochemical Exploration* (2025)  
**Scientific scope:** sphalerite geochemistry, S-Pb isotopes, ore-genesis interpretation, critical-metal enrichment  
**Methods:** deep neural networks, global Pb-Zn comparison data, mineral chemistry, isotope constraints, geological interpretation  
**Purpose:** evaluate mineralization style and critical-metal signals, including Ge-bearing sphalerite

This work combines predictive classification with geochemical and isotopic constraints; model output is treated as one line of evidence rather than a substitute for geological interpretation.

[Repository](https://github.com/Dr-Amar/Sphalerite-Gunga-Pb-Zn-DeepLearning) · [DOI](https://doi.org/10.1016/j.gexplo.2025.107771)

<div class="notice"><strong>Repository quality note:</strong> public repositories are research artifacts, not commercial exploration products. Dataset availability, licensing, publisher copyright, and reproducibility boundaries should be read from each repository before reuse.</div>

## Selected professional & computational R&D

### GeoAnomalyAI

**Status:** Active professional R&D · non-public implementation  
**Role:** research-to-product design and scientific validation  
**Problem:** multivariate anomaly intelligence for exploration geochemistry  
**Capabilities:** correlation structure, robust outlier diagnostics, clustering, manifold learning, Isolation Forest-style scoring, spatial confidence, threshold sensitivity, anomaly ranking, and map/target QA

The system is designed to move beyond single-element thresholding toward multivariate, spatially defensible anomaly evidence. Public descriptions intentionally exclude proprietary implementation and client data.

### GeoSpectraAI

**Status:** Active professional R&D · non-public implementation  
**Problem:** multimodal prospectivity screening and evidence integration  
**Evidence types:** remote-sensing/spectral, geological, geochemical, lithological, structural, field, and spatial information  
**Scientific emphasis:** provenance, mineral-system logic, transfer testing, uncertainty, and confidence assessment

GeoSpectraAI is intended to connect remote-sensing and geochemical evidence with geological reasoning rather than treat spectral or ML outputs as stand-alone targets.

### Target detection & spatial decision support

**Status:** Operational / professional R&D · non-public implementation  
**Problem:** translate cleaned exploration data and model outputs into ranked, field-usable targets  
**Capabilities:** geochemical evidence, target ranking, uncertainty products, geostatistical outputs, spatial validation, map QA, batch execution, and reproducible field deliverables

### Geostatistical & GPU R&D

**Status:** Active computational R&D  
**Problem:** scalable spatial uncertainty analysis for mineral exploration  
**Methods:** variography, kriging, sequential Gaussian simulation, uncertainty summaries, sensitivity analysis, Python implementation, and CUDA/GPU experimentation

The focus is not GPU acceleration by itself; acceleration is useful only where deterministic geometry, statistical equivalence, and uncertainty outputs remain validated.

## Exploration applications

### Saudi Arabia — Arabian Shield

**Work:** mineral-potential modelling, exploration-screening workflows, target ranking, remote sensing, geological interpretation, and integrated geochemical, geophysical, structural, lithological, and spectral evidence.

**Decision context:** regional prospectivity, licensing/technical screening, target prioritization, and management-ready exploration outputs.

### Mauritania — Sahara Gold

**Work:** AI-assisted gold targeting using soil geochemistry, remote sensing, geology, anomaly detection, spatial confidence, trench/drill evidence, target ranking, and report automation.

**Decision context:** evaluate whether multi-source evidence supports specific follow-up targets rather than treating anomaly scores as sufficient evidence on their own.

### Tanzania — Mpanda-Mbozi-Karema

**Work:** multi-element QA/QC, sample-type interpretation, detection-limit and outlier review, spatial-pattern analysis, anomaly confidence, and target-consistency checks.

**Decision context:** determine which geochemical patterns remain credible after analytical, sampling, and spatial-context checks.

> **IP and release boundary:** proprietary employer, client, or collaboration code, source data, internal thresholds, target coordinates, and unpublished datasets are not made public here unless release is explicitly authorized.

## Related pages

[Research](/research/) explains the scientific questions and validation philosophy behind these projects. [Publications](/publications/) provides the associated peer-reviewed record, while [GitHub](https://github.com/Dr-Amar) contains intentionally released research artifacts.

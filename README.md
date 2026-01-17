# Effects of NMDA antagonists on social behavior: a systematic review and meta-analysis of preclinical studies

[![DOI](https://zenodo.org/badge/18284730.svg)](https://doi.org/10.5281/zenodo.18284730)

This repository contains the data, analysis code, and outputs associated with a **systematic review and meta-analysis** examining the effects of non-competitive N-methyl-D-aspartate receptor (NMDAR) antagonists on **social behaviour** in laboratory animals, with secondary analyses assessing the modulatory effects of clinically approved antipsychotics and locomotor activity as a control outcome.

The project synthesises evidence from preclinical studies using MK-801, ketamine, and phencyclidine and applies correlated multilevel random-effects meta-analytic models with robust variance estimation.

---

## Research Objectives

**Primary objective**
- To quantify the effects of NMDAR antagonists on social behaviour in laboratory animals, separately for:
  - Social interaction paradigms  
  - Social preference paradigms  

**Secondary objectives**
- To evaluate whether clinically approved antipsychotics modify NMDAR antagonist–induced alterations in social behaviour.
- To assess locomotor activity measured during social testing to aid interpretation of social outcomes and identify potential non-specific motor effects.
- To characterise heterogeneity, publication bias, and methodological risk of bias in the preclinical literature.

---

## Repository Structure

### `flowchart_files/`
PRISMA flow diagram generation and outputs.

### `meta_analysis/`
All analysis scripts, outputs, figures, and tables organised by behavioural domain and experimental contrast:
- Antipsychotics on NMDA models  
- NMDA antagonist effects  
- Social interaction  
- Social preference  
- Locomotion  

Each subfolder contains:
- `.Rmd` and `.html` reproducible analysis files  
- `figures/` with graphical outputs  
- `tables/` with CSV summary results  

### `raw_data/`
Raw datasets extracted from the literature.

### `risk_of_bias/`
Risk-of-bias assessments, inter-rater reliability analyses, and visualisations.

# Longitudinal Statistical Analysis

![Made with RStudio](https://img.shields.io/badge/Made%20with-RStudio-blue?logo=rstudio)

This repository contains the **statistical report** of an anonymized longitudinal analysis conducted on clinical data.  
All references that could identify the study, institution, cohort, or specific diagnosis—as well as any unpublished conclusions—have been removed or generalized. Methods and code structure are preserved to ensure reproducibility.

## Scope

- **Objective:** Technical documentation and comparative statistical evaluation of longitudinal data collected at multiple timepoints.  
- **Audience:** Scientific and technical teams involved in clinical data analysis, reporting, and visualization.

## Workflow

1. **Data processing and cleaning:**
   - Import, transformation, and recoding of tabular datasets from multiple sources.  
   - Conversion between **cross-sectional (wide)** and **longitudinal (long)** data structures to enable time-based and subject-level analyses.  
   - Management of missing values, date/time variables, and data integrity checks across timepoints.  
   - Workflow implemented primarily with `tidyverse` (`dplyr`, `tidyr`, `lubridate`, `stringr`) for data wrangling, complemented by `reshape`, `Hmisc`, and `nlmeU` for dataset preparation and consistency validation.  

2. **Descriptive analysis:**
   - Summary statistics: median [IQR], counts (%), and stratified summaries.  
   - Exploratory visualizations of distributions, changes, and trends over time.

3. **Comparative analysis:**
   - **Paired tests:** parametric (`t.test`) and non-parametric (`wilcox.test`) for within-subject comparisons.  
   - **Group comparisons:** ANOVA / Kruskal–Wallis tests for continuous variables; Chi-square / Fisher’s exact tests for categorical data.  
   - **Effect size estimation** and graphical representation of differences.

4. **Visualization and reporting:**
   - Publication-ready plots and layouts using `ggplot2`, `ggprism`, `ggpubr`, and `patchwork`.  
   - Tables and summaries created with `kableExtra`.  
   - Fully reproducible document generation via **RMarkdown**.

## Main Packages
`Hmisc`, `ggeffects`, `ggfortify`, `ggplot2`, `ggprism`, `ggpubr`, `ggrepel`, `ggsci`, `gridExtra`, `kableExtra`, `patchwork`, `tidyverse`, `nlmeU`, `lattice`, `reshape`, `nlme`, `emmeans`, `rcompanion`, `pgirmess`

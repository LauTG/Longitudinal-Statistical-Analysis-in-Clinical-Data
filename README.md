# Longitudinal Statistical Analysis

**Goal.** Technical documentation of a longitudinal analysis in anonymized clinical data. This repository includes an anonymized RMarkdown report; all narrative references to specific diseases, drugs, centers, or unpublished outcomes have been removed. Methods and code structure are preserved for reproducibility.

## Workflow
- Data preparation (import, cleaning, recoding, date handling).
- Exploratory summaries and visualizations.
- Longitudinal/statistical modeling as appropriate (e.g., mixed-effects for repeated measures; survival/time-to-event if present).
- Reproducible reporting with RMarkdown.

## Statistical Methods
- Descriptives: median [IQR], counts (%), stratifications.
- Between/within-group comparisons: parametric or non-parametric tests as appropriate.
- Visualization of distributions, trends, and paired changes
- Model diagnostics and effect summaries with confidence intervals.

## R Packages
`Hmisc`,`ggeffects`, `ggfortify`, `ggplot2`, `ggprism`, `ggpubr`, `ggrepel`, `ggsci`, `gridExtra`, `kableExtra`, `patchwork`,`tidyverse`,`nlmeU`, `lattice`, 'reshape`, `nlme` , `emmeans`, `rcompanion`, `pgirmess`

## Reproducibility Notes
- Code chunks remain unmodified; only narrative text and headings were anonymized.
- Sections titled **Results/Discussion/Conclusions/Summary** were removed to avoid disclosure of unpublished findings.

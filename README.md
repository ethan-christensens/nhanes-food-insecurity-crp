# nhanes-food-insecurity-crp
# Food Insecurity and Systemic Inflammation (NHANES)

## Overview
This repository contains a reproducible quantitative analysis investigating the relationship between household food insecurity and systemic inflammation (measured via C-Reactive Protein) using data from the National Health and Nutrition Examination Survey (NHANES).

## Key Methods & Findings
* **Data Wrangling:** Cleaned and filtered an initial sample of $N = 11,933$ down to an analytic sample of $N = 6,680$, meticulously documenting all exclusions (missing values, "Refused", and "Don't know" survey codes).
* **Statistical Modeling:** Conducted a one-way ANOVA on log-transformed CRP ($F = 16.12, p < 0.0001$) with Tukey pairwise comparisons. 
* **Confounding & Diagnostics:** Fit an adjusted linear model controlling for BMI, verified residual diagnostics, and addressed cross-sectional study limitations.

## Tech Stack
* **Language:** R
* **Reporting:** Quarto (dynamic report generation)
* **Key Packages:** `tidyverse`, `ggplot2` (or whatever packages you used)

## Viewing the Report
You can view the fully rendered HTML report directly in your browser by downloading or viewing `output/analysis.html`.

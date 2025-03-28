# BIOF520_A4

## Survival Analysis in R

This repository contains code for performing survival analysis using the Cox proportional hazards model. It demonstrates how to:
- Fit a standard Cox model.
- Predict risk scores on a new dataset.
- Evaluate model performance using the concordance index (C-index) and AUROC.
- Generate Kaplan-Meier survival curves stratified by risk groups.
- Handle common data issues such as missing values and factor level mismatches.

## Requirements

The following R packages are required:
- `survival`
- `glmnet`
- `survminer`
- `pROC`
- `dplyr`
- `rms`

## Data Loading

The code uses two datasets:

- **uromol_data**: The training dataset.
- **knowles_data**: The test dataset.

Update the file paths below to match the locations on your system:

```r
uromol_data  <- readRDS("/projects/rli_prj/Courses/BIOF520/UROMOL_TaLG.teachingcohort.rds")
knowles_data <- readRDS("/projects/rli_prj/Courses/BIOF520/knowles_matched_TaLG_final.rds")


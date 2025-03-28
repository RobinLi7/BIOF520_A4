# BIOF520_A4

# Survival Analysis Demo in R

This repository contains demo code for performing survival analysis using the Cox proportional hazards model and LASSO Cox model. It demonstrates how to:
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

You can install these packages using:

```r
install.packages(c("survival", "glmnet", "survminer", "pROC"))


# Parental Leave Policy and Women's Leadership Representation

## Project Overview
This project examines whether the strength of parental leave policies predicts women’s representation in corporate leadership roles in the United States.

## Track
Quantitative Social Science Research (QSSR)

## Research Question
Does stronger parental leave policy predict higher representation of women in corporate leadership positions?

## Data Sources
- State-level parental leave policy data
- Corporate leadership gender representation data

## Repository Structure
- data/raw: original datasets
- data/processed: cleaned datasets
- notebooks: analysis notebooks
- src: reusable scripts
- reports: written deliverables

## Sprint 2
- Successfully acquired and cleaned primary datasets
- Constructed composite parental leave policy strength index
- Conducted exploratory data analysis with visualizations
- Identified data limitations and refined analytical approach
- Exported finalized analytical dataset for regression modeling

## Sprint 3
Goal: Estimate whether stronger paid leave policy (composite score) predicts women’s representation in senior and middle management.

Key outputs:

data/processed/analysis_dataset.csv — cleaned merged dataset used for modeling

notebooks/03_baseline_regression.ipynb — baseline regression models + exported tables/figures

notebooks/04_model_diagnostics.ipynb — residual diagnostics, Q–Q plot, VIF checks

results/figures/ — saved, publication-quality figures used in Sprint 3 report

How to run (reproduce results):

Create/activate environment (Anaconda kernel you used in notebooks)

Run notebooks in order:

01_data_acquisition_cleaning.ipynb

02_eda.ipynb

03_baseline_regression.ipynb

04_model_diagnostics.ipynb

Notes:

Primary regression is OLS with year fixed effects; robust standard errors (HC3).

Diagnostics indicate no major violations undermining inference (see 04_model_diagnostics.ipynb).


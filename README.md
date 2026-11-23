# Exploratory Analysis of Antibody and T-Cell Responses

## Overview

This project explores the relationship between antibody and T-cell responses following influenza vaccination.

The dataset contains measurements from 176 subjects across four influenza strains: H1N1, H3N2, BVic, and BYam.

## Research Questions

1. Can T-cell measurements help predict which influenza strain produces the strongest antibody response?
2. Are there associations between T-cell measurements and antibody fold changes?

## Methods

- Python, Pandas, and NumPy for data processing
- Matplotlib and Seaborn for visualization
- SciPy for statistical analysis
- Scikit-learn for machine learning

The analysis includes exploratory data analysis, log2 antibody fold-change calculations, Spearman correlation analysis, and machine-learning models using subject-level cross-validation.

## Preliminary Findings

- DR.106 and DR.107 showed positive associations with H3N2 antibody fold change.
- A Random Forest model achieved 34.66% prediction accuracy.
- The majority-class baseline accuracy was 32.95%.
- Prediction performance varied across influenza strains.

These findings are preliminary and require further validation.

## Repository Contents

- `analysis.ipynb`: Jupyter notebook containing the analysis and results.
- `README.md`: Project overview and summary.

## Running the Notebook

Install the required packages:

`pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels jupyter ipykernel`

Place the authorized dataset file in the same directory as the notebook, then open the notebook in VS Code or Jupyter.

## Notes

This project was completed as an exploratory research exercise. Findings should not be interpreted as evidence of causation.

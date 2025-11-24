# Fairness and Bias Analysis of the COMPAS Recidivism Dataset

This project introduces the concept of algorithmic bias and applies fairness metrics to the COMPAS recidivism risk score using a publicly available ProPublica dataset.

## Analysis Goals
- Explain different types of bias in machine learning (historical, measurement, algorithmic)  
- Investigate whether COMPAS produces unequal predictions for Black vs. non-Black individuals  
- Evaluate fairness using:
  - **Demographic Parity Difference**
  - **False-Positive-Rate Difference**

## Dataset
- Source: ProPublica / Kaggle  
- Years: 2013–2014  
- Observations: 6,172  
- Contains demographics, prior offenses, COMPAS score and two-year recidivism outcome

## Key Questions
- Does COMPAS assign higher false-positive rates to certain groups?
- Do prediction distributions differ by race?

## Contents
- `Doerr-BiasInKI.ipynb`: notebook combining conceptual overview and empirical fairness metrics

## Notes
This analysis is for educational use and replicates well-known fairness findings from the COMPAS dataset.

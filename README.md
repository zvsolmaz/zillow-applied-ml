# Zillow Applied Machine Learning

This repository contains an applied machine learning study on the
Zillow housing valuation dataset.

The project focuses on **model evaluation and robustness**, rather than
leaderboard optimization, by comparing different model families under a
realistic time-based split.

## Dataset
The dataset is provided by the Zillow Prize competition on Kaggle:

https://www.kaggle.com/competitions/zillow-prize-1

## Experimental Setup
- **Training data:** 2016 transactions
- **Test data:** 2017 transactions
- Time-based (temporal) train–test split to reflect real-world generalization
- Target variable: `logerror`

## Methods
- Linear models (baseline)
- Boosting models (XGBoost, LightGBM, CatBoost)
- Ensemble and hybrid approaches
- Hyperparameter tuning (GridSearch, Optuna)
- Robust evaluation using MAE
- Bootstrap Confidence Interval (CI)
- Bootstrap Significance Analysis (BSA)

## Goal
To analyze how different models and ensembles behave under
distribution shift and to assess whether small performance differences
are statistically meaningful.

📌 The full written report is not public.  
This repository shares the core methodology, experiments, and analysis.

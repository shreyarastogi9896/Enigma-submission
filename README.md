# Enigma26 Competition Solution

This repository contains my solution for the Enigma26 competition. The approach focuses on feature engineering, similarity-based matching, and ensemble learning to achieve strong predictive performance.

## Approach

* Created profile similarity features using overlap and Jaccard-based metrics.
* Engineered pairwise features including age difference, gender match, role match, industry match, company match, city match, and seniority match.
* Applied label encoding for categorical variables.
* Trained multiple gradient boosting models including XGBoost, LightGBM, and CatBoost.
* Combined model predictions using weighted ensembling for improved generalization.

## Performance

* **Leaderboard Score:** 0.00035

## Key Takeaway

Careful feature engineering combined with gradient boosting ensembles proved highly effective for capturing complex relationships in the dataset and improving prediction accuracy.

## Dataset

The dataset used in this project was provided as part of the Enigma26 Kaggle Competition.

Dataset and competition details can be found here:

https://www.kaggle.com/competitions/enigma26



# house-prices-eda-ml
This repository holds scripts and results data for an exploratory analysis and machine learning workflow for the Kaggle competition "House Prices - Advanced Regression Techniques".

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

## Objective
Predict house sale prices based on numeric and categorical data about the houses (e.g., year built, number of bathrooms, square footage) using supervised learning

## Approach
- Exploratory data analysis including (handling missing values, uni-, bi-, and multivariate analyses)
- Machine learning workflow (XGBRegressor/random forest/LGBM/ridge, grid search, cross-validation, ensemble learning)

## Results

As a baseline, the XGB Regressor had a cross-validated RMSE of ~0.13. The final stack regressor had a test RMSE of ~0.12 (top 15%)

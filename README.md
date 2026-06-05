# Retail Store Inventory Forecasting

## Overview

This project develops machine learning models to forecast product demand in retail stores and support inventory management decisions. The objective is to predict future units sold using historical sales, pricing, promotions, seasonality, and inventory-related information.

## Objectives

* Forecast product demand at the retail store level.
* Reduce stock shortages and overstock situations.
* Compare the performance of multiple machine learning models.
* Identify the key factors influencing sales demand.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* SHAP

## Feature Engineering

The project incorporates extensive feature engineering techniques:

* Lag Features (1, 7, 14, 28 days)
* Rolling Statistics (Mean, Std, Min, Max)
* Calendar Features (Week, Month, Quarter, Weekend)
* Price and Discount Interactions
* Competitor Pricing Features

## Models Evaluated

* Random Forest Regressor
* XGBoost Regressor

## Methodology

* Data Cleaning and Preprocessing
* Missing Value Handling
* Outlier Treatment
* Feature Engineering
* Time-Based Block Cross-Validation
* Hyperparameter Tuning
* Model Evaluation

## Evaluation Metrics

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)

## Key Findings

* XGBoost achieved the best forecasting performance.
* Historical sales patterns were highly predictive through lag and rolling features.
* Pricing, promotions, and competitor pricing significantly influenced product demand.

## Repository Structure

```text
metrics/
plots/
predictions/

metrics_Naive_Bayes/
metrics_RandomForest/
metrics_RandomForest_Fixed/
metrics_XGBoost/
metrics_XGBoost_Fixed/

plots_Naive_Bayes/
plots_RF/
plots_XGBoost/

predictions_Naive_Bayes/
predictions_RandomForest/
predictions_RandomForest_Fixed/
predictions_XGBoost/
predictions_XGBoost_Fixed/

Raindom_Forest(PTDL).ipynb
XGBoost_Regressor.ipynb
README.md
```

## Author

Le Nguyen Minh Thu

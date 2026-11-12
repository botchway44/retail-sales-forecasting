# Retail Sales Forecasting

An end-to-end machine learning project for forecasting store sales using historical transactions, oil prices, store information, promotions, and holiday events.

## Project overview

This graduate machine learning project used the Kaggle Store Sales - Time Series Forecasting competition. The work covered data cleaning, feature engineering, model training, validation, hyperparameter tuning, error analysis, and Kaggle submission generation.

## Models compared

- Linear Regression
- Random Forest Regressor
- XGBoost
- LightGBM

## Techniques used

- Time-based feature engineering
- Holiday and event indicators
- Categorical encoding
- Missing-value and outlier handling
- RandomizedSearchCV
- Model comparison using RMSLE
- Train/test evaluation and Kaggle submissions

## Verified results

The tuned Random Forest produced the best public Kaggle result recorded in the notebook, with an RMSLE of **1.7550**. The notebook records a leaderboard position of **593 at the time of submission**. Kaggle uses a rolling leaderboard, so the current rank may differ.

| Model | Public RMSLE |
|---|---:|
| Random Forest (tuned) | 1.7550 |
| XGBoost | 2.0885 |
| LightGBM (tuned) | 2.2611 |
| LightGBM (default) | 2.3499 |
| Linear Regression | 2.6026 |

Lower RMSLE is better.

## My contribution

I handled model training and validation, assisted with error analysis, and structured the final results into the project presentation. Major project decisions were made collaboratively by the team.

## Team

- Emmanuel Botwe
- Bhanu Pratap
- Aftab Shaikh

## Notebook and competition

- [Open the project notebook in Google Colab](https://colab.research.google.com/drive/1tBs6LS0JCedkvzxnKY0GFMEuoqepNVZF)
- [Kaggle Store Sales competition](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/)

## Technology

Python, pandas, NumPy, scikit-learn, XGBoost, LightGBM, Matplotlib, Seaborn, and Kaggle.

## Current status

The academic notebook is being cleaned for reproducibility. The dataset is not stored here; users should obtain it through Kaggle and follow the competition rules.

# House-Prices-Prediction
A data science project focused on predicting house prices using advanced regression techniques. The project follows the Kaggle House Prices competition and covers exploratory data analysis, feature engineering, modeling, and evaluation.

The project is based on the House Prices: Advanced Regression Techniques dataset provided by Kaggle.

Dataset source:  
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

---

## Project Overview

Accurate house price prediction requires a deep understanding of property characteristics,
feature interactions, and data quality. In this project, various numerical and categorical
features are analyzed and transformed to improve model performance, with `SalePrice` as
the target variable.

The main objective is to build a regression model that can generalize well and produce
reliable predictions.

---

## Repository Structure

- `Exploratory Data Analysis.ipynb`  
  Notebook for data exploration, visualization, and insights.

- `Feature Engineering.ipynb`  
  Notebook for feature engineering and preprocessing data.

- `Modeling.ipynb`  
  Notebook for model training, evaluation, and comparison.

- `train.csv`  
  The training dataset used for exploration and feature engineering.

- `test.csv`  
  The test dataset used for exploration and feature engineering.

- `train_fe.csv`  
  Feature-engineered training data for modeling.

- `test_fe.csv`  
  Feature-engineered test data for modeling.

- `submission_xgboost.csv`  
  Final prediction results.

---

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) is conducted to understand the structure and
characteristics of the dataset before modeling. The analysis includes:
- Examining the distribution of the target variable (`SalePrice`)
- Exploring the distribution of numerical and categorical features distributions
- Exploring basic relationships between selected features and house prices

All visualizations and observations are documented directly in the EDA notebook.

---

## Feature Engineering

Feature engineering in this project focuses on preparing the data for modeling.
The steps include:
- Handling missing values
- Creating simple derived features by combining existing variables

The goal of this stage is to produce a clean dataset that can be effectively used
in the modeling process.

---

## Modeling & Evaluation

Modeling is performed using a pipeline-based approach to ensure consistent
preprocessing across different models. A regularized linear regression model
(Ridge) is used as a baseline.

The baseline model is then compared with Random Forest Regressor model, and XGBoost Regressor model.

Model performance is evaluated using appropriate regression metrics.
Comparative results and performance differences between models are analyzed
in the modeling notebook.

In addition, feature influence and importance are examined to better understand
which features contribute most to house price predictions.

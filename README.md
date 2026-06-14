# Credit Card Default Prediction

## Overview

This project presents a comparative study of Logistic Regression and XGBoost for predicting credit card default using the UCI Credit Card Default Dataset.

The objective is to identify customers who are likely to default on their next credit card payment and compare the predictive performance of both machine learning models using standard evaluation metrics.

## Dataset

**Source:** UCI Machine Learning Repository

**Dataset:** Default of Credit Card Clients Dataset

### Dataset Information

* Total Records: 30,000
* Features: 23 Input Features
* Target Variable: Default Payment Next Month
* Default Cases: 6,636
* Non-Default Cases: 23,364

### Features Included

* Credit Limit Amount
* Age
* Gender
* Education
* Marital Status
* Repayment History
* Bill Statement Amounts
* Previous Payment Amounts

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* SHAP
* LIME

## Methodology

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Explainability Analysis

## Models Implemented

### Logistic Regression

A baseline classification model used for its simplicity and interpretability.

### XGBoost

A gradient boosting algorithm capable of capturing complex nonlinear relationships and improving predictive performance.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score

## Results

| Model               | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
| ------------------- | -------- | --------- | ------ | -------- | ------- |
| Logistic Regression | 0.8077   | 0.6868    | 0.2396 | 0.3553   | 0.7076  |
| XGBoost             | 0.8155   | 0.6495    | 0.3602 | 0.4634   | 0.7760  |

## Explainability

To improve transparency and interpretability, SHAP and LIME were used to analyze model predictions.

The explainability analysis provides:

* Global Feature Importance
* Local Prediction Explanations
* Model Transparency
* Better Understanding of Credit Risk Factors

## Key Findings

* XGBoost outperformed Logistic Regression in overall predictive performance.
* Repayment history variables were the most influential predictors of default.
* SHAP explanations improved model interpretability and transparency.

## Repository Contents

* xai_project.ipynb
* UCI_Credit_Card.csv
* README.md

## Authors

* Kishan Sharma
* Mandeep Kiran
* Priyanka Behki
* Sagar Raj

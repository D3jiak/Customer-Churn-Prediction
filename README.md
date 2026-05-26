# Customer Churn Prediction

Predicting customer churn for a fictional bank using Python and machine learning.

## Overview
Built a classification model to identify customers likely to churn, 
achieving 87% accuracy and 91% ROC-AUC score on test data.

## Tools & Libraries
Python · pandas · scikit-learn · matplotlib · seaborn

## What I Did
- Cleaned and preprocessed raw customer data using pandas
- Engineered features from date columns (tenure, recency)
- Trained and evaluated a classification model using scikit-learn
- Visualised top churn drivers for business interpretation

## Results
| Metric | Score |
|--------|-------|
| Accuracy | 87% |
| ROC-AUC | 91% |

## Key Finding
Contract type, account tenure, and product holdings were the 
strongest predictors of churn — customers on short-term contracts 
with low product engagement churned at significantly higher rates.

# Customer Churn Prediction

Predicting customer churn for a fictional bank using Python and machine learning.

## Overview
Built an end-to-end data analysis project to identify customers likely to churn, using exploratory analysis, visualisation, and a classification model achieving 87% accuracy and 91% ROC-AUC.

## Tools & Libraries
Python · pandas · scikit-learn · matplotlib · seaborn

## What I Did
- Cleaned and preprocessed 7,043 customer records — fixed TotalCharges dtype issue and removed 11 null rows
- Explored churn patterns through visualisations — identified 26.5% overall churn rate
- Found month-to-month contract customers churn at significantly higher rates than annual subscribers
- Found new customers (0–5 months tenure) are the highest churn risk group
- Trained and evaluated a classification model using scikit-learn

## Results
| Metric | Score |
|--------|-------|
| Accuracy | 87% |
| ROC-AUC | 91% |

## Kay Visualisations
Overall churn distribution (26.5% churn rate)
Churn by contract type — month-to-month vs annual
Churn by customer tenure — new customers highest risk

## Key Finding
Contract type, account tenure, and product holdings were the 
strongest predictors of churn — customers on short-term contracts 
with low product engagement churned at significantly higher rates.

# Customer Churn Prediction

Predicting customer churn for a telecom company using Python and machine learning.

## Overview
Built an end-to-end data analysis project to identify customers likely to churn, using exploratory analysis, visualisation, and a classification model achieving 79.18% accuracy and 0.84 ROC-AUC

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
| Accuracy | 79.18% |
| ROC-AUC | 0.84 |

## Key Visualisations
Overall churn distribution (26.5% churn rate)
Churn by contract type — month-to-month vs annual
Churn by customer tenure — new customers highest risk

## Key Finding
Total Charges, Tenure Months, and Monthly Charges were the strongest predictors of churn, newer customers paying higher monthly rates were the highest risk group. Contract type was also significant, with month-to-month customers churning more than annual subscribers.

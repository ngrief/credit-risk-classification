# credit-risk-classification
Module 20

# Module 12 Report Template

# Credit Risk Classification

## Overview

This project evaluates the performance of a logistic regression model designed for credit risk classification. The goal is to predict whether a loan is healthy (`0`) or high-risk (`1`) based on several financial indicators.

### Features used:
- Loan size
- Interest rate
- Borrower income
- Debt-to-income ratio
- Number of accounts
- Derogatory marks
- Total debt

## Machine Learning Workflow

1. **Data Preparation:**
   - Import dataset
   - Define features (`X`) and target variable (`y`)

2. **Train-Test Split:**
   - Training data: 75%
   - Testing data: 25%

3. **Model Training:**
   - Logistic Regression

4. **Evaluation:**
   - Confusion Matrix
   - Classification Report

## Model Performance

| Metric                              | Score |
|-------------------------------------|-------|
| Accuracy                            | 99%   |
| Precision (Healthy Loans - 0)       | 1.00  |
| Recall (Healthy Loans - 0)          | 0.99  |
| Precision (High-Risk Loans - 1)     | 0.85  |
| Recall (High-Risk Loans - 1)        | 0.91  |

## Conclusions

- **Best Model:** Logistic Regression model achieved high accuracy (99%) with effective identification of high-risk loans (91% recall).
- **Concern:** Misclassification of 56 high-risk loans as healthy.

## Recommendations

To improve the model further, consider:
- Handling class imbalance using SMOTE or class weighting
- Prioritizing accuracy in detecting high-risk loans depending on business objectives.


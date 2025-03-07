# Credit Risk Analysis Report

## Overview

The purpose of this analysis is to evaluate the effectiveness of a logistic regression model in predicting credit risk. The goal is to classify loans accurately as either healthy (`0`) or high-risk (`1`), based on key financial indicators. This enables the company to make informed decisions on loan approvals and risk management.

### Model Performance

- **Accuracy:** 99%
- **Precision:**
  - Healthy Loans (`0`): 1.00
  - High-Risk Loans (`1`): 0.85
- **Recall:**
  - Healthy Loans (`0`): 0.99
  - High-Risk Loans (`1`): 0.91

## Summary

The logistic regression model demonstrated high accuracy (99%), effectively distinguishing between healthy and high-risk loans. Although precision for high-risk loans was slightly lower (85%), the recall of 91% indicates strong capability in identifying the majority of high-risk cases.

### Recommendation

I recommend this logistic regression model for use by the company due to its high overall accuracy and strong recall performance on high-risk loans. However, given that 56 high-risk loans were misclassified as healthy, I suggest improving the model further by addressing class imbalance through methods such as SMOTE or adjusting class weights. Implementing these improvements will enhance the model's ability to detect high-risk loans accurately, aligning with the company's risk management objectives.


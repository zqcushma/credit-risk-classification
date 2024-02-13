# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this credit risk analysis is to develop and evaluate machine learning models that can predict creditworthiness based on financial information. The analysis focuses on understanding the performance of different models in identifying healthy and high-risk loans.

## Results

**Logistic Regression Model:**
  - **Accuracy Score:** 96.97%
  - **Precision Score (low-risk label):** 100%
  - **Recall Score (low-risk label):** 99%
  - **Precision Score (high-risk label):** 85%
  - **Recall Score (high-risk label):** 95%

* **Logistic Regression Model with Resampled Data:**
  - **Accuracy Score:** 99.36%
  - **Precision Score (low-risk label):** 100%
  - **Recall Score (low-risk label):** 99%
  - **Precision Score (high-risk label):** 84% 
  - **Recall Score (high-risk label):** 99%

## Summary

In summary, the models were evaluated based on accuracy, precision, and recall. The Logistic Regression model trained on the resampled data demonstrates improved performance in identifying high-risk loans. It is recommended for use by the company due to its balanced accuracy in predicting both healthy and high-risk loans.

**Justification:**
- The resampled model shows enhanced precision and recall for high-risk loans, which is crucial for minimizing false negatives in credit risk assessment.
- While the precision score for high-risk loans decreased by 1% after resampling, the overall improvement in recall and balanced accuracy supports the model's suitability for credit risk prediction.
- The balanced accuracy score indicates a well-rounded performance, making it a suitable choice for the company's credit risk prediction.
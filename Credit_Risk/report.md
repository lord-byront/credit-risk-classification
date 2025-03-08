
___________________

## Overview of the Analysis

The purpose of this analysis was to evaluate the performance of a machine learning model in predicting loan risk classification. Specifically, we aimed to determine whether a given loan is considered "high-risk" (1) or "healthy" (0) based on various financial factors. The dataset used for this analysis contained information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

The key objective was to train and test a logistic regression model using this data to assess its effectiveness in correctly classifying loans. The dataset was split into training and testing sets, and a logistic regression model was fitted using the training data. Model performance was evaluated using a confusion matrix and a classification report, which provided metrics such as accuracy, precision, and recall.

## Results

Machine Learning Model: Logistic Regression

Accuracy: 99%

Precision:

Class 0 (Healthy Loan): 1.00

Class 1 (High-Risk Loan): 0.84

Recall:

Class 0 (Healthy Loan): 0.99

Class 1 (High-Risk Loan): 0.94

F1-Score:

Class 0 (Healthy Loan): 1.00

Class 1 (High-Risk Loan): 0.89

## Summary

The logistic regression model performed exceptionally well overall, achieving a high accuracy of 99%. It demonstrated near-perfect performance in identifying healthy loans (Class 0), with both precision and recall scores close to 1.00. However, while the model performed well in identifying high-risk loans (Class 1), its precision was slightly lower at 0.84. This indicates that some loans were incorrectly classified as high-risk when they were actually healthy.

If the primary objective is to minimize the risk of misclassifying high-risk loans as healthy, recall for Class 1 (0.94) is an important metric, as it ensures that the majority of actual high-risk loans are correctly identified. However, if avoiding false positives (incorrectly labeling a healthy loan as high-risk) is more critical, then improving the precision for Class 1 should be considered.

Given the strong overall performance, the logistic regression model is a solid choice for predicting loan risk. However, additional techniques such as adjusting the decision threshold, using class weighting, or exploring alternative models like decision trees or ensemble methods could further enhance its predictive capability, especially for Class 1 loans.


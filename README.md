# Module 12 Report

## Overview of the Analysis

The objective of this analysis is to develop and assess machine learning models designed to predict loan risk. The lending dataset in CSV format employed in this analysis encompasses historical records of lending activities. The goal is to construct a model capable of evaluating the creditworthiness of borrowers and categorizing credit risk predictions accordingly.

The dataset includes various financial attributes of loan applicants, such as loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks total_debt and loan_status.

## Results
Logistic Regression Model:
Balanced Accuracy Score: 94.43%
Precision for class 0 (approved loans): 100%
Recall for class 0 (approved loans): 100%
Precision for class 1 (denied loans): 87%
Recall for class 1 (denied loans): 89%

## Summary
The logistic regression model demonstrates strong predictive performance in assessing loan risk. With a balanced accuracy score of 94.43%, it showcases reliability even in the presence of imbalanced classes within the dataset. Notably, the model achieves perfect precision and recall for class 0 (approved loans), underscoring its exceptional ability to accurately identify this category. Furthermore, it exhibits satisfactory precision and recall for class 1 (denied loans), indicating its proficiency in discerning both approved and denied loans.

Given its commendable performance across diverse evaluation metrics, the logistic regression model emerges as a prudent choice for predicting loan risk in this context. Its capacity to effectively predict both approved and denied loans renders it well-suited for comprehensive credit risk assessment. Moreover, the model's transparency and ease of interpretation enhance its applicability in real-world scenarios.

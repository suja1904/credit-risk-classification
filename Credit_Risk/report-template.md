# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis:
  The purpose of the analysis is to utilize machine learning models to assess credit risk using historical lending data. The objective was to   predict whether loans are likely to be 'healthy' or 'high-risk' based on various financial indicators.

* Explain what financial information the data was on, and what you needed to predict.
  The dataset (lending_data.csv) includes financial information such as
  loan_size,
  interest_rate,
  borrower_income,
  debt_to_income,
  num_of_accounts,
  derogatory_marks,
  total_debt.
  loan_status
  
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
A final column called loan status is provided that indicates whether the borrower defaulted on the loan. A '1' indicates that the   borrower defaulted, a '0' indicates a healthy loan.
  
* Describe the stages of the machine learning process you went through as part of this analysis.

  Stages of the Machine Learning Process:

    Data Collection and Preparation
    Model Selection
    Model Training
    Model Prediction
    Model Utilization

  
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
  The Logistic Regression Model was used to determine credit risk classification accuracy.
  The model's performance was evaluated based on the accuracy score.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1: LogisticRegression 
    * Description of Model 1 Accuracy, Precision, and Recall scores.
 
      precision    recall  f1-score   support

           0       1.00      1.00      1.00     15001
           1       0.86      0.91      0.88       507

    accuracy                           0.99     15508
   macro avg       0.93      0.95      0.94     15508
weighted avg       0.99      0.99      0.99     15508


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best
  
Only one prediction model was used in this exercise. In this case, it was Logistic Regression which has tests result in a highly accurate fit of 99%
The logistic regression model shows high accuracy (0.99) and good performance on other metrics (precision, recall, F1-score) for both classes. To confirm if it is the best model, it is essential to compare its performance with other models using a comprehensive set of metrics and validation techniques. This process ensures that the selected model meets the specific needs of your application and generalizes well to unseen data.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? 

Performance is impacted by the type of problems we are trying to solve. It is more complex identifying high risk.


If you do not recommend any of the models, please justify your reasoning:

By thoroughly comparing logistic regression with other models and focusing on the most relevant evaluation metrics, I can make a more informed decision about which model best meets the needs of our application.








# Module 20

## Overview of the Analysis

Purpose of the analysis is to predict the credit risk based on the provided dataset.
Data was on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts of the holders, and their loan status.
Basic information was number of loans, number of active loans.
Stages of machine learning were preparing the data, running the logistic regression models and then preparing this report. 
Used both the original data in the logistic regression model as well as resampled training data in a randomoversampler to verify results.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
  Accuracy    0.952
  Precision   0.85
  Recall
    healthy   0.99
    high-risk 0.91


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

  Accuracy    0.993
  Precision   0.84
  Recall
    healthy   0.99
    high-risk 0.99

## Summary

Model 1's accuracy stood at 0.952 with a precision of 0.85 and high-risk status at 0.91. This meant that at a sizable precision, the model was accurate at 95% at prediction true positive high risk loans at a 91%.
Model 2's accuracy stood at 0.993 with a precision of 0.84 and high-risk status at 0.99. the Logistic Regression model with resampled training data provided better recall results and a stronger accuracy. Model 2 performed best.
Performance depends on predicting both the healthy and high-risk loans. in this circumstance, we have strong evidence that the model predicts high-risk loans and shows true positives through the recall rate. It is more important to predict the healthy loans to know the overall financial position of the financial institution. 

Recommendation is model 2.


## References

credit-risk-classification_IH

- model built in majority using chatgpt and lecture material.
- imbalance version error solved using chatgpt where imbalance version dropped a few iterations.
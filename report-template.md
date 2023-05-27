# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

The purpose of this analysis to create a model that predicts high risk and low-risk or medium risk loans. The predicitve models take into account series of information to make these predictions including loan size,	interest, rate, borrower's income, debt to income ratio, the 	number of accounts,	derogatory marks, and total_debt to make the predicitions. We use two models one with the original data and another one with the resampled data to make the most accurate predictions.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Test Data Balanced Accuracy: 99%
  * Test Data Precision for 'healthy loans': 100%
  * Test Data Precision for 'high risk loans': 86%
  * Test Data Recall for 'healthy loans': 100%
  * Test Data Recall for 'high risk loans': 91%



* Machine Learning Model 2:
  * Test Data Balanced Accuracy: 99%
  * Test Data Precision for 'healthy loans': 99%
  * Test Data Precision for 'high risk loans': 99%
  * Test Data Recall for 'healthy loans': 99%
  * Test Data Recall for 'high risk loans': 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

The initial Logistic Regression model, trained on the original data, demonstrates excellent performance in predicting 'healthy loans' with high accuracy, precision, and recall, all close to 100%. However, it shows relatively lower performance in identifying 'high-risk loans' with a precision of 85% and a recall of 91%. This indicates that the model is relatively less effective at classifying high-risk loans compared to healthy loans, and compared to the second model which scores almost 100% in all data points. 
I recommend the second model as it has a higher level of precision in making these reccomendations. 

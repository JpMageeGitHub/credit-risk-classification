# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:



 The main purpose of this analysis is to use prior customer data to learn what factors contribute to loans defaulting. These loans are divided into high-risk and low risk, with respect to the likelihood of defaulting by initial factors. The creation of these models is intended to give the bank an accurate assessment of what loans will and won't be defaulted on.

Some of the initial data that was used to create the models included the loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The data was then split into training and testing sets, and scaled using the StandardScaler() method. The data was then resampled using the RandomOverSampler() method, and the LogisticRegression() method was used to create the models.

## Results



* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

Model 1 had a balanced accuracy score of 0.9520479254722232, a precision score of 0.99, and a recall score of 0.94.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Model 2 had a balanced accuracy score of 0.9936781215845847, a precision score of 1.0, and a recall score of 0.99.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Since there is much more potential damage to the bank with respect to high-risk loans, it is more important for the bank to correctly identify the high-risk loans than the low-risk loans. Therefore, the model with the highest recall score is the best model to use. With this in mind, the oversampled model that was used second in the analysis would be most appropriate.



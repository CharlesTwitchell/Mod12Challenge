# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to test predictive models for a loan credit application.  The consumer data included metrics around loan size, interest rate, borrower income, debt to incom ration, number of accounts, derogatory marks, and total debt.  These metrics were used to creat a predictive model to figure out if the consumer was a good risk or high risk loan.  

As part of this analysis, we loaded and cleaned the data with pandas.  We created training and testing data sets with the train/test/split module.  We then generated a predictive logistic regression model off of that training data.  Finally we compared that model's predictive capacity to the testing set.  

The final comparason was to use resampling methods of data to see if we can correct any oversampling errors.  The new model generated from this resampled data was slightly more accurate.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * A balanced accuracy score of 0.9911267024349979
  * Predicts healthy loans with 100% precision
  * Predicts unhealthy loans with 84% precision
  * Has 70 false predictions for unhealthy loans
  

* Machine Learning Model 2:
  * A balanced accuracy score of 0.9941188609162196
  * Predicts healthy loans with 100% precision
  * Predicts unhealthy loans with 84% precision
  * Has 0 false predictions for unhealthy loans


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
I would recommend using Machine Learning model 2.  Though both models worked well.  Model 2 did not make any errors with high risk loans.  Because avoiding poor predictions of high risk loans helps minimize loss for the bank, Model 2 has an advantage in real world applications.



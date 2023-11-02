# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

  The purpose of this analysis is to predict one's credit risk. This code uses several data points to predict this, including debt to income ratio, number of accounts, and derogatory marks on one's credit. We used two methods to do so, a logistic regression model with the original data provided, and a logistic regression model with resampled data that made sure the labels had an equal number of data points. The second method gave us a higher accuracy in predicting one's credit risk. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  *Accuracy is .99. 
  *Precision is 1.00 for predicted 0 values.
  *Precision is 0.85 for predicted 1 values.
  *Recall is 0.99 for actual 0 values.
  *Recall is 0.91 for actual 1 values.

  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
* Accuracy is .99.
* Precision is 1.00 for predicted 0 values.
* Precision is 0.84for predicted 1 values.
* Recall is 0.99 for actual 0 values.
* Recall is 0.99 for actual 1 values.
  * Description of Model 2 Accuracy, Precision, and Recall scores.



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

I would recommend the logistic regression model with resampled data as the accuracy, precision, and recall were all generally higher for this  model. I would say it is more important from a business perspective to better predict the 1's, so you can better predict who is more likely to be a risk.

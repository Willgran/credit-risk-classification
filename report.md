# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * With a 95% accuracy score, this model was very efficent in predicting low risk loans rather than high risk loans. As the recall for healthy loans is 0.99, and the unhealthy loans came at a recall of 0.91. In the Confusion matrix we see there were 56 False Positives and 102 False Negatives. 



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * This model did exceptionally well with an astounding 99% balanced accuarcy score. This is true when we display our recall which is 0.99 for both low and high risk loans. The model was much more accurate than the first model with a confusion matrix of 4 False Positives and 116 False Negatives. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
Based on the balanced accuracy score and recall, the second model is the best fit for predicting high risk loans. The first is not too far off from the second but when every percent matters, I would recommned using Model 2, the logistic regression model fitted with oversampled data.  


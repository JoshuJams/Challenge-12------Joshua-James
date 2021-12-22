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
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Accuracy Scores - Can predict with 95% accuracy
Precision Scores -  Can predict healthy models within the same range with 100% precision and can predict high-risk models with 85% precision
Recall Scores - Can predict healthy models with  99% recall and high-risk model with 91% recall


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
Accuracy Scores - Can predict with 99% accuracy
Precision Scores -  Can predict healthy models within the same range with 100% precision and can predict high-risk models with 84% precision
Recall Scores - Can predict healthy models with  99% recall and high-risk model with 99% recall


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Model 2 seems to perform better than Model 1. I can tell by the differences in percentage between the Accuracy, Precision, and Recall Scores. In models 1 and 2 the difference in Accuracy scores is 4% with Model 2 on the higher end. In models 1 and 2 the difference in Precision scores is 0% between the healthy models and 1% between the high-risk models with Model 2 on the higher end once again. In models 1 and 2 the difference in Recall scores is 0% between the healthy models and 8% between the high-risk models with Model 2 on the higher end once more. The performance does matter in this model, especially when predicting the 1(high-risk accounts).
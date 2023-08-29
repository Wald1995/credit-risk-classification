# Module 20 Report Template

## Overview of the Analysis

# Credit Risk Analysis

## Description:
The purpose of this analysis is to take advantage of the techniques learned about machine learning, in terms of logistic regressions of creditworthiness. Mainly using 2 variables: healthy and high risk loans (0 & 1).

* For the first machine learning model, a logistic regression model was created taking into account the original training (X_train, y_train). Subsequently, the training models were adjusted in order to create the predictions.
* In the second model, the original training data were sampled a second time using the RandomOverSampler module and new predictions were created. 

Each model was evaluated on the basis of the balance accuracy score, its recovery and the f1 score.

## Results
* Machine Learning Model 1:
  * When comparing the original data against the model we can observe that the high risk loans (1) obtained a result of 0.87 in precision and 0.89 in recall, so we can conclude that there is room for improvement, but even so it is not a quantity to be alarmed about. As for the health of the contracts (0) we obtained a result of 1.00 of accuracy which is excellent.
  * Taking into account both labels (0 & 1) vs the original data shows an accuracy of 94%, so the model is working very well.


* Machine Learning Model 2:
  * This model had better results generating an average accuracy of 96% between both labels. As in the previous model, healty loans (0) obtained a score of 1 in both precision and recall, while high-risk contracts (1) have a score of 0.87 in precision and 1 in recall.

## Summary
Considering both Models, we can conclude that the second model is more effective and performs better than the first one. The high risk loans (1) in both models were the least accurate, but still the overall result is very good. To conclude, I would like to recommend using Model 2.
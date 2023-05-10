# Module 12 Report Template

## Overview of the Analysis

A supervised learning model is created that predicts loan defaults based on a variety of factors including loan size, interest rate, income and past derogatory marks.

Pandas is used to import and structure the data while Sklearn is used to build, run and evaluate the model. The data is split into a test and train set, and a logistic regression model is fit to the training data. Predictions are made using the testing data, and various accuracy scores as well as a confusion matrix are generated to evaluate the validity of the model. Finally, the RandomOverSampler method is used to balance the highly disproportionate ratio of output values.

## Results

Note that the macro average is used when calculating precision and recall scores.

* Machine Learning Model 1:
  * Accuracy: 0.99 (0.95 balanced accuracy score)
  * Precision: 0.92
  * Recall: 0.95

* Machine Learning Model 2:
  * Accuracy: 0.99 (0.99 balanced accuracy score)
  * Precision: 0.92
  * Recall: 0.99
## Summary

Two models are made and evaluated in this project. Both are linear regression models with the same solver, but the data that goes into each model is different. For the first model with unprocessed data, the balanced accuracy score is about 95% which is good for a machine learning model. However, when the model is trained on balanced data, we achieve an accuracy score of 99% which is an exceptional score. Further changes could be made such as normalizing the feature data or using different solvers, but the improvement in accuracy would be minimal.

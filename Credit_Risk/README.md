
## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers.
* A dataset of historical lending activity from a peer-to-peer lending services company was used.
* Dependent variable in this analysis was the "loan status" indicating if a loan is healthy or at risk.
* For this analysis I split my dataset to training and test sets, then defined my dependent and independent variables. After this I created logistic LogisticRegression model and fit original data to this model. Trained model is used to make predictions and then evaluated performance of model.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy, Precision, and Recall scores for Model 1
  Accuracy: 0.99 ,
  Precision: 0.85 , 
  Recall: 0.91 ,
  Balanced Accuracy score:0.95.

* Machine Learning Model 2:
  * Accuracy, Precision, and Recall scores for Model 2
  Accuracy: 0.99 ,
  Precision: 0.84 , 
  Recall: 0.99 ,
  Balanced Accuracy score:0.99.

## Summary

Analysis show that collected data can be effectively used to train and test the Machine Learning Classification Model. For better predictions, solving the imbalance sampling issue is needed.

Randomly oversampling the data helps us to get higher balanced accuracy and recall scores. With higher recall value, model can predict risky loans more accurately.

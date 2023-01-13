# Credit Risk Analysis

## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
The purpose of this analysis is well defined (4 pt)
## Results
#### Naive Random Oversampling
- Accuracy score: 59%
- Precision: High risk = 0.01 | Low Risk = 1.0
- Recall Score: High risk = 0.57 | Low Risk = 0.68
#### SMOTE Oversampling
- Accuracy score: 61.9%
- Precision: High risk = 0.01 | Low Risk = 1.0
- Recall Score: High risk = 0.62 | Low Risk = 0.63
#### Undersampling
- Accuracy score: 56.5%
- Precision: High risk = 0.01 | Low Risk = 1.0
- Recall Score: High risk = 0.61 | Low Risk = 0.57
#### Combination (Over and Under) Sampling
- Accuracy score: 60.8%
- Precision: High risk = 0.01 | Low Risk = 1.0
- Recall Score: High risk = 0.70 | Low Risk = 0.58
#### Balanced Random Forest Classifier
- Accuracy score: 88.8%
- Precision: High risk = 0.03 | Low Risk = 1.0
- Recall Score: High risk = 0.64 | Low Risk = 0.89
#### Easy Ensemble AdaBoost Classifier
- Accuracy score: 94.2%
- Precision: High risk = 0.09 | Low Risk = 1.0
- Recall Score: High risk = 0.92 | Low Risk = 0.94

## Summary

Overall, Easy Ensemble AdaBoost Classifier has the highest accuracy precision, and recall score in comparison to the other models. If I were to make a recommendation, I'd recommned Easy Ensemble AdaBoost Classifer due to its high scores in accuracy and other areas.

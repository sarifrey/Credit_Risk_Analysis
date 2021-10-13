# Credit_Risk_Analysis
Module 17 Supervised Machine Learning and Credit Risk

## Overview
Overview of the loan prediction risk analysis:
The purpose of this analysis is well defined 

This project looks at credit card risk from the LendingClub dataset. The imbalanced-learn and scikit-learn libraries are used to build and evaluate modes through resampling. Four different algorithms are used to oversample and undersample the data.
* Random Over Sampler
* SMOTE
* ClusterCentroids
* SMOTEENN

Two different maching learning models are used to reduce bias and predict credit risk.
* Balanced Random Forest Classifier
* Easy Ensemble Classifier

## Results
The results of four algorithms used for predicting credit risk.

### Random Over Sampler
* The balanced accuracy score is 62.5 percent.
* Precision for high risk is 1 percent.
* Recall of high risk is 60 percent.

#### Accuracy Score

![alt text](

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 5952.
![alt text](

#### Imbalanced Classification Report
The f1 score is 78 percent.
![alt text](

### Synthetic Minority Oversampling Technique (SMOTE)
* The balanced accuracy score is 65.1 percent.
* Precision for high risk is 1 percent.
* Recall of high risk is 64 percent.

#### Accuracy Score

![alt text](

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 5840.
![alt text](

#### Imbalanced Classification Report
The f1 score is 79 percent.

![alt text](

### ClusterCentroids
* The balanced accuracy score is 65.1 percent.
* Precision for high risk is 1 percent.
* Recall of high risk is 59 percent.

#### Accuracy Score

![alt text](

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 9677.
![alt text](

#### Imbalanced Classification Report
The f1 score is 60 percent.
![alt text](

### SMOTEENN 
* The balanced accuracy score is 51.0 percent.
* Precision for high risk is 1 percent.
* Recall of high risk is 70 percent.

#### Accuracy Score

![alt text](

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 7294.
![alt text](

#### Imbalanced Classification Report
The f1 score is 72 percent.
![alt text](

The results for the machine learning models.
### Balanced Random Forest Classifier
* The balanced accuracy score is 78.7 percent.
* Precision for high risk is 4 percent.
* Recall of high risk is 67 percent.

#### Accuracy Score

![alt text](

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 1560.
![alt text](

#### Imbalanced Classification Report
The f1 score is 95 percent.

![alt text](

#### Features

![alt text](

### Easy Ensemble AdaBoost Classifier
* The balanced accuracy score is 92.5 percent.
* Precision for high risk is 7 percent.
* Recall of high risk is 91 percent.

#### Accuracy Score

![alt text](

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 979.
![alt text](

#### Imbalanced Classification Report
The f1 score is 97 percent.
![alt text](

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models.
Use screenshots of your outputs to support your results.

## Summary (5 pts)

The Easy Ensemble AdaBoost Classifier performed better in accurately predicting high-risk credit card applicants and low-risk applicants at 92.5 percent accuracy. It also had the least false negative for high risk.
The recommended model to use is the Easy Ensemble AdaBoot Classifier

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 
If you do not recommend any of the models, justify your reasoning.
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
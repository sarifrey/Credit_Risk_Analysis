# Credit_Risk_Analysis
Module 17 Supervised Machine Learning and Credit Risk

## Overview
This project looks at credit card risk from the LendingClub dataset. The imbalanced-learn and scikit-learn libraries are used to build and evaluate models through resampling. Four different algorithms are used to oversample and undersample the data.
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
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/RoS_balancedaccuracy.jpg)

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 5952.
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/RoS_confusionmatrix.jpg)

#### Imbalanced Classification Report
The f1 score is 78 percent.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/RoS_imbalancedclassificationreport.jpg)

### Synthetic Minority Oversampling Technique (SMOTE)
* The balanced accuracy score is 65.1 percent.
* Precision for high risk is 1 percent.
* Recall of high risk is 64 percent.

#### Accuracy Score
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/SMOTE_balancedaccuracy.jpg)

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 5840.
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/SMOTE_confusionmatrix.jpg)

#### Imbalanced Classification Report
The f1 score is 79 percent.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/SMOTE_imbalancedclassificationreport.jpg)

### ClusterCentroids
* The balanced accuracy score is 65.1 percent.
* Precision for high risk is 1 percent.
* Recall of high risk is 59 percent.

#### Accuracy Score
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/ClusterCentroid_balancedaccuracy.jpg)

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 9677.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/ClusterCentroids_confusionmatrix.jpg)

#### Imbalanced Classification Report
The f1 score is 60 percent.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/ClusterCentroids_imbalancedclassificationreport.jpg)

### SMOTEENN 
* The balanced accuracy score is 51.0 percent.
* Precision for high risk is 1 percent.
* Recall of high risk is 70 percent.

#### Accuracy Score
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/SMOTEENN_balancedaccuracy.jpg)

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 7294.
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/SMOTEEN_confusionmatrix.jpg)

#### Imbalanced Classification Report
The f1 score is 72 percent.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/SMOTEENN_imbalancedclassificationreport.jpg)

The results for the machine learning models.
### Balanced Random Forest Classifier
* The balanced accuracy score is 78.7 percent.
* Precision for high risk is 4 percent.
* Recall of high risk is 67 percent.

#### Accuracy Score

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/BRFC_balancedaccuracy.jpg)

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 1560.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/BRFC_confusionmatrix.jpg)

#### Imbalanced Classification Report
The f1 score is 95 percent.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/BRFC_imbalancedclassificationreport.jpg)

#### Features
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/BRFC_features.jpg)

### Easy Ensemble AdaBoost Classifier
* The balanced accuracy score is 92.5 percent.
* Precision for high risk is 7 percent.
* Recall of high risk is 91 percent.

#### Accuracy Score
![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/EEAC_balancedaccuracy.jpg)

#### Confusion Matrix
The number of false positive or low risk credit cards that predicted high risk is 979.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/EEAC_confusionmatrix.jpg)

#### Imbalanced Classification Report
The f1 score is 97 percent.

![alt text](https://github.com/sarifrey/Credit_Risk_Analysis/blob/main/resources/EEAC_imbalancedclassificationreport.jpg)

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models.
Use screenshots of your outputs to support your results.

## Summary

The Easy Ensemble AdaBoost Classifier performed better in accurately predicting high-risk credit card applicants and low-risk applicants at 92.5 percent accuracy. It also had the least false negative for high risk. The other models did not perform as well in predicting high-risk credit card applicants.
The recommended model to use is the Easy Ensemble AdaBoot Classifier

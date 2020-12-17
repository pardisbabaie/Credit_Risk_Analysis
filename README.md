# Credit_Risk_Analysis
## Overview
The purpose of this project is to predict credit risk by using various models of machine learning to evaluate the credit risk. We will use the credit card credit dataset from LendingClub, a peer-to-peer lending services company as our data set to analyze the credit risk.
## Results
### Oversampling
#### Naive Random Oversampling Results
The accuracy score of this model as shown below is approximately 64%. The precision score total is high at 0.99 but the sensitivity score is only at 0.56 which is not very high.


#### SMOTE Oversampling
The accuracy score of this model as shown below is approximately 66% which is higher than the last model. The precision score total is the same as the last model at 0.99 but the sensitivity score is a bit higher at 0.68 but still not very high.


### Undersampling
The accuracy score of this model as shown below is approximately 66% which is the same as the SMOTE oversampling model. The precision score total is also the same as the last model at 0.99 but the sensitivity score is much lower at 0.56.

### Combination (Over and Under) Sampling
The accuracy score of this model as shown below is approximately 59% which is the lowest accuracy of all the models. The precision score total is the same as the others 0.99 but the sensitivity score is also the lowest at 0.42.


### Ensemble
#### Balanced Random Forest Classifier
The accuracy score of this model as shown below is approximately 79% which is better than the previous models. The precision score total is the same as the others 0.99 and the sensitivity score is higher than the previous model at at 0.87.

#### Easy Ensemble AdaBoost Classifier
The accuracy score of this model as shown below is approximately 93% which is better than the previous models. The precision score total is the same as the others 0.99 and the sensitivity score is the highest of all the models at 0.95.


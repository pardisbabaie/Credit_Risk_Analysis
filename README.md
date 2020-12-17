# Credit_Risk_Analysis
## Overview
The purpose of this project is to predict credit risk by using various models of machine learning to evaluate the credit risk. We will use the credit card credit dataset from LendingClub, a peer-to-peer lending services company as our data set to analyze the credit risk.
## Results
### Oversampling
#### Naive Random Oversampling Results
The accuracy score of this model as shown below is approximately 64%. The precision score total is high at 0.99 but the sensitivity score is only at 0.56 which is not very high.

<img width="612" alt="Screen Shot 2020-12-15 at 8 17 26 PM" src="https://user-images.githubusercontent.com/69806770/102426423-561d1180-3fdd-11eb-8905-957f268c11a9.png">

#### SMOTE Oversampling
The accuracy score of this model as shown below is approximately 66% which is higher than the last model. The precision score total is the same as the last model at 0.99 but the sensitivity score is a bit higher at 0.68 but still not very high.

<img width="616" alt="Screen Shot 2020-12-16 at 8 28 10 PM" src="https://user-images.githubusercontent.com/69806770/102426480-6af9a500-3fdd-11eb-8121-a00ace187e25.png">

### Undersampling
The accuracy score of this model as shown below is approximately 66% which is the same as the SMOTE oversampling model. The precision score total is also the same as the last model at 0.99 but the sensitivity score is much lower at 0.56.

<img width="617" alt="Screen Shot 2020-12-16 at 8 28 21 PM" src="https://user-images.githubusercontent.com/69806770/102426501-78169400-3fdd-11eb-84af-bcb1e04ced6e.png">

### Combination (Over and Under) Sampling
The accuracy score of this model as shown below is approximately 59% which is the lowest accuracy of all the models. The precision score total is the same as the others 0.99 but the sensitivity score is also the lowest at 0.42.

<img width="603" alt="Screen Shot 2020-12-16 at 8 28 38 PM" src="https://user-images.githubusercontent.com/69806770/102426546-86fd4680-3fdd-11eb-8146-8c1f1467839f.png">

### Ensemble
#### Balanced Random Forest Classifier
The accuracy score of this model as shown below is approximately 79% which is better than the previous models. The precision score total is the same as the others 0.99 and the sensitivity score is higher than the previous model at at 0.87.

<img width="612" alt="Screen Shot 2020-12-16 at 8 31 04 PM" src="https://user-images.githubusercontent.com/69806770/102426628-aac08c80-3fdd-11eb-8061-25430aad5e37.png">

#### Easy Ensemble AdaBoost Classifier
The accuracy score of this model as shown below is approximately 93% which is better than the previous models. The precision score total is the same as the others 0.99 and the sensitivity score is the highest of all the models at 0.95.

<img width="603" alt="Screen Shot 2020-12-16 at 8 31 15 PM" src="https://user-images.githubusercontent.com/69806770/102426645-b3b15e00-3fdd-11eb-84a3-d573c39c288f.png">

## Summary
Overall, the resampling tests did not perform very well in terms of accuracy and sensitivity. The ensemble models performed much better with higher accuracy scores and sensitivity scores and the same precision scores. The machine learning model I would recommend to choose is the Easy Ensemble AdaBoost as it has the highest accuracy score at a 93% which is fairly high as well as high scores for both the precision and sensitivity at 0.99 and 0.95 respectively which were both good scores.

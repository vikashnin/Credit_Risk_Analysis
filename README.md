# Credit_Risk_Analysis

## Overview of Analysis:

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Then, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once I am done I will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results
### 1. Naive Random Oversampling
<img width="909" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/98666231/172072117-50306e90-82b7-4e7f-bb5d-5425296f50f7.png">
Balanced Accuracy Score: 0.6742571941946299.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.74
  Low_Risk:0.61
  


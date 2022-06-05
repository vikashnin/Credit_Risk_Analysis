# Credit_Risk_Analysis

## Overview of Analysis:

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Then, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once I am done I will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results
### 1. Naive Random Oversampling
<img width="697" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/98666231/172074046-589d43d1-7f0d-46a3-9c30-a714bee059a7.png">
Balanced Accuracy Score: 0.6742571941946299.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.74
  Low_Risk:0.61
  
### 2. SMOTE Oversampling
<img width="650" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/98666231/172074050-7b0daed8-8717-4f3d-b135-276b56b218b8.png">
Balanced Accuracy Score: 0.6623356588465208.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.63
  Low_Risk:0.69
 
### 3. Undersampling
<img width="647" alt="Undersampling" src="https://user-images.githubusercontent.com/98666231/172074055-049cab2f-294b-426b-b695-2369e9aa0e97.png">
Balanced Accuracy Score: 0.5442166848817717.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.69
  Low_Risk:0.40
  
### 4. Combination (Under and Over) Sampling 
<img width="642" alt="Combination (Over and Under) Sampling" src="https://user-images.githubusercontent.com/98666231/172074074-9845c6f6-6460-40e0-a720-23cea22286fa.png">
Balanced Accuracy Score: 0.5441784794709592.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.72
  Low_Risk:0.57

### 5. Balanced Random Forest Classifier 
<img width="650" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/98666231/172074077-323f4f5a-9244-4f3e-8542-05990e3f99bd.png">
Balanced Accuracy Score: 0.7885466545953005.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.70
  Low_Risk:0.87

### 6. Easy Ensemble AdaBoost Classifier
<img width="651" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/98666231/172074082-95b4e20b-201e-4eb5-bb58-e2d2de7ef373.png">
Balanced Accuracy Score: 0.9316600714093861.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.92
  Low_Risk:0.94

## Summary
All the models that were used showed a very poor precision for for calculating credit risk. The majority of the balanced accuracy score is 54-93%.
From my observations the best model to use is the Easy Ensemble AdaBoost Classifier because overall it had the highest score for balance, precision, and recall.



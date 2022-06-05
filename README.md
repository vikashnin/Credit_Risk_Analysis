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
  
### 2. SMOTE Oversampling
<img width="807" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/98666231/172072534-646a6450-41b1-4478-8d7e-b6aca3d4ee36.png">
Balanced Accuracy Score: 0.6623356588465208.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.63
  Low_Risk:0.69
 
### 3. Undersampling
<img width="804" alt="Undersampling" src="https://user-images.githubusercontent.com/98666231/172072537-461e5a5d-8a05-4cfa-bd21-6d39cdcc1d33.png">
Balanced Accuracy Score: 0.5442166848817717.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.69
  Low_Risk:0.40
  
### 4. Combination (Under and Over) Sampling 
<img width="804" alt="Combination (Over and Under) Sampling" src="https://user-images.githubusercontent.com/98666231/172072539-1c90f55e-8aff-4da9-b5e6-bfb14ce4bbb9.png">
Balanced Accuracy Score: 0.5441784794709592.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.72
  Low_Risk:0.57

### 5. Balanced Random Forest Classifier 
<img width="797" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/98666231/172072542-107340fc-0e4e-4e7d-a8ac-9441d092ba91.png">
Balanced Accuracy Score: 0.7885466545953005.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.70
  Low_Risk:0.87

### 6. Easy Ensemble AdaBoost Classifier
<img width="805" alt="Easy Ensemble AdaBoost Classidier" src="https://user-images.githubusercontent.com/98666231/172072550-68a58777-6945-4dbc-939d-f2934d1b98f3.png">
Balanced Accuracy Score: 0.9316600714093861.
Precision Score: The precision for high_risk loans is low and the low_risk loans is high.
Recall Score
  High_Risk:0.92
  Low_Risk:0.94

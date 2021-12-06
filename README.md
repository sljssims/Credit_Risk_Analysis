### Credit Risk Analysis
The purpose of this analysis is to develop a learning model that can detect high risk loans based on data provided. Using sklearn we compared various sampling nmodels to determine which model is the best fit. 

# RandomOverSampler Model
- Accuracy Score is 64%
- Precision High Risk Score is 1%
- Precision Low Risk score is 100%
- Recall High Risk Score is 74%
# Naive Random Oversampling
![Naive Random Oversampling](https://user-images.githubusercontent.com/87907584/144817378-0f53981e-c35b-4829-82d1-aadc300a3130.PNG)

# SMOTE Model
- Accuracy score 66%
- Precision High Risk Score 1%
- Precision Low Risk Score is 100%
- Recall High Risk Score is 63%
- Recall Low risk score is 69%
# Smote Oversampling 
![SMOTE Oversampling](https://user-images.githubusercontent.com/87907584/144817982-039883c7-c8c3-423c-bcea-6be964192888.PNG)


# ClusterCentroids Model
- Accuracy Score is 54%
- Precision High Risk Score is 1%
- Precision Low Risk Score is 100%
- Recall High Risk Score is 67%
- Recall Low Risk Score is 42%
# Undersampling
![Undersampling Model](https://user-images.githubusercontent.com/87907584/144816842-c827faf4-a1f4-4885-80c8-f90aeb713d41.PNG)


# SMOTEENN Model
- Accuracy Score is 66%
- Precision High Risk Score is 1%
- Precision Low Risk Score is 100%
- Recall High Risk Score is 63%
- Recall Low Risk Score is 69%
# Combination (Over and Under) Sampling
![SMOTE Oversampling](https://user-images.githubusercontent.com/87907584/144817982-039883c7-c8c3-423c-bcea-6be964192888.PNG)

# BalancedRandomForest Classifier Model
- Accuracy Score is 78%
- Precision High Risk Score is 3%
- Precision Low risk Score is 100%
- Recall High Risk Score is 70%
- Recall Low Risk Score is 87%
# Balanced Random Forest Classifier
![Balanced Randon Forrester](https://user-images.githubusercontent.com/87907584/144816763-3c323a06-20a9-4e96-bddf-435162db7537.PNG)
)
# Easy Ensemble Classifier Model
- Accuracy Score is 93%
- Precision High Risk Score is 9%
- Precision Low Risk Score is 100%
- Recall High Risk Score is 92%
- Recall Low Risk Score is 94%

# EasyEnsembleAdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/87907584/144816732-382c8823-d9dc-4143-b404-dc45a2bc1545.PNG)


### Summary
The results show that the Ensemble Classifiers appear to perform the best.  The purpose of the analysis is to determine which models can accurately predict when a loan is high risk. By comparing the recall high risk score between all machine learning models we can see the the easy ensemble Classifier models hat the highest scores at 78% and 93%.  As a result, I would use the Easy Ensemble Classifer models for predicting high risk loans. 

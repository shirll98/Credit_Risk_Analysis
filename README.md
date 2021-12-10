# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis 
In this data analysis I used Python and machine learning models to predict credit risks in a dataset. In addition, these machine learning models will be evaluated and compared to each other. 
## Results 
### RandomOverSampler model 
The balance accuracy score is 0.63 and high risk precision is 0.01. 
### SMOTE model 
The balance accuracy score is 0.63 and high risk precision is 0.01. 
### ClusterCentroids model 
The balance accuracy score is 0.51 and high risk precision is 0.01. 
### SMOTEENN model 
The balance accuracy score is 0.78 and high risk precision is 0.04. 
### BalancedRandomForestClassifier model 
The balance accuracy score is 0.78 and high risk precision is 0.04. 
### EasyEnsembleClassifier model 
The balance accuracy score is 0.92 and high risk precision is 0.07. 
## Summary 
The models in this analysis show relatively lower precision in determining the credit risk. The Ensemble model shows more sensitivity on credit risk analysis. The Easy Ensemble Classifier model seems to detect most of the high risk credit. These models do not accurately predict credit risk. 

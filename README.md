# Credit_Risk_Analysis
# Overview
The purpose of the analysis is to evaluate three machine learning models - Logistic Regression, SMOTEENN, and 2 Ensemble Classifiers (Balanced Random Forest Classifier & Easy Ensemble Classifier) - to determine which is better at predicting credit risk.

# Results
1. Logistic Regression - Naive Random Oversampling
  * Accurancy Score: .63  
  * High Risk:
    * Precision: .01, the ones identified as high risk are actually high risk
    * Sensitivity: .60, the one that we know are high risk are actually classified as high risk 
  * Low Risk:
    * Precision: 1.0 the ones identified as low risk are actually low risk
    * Sensitivity: .66, the one that we know are low risk are actually classified as low risk 
2. SMOTEE - Oversampling
  * Accurancy Score: .64  
  * High Risk:
    * Precision: .01, the ones identified as high risk are actually high risk
    * Sensitivity: .63, the one that we know are high risk are actually classified as high risk 
  * Low Risk:
    * Precision: 1.0 the ones identified as low risk are actually low risk
    * Sensitivity: .66, the one that we know are low risk are actually classified as low risk
3. Logistic Regression - Undersampling
  * Accurancy Score: .52  
  * High Risk:
    * Precision: .01, the ones identified as high risk are actually high risk
    * Sensitivity: .61, the one that we know are high risk are actually classified as high risk 
  * Low Risk:
    * Precision: 1.0 the ones identified as low risk are actually low risk
    * Sensitivity: .45, the one that we know are low risk are actually classified as low risk 
4. Logistic Regression - Combination Sampling
  * Accurancy Score: .63  
  * High Risk:
    * Precision: .01, the ones identified as high risk are actually high risk
    * Sensitivity: .61, the one that we know are high risk are actually classified as high risk 
  * Low Risk:
    * Precision: 1.0 the ones identified as low risk are actually low risk
    * Sensitivity: .66, the one that we know are low risk are actually classified as low risk 
5. Balanced Random Forest Classifier
  * Accurancy Score: .64  
  * High Risk:
    * Precision: .01, the ones identified as high risk are actually high risk
    * Sensitivity: .62, the one that we know are high risk are actually classified as high risk 
  * Low Risk:
    * Precision: 1.0 the ones identified as low risk are actually low risk
    * Sensitivity: .66, the one that we know are low risk are actually classified as low risk 
6. Easy Ensemble Classifier
  * Accurancy Score: .63  
  * High Risk:
    * Precision: .01, the ones identified as high risk are actually high risk
    * Sensitivity: .61, the one that we know are high risk are actually classified as high risk 
  * Low Risk:
    * Precision: 1.0 the ones identified as low risk are actually low risk
    * Sensitivity: .66, the one that we know are low risk are actually classified as low risk 

# Summary
Overall, I do not think any of these models have an accuracy score high enough to be used to predict credit risk. Additionally, they all have low precision, meaning that out of the ones that are identified high risk only a low number are actually classified as such.

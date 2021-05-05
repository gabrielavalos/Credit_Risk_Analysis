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
  * Accurancy Score: .87  
  * High Risk:
    * Precision: .03, the ones identified as high risk are actually high risk
    * Sensitivity: .70, the one that we know are high risk are actually classified as high risk 
  * Low Risk:
    * Precision: 1.0 the ones identified as low risk are actually low risk
    * Sensitivity: .87, the one that we know are low risk are actually classified as low risk 
6. Easy Ensemble Classifier
  * Accurancy Score: .94  
  * High Risk:
    * Precision: .09, the ones identified as high risk are actually high risk
    * Sensitivity: .92, the one that we know are high risk are actually classified as high risk 
  * Low Risk:
    * Precision: 1.0 the ones identified as low risk are actually low risk
    * Sensitivity: .94, the one that we know are low risk are actually classified as low risk 

# Summary
The Easy Ensemble Classifier model produced the highest accuracy score at .94. Additionally, Precision and Sensity for High Risk are both high, meaning that the ones identified as high risk, really are high risk and the ones we know are high risk, are actually classified as high risk.

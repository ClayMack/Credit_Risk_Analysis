# Credit_Risk_Analysis

## Analysis Overview
Utilizing Python to build and evaluate multiple machine learning models to predict credit risk.
The performance of these models will be used to make a recommendation on whether they should be used to predict credit risk.


Models used:
- **Naive Random Oversampling** 
- **SMOTE Oversampling**
- **Cluster Centroid Undersampling**
- **SMOTEENN Over and Under Sampling**
- **Balanced Random Forest Classifying** 
- **Easy Ensemble Classifying**.



## Resources
- Data Source: LoanStats_2019Q1.csv


## Results 

**Naive Random Oversampling results:**
- Accuracy: 65.5%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall (Sensitivity) High Risk: 72%
- Recall (Sensitivity) Low Risk: 59%

<p align="center">
  <img src="https://github.com/ClayMack/Credit_Risk_Analysis/blob/main/screenshots/Naive%20Random%20Oversampling.png">
</p>

**SMOTE oversampling results:**
- Accuracy: 66.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall (Sensitivity) High Risk: 63%
- Recall (Sensitivity) Low Risk: 69%

<p align="center">
<img width="1286" alt="smote" src="https://github.com/ClayMack/Credit_Risk_Analysis/blob/main/screenshots/SMOTE%20Oversampling.png">

**Cluster Centroid Undersampling:**
- Accuracy: 66.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall (Sensitivity) High Risk: 69%
- Recall (Sensitivity) Low Risk: 40%

<p align="center">
<img width="1315" alt="undersampling" src="https://github.com/ClayMack/Credit_Risk_Analysis/blob/main/screenshots/Cluster%20Centroid%20Undersampling.png">

**SMOTEENN Over and Under Sampling:** 
- Accuracy: 54.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall (Sensitivity) High Risk: 72%
- Recall (Sensitivity) Low Risk: 57%

<p align="center">
<img width="1355" alt="combination" src="https://github.com/ClayMack/Credit_Risk_Analysis/blob/main/screenshots/Combination%20(Over%20and%20Under)%20Sampling.png">

**Balanced Random Forest Classifier results:** 
- Accuracy: 76.1%
- Precision High Risk: 3%
- Precision Low Risk: 100%
- Recall (Sensitivity) High Risk: 65%
- Recall (Sensitivity) Low Risk: 87%

<p align="center">
<img width="1293" alt="random forest" src="https://github.com/ClayMack/Credit_Risk_Analysis/blob/main/screenshots/Balanced%20Random%20Forest%20Classifier.png">

**Easy Ensemble Classifying results:**
- Accuracy: 93.2%
- Precision High Risk: 9%
- Precision Low Risk: 100%
- Recall (Sensitivity) High Risk: 94%
- Recall (Sensitivity) Low Risk: 92%

<p align="center">
<img width="1353" alt="ensemble" src="https://github.com/ClayMack/Credit_Risk_Analysis/blob/main/screenshots/Easy%20Ensemble%20AdaBoost%20Classifier.png">

## Summary: 


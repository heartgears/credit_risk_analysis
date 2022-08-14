# credit_risk_analysis

## Overview
Given demographic data concerning applicants for loans - their marital and income status, previous loans, etc - the purpose of this analysis is to build machine learning models that can correctly predict whether a loan application is of high or low risk.

## Results
The first four machine learning models - Naive Random Oversampling, SMOTE, Cluster Centroids, and Smoteen, all delivered results that were just over a 50/50 shot in the dark, landing in the 60% balanced accuracy range. The results of these models were therefore subpar.

![Deliverable_1.1_Screenshot](https://github.com/heartgears/credit_risk_analysis/blob/main/Challenge/Screenshots/Naive_Random_Oversampling.png)

![Deliverable_1.2_Screenshot](https://github.com/heartgears/credit_risk_analysis/blob/main/Challenge/Screenshots/SMOTE_Oversampling.png)

![Deliverable_1.3_Screenshot](https://github.com/heartgears/credit_risk_analysis/blob/main/Challenge/Screenshots/ClusterCentroids_Results.png)

![Deliverable_2.1_Screenshot](https://github.com/heartgears/credit_risk_analysis/blob/main/Challenge/Screenshots/SMOTEENN_Results.png)

The final two models, Balanced Random Forest Classifier and Easy Ensemble Classifier (ADA Boost) both delivered superior results, while they delivered nearly identical recall scores, they landed at 78% and 87% balanced accuracy respectively. 

![Deliverable_3.1_Screenshot](https://github.com/heartgears/credit_risk_analysis/blob/main/Challenge/Screenshots/BRFC_Results.png)

![Deliverable_3.2_Screenshot](https://github.com/heartgears/credit_risk_analysis/blob/main/Challenge/Screenshots/EEC_ADABoost_Results.png)

## Summary

The Easy Ensemble Classifier is the best model for the purpose of this analysis. It delivered slightly better results than Balanced Random Forest Classifier, and vastly superior results to the other four utilized.

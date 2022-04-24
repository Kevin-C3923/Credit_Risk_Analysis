# Credit_Risk_Analysis

## Overview of the analysis:

The purpose of the analysis is to examine a credit card dataset and predict credit risk using algotithms like RandomOverSampler, SMOTE, ClusterCentroids, and SMOTEENN. Additionally, the machine learning models, BalancedRandomForestClassifier and EasyEnsembleClassifier, will be used reduce bias when predicting credit risk.

## Results:

### Naive Random Oversampling
![]( https://github.com/Kevin-C3923/Credit_Risk_Analysis/blob/main/Images/NaiveRandomOversampling.png )

### SMOTE Oversampling
![]( https://github.com/Kevin-C3923/Credit_Risk_Analysis/blob/main/Images/SMOTE_Oversampling.png )

### Undersampling ClusterCentroids 
![]( https://github.com/Kevin-C3923/Credit_Risk_Analysis/blob/main/Images/UndersamplingClusterCentroids%20.png )

### SMOTEENN
![]( https://github.com/Kevin-C3923/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.png )

### Balanced Random Forest Classifier
![]( https://github.com/Kevin-C3923/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassifier.png )

### Easy Ensemble AdaBoost Classifier
![]( https://github.com/Kevin-C3923/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble_AdaBoost_Classifier.png )

## Summary:

To summarize the results for the machine learning models, the precision average for the test showed strong results for all six, but doesn't mean much. When looking at the recall average, we can clearly see that both Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier had a higher percentage compared to the other four models. Additionally, these two models also performs well in the f1-score, ~90% - ~95%, while Undersampling ClusterCentroids performs the worse, 56%, and the other three are more or less average, ~70% - ~80%.

With all six models giving varying results and having minor similarity, I felt that either Balanced Random Forest Classifier or Easy Ensemble AdaBoost Classifier would be the ideal models to use as the results showed higher percentage in the chart.

# Credit_Risk_Analysis

# Overview

The purpose of this project is use machine laerning to predict credit risk and provide quick and reliabe loan experience. 

Techniques used:
- #RandomOverSampler and #SMOTE algorithms to oversample the data
- #ClusterCentroids to undersample the data
- #Over and #undersampling using the SMOTEENN algorithm.

# Resources
- Software: Visual Studio Code, Jupyter Lab
- Languages: Python
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn

# DERIVABLE

## Naive Random Oversampling

![Naive_Random_Oversampling.png](https://github.com/jeperes/Credit_Risk_Analysis/blob/main/Resources/Naive_Random_Oversampling.png)

## SMOTE Oversampling

![SMOTE_Oversampling.png](https://github.com/jeperes/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Oversampling.png)

## ClusterCentroids model 

![Cluster_Centroids.png](https://github.com/jeperes/Credit_Risk_Analysis/blob/main/Resources/Cluster_Centroids.png)

## Combination Sampling Smoteenn

![SMOTEENN_Combination_Sampling.png](https://github.com/jeperes/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN_Combination_Sampling.png)

## Balanced Random Forest Classifier

![Balanced_RandomForest_Classifier.png](https://github.com/jeperes/Credit_Risk_Analysis/blob/main/Resources/Balanced_RandomForest_Classifier.png)

## Easy Ensemble AdaBoost Classifier

![EasyEnsemble_AdaBoostClassifier.png](https://github.com/jeperes/Credit_Risk_Analysis/blob/main/Resources/EasyEnsemble_AdaBoostClassifier.png)

# Summary

Both Emsemble and Resambling techniques show very accurate predction of high-risk credit card applicants and low-risk applicants. 
The EasyEnsembleClassifier model detects almost all high risk credit with 92% recall. But the low precision, a lot of low risk credits are still falsely detected as high risk. 
Since the models are not very accurate, I woudn't recommend being used to predict credit risk.




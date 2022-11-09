# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to identify credit card risk for high versus low risk loans. As this issue is inherently imbalanced (more low risk loans than high risk), this analysis utilizes imbalanced machine learning to identify the probabilities.

## Results

Results of splitting and training data
![split_test_train.png](./Data/split_test_train.png)

Results of RandomOverSampler
![oversampling.png](./Data/oversampling.png)

Results of SMOTE Oversampling
![smote_oversampling.png](./Data/smote_oversampling.png)

Results of ClusterCentroids Undersampling
![undersampling.png](./Data/undersampling.png)

Results of SMOTEENN Sampling
![combo_sampling.png](./Data/combo_sampling.png)

Results of Balanced Random Forest Classifer
![balanced_random.png](./Data/balanced_random.png)

Results of Easy Ensemble AdaBoost Classifier
![adaboost.png](./Data/adaboost.png)

## Summary
Due to the imbalanced nature of the dataset (high risk vs. low risk) it seems there isn't much difference in the resulting data according to machine learning method. The results that see the biggest difference are the ensemble classifiers, Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier. I would reccommend using these models for further analysis as a greater difference is seen and can be used in making a wider scale for decision-making.

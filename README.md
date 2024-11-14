# Breast-Cancer-Prediction
## Overview
The dataset has been obtained from the UC Irvine Machine Learning repository. (Breast Cancer Wisconsin diagnostic). A number of parameters have been used to detect the traits of a tumor, (malignant or benign). The dataset consists of 569 entries with varying parameters that factor into the behaviour of the tumor. These parameters have been taken into account by the logistic regression model to predict whether or not a certain case has a malignant tumor.

## Implementation
The dataset has been taken from Breast Cancer Wisconsin (Diagnostic). The feature values in the diagnosis have been deduced based on a paper "Nuclear feature extraction for breast tumor diagnosis" by W.Street, W.Wolberg, O.Mangasarian published on 29th July 1993. In this logistic regression model, the redundant and common features have been eliminated from the dataset for better accuracy in the prediction. The result (malignant or benign), has been converted into a binary series of 0 for benign and 1 for malignant. The dataset is then divided into parameters and target. The parameter dataframe has been normalised for higher precision in determining the prediction. The data is then split into 70% for the training set and 30% for the testing set. The predictions have then been evaluated, which resulted in a 96% accuracy and 98% precision. These statistics are highly positive, and can be used in real life applications of detecting a malignant tumor early and possibly giving the patient a better chance at recovery. (The logistic regression model has not been scikitlearn, thus it might be off by a little factor).

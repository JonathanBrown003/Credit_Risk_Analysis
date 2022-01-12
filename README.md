# Credit_Risk_Analysis
Using structured machine learning to make financial credit decisions.

## Overview
The purpose of this analysis is to predict credit risk using machine learning algorithms based on a data set composed of features. The objective is to find creditworthy candidates for loans which should ensure low loan default rates. Different machine learning models were used for this task and their results were analyzed by calculating balanced accuracy, precision and recall scores.

## Results Pt. 1 - Logistic Regression

### Random Oversampling
- Balanced Accuracy: 67.4%
- Precision and Recall: This model predicted high risk datapoints with a precision of 0.01 and a recall of 0.60

### SMOTE Oversampling
- Balanced Accuracy: 65.8%
- Precision and Recall: This model predicted high risk datapoints with a precision of 0.01 and a recall of 0.63

### Clustercentroids Model
- Balanced Accuracy: 43.5%
- Precision and Recall: This model predicted high risk datapoints with a precision of 0.01 and a recall of 0.60

### SMOTEEN sampling
- Balanced Accuracy: 53.8%
- Precision and Recall: This model predicted high risk datapoints with a precision of 0.01 and a recall of 0.71

## Results Pt. 2 - Ensemble Classifiers

### Random Forest Classifier
- Balanced Accuracy: 90.7%
- Precision and Recall: This model predicted high risk datapoints with a precision of 0.04 and a recall of 0.67

## Summary

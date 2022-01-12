# Credit_Risk_Analysis
Using structured machine learning to make financial credit decisions. The main objective is to spot high credit risk applicants with these different models. 

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
The Random Forest Classifier had the highest balanced accuracy of any of the models at 90.7%. It is however very adept at predicting low risk applicants as opposed to high risk applicants which is the objective. 
All of the models had low precision scores which means they have a low probability in classifying an applicant as a true positive or high credit risk - they have low positive predictive value. They may in actuality classify a low credit risk as a high credit risk. With all models displaying low precision, I would not recommend any of these models as an inaccurate model could lead to a myriad of legal and credibility issues in practice. 

# Breast-Cancer-Prediction

In this Kaggle dataset, I built classfication models using decision tree, KNN, logistic regression, and SVM to predict the diagnose result based on ten real-valued features. Also, I applied cross validation and grid serach technique to find the best parameter and avoid ovetfitting. Finally, based on accuracy scores, I found the logistic regression model performed the best. {'Decision Tree': 0.94, 'KNN': 0.96, 'Logistic Regression': 0.98, 'SVM': 0.97}. To provide more information on model performace, I calculated classification report, AUC, kappa, MCC and plotted the ROC curve.

## About Data
Data: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data

Description: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer%02wisconsin/wdbc.names

## Action
- Data Exploratory Analysis: Get the top3 highest correlated features
- Cross validation
- Modeling: decision tree, KNN, Logistic Regression, SVM
- Confusion Matrix: Get the best score/estimator on each model

## Result
Based on the classification report, AUC, kappa, MCC and plotted the ROC curve, the **logistic regression** model performed the best.


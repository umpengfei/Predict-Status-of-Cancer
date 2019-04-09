# Predict-Status-of-Cancer

## Description

Propose a machine learning model to predict whether the cancer is benign or malignant. The data set is from Kaggle datasets (https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). The whole features of the data set can be grouped into three groups(Mean, Standard Error, Worst). Each of them contains 10 features, thus resulting in 30 features together. 

Based on this characteristic of the data set, there will be two possible approaches. The first one is to deal those 30 features together. And second one is to deal those three groups separately and then choose the best one. This project will 
take both of the them and then choose a better predict result.

For each approach, this project will use three Machine Learning Models (gradientBoosting, logisticRegression, kNeighborsClassifier) one by one and take the best model.



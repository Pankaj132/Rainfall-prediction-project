# Rainfall-prediction-project
Rainfall_prediction project based on logistic regression

## some importan points in the project

## Data Preprocessing:

Missing Values Handled by Random Sample imputation to maintain the variance

Categorical Values like location, wind direction are handled by using Target guided encoding
Outliers are handled using IQR and boxplot

Feature Selection and was done but didnt perform well it can be seen in testing_notebook/Prediction.ipynb

Feature Scaling didnt give a lot of difference it also can be seen in testing_notebook

Used Barplot to check the relation between the dataset, and also used distplot to check whether data is normally distributed or skewed.

main model comes into the picture which is used to check whether the dataset I had built is working well or not by using Logistic Regression. Accuracy_score using Logistic Regression is coming to 90%.

While using some metrics of classification like precision, recall, and F1 score my model is working well.

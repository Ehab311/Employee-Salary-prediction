# Income Prediction Model 
## Overview
This repository contains code for building a machine learning model to predict income based on various demographic and employment-related features. The model aims to classify whether an individual's income is above or below $50,000 per year.

## Code Files:

income_prediction.ipynb: Jupyter Notebook containing Python code for data preprocessing, model building, and prediction.
train.csv: Dataset containing training data.
test.csv: Dataset containing test data.
README.md: This file, providing an overview and instructions for using the code.


## Data Preprocessing:

Handle missing values.
Clean categorical data by removing outliers and visualizing distributions.
Bucket categorical variables for better representation.
Encode categorical data (label encoding for ordinal data and one-hot encoding for nominal data).
Normalize numerical data.
## Model Building:

Train various classifiers including CatBoostClassifier, LogisticRegression, RandomForestClassifier, AdaBoostClassifier, and ExtraTreesClassifier.
Evaluate models and select the best performing one.
## Prediction:

Use the trained model to predict income on the test dataset.
Save the predictions as CSV files for further analysis.
Results
The trained model achieves satisfactory performance in predicting income based on the provided features. Detailed results and predictions are available in the corresponding CSV files.

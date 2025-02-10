# Heart Failure Detection
## Overview
This repository contains code for a heart disease prediction model built using Python. The model aims to predict the likelihood of heart disease based on various demographic and health-related features.

## Exploratory Data Analysis
The dataset used for training the model contains information such as age, sex, cholesterol levels, resting blood pressure, and more. Exploratory data analysis was conducted to understand the distribution and relationships between different features.

## Data Visualization
Distribution of Heart Failure: A pie chart illustrates the distribution of heart failure cases in the dataset, showing that 53.3% of the individuals had heart disease.
Distribution of Sex: A pie chart displays the distribution of sex in the dataset, indicating that approximately 79% of the data is from men.
Histograms: Histograms are plotted for each numerical variable to visualize their distributions.
Diagnostic Plots
Diagnostic plots, including histograms, scatter plots, box plots, and bar plots, are generated to explore relationships between numerical variables and the presence of heart disease.

## Outlier Detection
Outliers in numerical variables such as resting blood pressure and cholesterol levels were identified using the Interquartile Range (IQR) method.

## Data Preprocessing
Missing Value Imputation: Simple imputation was performed to replace missing values in certain features with the median of the respective columns.
Label Encoding: Categorical variables were encoded using label encoding to convert them into numerical format.
Feature Scaling: Standardization was applied to numerical features to bring them to a common scale.

## Model Building
Four machine learning models were implemented and evaluated:
Logistic Regression
K-Nearest Neighbor Classifier
Support Vector Machine
Decision Tree Classifier

## Hyperparameter Optimization
The Hyperopt library was used for hyperparameter optimization to fine-tune the Support Vector Machine model. The optimized model achieved an accuracy score of 89.13% on the test dataset.

## Conclusion
The heart disease prediction model demonstrates promising performance in accurately predicting the likelihood of heart disease based on the provided features. Further analysis and refinement can be explored to enhance the model's effectiveness in real-world applications.

For more details and code implementation, refer to the Jupyter Notebook provided in this repository.

# Hearing-test-logistic-regression
Hearing Test Data Analysis and Classification
This repository contains code for analyzing hearing test data and performing a classification task using machine learning. The dataset used in this analysis is "hearing_test.csv."

# Contents
1.Introduction <br>
2.Requirements <br>
3.Usage <br>
4.Data Cleaning <br>
5.Feature Engineering <br>
6.Exploratory Data Analysis (EDA) <br>
7.Machine Learning Classification <br>
8.Results and Evaluation <br>

# Introduction
The goal of this project is to analyze hearing test data and build a classification model to predict test results based on various features, such as age, physical score, and more. This README provides an overview of the code and its usage.

# Requirements
Before running the code, ensure you have the following dependencies installed:

Python (>= 3.7)
scikit-learn (for machine learning)
pandas (for data manipulation)
numpy (for numerical operations)
seaborn (for data visualization)
matplotlib (for creating plots)

# Usage
 Data Preparation: Make sure you have the dataset, "hearing_test.csv," available. You can replace this file with your own data if needed.

 Run the Code: Execute the provided Python script in your favorite Python environment (e.g., Jupyter Notebook or a code editor).

 Review the Results: The code performs the following steps:

1.Data cleaning: Missing values are imputed with the mean. <br>
2.Feature engineering: Polynomial features are generated to capture non-linear relationships. <br>
3.Exploratory Data Analysis (EDA): Data visualizations and analysis are conducted. <br>
4.Machine Learning Classification: A Logistic Regression model is trained and evaluated for test result prediction. <br>
5.Results and Evaluation: Accuracy, confusion matrix, and classification report are displayed. <br>

# Data Cleaning
The dataset is loaded and missing values are imputed using the mean value of each column.

# Feature Engineering
Polynomial features up to the third degree are generated to capture non-linear relationships in the data.

# Exploratory Data Analysis (EDA)
Count plot: Shows the distribution of test results.<br>
Box plots: Establish relationships between test results and age and physical scores.<br>
Scatter plot: Visualizes the relationship between age and physical score, with test result categories indicated by color.<br>

# Machine Learning Classification
A Logistic Regression model is trained and evaluated for predicting test results. Data is split into training and testing sets, and features are scaled.

# Results and Evaluation
The model's performance is evaluated using accuracy, a confusion matrix, and a classification report. Visualizations are also provided to aid in result interpretation.

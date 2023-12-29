# Loan Prediction

This project analyzes and predicts loan approval status based on various features.

## Overview

This project aims to understand the factors influencing loan approval decisions and build predictive models to forecast whether a loan application will be approved or not.

## Dataset

The dataset used in this project contains information about loan applicants, including features such as gender, education, income, loan amount, and more.

## Data Preprocessing

To prepare the data for modeling, missing values were handled using forward filling, and categorical variables were encoded. Additionally, feature scaling was applied to ensure a consistent scale across features.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) was conducted to gain insights into the dataset. Visualizations such as histograms and a correlation matrix were used to understand the distribution of variables and relationships between them.

## Modeling

The following machine learning models were trained and evaluated for loan prediction:

### 1- Logistic Regression

Logistic Regression is a widely used algorithm for binary classification. The model was trained on the preprocessed data, and its performance was evaluated using classification metrics.

### 2-Support Vector Machine (SVM)

A Support Vector Machine with a radial basis function (RBF) kernel was employed for its ability to handle complex relationships. The SVM model's accuracy score was used as an evaluation metric.

### 3-Random Forest

The Random Forest model, known for its robustness and ensemble learning approach, was trained and evaluated using accuracy scores.

### 4-K-Nearest Neighbors (KNN)

K-Nearest Neighbors, a simple yet effective algorithm, was used for loan prediction. Both training and testing performance were assessed.

## Conclusion

In conclusion, this project provides insights into loan approval predictions based on different machine learning algorithms. The models were evaluated, and their performances compared. Future work may involve fine-tuning the models or exploring additional features.



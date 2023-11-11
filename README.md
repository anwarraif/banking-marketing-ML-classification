# banking-marketing-ML-classification

## Project Overview

This project involves the implementation of a classification model using various machine learning algorithms to predict a target variable. 
The dataset is loaded, preprocessed, and used to train different classification models. 
The evaluation of the models is conducted using metrics such as confusion matrix, learning curves, and other relevant performance indicators.
## Overall Steps:
1. Import all Libraries & Load the Dataset
   Import necessary libraries for data manipulation, visualization, and machine learning.
   Load the dataset for analysis.

2. Split Data (Train and Test)
   Divide the dataset into training and testing sets for model training and evaluation.

3. Exploratory Data Analysis (EDA)
   Analyze categorical and numerical data for insights into the dataset.

4. Removing Redundant Variables
   Identify and remove redundant variables based on business value.

5. Data Preparation: Data Train
    Drop duplicated data.
    Analyze and handle outliers.
    Handle missing values.

6. Data Preparation: Data Test
  Drop duplicated data.
  Analyze and handle outliers.
  Handle missing values.

7. Split Data into Xtrain, ytrain, Xtest, ytest
   Separate features (X) and target variable (y) for both training and testing sets.

8. Encoding Preparation
        Prepare the data for encoding.

9. Encode Separately for Data Train and Data Test
        Perform encoding on categorical variables for both training and testing sets.

10. Split Xtrain and Xtest into Different Categories

    Split the features into different categories.

11. Standard Scaler
    Standardize the features using Standard Scaler.

12. Modelling Classification ML Algorithms:
    Logistic Regression
    K-Nearest Neighbor (KNN)
    Naive Bayes
    Support Vector Machine (SVM)

13. Evaluation Model:
    Confusion Matrix Evaluation
    Learning curve Regression
    Learning curve K-Nearest Neighbor (KNN)
    Learning curve Naive Bayes
    Learning curve Support Vector Machine (SVM)

## Requirements :
pandas: 1.5.3
numpy: 1.24.3
matplotlib: 3.7.1
seaborn: 0.12.2
plotly: 5.9.0
scipy: 1.10.1
scikit-learn: 1.3.0

#Tags 
banking, classification, machine learning, deposito

# House Price Prediction

This project is a student-level machine learning project based on the Kaggle competition:

[House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)

The goal is to predict house sale prices using property characteristics from the Ames Housing dataset. This project was developed to practice exploratory data analysis, data preprocessing, regression models, model evaluation, and learning from data.

## Dataset

The dataset is provided by the Kaggle House Prices competition.

The main files used in this project are:

- train.csv: training data with the target variable SalePrice
- test.csv: test data without SalePrice
- data_description.txt: descriptions of the dataset features
- sample_submission.csv: example Kaggle submission format

## Project Workflow

- Load and inspect the dataset
- Analyze missing values
- Distinguish structural missing values from real missing values
- Explore numerical and categorical features
- Analyze the SalePrice distribution
- Inspect potential outliers
- Split the data into training and validation sets
- Apply encoding and scaling with a scikit-learn pipeline
- Train a baseline regression model
- Train and tune a Ridge regression model
- Evaluate models using MAE, RMSE, and R2

## Current Model

The current tuned model is a Ridge regression pipeline. It includes preprocessing for numerical and categorical features and saves the trained model as:

    models/best_ridge_model.joblib

## Evaluation Metrics

- MAE: Mean Absolute Error
- RMSE: Root Mean Squared Error
- R2: Coefficient of Determination

## Project Status

The exploratory data analysis, missing-value handling, outlier inspection, preprocessing, and initial Ridge model experiments have been completed. Future steps include comparing additional regression models, applying cross-validation, and creating a Kaggle submission.

## Developer

Baris AK
Artificial Intelligence and Data Engineering Student

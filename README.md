# **House Price Prediction Project**

This repository contains a machine learning project that predicts house prices using the California Housing dataset. The project involves data cleaning, exploratory data analysis (EDA), feature engineering, model building with linear regression, and evaluation of the model's performance.

## Project Structure

1. house_price_prediction.ipynb: Jupyter notebook containing the Python code for the project.

2. housing.csv: Dataset used for training and testing the model.

3. README.md: This file, providing an overview of the project.

 4.`predicted_prices.xlsx`: Excel file showing actual vs predicted house prices.

## Project Overview

The project includes the following steps:

1. Loading and Unzipping the Dataset:  The California Housing dataset is loaded and unzipped from the provided ZIP file.

2. Data Cleaning:  Handling missing values and duplicates in the dataset to ensure data quality.

3. Feature Engineering and Selection: Selecting relevant features (total_bedrooms, total_rooms, median_income) based on domain knowledge and availability.

4. Exploratory Data Analysis (EDA):  Visualizing relationships between selected features and the target variable (median_house_value) using pair plots and correlation matrices.

5. Model Building:  Using a linear regression model to predict house prices. The data is split into training and testing sets, the model is trained, and predictions are made on the test set.

6. Model Evaluation:  Evaluating the model's performance using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared. Cross-validation is also performed to validate the model.

7. Results Visualization:  Visualizing model predictions compared to actual prices, plotting residuals to check for model performance.

## Requirements

1. Python 3.x
2. Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn

## Results

* The model achieved a test RMSE of X, MAE of Y, and R-squared of Z, indicating reasonable predictive performance.
* Residuals are normally distributed, suggesting that the model assumptions are met.
* The file `predicted_prices.xlsx` contains a comparison of actual and predicted house prices, providing insights into model accuracy.

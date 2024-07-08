# Predicting Diamond Prices

## Overview
Welcome to the "Predicting price of diamonds" repository! This project is part of the Business Analytics course (23/24) and aims to predict the price of diamonds using the diamonds dataset from the ggplot2 package. The main goal is to build predictive models that can accurately estimate diamond prices based on various features provided in the dataset.

## Dataset
The diamonds dataset contains nearly 54,000 observations with attributes such as carat weight, cut, color, clarity, dimensions (x, y, z), and price. The primary target variable for prediction is the diamond's price, which is a numerical variable.

## Exploratory Data Analysis
Before diving into modeling, it's essential to explore the distribution of the target variable price. Initially, we observe a right-skewed distribution, indicating that many diamonds have higher prices than expected under a normal distribution.

## Preprocessing
To enhance model performance, we transform the price variable using its logarithm (log_price). This transformation helps in dealing with the skewed distribution, making the target variable more suitable for predictive modeling.

## Features
The dataset includes both categorical (cut, color, clarity) and numeric (carat, dimensions) features. These features are analyzed for correlations and transformations to improve the accuracy of our predictive models.

## Models
Two primary predictive models are explored:

- Regularized Regression (glmnet)
- Boosted Trees (using xgboost)

These models are trained and evaluated using cross-validation techniques to ensure robustness and generalizability.

## Evaluation
Performance metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (rsq) are used to evaluate and compare model performance. The model with the best performance metrics will be selected for predicting diamond prices.

## Conclusion
This repository provides a comprehensive exploration and predictive modeling of diamond prices using the diamonds dataset. It includes detailed steps from data preprocessing to model evaluation, aiming to provide insights into predicting diamond prices accurately.

For more details, you can view the full analysis [here](https://rpubs.com/ljerocha/1202684).

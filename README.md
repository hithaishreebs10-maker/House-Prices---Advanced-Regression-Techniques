## Project Overview

This project implements a Linear Regression model to predict house prices using the popular Kaggle dataset House Prices: Advanced Regression Techniques. The model estimates the selling price of houses based on important features such as living area, number of bedrooms, and number of bathrooms.

The goal of this project is to demonstrate the end-to-end machine learning pipeline including data preprocessing, model training, evaluation, and prediction.

## Objectives

Predict house sale prices accurately

Apply Linear Regression for supervised learning

Perform data preprocessing and feature selection

Evaluate model performance using standard metrics

## Dataset

Dataset used: House Prices — Advanced Regression Techniques

Source: Kaggle
File used: train.csv

## Features Used

GrLivArea — Above ground living area (square feet)

BedroomAbvGr — Number of bedrooms

FullBath — Number of bathrooms

SalePrice — Target variable (house price)

## Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib (optional for visualization)

## Project Workflow
1 Data Collection

Download dataset from Kaggle

Load using pandas

2 Data Preprocessing

Select relevant features

Handle missing values

Split dataset into training and testing sets

3 Model Training

Apply Linear Regression

Train model on training data

4 Model Evaluation

Mean Squared Error (MSE)

R² Score

5 Prediction

Predict house price for new input data

## Evaluation Metrics

Mean Squared Error (MSE) — Measures prediction error

R² Score — Measures model accuracy

Typical performance with selected features:

R² Score: ~0.60 – 0.75

## Future Improvements

Use more features for better accuracy

Apply advanced models (Random Forest, XGBoost)

Perform feature engineering

Add hyperparameter tuning

Build web app using Flask or Streamlit

## License

This project is for educational purposes.

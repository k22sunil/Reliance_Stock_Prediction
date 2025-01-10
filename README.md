# Reliance_Stock_Prediction
Machine learning models for predicting Reliance stock prices.

Here's the refined README with updated MSE presentation for better clarity and precision:

#Reliance Stock Prediction Using Machine Learning#
Project Description
This project applies machine learning algorithms to predict the future stock prices of Reliance Industries (RELIANCE.NS). The objective is to analyze historical data and provide predictions to assist investors and analysts in making informed decisions.

The project leverages various models, including Support Vector Regression (SVR), Random Forest, K-Nearest Neighbors (KNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU) neural networks, to compare their performance and identify the most accurate predictive model.

Features
Fetches real-time stock data from Yahoo Finance.
Implements data preprocessing, including scaling and splitting into train/test sets.
Utilizes multiple machine learning models for prediction.
Compares model performances using Mean Squared Error (MSE).
Saves and loads the best-performing model for future predictions.
Visualizes feature importance for interpretability.
Hyperparameter optimization using GridSearchCV
Results
Model Performances
Below are the Mean Squared Error (MSE) values for each model:

Model	MSE
Support Vector Regression (SVR)	22,063.37
Random Forest	403.62
K-Nearest Neighbors (KNN)	585.91
Long Short-Term Memory (LSTM)	3,277.20
Gated Recurrent Unit (GRU)	1,680.55
Best Model
Random Forest outperforms all other models with the lowest MSE of 403.62, making it the most reliable model for predicting Reliance stock prices.

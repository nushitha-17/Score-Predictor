InningForecast: Machine Learning-Based IPL Score Predictor
📌 Project Overview

InningForecast is a machine learning project designed to predict the total score of an IPL innings based on match conditions and historical data. The model leverages multiple regression algorithms to provide accurate score predictions in real-time scenarios.

This project is especially useful for:

Cricket analysts
Fantasy sports players
Data science learners exploring sports analytics
🎯 Objective

The main goal of this project is to:

Predict the final score of an IPL innings
Analyze how different factors (overs, wickets, runs, etc.) influence outcomes
Compare the performance of different machine learning models
📊 Dataset
Dataset used: ipl.csv
Contains ball-by-ball IPL match data
Key features:
Batting team
Bowling team
Current score
Overs completed
Wickets fallen
Runs in last 5 overs
⚙️ Technologies Used
Python
Pandas – Data preprocessing
NumPy – Numerical operations
Scikit-learn – Machine learning models
Matplotlib / Seaborn – Data visualization
Jupyter Notebook – Development environment
🧠 Machine Learning Models Used
Linear Regression
Random Forest Regressor
XGBoost Regressor
🔄 Project Workflow
Data Collection
Loaded IPL dataset from CSV file
Data Preprocessing
Removed irrelevant columns
Handled missing values
Converted categorical data (teams) using encoding
Feature Engineering
Created features like:
Runs in last 5 overs
Wickets fallen
Overs completed
Model Training
Split data into training and testing sets
Trained multiple models
Model Evaluation
Compared models using:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Prediction
Predicted final score based on live match inputs
📈 Results
Random Forest and XGBoost performed better than Linear Regression
The model can predict IPL scores with reasonable accuracy
Helps understand match dynamics effectively

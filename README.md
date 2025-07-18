# Stock-Price-Prediction

This project uses historical stock data to predict future prices using machine learning models. The aim is to understand how past trends can help forecast future stock movements.

## Project Overview

- Predicts stock prices using time-series data (Open, High, Low, Close)
- Uses sliding windows (e.g., 30, 45, 60 days) as input features
- Compares different models and evaluates prediction performance
- Visualizes actual vs. predicted prices for clarity

## Tools and Technologies

- Python
- Pandas, NumPy
- Scikit-learn (KNN, Random Forest, Linear Regression)
- Matplotlib, Seaborn

## Model Performance

- Best performing model: K-Nearest Neighbors (KNN)
- Input window: 45-day High price
- Mean Absolute Error (MAE): Approximately 171

## Visualizations

- Historical stock price trends
- Moving averages for trend smoothing
- Actual vs. Predicted price comparison

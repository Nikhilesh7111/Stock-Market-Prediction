Stock Market Prediction Using Machine Learning

Overview


This project is focused on predicting stock market trends using historical data. The primary objective is to develop a Python application that leverages machine learning algorithms to forecast stock prices. Apple Inc. (AAPL) stock data from Yahoo Finance is used as the primary dataset for analysis and prediction.

Features
Fetching historical stock data using the yfinance library.
Preprocessing data to include relevant financial indicators, such as the 20-day Simple Moving Average (SMA).
Implementing a Linear Regression model to predict stock prices.
Evaluating the model's performance using the Mean Squared Error (MSE) metric.
Visualizing actual vs. predicted stock prices using matplotlib.
Technologies Used
Python
Pandas & NumPy: Data manipulation
yfinance: Downloading stock data
scikit-learn: Machine learning
Matplotlib: Data visualization
How It Works
Data Collection: The script fetches historical stock data for Apple Inc. from Yahoo Finance.
Data Processing: It calculates the 20-day SMA and uses it, along with other features like Open, High, and Low prices, to prepare the dataset.
Model Training: A Linear Regression model is trained with the processed data.
Prediction & Evaluation: The model predicts stock prices, and the predictions are evaluated using the MSE.
Visualization: The actual and predicted stock prices are plotted to visualize the model's effectiveness.

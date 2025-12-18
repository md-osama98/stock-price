# stock-price
Stock Price Prediction & Trend Analysis
Using LSTM with Attention Mechanism
An end-to-end Machine Learning project that predicts stock price trends using LSTM with a custom Attention mechanism, supports near real-time inference, and provides an interactive Streamlit dashboard for visualization.

Project Overview
Stock market data is inherently time-series, noisy, and non-linear.
This project leverages Long Short-Term Memory (LSTM) networks enhanced with an Attention mechanism to capture long-term dependencies and focus on the most influential historical time steps for accurate trend prediction.

The trained model is deployed using Streamlit, enabling interactive visualization and near real-time predictions using live market data from Yahoo Finance.

Key Features
Time-series forecasting using LSTM + Attention

Custom Attention layer for improved trend learning

Near real-time prediction with live stock data fetching

Interactive Streamlit web dashboard

Visualization of actual vs predicted prices

Model evaluation using RMSE & MAE

Modular and clean code structure

Deployment-ready ML pipeline

Tech Stack
Programming Language: Python 3.10

Deep Learning: TensorFlow / Keras

Data Processing: NumPy, Pandas, scikit-learn

Data Source: Yahoo Finance (yfinance)

Visualization: Matplotlib, Streamlit

Deployment: Streamlit Web App

Model Evaluation
The model performance is evaluated using:

RMSE (Root Mean Square Error)

MAE (Mean Absolute Error)

These metrics provide a realistic assessment of prediction accuracy on volatile financial data.

Dashboard Preview (What It Shows)
Actual vs Predicted stock prices

Latest trend direction (UP / DOWN)

Error metrics (RMSE, MAE)

Interactive controls for live data refresh

Use Cases
Stock trend analysis

Financial time-series forecasting



# LSTM Time Series Forecasting - NIFTY50

## Project Overview
This project implements an LSTM model for multi-step stock price forecasting using NIFTY50 dataset.

## Steps Followed
- Acquisition and loading of the dataset
- Data preprocessing and cleaning  
- Feature scaling using MinMaxScaler  
- Sequence creation using sliding window approach  
- LSTM model training for multi-step prediction  
- Evaluation using MSE, MAE, RMSE  
- Visualization of actual vs predicted values  

## Output
The model predicts the next 5 days of stock prices using the previous 10 days of data.

## Tools Used
Python, Pandas, NumPy, PyTorch, Scikit-learn, Matplotlib

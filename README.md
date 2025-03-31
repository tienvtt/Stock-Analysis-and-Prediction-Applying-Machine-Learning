## Project Overview
This project aims to **analyze and predict stock prices** using a combination of **quantitative analysis** and **machine learning models**, including **LSTM, GRU, and XGBoost**. 

## Project Objectives
- Perform **quantitative analysis** of stock market trends.
- Compute and analyze **technical indicators** such as **SMA, EMA, RSI, MACD**.
- Develop **predictive models** to forecast stock prices accurately.
- Compare the effectiveness of **LSTM, GRU, and XGBoost** for stock prediction.
- Provide **investment insights** based on model predictions.

## Technologies
- **Programming Language:** Python
- **Machine Learning:** LSTM, GRU, XGBoost

## Quantitative Analysis
The project includes a detailed analysis of stock market trends through:
- **Simple Moving Average (SMA):** Identifies trend direction.
- **Exponential Moving Average (EMA):** Weighs recent prices more heavily.
- **Relative Strength Index (RSI):** Measures stock momentum.
- **Moving Average Convergence Divergence (MACD):** Identifies trend changes and market momentum.

## Data & Features
The dataset is retrieved using **vnquant**, and various technical indicators are computed to enhance predictive accuracy. The dataset consists of historical stock data for financial services companies, obtained using **vnquant**:
**Stock Symbols:** SHB, VHM, FPT, HPG, HCM  
**Time**: from 2023-01-01 to 2025-03-26
**Features:** Open, High, Low, Close, Volume, Adjusted Close  
**Technical Indicators:** SMA, EMA, RSI, MACD  

## Model Implementation
- **Data Preprocessing:**
  - Data collected using **vnquant**.
  - Cleaned stock price data and computed technical indicators.
  - Normalized data for deep learning models.

- **Prediction Models:**
  - **LSTM & GRU:** Used for sequence-based forecasting.
  - **XGBoost:** Applied for feature-engineered time series prediction.
  - Hyperparameter tuning using **Grid Search and Bayesian Optimization**.

- **Performance Evaluation:**
  - Compared models using **MAE, MSE, RMSE, MAE, and MAPE**.
  - Visualized predictions vs. actual stock prices using **Matplotlib & Seaborn**.

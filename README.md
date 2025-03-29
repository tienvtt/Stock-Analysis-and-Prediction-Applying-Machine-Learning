# Stock-Analysis-and-Prediction-Applying-Machine-Learning
# Stock Market Prediction Using LSTM, GRU, and XGBoost

## Project Overview

This project focuses on **predicting stock prices** using advanced machine learning techniques, including **Long Short-Term Memory (LSTM)**, **Gated Recurrent Units (GRU)**, and **XGBoost**. By leveraging historical stock data and technical indicators, the models aim to provide insights for investment decision-making.

## Features
- **Data Collection & Preprocessing:**
  - Loaded and cleaned historical stock price data (Open, High, Low, Close).
  - Computed technical indicators such as **MACD, RSI, SMA, EMA**.
  - Normalized data for deep learning models (LSTM, GRU, XGBoost).

- **Model Implementation:**
  - Implemented **LSTM and GRU** for sequence-based forecasting.
  - Used **XGBoost** for tabular-based time series prediction.
  - Optimized hyperparameters using **Grid Search and Bayesian Optimization**.

- **Performance Evaluation:**
  - Compared models using **MAE, MSE, RMSE, and R2-Score**.
  - Visualized predictions vs. actual stock prices using **Matplotlib & Seaborn**.

## Dataset
The dataset consists of historical stock data from financial services companies, including:
✅ **Stock symbols:** SSI, VND, VCI, VIX, HCM  
✅ **Features:** Open, High, Low, Close, Volume, Adjusted Close  
✅ **Technical Indicators:** MACD, RSI, SMA, EMA  

## 🛠 Technologies & Libraries
- **Programming:** Python
- **Libraries:** TensorFlow/Keras, Scikit-learn, Pandas, NumPy, Matplotlib, XGBoost
- **Deep Learning Frameworks:** LSTM, GRU
- **Machine Learning:** XGBoost

## 📌 Results & Insights
- LSTM and GRU models captured sequential dependencies effectively, outperforming traditional models.
- XGBoost provided strong performance on feature-engineered tabular data.
- The combination of **technical indicators and deep learning** significantly improved prediction accuracy.

## 📜 Future Improvements
✅ Integrate real-time stock price updates  
✅ Test additional time series models (e.g., Transformer-based models)  
✅ Deploy the model as an API for live predictions  

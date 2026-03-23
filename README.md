# Tesla-Stock-Price-Prediction-Using-RNN-and-LSTM
Deep Learning project for Tesla stock price prediction using SimpleRNN and LSTM models with time-series analysis, data preprocessing, and performance comparison.
# 🚀 Tesla Stock Price Prediction using RNN & LSTM

## 📌 Project Overview
This project focuses on predicting Tesla stock prices using Deep Learning models such as SimpleRNN and LSTM. Since stock market data is sequential in nature, Recurrent Neural Networks are used to capture temporal dependencies and forecast future prices.

---

## 🎯 Objective
- Predict Tesla stock closing prices using historical data
- Implement and compare SimpleRNN and LSTM models
- Perform time-series forecasting for:
  - 1-day prediction
  - 5-day prediction
  - 10-day prediction

---

## 🧠 Skills & Technologies Used
- Python
- NumPy & Pandas
- Matplotlib & Seaborn (Data Visualization)
- Scikit-learn (Preprocessing & Scaling)
- TensorFlow / Keras (Deep Learning)
- Time Series Analysis

---

## 📊 Dataset
- Tesla stock price dataset (TSLA)
- Features:
  - Date
  - Open
  - High
  - Low
  - Close
  - Adj Close
  - Volume

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Handling missing values
- Converting Date column to datetime
- Feature selection (Closing Price)
- Data normalization using MinMaxScaler

### 2. Time-Series Preparation
- Created sequences using sliding window technique
- Used past data to predict future stock prices

### 3. Model Building
- Implemented:
  - SimpleRNN model
  - LSTM model
- Added Dropout layers to reduce overfitting

### 4. Model Training
- Loss function: Mean Squared Error (MSE)
- Optimizer: Adam
- Used EarlyStopping for better performance

### 5. Model Evaluation
- Compared actual vs predicted stock prices
- Evaluated using Mean Squared Error (MSE)

---

## 📈 Results
- LSTM model performed better than SimpleRNN in capturing long-term dependencies
- Predictions closely followed actual trends with some deviations due to market volatility

---

## 💼 Business Use Cases
- Stock market prediction for trading strategies
- Portfolio management & risk analysis
- Financial forecasting

---

## ⚠️ Limitations
- Stock prices are highly volatile and influenced by external factors
- Model does not consider news sentiment or macroeconomic indicators

---

## 🚀 Future Improvements
- Add sentiment analysis from news/social media
- Use advanced models like GRU or Transformers
- Deploy using Streamlit for real-time prediction

---

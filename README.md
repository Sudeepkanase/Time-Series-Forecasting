# 📈 Time Series Forecasting: Apple Stock Price (AAPL)

An end-to-end Machine Learning project designed to predict future stock prices using advanced time-series models. This project compares statistical methods, machine learning, and deep learning to achieve high-precision forecasting.

## 🚀 Project Overview
Predicting stock market trends is challenging due to high volatility. This project implements a comparative study between *ARIMA* (Statistical), *Random Forest* (Machine Learning), and *LSTM* (Deep Learning) to forecast Apple Inc. (AAPL) stock prices for the next 30 days.

## 🛠️ Tech Stack
•⁠  ⁠*Python:* Core language
•⁠  ⁠*Deep Learning:* TensorFlow/Keras (LSTM)
•⁠  ⁠*Machine Learning:* Scikit-Learn (Random Forest)
•⁠  ⁠*Statistics:* Statsmodels (ARIMA)
•⁠  ⁠*Data Handling:* Pandas & NumPy
•⁠  ⁠*Visualization:* Matplotlib & Plotly

## 📊 Key Features
•⁠  ⁠*Comparative Analysis:* Evaluates three distinct modeling architectures to find the lowest RMSE (Root Mean Square Error).
•⁠  ⁠*30-Day Forecasting:* Generates future price predictions beyond the current dataset.
•⁠  ⁠*Stationarity Testing:* Includes Augmented Dickey-Fuller (ADF) tests to ensure data readiness for statistical modeling.
•⁠  ⁠*Feature Engineering:* Implements rolling windows and lag features to capture temporal dependencies.

---

## 🌐 Project Results
The project generates specialized forecast reports for each model:
•⁠  ⁠⁠ arima_30_day_forecast.csv ⁠
•⁠  ⁠⁠ lstm_30_day_forecast.csv ⁠
•⁠  ⁠⁠ rf_30_day_forecast.csv ⁠
•⁠  ⁠⁠ models_summary.csv ⁠ — A side-by-side performance comparison.

---

## 🏁 How to Run Locally
1.  Clone the repository:
    ⁠ bash
    git clone [https://github.com/sudeepkanase/Time-Series-Forecasting.git](https://github.com/sudeepkanase/Time-Series-Forecasting.git)
     ⁠
2.  Install dependencies:
    ⁠ bash
    pip install pandas numpy matplotlib scikit-learn tensorflow statsmodels
     ⁠
3.  Run the Analysis:
    Open ⁠ time_series.ipynb ⁠ in Jupyter Notebook or VS Code and run all cells to generate the forecasts.

---

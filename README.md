# 📈 Apple Stock Price Forecasting using Time Series Analysis

## 📌 Project Overview

This project focuses on forecasting Apple stock prices using Time Series Analysis techniques in Python.
The objective is to analyze historical stock price trends and build forecasting models to predict future prices.

The project demonstrates a complete time series workflow including data collection, stationarity testing, ARIMA modeling, and forecasting evaluation.

---

## 📊 Dataset

Stock price data was collected using the **yfinance API**, which provides historical financial market data from Yahoo Finance.

Dataset features include:

* Date
* Open price
* High price
* Low price
* Close price
* Volume

The analysis primarily focuses on the **Closing Price**.

---

## 🛠️ Tools & Libraries

The following Python libraries were used:

* Python
* Pandas
* NumPy
* Matplotlib
* Statsmodels
* pmdarima
* scikit-learn
* yfinance

---

## 🔍 Project Workflow

### 1️⃣ Data Collection

Downloaded 5 years of Apple stock price data using the yfinance API.

### 2️⃣ Data Exploration & Visualization

Analyzed stock price trends and visualized historical data using line plots.

### 3️⃣ Stationarity Testing

Performed Augmented Dickey-Fuller (ADF) test to determine whether the time series is stationary.

### 4️⃣ Differencing

Applied first-order differencing to convert non-stationary data into stationary time series.

### 5️⃣ ACF & PACF Analysis

Used ACF and PACF plots to identify appropriate ARIMA model parameters.

### 6️⃣ ARIMA Modeling

Built a baseline **ARIMA(0,1,0)** model to forecast stock prices.

### 7️⃣ Model Evaluation

Performed train-test split and evaluated model performance using **Root Mean Squared Error (RMSE)**.

### 8️⃣ Model Improvement

Implemented **Auto ARIMA** to automatically determine optimal model parameters and improve forecasting accuracy.

---

## 📈 Results

| Model         | RMSE  |
| ------------- | ----- |
| ARIMA (0,1,0) | 29.65 |
| Auto ARIMA    | 18.40 |

The Auto ARIMA model significantly improved forecasting accuracy by automatically selecting better model parameters.

---

## 📊 Forecast Visualization

The model forecasts future Apple stock prices based on historical trends.

(Add your forecast graph screenshot here)

---

## 💡 Key Insights

* Apple stock shows a strong long-term upward trend.
* The original time series was non-stationary and required differencing.
* Auto ARIMA improved forecasting performance compared to the baseline ARIMA model.

---

## 🚀 Future Improvements

Possible improvements for this project include:

* Using SARIMA for seasonal patterns
* Implementing Facebook Prophet forecasting
* Applying deep learning models such as LSTM
* Including external features like market indicators

---

## 👩‍💻 Author

Chanchal Karande

Aspiring Data Analyst / Data Scientist

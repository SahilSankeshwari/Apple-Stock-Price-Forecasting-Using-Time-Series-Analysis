# Apple-Stock-Price-Forecasting-Using-Time-Series-Analysis
A comprehensive time series analysis and forecasting project using ARIMA, SARIMA, LSTM, and Prophet models on Apple Inc. stock data (1980–2024).

# 📊 Apple Stock Price Forecasting Using Time Series Analysis

This project presents a comprehensive time series analysis and forecasting of Apple Inc. (AAPL) stock prices using both traditional statistical models and modern machine learning techniques. The analysis spans over **four decades (1980–2024)** and explores various models including **ARIMA, SARIMA, LSTM**, and **Facebook Prophet** to compare forecasting accuracy and provide insights for future trends.

---

## 📁 Dataset

- **Source**: [Kaggle - Apple Stock Historical Data](https://www.kaggle.com/)
- **Duration**: December 12, 1980 to March 12, 2024
- **Columns**: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Change %`
- **Total Records**: 10,911 rows × 6 columns

---

## 🎯 Objectives

1. Collect and preprocess Apple stock price data.
2. Conduct exploratory data analysis (EDA) to uncover trends, patterns, and anomalies.
3. Implement multiple time series models:
   - ARIMA
   - SARIMA
   - LSTM (Long Short-Term Memory)
   - Facebook Prophet
4. Evaluate model performance using **MSE** and **RMSE**.
5. Provide short-term and long-term forecast insights for financial planning.

---

## 🧪 Methodology

The following steps were followed:

- **Data Cleaning & Preprocessing**
- **Stationarity & Volatility Analysis**
- **Train-Test Split**
- **Time Series Decomposition**
- **Model Implementation**:
  - ARIMA: Auto parameter tuning using AIC
  - SARIMA: Captures both trend and seasonality
  - LSTM: Deep learning-based sequential model
  - Prophet: Robust forecasting with holidays and missing data
- **Performance Evaluation** (MSE & RMSE)
- **Model Comparison** using visualizations

---

## 📈 Results

| Model     | RMSE Score |
|-----------|------------|
| ARIMA     | 82.34      |
| SARIMA    | 66.10      |
| LSTM      | 8.77       |
| Prophet   | 27.88      |

The **LSTM model** outperformed the others in terms of accuracy (lowest RMSE).

---

## 🖼️ Visualizations

- Line chart of closing prices
- Moving averages
- Seasonal decomposition
- Forecast graphs for each model
- RMSE comparison bar plot

---

## 🔚 Conclusion

This project demonstrates how various time series models can be applied to stock market data for forecasting purposes. The LSTM model provided the best predictions, showcasing the power of deep learning in financial forecasting. This kind of analysis can aid investors and analysts in making data-driven decisions.

---

## 📚 References

1. [Apple Stock Dataset on Kaggle](https://www.kaggle.com/)
2. Box, G. E. P., Jenkins, G. M., & Reinsel, G. C. (1970). Time Series Analysis.
3. Hyndman, R.J. & Athanasopoulos, G. (2018). Forecasting: Principles and Practice.
4. Statsmodels Documentation – ARIMA & SARIMA.
5. TensorFlow Keras – LSTM Implementation.
6. Facebook Prophet Documentation.
7. Scikit-learn: Evaluation Metrics.
8. Investopedia – Time Series in Finance.
9. Python Official Documentation (Pandas, NumPy, Matplotlib, Seaborn).
10. Towards Data Science – Time Series Forecasting Guides.

---

## 👤 Author

**Sahil Sankeshwari**  
M.Sc. Statistics  
Aspiring Data Scientist
📧 sankeshwarisahil2003@gmail.com


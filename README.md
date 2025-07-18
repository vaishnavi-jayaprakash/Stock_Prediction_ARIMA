# Stock Price Prediction using ARIMA Model

This project implements a time series forecasting model using **ARIMA** (AutoRegressive Integrated Moving Average) to predict stock prices. It demonstrates the use of statistical modeling for financial data analysis and prediction.

##  Overview

- 📊 Analyzes historical stock price data
- 📈 Applies the ARIMA model for univariate time series forecasting
- 📉 Evaluates model performance through visual comparison and error metrics

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Statsmodels (ARIMA)


## 🧪 Steps Performed

1. **Data Preprocessing**
   - Loaded CSV dataset
   - Parsed dates and set time index
   - Handled missing values

2. **Exploratory Data Analysis (EDA)**
   - Visualized stock trends and volatility
   - Checked stationarity using Augmented Dickey-Fuller (ADF) test

3. **Modeling with ARIMA**
   - Determined optimal `(p, d, q)` parameters using ACF/PACF plots and `auto_arima`
   - Fitted ARIMA model to training data
   - Generated future forecasts

4. **Evaluation**
   - Compared actual vs predicted values
   - Calculated Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)


## 📜 License

This project is open-source and available under the MIT License.

---

## 🙋‍♀️ About Me

**Vaishnavi Jayaprakash**  
Aspiring data scientist | AI & DS undergraduate  
🔗 [LinkedIn](https://linkedin.com/in/vaishnavi_j) | [GitHub](https://github.com/vaishnavi-jayaprakash)

---



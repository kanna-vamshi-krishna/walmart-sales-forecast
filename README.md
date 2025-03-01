# walmart-sales-forecast
"Walmart Weekly Sales Forecasting using SARIMA. This project analyzes sales trends and predicts future sales using Time Series Analysis."
# 🛒 Walmart Sales Forecasting using SARIMA

## 📌 Overview
This project applies **Time Series Analysis** to forecast **weekly sales** for Walmart stores using the **SARIMA (Seasonal AutoRegressive Integrated Moving Average) model**. The goal is to analyze **sales trends, seasonality, and patterns** to support business decision-making.

## 📊 Model Used
- **SARIMA (Seasonal ARIMA)**  
  - Captures **trend and seasonality** in time series data.  
  - Forecasts **next 12 weeks** of Walmart store sales.  

## 🔢 Data Processing
- Converted `Date` to datetime format and resampled data to **weekly frequency**.  
- Aggregated **weekly sales** at the store level.  
- Handled missing values using **forward fill**.

## 🚀 Results & Insights
- The **SARIMA model successfully predicts sales trends** over the next 12 weeks.  
- Sales data shows **clear seasonality**, validating the choice of SARIMA.  
- **Confidence intervals widen over time**, indicating increasing uncertainty in long-term forecasts.

## 🛠️ Installation & Usage
### Clone Repository:
```bash
git clone https://github.com/YourGitHubUsername/walmart-sales-forecast.git

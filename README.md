# walmart-sales-forecast
"Walmart Weekly Sales Forecasting using SARIMA. This project analyzes sales trends and predicts future sales using Time Series Analysis."
# 🛒 Walmart Sales Forecasting using SARIMA

## 📌 Overview
This project applies **Time Series Analysis** to forecast **weekly sales** for Walmart stores using the **SARIMA (Seasonal AutoRegressive Integrated Moving Average) model**. The goal is to analyze **sales trends, seasonality, and patterns** to support business decision-making.

## 📊 Model Used
- **SARIMA (Seasonal ARIMA)**  
  - Captures **trend and seasonality** in time series data.  
  - Forecasts **next 12 weeks** of Walmart store sales.  

## 📈 Visualizations & Insights
This project includes various **data visualizations** to understand sales trends and patterns:

### **1️⃣ Data Exploration & Trend Analysis**
- **Time Series Plot** – Visualizes overall sales trends over time.  
  ![Time Series Plot](https://raw.githubusercontent.com/YourGitHubUsername/walmart-sales-forecast/main/images/time_series_plot.png)

- **Seasonal Trend Plot** – Shows seasonal variations in sales across months.  
  ![Seasonal Trend Plot](https://raw.githubusercontent.com/YourGitHubUsername/walmart-sales-forecast/main/images/seasonal_trend.png)

### **2️⃣ Statistical Analysis**
- **Box Plot for Outliers** – Identifies potential outliers in sales data.  
  ![Box Plot](https://raw.githubusercontent.com/YourGitHubUsername/walmart-sales-forecast/main/images/box_plot.png)

- **Correlation Plots** – Examines relationships between sales and factors like CPI, Unemployment, and Temperature.  
  ![Correlation Plot](https://raw.githubusercontent.com/YourGitHubUsername/walmart-sales-forecast/main/images/correlation_plot.png)

### **3️⃣ SARIMA Forecasting**
- **SARIMA Model Forecast Plot** – Displays actual vs. forecasted sales for the next 12 weeks.  
  ![SARIMA Forecast](https://raw.githubusercontent.com/YourGitHubUsername/walmart-sales-forecast/main/images/sarima_forecast.png)

- **Confidence Interval Bands** – Highlights prediction uncertainty over time.  
  ![Confidence Interval](https://raw.githubusercontent.com/YourGitHubUsername/walmart-sales-forecast/main/images/confidence_interval.png)

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


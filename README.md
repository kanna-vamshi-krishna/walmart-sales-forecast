# 🛒 Walmart Sales Forecasting using SARIMA

## 📌 Overview
This project applies **Time Series Analysis** to forecast **weekly sales** for Walmart stores using the **SARIMA (Seasonal AutoRegressive Integrated Moving Average) model**. The goal is to analyze **sales trends, seasonality, and patterns** to support business decision-making.

## 📊 Model Used
- **SARIMA (Seasonal ARIMA)**  
  - Captures **trend and seasonality** in time series data.  
  - Forecasts **next 12 weeks** of Walmart store sales.  

---

## 📈 Visualizations & Insights  
This project includes various **data visualizations** to analyze patterns in Walmart's sales data:

### **1️⃣ Data Exploration & Trend Analysis**
- **Box Plot for Outliers** – Identifies potential outliers in sales data.  
  ![Box Plot](boxplot_walmart.png)

- **Unemployment vs. Weekly Sales (Scatter Plot)** – Analyzes if the unemployment rate affects sales.  
  ![Unemployment vs Sales](unemployement_vs_sales.png)

- **Seasonal Trend of Weekly Sales (Line Plot)** – Shows how sales change throughout the year.  
  ![Seasonal Trend](seasonal_trend.png)

### **2️⃣ Statistical Analysis**
- **Weekly Sales vs Temperature (Scatter Plot)** – Examines if temperature impacts sales.  
  ![Sales vs Temperature](sales_vs_temp.png)

- **Weekly Sales vs Consumer Price Index (Scatter Plot)** – Analyzes the effect of CPI on sales.  
  ![Sales vs CPI](sales_vs_cpi.png)

### **3️⃣ Store Performance Analysis**
- **Top 5 Performing Stores (Bar Plot)** – Shows the highest sales-generating stores.  
  ![Top 5 Stores](top_5_stores.png)

- **Highest & Lowest Sales (Bar Plot)** – Compares the best and worst-performing stores.  
  ![Highest vs Lowest Sales](highest_vs_lowest_sales.png)

### **4️⃣ SARIMA Forecasting**
- **SARIMA Model Forecast for Store 1 (Line Plot)** – Displays actual vs. forecasted sales for the next 12 weeks.  
  ![SARIMA Forecast](sarima_forecast.png)

---

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
git clone https://github.com/kanna-vamshi-krishna/walmart-sales-forecast.git


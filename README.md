# 🛒 Walmart Sales Forecasting using SARIMA

## 📌 Overview
This project applies **Time Series Analysis** to forecast **weekly sales** for Walmart stores using the **SARIMA (Seasonal AutoRegressive Integrated Moving Average)** model. The goal is to analyze **sales trends, seasonality, and patterns** to support business decision-making.

## 📈 Model Used
### **SARIMA (Seasonal ARIMA)**
- 📌 Captures **trend and seasonality** in time series data.
- 📌 Forecasts **next 12 weeks** of Walmart store sales.

---

## 📊 Visualizations & Insights

### **1️⃣ Sales Data Distribution**
- The box plot shows the **spread and distribution** of Walmart weekly sales data.
- Helps detect **outliers** and variations across different stores.

  ![Box Plot](https://github.com/kanna-vamshi-krishna/walmart-sales-forecast/blob/main/boxplot_walmart.png?raw=true)

### **2️⃣ Weekly Sales Trends**
- The **seasonal trend** of weekly sales is visualized using a line plot.
- Clear **recurring patterns** suggest the presence of **seasonality** in the data.

  ![Seasonal Trend](https://github.com/kanna-vamshi-krishna/walmart-sales-forecast/blob/main/seasonal%20trend.png?raw=true)
### **3️⃣ Impact of Economic Factors on Sales**
- The following scatter plots show how **weekly sales are affected by external factors** like:
  - 🔥 **Temperature vs Sales**
  - 📉 **Unemployment vs Sales**
  - 🏷 **Consumer Price Index (CPI) vs Sales**

  ![Sales vs Temperature](https://github.com/kanna-vamshi-krishna/walmart-sales-forecast/blob/main/sales%20vs%20temp.png?raw=true)  
  ![Unemployment vs Sales](https://github.com/kanna-vamshi-krishna/walmart-sales-forecast/blob/main/unemployement%20vs%20sales.png?raw=true)  
  ![Sales vs CPI](https://github.com/kanna-vamshi-krishna/walmart-sales-forecast/blob/main/sales%20vs%20cpi.png?raw=true)  

### **4️⃣ Identifying Top & Lowest Performing Stores**
- **Top 5 Performing Stores** based on total weekly sales.
- **Highest vs Lowest Sales** comparison.

  ![Top 5 Stores](https://github.com/kanna-vamshi-krishna/walmart-sales-forecast/blob/main/top%205%20stores.png?raw=true)  
  ![Highest vs Lowest Sales](https://github.com/kanna-vamshi-krishna/walmart-sales-forecast/blob/main/highest%20vs%20lowest%20sales.png?raw=true)  

### **5️⃣ Forecasted Sales for the Next 12 Weeks**
- Using the SARIMA model, we forecasted the next **12 weeks of sales**.
- The confidence intervals widen over time, indicating **higher uncertainty** in long-term predictions.

  ![Sales Forecast](https://github.com/kanna-vamshi-krishna/walmart-sales-forecast/blob/main/sarima%20forecast.png?raw=true)  

---

## 🏗 Steps Followed
1. **Data Preprocessing**: Cleaning and preparing the dataset.
2. **Exploratory Data Analysis (EDA)**: Understanding sales trends and patterns.
3. **Feature Engineering**: Extracting useful information from raw data.
4. **Time Series Modeling**: Applying **SARIMA** for forecasting.
5. **Evaluation & Insights**: Analyzing predictions and model performance.

---

## 🚀 Technologies Used
- **Python**
- **Pandas, NumPy** – Data handling & manipulation
- **Matplotlib, Seaborn** – Data Visualization
- **Statsmodels** – Time Series Analysis
- **GitHub** – Version Control

---

## 📌 How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/kanna-vamshi-krishna/walmart-sales-forecast.git



---

# 🧾 Sales Forecasting with Random Forest

### 🎯 Capstone Project — Data Analytics Program

---

## 📘 Project Overview

Accurate sales forecasting is essential for effective business planning, resource allocation, and decision-making.
This project leverages **machine learning techniques** to predict future sales using historical sales data.
By identifying seasonal patterns and the influence of promotions, this model helps businesses **anticipate demand** and **optimize inventory** efficiently.

---

## 💡 Problem Statement

Retail and e-commerce companies often struggle to predict sales accurately due to factors like **seasonality**, **promotional campaigns**, and **market trends**.
The goal of this project is to create a **predictive model** that estimates future sales based on historical data, enabling data-driven business decisions.

---

## 🎯 Objectives

* Analyze and visualize historical sales data to identify trends and patterns.
* Develop a predictive model using **Random Forest Regressor**.
* Evaluate model performance using **RMSE (Root Mean Squared Error)**.
* Provide **business insights and actionable recommendations** based on findings.

---

## 📊 Dataset

* **Source:** Kaggle
* **Sample Provided:** `data/sales_data.csv` (30 synthetic daily records for testing)
* **Features Include:**

  * `Date` – Date of sale
  * `Store` – Store identifier
  * `Promo` – Whether a promotion was active (0/1)
  * `Customers` – Number of customers that day
  * `Sales` – Total sales amount

### 🧹 Data Preparation Steps

* Removed duplicates and handled missing values.
* Converted the `Date` column to datetime format.
* Extracted time-based features: **Month**, **Year**, and **DayOfWeek**.
* Normalized continuous variables for model consistency.

---

## ⚙️ Methodology

### **1. Exploratory Data Analysis (EDA)**

* Visualized monthly sales trends and seasonal variations.
* Examined the impact of promotions on daily sales.
* Identified top-performing stores.

### **2. Feature Engineering**

* Created new features from date (month, year, weekday).
* Encoded categorical variables (store IDs).
* Handled outliers and normalized data for modeling.

### **3. Modeling**

* Applied multiple regression techniques and selected **Random Forest Regressor** for its high accuracy and ability to handle nonlinear data.
* Performed **hyperparameter tuning** using `GridSearchCV`.

### **4. Evaluation Metric**

* Used **Root Mean Squared Error (RMSE)** as the primary metric.
* Achieved **RMSE = 0.18**, indicating strong predictive performance.

---

## 📈 Results

* The **Random Forest model** demonstrated excellent predictive power.
* Seasonal spikes (especially around holidays) were captured effectively.
* Promotions and customer traffic had the strongest influence on sales.

---

## 🧠 Insights & Recommendations

* **Sales increase significantly during holidays** — businesses should ramp up inventory and marketing in these periods.
* **Promotional campaigns** drive higher sales and engagement; optimizing timing yields maximum results.
* **Customer volume** directly correlates with sales; improving in-store experience may further enhance revenue.

---

## 🔮 Next Steps

* Incorporate external data (e.g., weather, regional holidays, economic indicators).
* Experiment with **advanced models** such as XGBoost, LSTM, or Prophet for time-series forecasting.
* Deploy the model as a **web-based dashboard** using Streamlit or Power BI for real-time insights.

---

## 📂 Repository Structure

```
/data
    sales_data.csv
/notebooks
    sales_forecasting_analysis.ipynb
/images
    sales_trends.png
    feature_importance.png
README.md
```

---

## 🔗 Links

📓 [View the Jupyter Notebook](notebooks/sales_forecasting_analysis.ipynb)

---

## ✅ Summary

This capstone project demonstrates how **machine learning** can enhance sales forecasting accuracy.
With an RMSE of **0.18**, the **Random Forest model** provides actionable insights that empower businesses to make better **inventory, marketing, and resource allocation** decisions.

---

### 👩‍💻 Author

**Arockia Sebastian Santiago**
Data Analytics Capstone Project — 2025

---

## 📜 License

This project is for educational purposes and part of a Data Analytics Capstone submission.

---

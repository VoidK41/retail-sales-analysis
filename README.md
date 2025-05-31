
<p align="center">
  <img src="images/banner.png" alt="Retail Sales Analysis Banner" width="100%">
</p>

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

# 🛍️ Retail Sales Analysis & Prediction

This project explores and analyzes retail sales data to uncover key business insights and build a predictive model for forecasting sales. Using a combination of exploratory data analysis (EDA), data visualization, and machine learning, the goal is to assist retail stakeholders in making data-driven decisions.

## 📊 Project Overview

* 🔍 **Dataset**: Retail sales data (orders, product categories, time, quantity, prices, etc.)
* 🛠 Tools: Python, Pandas, Matplotlib, Seaborn, Scikit-learn
* 🎯 Objectives:
  * Understand sales patterns and trends over time
  * Identify top-performing products and categories
  * Detect seasonal behaviors in sales
  * Build a machine learning model to predict sales

## ❓ Key Questions Answered

* Which products are the top sellers?
* Are there any seasonal patterns in sales?
* What is the distribution of sales by product category?
* Are there noticeable trends over time?
* Can we build a predictive model for future sales?

## 📈 Exploratory Data Analysis (EDA)

### 🔝 Top 10 Best Selling Products
<img src="C:\Project Coding\AI Engineer\retail_sales_prediction\images\topselling.png" alt="Top Products" width="700">

### 📅 Monthly Sales Trend
<img src="C:\Project Coding\AI Engineer\retail_sales_prediction\images\monthlysales.png" alt="Monthly Sales Trend" width="700">

### 🗂️ Sales by Product Category
<img src="C:\Project Coding\AI Engineer\retail_sales_prediction\images\salesbycategory.png" alt="Category Sales" width="700">

### 📉 Sales Trend Over Time
<img src="C:\Project Coding\AI Engineer\retail_sales_prediction\images\salesovertime.png" alt="Sales Trend Over Time" width="700">

## 🤖 Machine Learning

A regression model using a `RandomForestRegressor` was built and evaluated:

* Data preprocessing with `StandardScaler`
* Train-test split and model training
* Hyperparameter tuning using `GridSearchCV`
* Model evaluation with MSE and R² Score
* Cross-validation for performance stability

✅ The final model achieved strong predictive performance and was saved using `joblib` for deployment.

## 📂 Project Structure

```
RETAIL_SALES_PREDICTION/
├── data/
│   └── sales_data_sample.csv
├── notebooks/
│   └── retail_sales_analysis_FINAL.ipynb
├── models/
│   └── final_model.pkl
├── images/
│   ├── top_products.png
│   ├── monthly_sales_trend.png
│   ├── category_sales.png
│   └── sales_trend_time.png
├── requirements.txt
├── .gitignore
└── README.md
```

## 📌 Final Insights

* 📈 Classic and Vintage Cars dominate total sales
* 📅 End-of-year months (Nov–Dec) show consistent peaks
* 🔹 Some products outperform others by a large margin
* 🔎 Predictive modeling shows strong potential for automation

## 🚀 Future Work

* Deploy model in a live dashboard or API
* Add customer segmentation for targeted insights
* Incorporate marketing/promotional data into analysis

## 📚 Requirements

* Python 3.x
* pandas
* matplotlib
* seaborn
* scikit-learn
* joblib

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🙌 Acknowledgements

Thanks to the open dataset provider and the community for continuous inspiration.

---

Made with ❤️ by **Kaii**  
📢 Feel free to ⭐ star this repo, fork it, or reach out with suggestions!

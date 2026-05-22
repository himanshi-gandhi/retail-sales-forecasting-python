# Retail Sales Forecasting & Business Insights using Python

## Project Overview

This project analyzes Walmart retail sales data using Exploratory Data Analysis (EDA) and Machine Learning techniques to identify sales trends, seasonal patterns, holiday impacts, and forecasting opportunities.

The goal of this project is to generate business insights and build predictive models that can support retail decision-making and sales forecasting.

---

## Business Objectives

- Analyze weekly retail sales trends
- Identify seasonal and holiday shopping patterns
- Understand the impact of economic indicators on sales
- Detect outliers affecting business performance
- Forecast weekly sales using machine learning models

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Dataset Features

| Feature | Description |
|---|---|
| Store | Store number |
| Date | Weekly sales date |
| Weekly_Sales | Weekly sales revenue |
| Holiday_Flag | Holiday indicator (0 = No, 1 = Yes) |
| Temperature | Average temperature |
| Fuel_Price | Fuel cost in the region |
| CPI | Consumer Price Index |
| Unemployment | Unemployment rate |

---

## Exploratory Data Analysis

The analysis includes:

- Correlation Heatmap
- Monthly Sales Trend Analysis
- Yearly Sales Comparison
- Holiday vs Non-Holiday Sales
- Sales Distribution Analysis
- Outlier Detection using Boxplots
- Feature Engineering using Date Columns

---

## Machine Learning Models

### 1. Linear Regression
- Train Accuracy: 13.08%
- Test Accuracy: 11.82%

### 2. Random Forest Regressor
- Train Accuracy: 99.39%
- Test Accuracy: 96.24%

The Random Forest model significantly outperformed Linear Regression, indicating that retail sales are influenced by nonlinear relationships and complex business patterns.

---

## Key Business Insights

- Holiday periods generated higher average weekly sales.
- End-of-year months showed peak retail demand.
- Economic indicators moderately influenced sales performance.
- Store ID was one of the strongest predictors of weekly sales.
- Random Forest provided highly accurate forecasting results.

---

## Project Structure

```bash
retail-sales-forecasting-python/
│
├── retail_sales_forecasting_analysis.ipynb
├── Walmart_Store_sales.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Conclusion

This project demonstrates how data analytics and machine learning can be used together to generate business insights and improve retail sales forecasting.

The project combines exploratory data analysis, visualization, feature engineering, and predictive modeling to support data-driven retail decision-making.

---

## Author

Himanshi Gandhi

- LinkedIn: https://www.linkedin.com/in/himanshi-gandhi/
- GitHub: https://github.com/himanshi-gandhi
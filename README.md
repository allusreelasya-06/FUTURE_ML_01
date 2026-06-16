# FUTURE_ML_01
# 📊 Sales & Demand Forecasting — FUTURE_ML_01

## Overview
This project builds a time-series forecasting model to predict future sales/demand using 3 years of historical business data, as part of the Future Interns Machine Learning internship (Task 1).

## Objective
Forecast monthly sales for the next 6 months using historical trends and seasonality, to support inventory and business planning decisions.

## Dataset
- 36 months of synthetic monthly sales data (2022–2024)
- Categories: Electronics, Apparel, Grocery, Furniture, Toys
- Seasonal boosts applied to Electronics & Toys during Nov–Dec (holiday effect)

## Tools & Libraries
- Python, Jupyter Notebook (VS Code)
- pandas, numpy, matplotlib, seaborn
- scikit-learn (Linear Regression)
- statsmodels

## Approach
1. Data cleaning & exploratory analysis
2. Feature engineering — time index, sine/cosine seasonal encoding
3. Train/test split (time-series style, last 6 months held out)
4. Linear Regression model training
5. Model evaluation — MAE, RMSE, R²
6. 6-month forward forecast
7. Business insights & recommendations

## Results
| Metric | Value |
|---|---|
| MAE | $5,928.26 |
| RMSE | $6,989.78 |
| R² Score | 0.213 |

## Key Insight
Sales show clear seasonal peaks in November–December, driven by Electronics and Toys. Forecast suggests a 5.18% projected increase in average monthly sales for early 2025.

## Visuals
- `sales_trend.png` — historical sales trend
- `category_comparison.png` — category-wise breakdown
- `actual_vs_predicted.png` — model validation
- `final_forecast.png` — 6-month forward forecast

## Author
Allu Sree Lasya — Machine Learning Intern, Future Interns

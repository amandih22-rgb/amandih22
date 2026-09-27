---
title: "Fast-Food Sales Prediction"
excerpt: "Machine learning and demand forecasting using R, feature engineering, Random Forest and XGBoost."
collection: portfolio
---

A machine-learning project focused on predicting daily fast-food sales and investigating how pricing, discounts and calendar characteristics influence demand. The project began as a DataCamp exercise and was extended into a more comprehensive predictive modelling workflow.

The analysis included data cleaning and exploratory analysis, with an overall correlation of **0.645 between discount percentage and sales quantity**. Feature engineering was then used to create calendar and pricing variables, including day of week, week of year, discount amount and effective selling price.

To assess model performance realistically, I implemented **time-based validation** rather than randomly splitting the data, reflecting the project's objective of forecasting future sales. Linear Regression, Random Forest and XGBoost models were compared, followed by **Random Forest hyperparameter tuning and rolling time-based validation**.

The analysis also included **feature importance and product-level error analysis**, identifying substantial differences in predictive performance between restaurant-item combinations. The final Random Forest model was used to generate forward sales forecasts for R1 Burger for 1–10 December.

**Key Results:** Random Forest achieved a validation RMSE of **21.89**, compared with **22.19** for Linear Regression. Rolling validation demonstrated variability in model performance across forecasting periods, highlighting the challenges of forecasting with a small dataset and volatile daily sales.

**Tools:** R · RStudio · tidyverse · ggplot2 · Random Forest · XGBoost · Machine Learning · Feature Engineering · Time-Based Validation · Data Visualisation

[View Project on GitHub](https://github.com/amandih22-rgb/datacamp-fast-food-sales-prediction.git)

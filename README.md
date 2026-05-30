# Sales & Demand Forecasting for Businesses

## Project Overview

This project was developed as part of the Future Interns Machine Learning Internship (Task 1).
The objective is to forecast future sales using historical business data and provide insights that can help businesses make informed decisions regarding inventory management, staffing, budgeting, and demand planning.

## Dataset
Dataset Used: Superstore Sales Dataset
The dataset contains:
* Order Date
* Product Information
* Category
* Region
* Sales
* Quantity
* Profit
Total Records: 9,994

## Project Workflow
### 1. Data Cleaning
* Loaded dataset using Pandas
* Checked for missing values
* Converted Order Date to datetime format
### 2. Time-Based Feature Engineering
Created:
* Month
* Year
* Lag_1
* Lag_2
* Lag_3
These features help the model learn historical sales patterns.
### 3. Sales Forecasting
Monthly sales were aggregated from transaction-level data.
A Gradient Boosting Regressor was used to forecast future sales based on historical trends.
### 4. Model Evaluation
Evaluation Metrics:
* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score
These metrics were used to measure forecasting performance.
### 5. Visualizations
The project includes:
* Monthly Sales Trend
* Sales by Category
* Sales by Region
* Actual vs Predicted Sales
* Future Sales Forecast
  
### Business Insights
* Sales show seasonal fluctuations throughout the year.
* Historical sales patterns can be used to estimate future demand.
* Forecasting helps businesses optimize inventory and resource planning.
* Future demand predictions support better business decision-making.
  
## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## Future Improvements
* Use larger historical datasets
* Implement advanced time-series models
* Incorporate holiday and seasonal indicators
* Deploy forecasting model as a web application

## Author
Sri Nivya Saladi

Future Interns – Machine Learning Internship

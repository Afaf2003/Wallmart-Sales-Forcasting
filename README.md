# Walmart Sales Forecasting

This project is part of the Intellipaat Capstone Project and aims to help Walmart manage inventory effectively by forecasting weekly sales for multiple stores based on various influencing factors.

## Project Overview

A retail store like Walmart with multiple outlets across the country faces challenges in managing inventory to meet demand accurately. This project provides insights into weekly sales patterns and builds predictive models to forecast future sales.

## Dataset

- **File**: `Walmart DataSet.csv`
- **Rows**: 6,435
- **Columns**: 8
- **Features**:
  - **Store**: Store number
  - **Date**: Week of sales
  - **Weekly_Sales**: Sales for the given store in that week
  - **Holiday_Flag**: Indicator if the week includes a holiday
  - **Temperature**: Temperature on the day of sales
  - **Fuel_Price**: Fuel price in the region
  - **CPI**: Consumer Price Index
  - **Unemployment**: Unemployment rate in the region

## Project Structure

- **main.ipynb**: The main Jupyter notebook containing all code and analysis steps
- **Walmart DataSet.csv**: The primary dataset used in the analysis

## Outline

1. **Importing Necessary Libraries**: Setting up the Python environment by importing the required libraries for data manipulation, visualization, and modeling.
2. **Reading Walmart DataSet**: Loading and understanding the structure of the dataset.
3. **Performing EDA - Walmart Dataset**: Conducting exploratory data analysis to identify patterns, outliers, and insights about factors affecting sales.
4. **Predictive Modeling Techniques**:
   - Building and evaluating predictive models to forecast weekly sales.
   - Checking model accuracy and performance.
5. **Stationary Analysis**: Analyzing if the time series is stationary and transforming data if necessary.
6. **Forecasting Weekly Sales**: Using statistical and machine learning techniques to predict sales for the next 12 weeks.
7. **Conclusion**: Summarizing findings and discussing how the insights can help Walmart improve inventory management.

## Key Analysis and Findings

- **Exploratory Data Analysis**:
  - Investigated the impact of external factors (e.g., unemployment, temperature, CPI) on weekly sales.
  - Analyzed holiday and seasonal effects to identify peaks in sales.
- **Top and Bottom Stores**: Identified the best and worst-performing stores based on historical sales data.
- **Predictive Modeling**:
  - Built time series forecasting models (ARIMA, Prophet) to forecast sales for each store for the next 12 weeks.

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Scikit-Learn, Statsmodels, Prophet
- **IDE**: Jupyter Notebook

## Results

This project provides a robust forecasting model that helps Walmart align inventory with expected demand, reducing overstocking and understocking issues and improving customer satisfaction.

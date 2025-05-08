# Equipment Energy Consumption Analysis Report

## 1. Problem Approach

The objective of this project was to predict equipment energy consumption using sensor data from multiple building zones. The approach consisted of:

- Loading and cleaning a dataset with 16,857 rows and 29 columns
- Converting object columns to numeric data types
- Handling missing values across multiple measurements
- Parsing timestamps and generating temporal features (hour, day_of_week, month)
- Conducting exploratory data analysis to understand patterns
- Feature engineering including cyclical encoding of time variables
- Building regression models for prediction
- Evaluating model performance

## 2. Key Insights from Data

- **Data Structure**: The dataset contains measurements from 9 different zones including temperature and humidity readings
- **Environmental Variables**: Includes outdoor temperature, humidity, wind speed, and atmospheric pressure
- **Missing Values**: Several columns had missing values that required preprocessing
- **Data Types**: Initial mixed data types required conversion to appropriate numeric formats
- **Temporal Features**: Hour, day of week, month, day of year, and weekend indicators were created from timestamps
- **Cyclical Encoding**: Sine and cosine transformations were applied to hour and month variables

## 3. Model Performance Evaluation

The modeling approach included:

- Splitting data into training and testing sets
- Implementing regression models (likely Random Forest, Linear Regression and XGBoost)


## 4. Recommendations for Reducing Energy Consumption

### Zone Temperature Optimization:
- Adjust temperature settings in zones showing high correlation with energy usage

### Time-Based Scheduling:
- Implement energy-saving measures during identified high-consumption periods

### Humidity Control:
- Monitor and regulate humidity levels which appear to influence energy consumption

### Environmental Response Planning:
- Adjust operations based on outdoor conditions that impact energy usage

### Data-Driven Maintenance:
- Use predictive models to identify potential inefficiencies before they impact consumption


**Analyst:** *Tannu*  
**Date:** May 2025

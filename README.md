# SALES-FORECASTING-WITH-LINEAR-REGRESSION
## Data Science & Analytics Internship – Tamizhan Skills

## Introduction
This project is developed as part of the Data Science and Analytics Internship at Tamizhan Skills. The project focuses on predicting future sales revenue using historical data and the Linear Regression algorithm. The complete workflow implemented in Python matches the provided program code, including data preprocessing, model training, evaluation, visualization, and future forecasting.

## Dataset Preview
The dataset is loaded from a CSV file and inspected using Pandas.

## Problem Statement
Businesses face difficulty in estimating future sales due to the lack of predictive models. This project addresses the issue by applying Linear Regression on historical sales data.

## Data Preprocessing
The following preprocessing steps were applied (as implemented in the code):
- Removal of extra spaces in column names
- Handling missing product names using mode
- Cleaning revenue values and converting to float
- Handling missing quantities using median
- Date conversion and feature extraction (year, month, day)
  
## Model Training & Evaluation
The dataset is split into training and testing sets using train_test_split(). 
A Linear Regression model is trained and evaluated using:
- Mean Squared Error (MSE)
- R² Score

## Actual vs Predicted Sales
The comparison between actual and predicted sales revenue is visualized using Matplotlib.

## Conclusion
This project successfully demonstrates how Linear Regression can be applied to real-world sales forecasting problems. Through the Tamizhan Skills Data Science & Analytics Internship, practical skills in data preprocessing, machine learning, visualization, and forecasting were developed. The project code and outputs are fully aligned, making this repository suitable for academic submission and internship evaluation.

## OUTPUT
## Future Sales Forecast
The model forecasts sales for the next 30 days using median quantity values.

### Forecast Graph
<img width="1130" height="620" alt="Screenshot 2025-12-26 174651" src="https://github.com/user-attachments/assets/42380a1a-df60-4114-8fcc-668281171d4e" />

### Actual vs predictive sales Graph
<img width="1150" height="631" alt="Screenshot 2025-12-26 174626" src="https://github.com/user-attachments/assets/892a4464-c2e5-4d83-804d-aa9168fe41d6" />

## Internship Organization
Tamizhan Skills

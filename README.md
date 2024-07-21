# Time Series Modeling of Retail Sales

## Overview

This project analyzes and predicts U.S. monthly retail sales from January 1992 to June 2021. Retail sales are a crucial economic indicator, providing insights into consumer spending patterns and overall economic health.

## Objectives

- Analyze historical retail sales data.
- Develop a predictive model to forecast future monthly retail sales.
- Evaluate the model's performance using Root Mean Square Error (RMSE).

## Data Description

The dataset contains monthly retail sales figures in thousands of dollars from January 1992 to June 2021.

## Methodology

1. **Data Loading and Exploration**:
    - Load the dataset and examine its structure.
    - Visualize the data to identify trends and seasonal patterns.

2. **Data Preparation**:
    - Convert the data to a long format for easier manipulation and visualization.
    - Create a date column for time series analysis.

3. **Visualization**:
    - Plot the monthly retail sales data from 1992 to 2021.

4. **Model Development**:
    - Split the data into training (before July 2020) and testing sets (July 2020 to June 2021).
    - Develop a linear regression model to predict monthly sales.

5. **Model Evaluation**:
    - Evaluate the model's performance using the RMSE metric.

## Results

- **Visualization**: The retail sales data showed noticeable trends and seasonal patterns over nearly three decades.
- **Model Performance**: The linear regression model achieved an RMSE of approximately 66,429, indicating a moderate level of prediction error.

## Conclusion

The linear regression model provided valuable insights into retail sales trends and performed moderately well in predicting future sales. The prediction accuracy can be improved by incorporating more advanced time series models or additional economic indicators.

## Future Work

- Explore more complex models such as ARIMA, SARIMA, or machine learning techniques.
- Include additional predictors like unemployment rates or consumer confidence indexes.

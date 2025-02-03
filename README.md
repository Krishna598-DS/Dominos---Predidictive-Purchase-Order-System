# Dominos-Predictive Purchase Order System

## Skills Takeaway from This Project
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Time series forecasting
- Predictive modeling
- Business decision-making
- Real-world application of data science

## Domain: Food Service Industry

## Problem Statement
Domino's wants to optimize the process of ordering ingredients by predicting future sales and creating a purchase order. By accurately forecasting sales, Domino's can ensure that it has the right amount of ingredients in stock, minimizing waste and preventing stockouts. This project aims to leverage historical sales data and ingredient information to develop a predictive model and generate an efficient purchase order system.

## Business Use Cases
- **Inventory Management:** Ensuring optimal stock levels to meet future demand without overstocking.
- **Cost Reduction:** Minimizing waste and reducing costs associated with expired or excess inventory.
- **Sales Forecasting:** Accurately predicting sales trends to inform business strategies and promotions.
- **Supply Chain Optimization:** Streamlining the ordering process to align with predicted sales and avoid disruptions.

## Approach

### Data Preprocessing and Exploration
1. **Data Cleaning:** Remove any missing or inconsistent data entries, handle outliers, and format the data appropriately.
2. **Exploratory Data Analysis (EDA):** Analyze sales trends, seasonality, and patterns in the historical sales data. Visualize the data to identify significant features.

### Sales Prediction
3. **Feature Engineering:** Create relevant features from the sales data, such as day of the week, month, promotional periods, and holiday effects.
4. **Model Selection:** Choose an appropriate time series forecasting model (e.g., ARIMA, SARIMA, Prophet, LSTM, Regression Model).
5. **Model Training:** Train the predictive model on the historical sales data.
6. **Model Evaluation:** Use Mean Absolute Percentage Error (MAPE) to evaluate model performance.

### Purchase Order Generation
7. **Sales Forecasting:** Predict pizza sales for the next one week (or another specified period) using the trained model.
8. **Ingredient Calculation:** Calculate the required quantities of each ingredient based on the predicted sales and the ingredient dataset.
9. **Purchase Order Creation:** Generate a detailed purchase order listing the quantities of each ingredient needed for the predicted sales period.

## Results
- Accurate sales predictions.
- A comprehensive purchase order detailing the required ingredients for the forecasted sales period.


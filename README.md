REVOLUTIONIZING-WALMART-SALES-FORECASTING-A-TIME-SERIES-ANALYSIS-APPROACH-
This project aims to forecast weekly sales for Walmart stores using two different time series forecasting techniques: "SARIMAX" and "PROPHET". The dataset used in this project contains historical weekly sales data for 45 Walmart stores.

Techniques Used:
SARIMAX Model:
Utilized SARIMAX model with (1,0,1) order and (1,0,1,52) seasonal order to forecast weekly sales for each store.
Evaluated the model's performance using Mean Absolute Scaled Error (MASE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R^2) score.
Visualized the forecasted sales alongside the actual data for each store.
Prophet Model:
Implemented Facebook's Prophet forecasting model, which handles seasonality and holiday effects automatically.
Trained separate Prophet models for each store to forecast weekly sales.
Evaluated the model's performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R^2) score.
Visualized the historical sales data, forecasted sales, and uncertainty intervals for each store.

# Forecasting-Project
Sales Forecasting Using Machine Learning

This project focuses on forecasting daily product sales for the next 30 days, supporting inventory management and demand planning for retail businesses.

📊 Project Overview
We applied a combination of:

XGBoost and LightGBM (Gradient Boosting Decision Trees)

LSTM (Long Short-Term Memory Recurrent Neural Networks)

These models are optimized for capturing short-term trends, seasonality, and temporal dependencies in sales data.

📁 Dataset
Input Data: Daily sales quantity per product from ~12 months of historical sales records.

Assumptions: Only active products included (≥10 units sold in the last 90 days), no external factors (e.g., prices, promotions).

🛠️ Feature Engineering
Lag Features (1-day, 7-day)

Rolling Statistics (7-day, 14-day means, standard deviation)

Calendar Features (day of week, month, weekends)

Days Since Last Sale

🧪 Model Evaluation
Models are evaluated using:

MAPE, RMSE, and WMAPE

🚀 Potential Improvements
Longer time window (24+ months)

External data (holidays, promotions, prices)

Hierarchical modeling, advanced time-series models (Prophet, TCNs), and uncertainty estimation.

✅ Status: Completed
📌 Deliverables: Trained models, feature engineering pipeline, performance comparison, and forecasts exported to CSV.


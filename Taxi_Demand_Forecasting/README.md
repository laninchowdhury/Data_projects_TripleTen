# Taxi Demand Forecasting

This project forecasts taxi ride demand using time series data to help improve fleet allocation and reduce customer wait times.

## 🎯 Problem

Taxi companies face fluctuating demand. Predicting when and where rides are needed helps maximize profits and customer satisfaction.

## 🛠️ Tools & Technologies

- Python, pandas, matplotlib  
- statsmodels, scikit-learn  
- Time Series Analysis (Decomposition, Autocorrelation)

## 🔄 Process Overview

1. **Data Preprocessing** – Cleaned and formatted datetime values  
2. **EDA** – Identified seasonal trends and demand spikes  
3. **Feature Engineering** – Created time-based features (hour, day, etc.)  
4. **Modeling** – Used SARIMA and Random Forest  
5. **Evaluation** – Compared RMSE across models

## 📈 Results

- SARIMA model captured seasonality well  
- Forecasts helped predict peak demand hours  
- Business insight: Ride demand spikes during weekends and evenings

## 📁 Files

- `taxi_forecasting.ipynb` – Main notebook  
- `data/` – Raw and processed time series data
![Churn Distribution](images/Churn_distribution.png)
![ROC Curve](images/sklearn_metrics_roc.png)
📊 Visualizations

**Time Series Decomposition**
![Time Series Decomposition](images/Time_series_decompose.png)

**Predicted Taxi Orders by Hour**
![Hourly Demand](images/Hourly_Demand.png)

🧾 Conclusion

This project successfully demonstrated how time series forecasting can improve taxi fleet management. By identifying seasonal trends and using machine learning models like Random Forest and SARIMA, we were able to predict hourly taxi demand with reasonable accuracy. The insights can help taxi companies better allocate resources during peak hours, ultimately enhancing operational efficiency and customer satisfaction.


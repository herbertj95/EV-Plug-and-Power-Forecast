# EV-Plug-and-Power-Forecast
1-day forecast of Electric Vehicles (EVs) usage in the power system, specifically predicting the variables:
- Plug (Classification): 1 if a car is charging, or 0 if not.
- Power Consumption (Regression): the power consumed in the charging station every 15-min. 

**Data**
- "Colorado Boulder New.csv"

Includes 62.378 EV charging sessions from Boulder city in Colorado. Each row corresponds to one charging session and the information available corresponds to: Start Date Time, End Date Time, Total Duration, Charging Time, Energy Consumed (kWh), etc.    

**Jupyter Notebook** 
- "Colorado EV Power 1 Day Forecast 15min FINAL.ipynb"

Pipeline including Pre-Processing (Data Preparation), Feature Engineering , Exploratory Data Analysis (EDA), Clustering, Feature Selection, Forecasting (Models: Persistence, MLR, DT, RF, XGBOOST, LGBM, LSTM-NN and Stacking) and Comparison of Results (Metrics: MAE, NRMSE, R2 and Execution Time) for one station (BOULDER / N BOULDER REC 1).

**Auxiliary files**
- "conf.yml"
- "deep_model.py"

Used to construct LSTM-NN model.

# Air Quality Forecasting - Beijing PM2.5

Predicting daily PM2.5 air quality levels in Beijing using historical sensor data and weather measurements. Compares ARIMA, Prophet, and Random Forest with lag features.

Weekly project for Advanced Machine Learning II (Week 3 - Time Series).

## What is in here

- `notebooks/air_quality_forecasting.ipynb` - main notebook
- `notebooks/08.Week_3_Project.ipynb` - original Zindua project brief
- `data/beijing_air_quality.csv` - hourly readings from 12 Beijing stations (2013-2017)

## Methods

- ARIMA(5,1,0) - classical statistical time series model
- Prophet - Facebook's seasonal decomposition model
- Random Forest - ML approach using lag features, rolling averages, and weather data

## Data

UCI Beijing Multi-Site Air Quality dataset via OpenML (ID 42933). 420,768 hourly records across 12 monitoring stations. Analysis uses the Aotizhongxin station aggregated to daily averages.

## Author

James Mahinda

## ED-Analysis： 
### 1. Forecasting infectious and parasitic diseases emergency department admissions using high-dimensional data and forecast combinations
### 2. Ecological analysis
### 3. Processed data
####   'weather_half.csv’: meteorological and pollutant data in the daily resolution.

####   'variables.csv’: data frame of disease surveillance data, meteorological and pollutant data in the Epidemiological week (EW) resolution.

####   'forecast_assessment.xlsx’: MAPE, MASE and MAE of the forecasts versus observations.

####   Note: disease surveillance data and environmental data are confidential, so we have not made the dataset publicly available.
### 4.Code:
####   ‘data_preview.ipynb”: data processing for disease surveillance data, meteorological and pollutant data and visualization for disease surveillance data.

####   ‘forecast combinations&DM analysis.ipynb’: forecast combinations based on simple and trimmed mean and visualization of Diebold-Mariano test result.

####   ‘Autoregression.ipynb’: autoregression with exogenous variables model (lasso) & post selection inference. 

####   ‘AR&Naive and RF&GBM.ipynb’: autoregressive model and naive forecasting model & random forest model and gradient boosted machines.

####   ‘ED_LSTM_CNN_New.ipynb’: LSTM-CNN implemented in Pytorch.

# Times-Series
Forecasting on Global Active Power using SARIMAX vs Prophet

This project focuses on forecasting the Global Active Power consumption using time series analysis. The data includes daily measurements, with a significant seasonal component observed every 12 months. Various models, including SARIMA and Prophet, are evaluated for their effectiveness in predicting future power consumption. The seasonal ARIMA (SARIMA) model is applied with parameters tuned to capture the observed seasonality (S = 12). The Prophet model is also employed, providing a robust forecast with confidence intervals. Model performance is evaluated using metrics like MSE and MAE to determine the best-fit model.

### SARIMAX
Mean Squared Error (MSE): 0.1184408352482825

Mean Absolute Error (MAE): 0.24184884465585382

![image](https://github.com/user-attachments/assets/28a77fa9-98d3-4789-be31-d37817831b42)

### Prophet
Prophet Mean Squared Error (MSE): 0.08610210001315909

Prophet Mean Absolute Error (MAE): 0.2186598527771859

![image](https://github.com/user-attachments/assets/4545e23f-235d-4da3-a28e-ce0cdc239a87)

### Prediction on next 6 days with Prophet
![image](https://github.com/user-attachments/assets/2d5a6ae7-ef2e-43a4-9477-7427f873a934)

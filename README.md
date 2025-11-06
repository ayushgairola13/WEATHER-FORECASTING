# WEATHER-FORECASTING

This project aims to forecast future weather parameters (such as temperature, humidity, pressure, wind speed, etc.) using Deep Learning models.

REQUIRED LIBRARIES

* NumPy
* Pandas  
* Scikit-learn
* TensorFlow/Keras

DATASET:

('weather_data.csv')
The main forecasting target in this project is Temperature.

APPROACH:

1. Load the dataset and  prepare it by normalizing values, handling missing data.
2. Converting the data into a suitable format for time-series forecasting. 
3. Reshaped data for LSTM model.
4. Train the model on previous data and evaluate its performance.
5. now use the last available data for forecasting future temperature.

RESULT:
 Use the trained model to predict future weather conditions i.e *Forecasted Temperature for the next time step: 26.559833907507358*



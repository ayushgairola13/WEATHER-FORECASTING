# **WEATHER FORECASTING using LSTM (Deep Learning model)**


This project focuses on applying deep learning techniques, specifically Long Short-Term Memory (LSTM) networks, for time-series weather forecasting. The model predicts future temperature values using historical weather data that includes temperature, humidity, pressure, and wind speed.
LSTM models are well-suited for this task as they effectively learn sequential and temporal patterns, making them ideal for meteorological predictions.

## **Technical Overview :**

* Model Type: Sequential LSTM Neural Network
* Objective: Predict future temperature trends
* Frameworks Used: TensorFlow / Keras
* Dataset: weather_data.csv containing meteorological parameters
  

## **LIBRARIES USED :**

* NumPy
* Pandas
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
  
  
## **APPROACH :**

1. **Data Preprocessing**
   * Loaded and visualized weather data using Pandas and Matplotlib.
   * Normalized features (Temperature, Humidity, Wind Speed, Pressure) using MinMaxScaler.
   * Converted data into sequential format suitable for LSTM time-series forecasting.

2. **Model Development**
   * Built a two-layer LSTM model with Dropout layers to prevent overfitting.
   * Added Dense layers for final output prediction.
   * Compiled the model using the Adam optimizer and Mean Squared Error (MSE) loss function.

3. **Model Training and Evaluation**
   * Trained the model for 20 epochs with a train-test split of 80:20.
   * Monitored model performance using training and validation loss curves.
   * Achieved low validation loss (~0.0091), indicating good prediction accuracy.

4. **Prediction and Forecasting**
   * Compared actual and predicted temperature values using visualization.
   * Used the last available time window to forecast future temperature values.
     

## **RESULTS :**

* The LSTM model successfully captured temporal dependencies in the dataset.
* Forecasted temperature for the next time step: **26.56°C**
* Training and validation loss curves demonstrated stable learning and good generalization performance.



## **VISUALISATION**
* Temperature trend over time
* Training vs. Validation loss curve
* Actual vs. Predicted temperature plot

**STOCK_PRICE_FORECASTING_FOR_NEXT_10_CONSECUTIVE_DAYS**

Forecasting model was created by using Long-Short Term Memory(LSTM) and Tensorflow and Keras Framework was used

Long Short-Term Memory is an advanced version of recurrent neural network (RNN) architecture that was designed to model chronological sequences and their long-range dependencies more precisely than conventional RNNs. 

```python
Steps involved in model creation:
```
    Step1 : Importing necessary libraries
    Step2 : Analyzing the descriptive data
    Step3 : Visualizing the open price and close price data
    Step4 : Scaling the data for sensitive LSTM model
    Step5 : Splitting dataset into train and test split
    Step6 : Converting array of dataset into dataset matrix
    Step7 : reshape input to be [samples, time steps, features] which is required for LSTM
    Step8 : Create the Stacked LSTM model
    Step9 : Predict and check evaluation metrics
    Step10 : Transform back to original form
    Step11 : Calculate RMSE Performance metrics
    Step12 : Plotting the train prediction and test prediction
    Step13 : Demonstrating the prediction for next 10 days
    Step14 : Plotting the graph for predicted 10 days

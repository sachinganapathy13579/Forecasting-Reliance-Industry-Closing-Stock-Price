# Forecasting-Reliance-Industry-Closing-Stock-Price

## Business Objective:
    *  Predict the Reliance Industries Stock price for the next 30 days, i.e. for the month of February. Obtain the open, high, low and close prices from January 2015        to January 2023.
    
## The data was collected from :
    *  [finance.yahoo.](https://finance.yahoo.com/)

## Project Architecture :
    * Data Collection
    * EDA & Data Cleaning
    * Data Visualization
    * Model Building
    * Model Deployment using Streamlit

## Variable Description
    
    * Date : The day an investor places the buy order in the market or an exchange.
    * Open : Opening prices of a stock for a particular period of time.
    * High : High price a stock attained for a particular period of time.
    * Low : Low price a stock attained for a particular period of time.
    * Close : Closing prices of a stock for a particular period of time.
    * Adj Close : The closing price after adjustments for all applicable splits and dividend distributions.
    * Volume : The number of shares traded in a particular stock, index, or other investment over a specific period of time.

## EDA

    * The main purpose of EDA is to help look at data before making any assumptions. It can help identify obvious errors, as well as better understand patterns within       the data, detect outliers or anomalous events, find interesting relations among the variables.
    * I have used line plots to show the moving averages(uptrend and downtrend of data) and boxplots to show the dispersion of data from plotly.
    * Have checked for outliers and null and duplicate values in that data.
   
## Modelling

    * Used LSTM-Model for Forecasting Closing Stock Price.
    * The Long Short-Term Memory model is a subtype of Recurrent Neural Networks (RNN). It is used to recognize patterns in data sequences, such as those that appear         in sensor data, stock prices, or natural language.
    * RNN and LSTMs are types of neural networks that process sequential data. RNNs remember information from previous inputs but may struggle with long-term                 dependencies. LSTMs effectively store and access long-term dependencies using a special type of memory cell and gate.
    * LSTM uses three gates: input gate, forget gate, and output gate for processing.
    * The LSTM cell adds long-term memory in an even more performant way because it allows even more parameters to be learned. This makes it the most powerful to do         forecasting, especially when you have a longer-term trend in your data.
    
## Model Deployment : 
    * Used Streamlit for Model Deployment .
    * Streamlit allows you to re-use any Python code you have already written. This can save considerable amounts of time compared to non-Python based tools where all       code to create visualizations needs to be re-written.
    *  It is compatible with major python libraries such as scikit-learn, keras, PyTorch, latex, numpy, pandas, matplotlib, etc.

## Link to the Forecasting Model : https://sachinganapathy13579-forecasting-r-forecastinglstm-model-5egqvl.streamlit.app/

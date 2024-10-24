# StockPricePrediction
This repository is for prediction of stock price based on the data for Last 60 days. 

# Problem Statement:
Problem Statement 1:Predicting future stock prices based on historical data using a neural network. You can use a publicly available dataset like the Yahoo Finance dataset or any other stock market dataset of a company for the past 5 years. Your goal is to build a model that predicts the next day's closing price based on the previous 60 days of data.

# Approach:
Here I am considering the dataset Yahoo Finance dataset for company Asian Paints Limitedfor predicting stock price for the next day cloasing.

To solve these problem we can have following steps in our case study:

Data Gathering
Data Preprocessing
Model selection
Model Training
Stock price prediction

# Step 1 : Data Gathering 
Here we are gathering the data for the company Asian Paints Ltd. for Last 5 years

# Step 2 : Data Preprocessing
Data Normalization with MinMaxScaler.

# Step 3 : Model Selection
Here I have chosen LSTM model for stock price prediction.

Reason for Selection: We have multiple option available for predicting stock prices as below:

1. ARIMA
2. Holt-Winters
3. Linear Regression
4. SVR
5. RNN
6. LSTM
7. GRU etc.
   
We have chosen LSTM because

1. It performs better on Financial Time Series.
2. It can learn and handle Long Term dependencies.
3. Non Linearity can be easily handeled.

# Step 4: Model Training
I am using **adam** optimizer and **mean_squared_error** as loss functions. The resons are:

`adam`: As it has adaptive learning rate and roburst performance for regression problems.

`mean_squared_error`: It is widely used for regression problems for prediction of continuous values.

# Step 5 : Stock Price prediction for Asian Paints
Final prediction graph for stock price of Asian paints.

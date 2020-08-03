# Forcasting-Stock-Market-Prices-

As financial institutions begin to embrace artificial intelligence, machine learning is increasingly utilized to help make trading decisions. Although there is an abundance of stock data for machine learning models to train on, a high noise to signal ratio and the multitude of factors that affect stock prices are among the several reasons that predicting the market difficult. At the same time, these models don’t need to reach high levels of accuracy because even 60% accuracy can deliver solid returns. One method for predicting stock prices is using a long short-term memory neural network (LSTM) for times series forecasting.

## LSTMs:

LSTMs are an improved version of recurrent neural networks (RNNs). LSTMs are a type of RNN that remember information over long periods of time, making them better suited for predicting stock prices. 

## Dataset:

The dataset contains the actual stock market prices of Google for a certain number of years (5 years). This data is sufficient for predicting the variations in the prices of the concerned stock. Our goal is to predict the prices of the aforementioned stock for a particular month (January) of the following year. 
We then compare the predicted prices and actual prices in order to jump to a conclusion.

### Requirements: 

Numpy, Pandas, Sci-kit Learn, Matplotplib, Keras

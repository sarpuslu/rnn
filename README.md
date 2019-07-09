# Time Series Forecasting with Recurrent Neural Networks

## Introduction
This is a sample from my Financial Engineering Master's Thesis Project at Stevens Institute of Technology. 

## Motivation
Recurrent Neural Networks are ideal neural architectures for forecasting sequential data such as financial time series. The goal of this project is to apply LSTM, GRU and Elman networks for financial time series forecasting. 

## Approach
Neural networks are function approximators between input and output values. For time series data, inputs are fixed size windows of past values are outputs are fixed size windows of future values. 

In this project, fixed size window of past S&P500 daily index values are fed into the network and mapped to the next day's value. This one step ahead forecasting system is tested with various RNN architectures and compared by forecasting errors observed. 

## Details
See the pdf file for an in depth description of the project and the results. [Click here](https://github.com/sarpuslu/rnn/blob/master/Stock%20Time%20Series%20Forecasts%20by%20Recurrent%20Neural%20Networks.pdf)

See jupyter notebook to see an application of GRU Recurrent Neural Network to forecast one day ahead SP500 index values given four day length lagged fixed length window inputs. [Click here] (https://github.com/sarpuslu/rnn/blob/master/rnn-sp500index-forecast.ipynb)

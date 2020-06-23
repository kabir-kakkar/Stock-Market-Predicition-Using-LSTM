# Stock-Market-Prediction-Using-LSTM

## Introduction

Broadly stock market analysis is divided into two parts - Fundamental Analysis and Technical Analysis

1. Fundamental Analysis includes analyzing the company's future by analyzing its current business management and financial performance, balance sheet, etc.
2. Technical Analysis includes reading the prices of a stock by analyzing the charts.

We will be using the technical analysis part to determine stock prices. 

## Dataset

The Historical Stock Prices of AsianPaints have been prepared from nseindia website.

## The Long Short Term Memory

LSTMs can be considered as a tweaked version of Recurrent Neural Network (RNN) architecture, which has a useful property of remembering
only the important information and forgetting the networks that are not important. 

LSTMs have proven to be quite useful when it comes to predicting sequential dataset. They consist of <b>a cell, an input gate
, an output gate </b> and <b> a forget gate </b>.

The cell remembers values over random time intervals and the rest of the structure are responsible for adjusting the flow of information. 

## Result 

![Screenshot 1](https://user-images.githubusercontent.com/48717801/63224269-6b164480-c1df-11e9-96a9-ffcc10d563c5.PNG)

The output files were not exact but accurate enough to tell the momentum of a stock price, i.e., if the stock prices were going up or down.

# Predicting the crypto market

## About

This is a Mini-Project for SC1015 in which we try to predict the biggest cryptocurrency, Bitcoin and we further tested our model's capabilities on smaller cryptocurrency, Dogecoin.

## Problem Definition

- Are we able to predict the change in price of Bitcoin?
- Is there a model that can result in a profit?

## Models Used

1. Ordinary least square Linear Regression
2. Long Short-term memory Neural Networks

## Conclusion
- Although linear regression has a good R^2 and MSE, it does not translate to a profit
- Neural networks are more accurate in terms of predicting the overall trend to result in a net profit
- Although large number of neurons in hidden layer improves accuracy, the time taken for larger number of neurons in hidden layers is much greater
- Neural network model is more accurate on Bitcoin over Dogecoin
- It is still very possible to have multiple losing trades in row which can wipe out capital even if over a longer period it is profitable (Risk Management is still important)

## What did we learn from this project?
- Neural Networks, Keras and Tensorflow
- Using Plotly to visualise candlestick plot
- Using scaler to manipulate data for better sensitivity with neural networks


## Contents
- Dataset: The data sets that have been used in the project
- MiniProj: Code for Mini Project

## Members
- [@lolmode](https://github.com/lolmode):  Data cleaning, EDA on sample data, Script drafting
- [@Hexumicx](https://github.com/Hexumicx): Linear regression, LSTM RNN modeling, prediction on test sets, Script drafting
- Jun Kai: Analysis of simulated trading on test sets, Script, Presentation




The TSLA option chians dataset used in this project is downloaded from Kaggle (uploaded by Kyle Graupe)
https://www.kaggle.com/datasets/kylegraupe/tsla-daily-eod-options-quotes-2019-2022

This project investigates option pricing methods and dynamic hedging strategies. 
We compare two pricing models: the Black-Scholes model and the Merton Jump model.
We compute both historical and implied volatility from market data, 
then examine the volatility smile phenomenon across different strike prices. 

The project implements dynamic delta hedging using historical volatility and evaluates its effectiveness. 
We calibrate the Merton model to market data and compare hedging performance under both models. 
Despite significant pricing differences between models, hedging outcomes remain remarkably similar, 
suggesting that delta hedging robustness transcends model assumptions and volatility behavior.

# Forex Price Prediction with Recurrent Neural Networks (RNN)

![GitHub repo size](https://img.shields.io/github/repo-size/alimirash/RNN_Forex_Price_Prediction)
![GitHub contributors](https://img.shields.io/github/contributors/alimirash/RNN_Forex_Price_Prediction)
![GitHub stars](https://img.shields.io/github/stars/alimirash/RNN_Forex_Price_Prediction?style=social)
![GitHub forks](https://img.shields.io/github/forks/alimirash/RNN_Forex_Price_Prediction?style=social)

This is a simple RNN project for predicting forex (foreign exchange) prices. It utilizes historical forex price data to train an RNN model for price prediction.


## About
Forex Price Prediction with Recurrent Neural Networks (RNN) is an innovative project that leverages deep learning techniques to forecast currency exchange rates, specifically focusing on the EUR/USD pair. The aim of this project is to provide traders and financial analysts with a valuable tool for making more informed trading decisions in the dynamic forex market.

### Key Features

- **Time Series Forecasting:** We employ RNNs, a class of deep learning models well-suited for sequential data, to capture complex patterns and dependencies in historical forex price data.

- **Data Preprocessing:** The project includes robust data preprocessing pipelines, allowing users to efficiently prepare their historical forex price datasets for model training.

- **LSTM Architecture:** The RNN model used in this project consists of stacked Long Short-Term Memory (LSTM) layers, designed to capture both short-term and long-term price trends.

- **Dropout Layers:** To prevent overfitting and enhance model generalization, dropout layers are incorporated within the RNN architecture.

## Why Forex Price Prediction?

The foreign exchange (forex) market is one of the most liquid and dynamic financial markets globally, characterized by rapid price fluctuations. Accurate price forecasting is crucial for traders and investors to minimize risks and maximize profits. Traditional methods often struggle to capture the nuances of forex data, making deep learning approaches like RNNs an attractive alternative.

## Incorporating RSI (Relative Strength Index)

In this project, we have incorporated the Relative Strength Index (RSI) as an additional feature for forex price prediction. RSI is a popular momentum oscillator used in technical analysis to identify overbought or oversold conditions in a financial market.

### How RSI is Used

We have calculated the RSI based on historical price data, specifically the opening prices of the EUR/USD currency pair. The RSI values are used as part of the input features for training our Recurrent Neural Network (RNN) model.

- RSI values below 30 are typically considered oversold, suggesting a potential buying opportunity.
- RSI values above 70 are generally considered overbought, indicating a potential selling opportunity.

![RSI](https://github.com/alimirash/RNN_Forex_Price_Prediction/blob/d060a0a4b870dd524db2f37f9a79c0f6421781a2/RSI.png)


By incorporating RSI into our model, we aim to capture market sentiment and momentum, providing an additional dimension to our forex price predictions.

The RSI values are visualized in the project, allowing users to assess their significance in the context of price movements.

### Customization

Users are encouraged to explore and customize the RSI calculation and utilization in the project code to suit their specific needs and trading strategies.

Including RSI in our forex price prediction model enhances its capabilities and provides traders and analysts with a more comprehensive tool for decision-making.

## Who Can Benefit?

- **Traders:** Forex traders can utilize this tool to enhance their trading strategies by making data-driven decisions.

- **Financial Analysts:** Professionals in finance can leverage the RNN model for in-depth market analysis and trend predictions.

- **Educational Purposes:** Students and enthusiasts can explore the code and learn about deep learning applications in finance.

This project represents an exciting intersection of deep learning and finance, offering valuable insights into forex market dynamics. Whether you are a trader, analyst, or enthusiast, Forex Price Prediction with RNNs provides an accessible platform for currency exchange rate forecasting.

## Actual vs. Predicted Prices

This chart shows the comparison between actual and predicted prices.

![Actual vs. Predicted Prices](https://github.com/alimirash/RNN_Forex_Price_Prediction/blob/770fd6d8b05c93e11ef50253d8fa180fee16d711/Actual%20vs.%20Predicted%20Prices.png)


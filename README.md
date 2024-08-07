# Objective
The overarching goal of this project is to architect a sophisticated Q-learning model tailored for the stock market—a model that can not only compete with but also potentially eclipse the performance of traditional trading systems. 

# Data Sourcing
In this project, we conducted an extensive study on stock trading using reinforcement learning, specifically employing Q-learning techniques. To train and evaluate our models, we sourced historical stock price data for five major companies: Google, Amazon, Meta (formerly Facebook), IBM, and Apple. This data was collected through two primary sources: the Alpha Vantage API and Yahoo Finance and stored them to our Drive.

# EDA and Feature Engineering
After the data sourcing we have used the obtained data and did the exploratory data analysis to obtain meaningful insights. Then we did the feature engineerin. The meaningful features in our environment are
1. MACD(moving average convergence divergence): Used to identify trends and momentum by comparing relationship between two moving averages of stock prices.
2. RSI(relative strength index): Measures the speed and change of price movements to identify overbought or oversold conditions.
3. Bollinger Bands: Provides insights into price volatility.
4. Volatility: Measured over a fixed time period as the standard deviation of price changes.
5. Moving Averages: Measured over a fixed time period as the standard deviation of price changes.
6. Price Levels: By categorizing continuous price data into discrete levels, the model can more easily learn typical behaviors or outcomes associated with specific price ranges.

# Code Explination
The code provided demonstrates how the Q-learning model is implemented and applied to stock trading. We detail the functions and methods, explaining how each contributes to the overall learning and decision-making process of the agent.
## Initialization and Environment Setup
The code begins with importing essential libraries and initializing the TradingEnvironment with historical stock data for Meta Platforms, Inc.
## Agent Training and Q-table Optimization
A series of epochs runs where the QLearningTrader interacts with the environment, makes decisions, and learns from the results, optimizing its Q-table to make better decisions in future episodes.
This research showcases the potential of Q-learning in constructing algorithmic trading strategies that are both adaptive and data-driven. The success of the model across different stocks indicates the versatility and robustness of reinforcement learning in the financial domain.





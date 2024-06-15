
Stock Market Predictor using Reinforcement Learning 

This project demonstrates the application of Reinforcement Learning (RL) in predicting stock market trends and making trading decisions. The agent is trained using Q-learning to maximize profit by buying, selling, or holding stocks based on historical price data.

Overview : 
The goal of this project is to develop a Q-learning agent capable of predicting stock market movements and making informed trading decisions. The agent is trained using historical stock data of RELIANCE for the year 2020. By analyzing past price movements, the agent learns to optimize its trading strategy to maximize profit.

Methodology : 
The Q-learning algorithm forms the core of this project. Q-learning is a model-free RL algorithm that enables the agent to learn the best actions to take in a given state. The key components of the project include:

1. State Representation: The agent's state is represented by the price differences in a sliding window of closing prices. This representation allows the agent to capture relevant patterns in the stock price movements.

2. Action Space: The agent can take three actions - buy, sell, or hold - based on its current state and learned policy.

3. Reward System: The agent receives rewards based on the profit made from its actions. A successful trade results in a positive reward, while an unsuccessful trade leads to a negative reward.

4. Experience Replay: To improve learning efficiency, the agent stores its experiences and samples them randomly to train the model in batches.

5. Exploration vs Exploitation: Initially, the agent explores different actions to learn about the environment. As it gains experience, it shifts towards exploiting the best-known actions to maximize profit.

The agent's performance is evaluated based on the total gains and the percentage of investment returns. The plot generated shows the stock prices with the points where the agent decided to buy or sell.

Usage : 
Install the required libraries: pandas, numpy, seaborn, matplotlib, yfinance, pandas_datareader, tensorflow.
Run the main.py file to train the Q-learning agent on historical stock data and visualize its performance.


![image](https://github.com/22b2272/SOC-RLstock/assets/126689571/6197c0e4-7519-42b0-a2fc-c4ccc1ed303f)

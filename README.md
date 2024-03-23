# Real-time-Stock-Price-Analysis-and-Algorithmic-Trading

## Introduction

This project is a sophisticated system designed for real-time stock price analysis and algorithmic trading. It comprises two main components: data collection, storage, and preprocessing (Part 1), and algorithm development, mock trading environment, and performance evaluation (Part 2).

## Part 1: Data Collection, Storage, and Preprocessing

In Part 1, we established the foundational elements of our stock analysis and trading system. This phase involved leveraging a variety of technologies and techniques:

#### Technologies Used
Yahoo Finance API (yfinance): Utilized for collecting real-time stock price data from a diverse range of stocks.
MySQL Database: Employed for efficient storage, retrieval, and manipulation of collected data.

#### Novel Contributions
Custom Data Preprocessing Techniques: Developed innovative methods for cleaning, transforming, and engineering features in the collected data, ensuring its suitability for advanced analysis and modeling.

## Part 2: Algorithm Development and Mock Trading Environment

### 1. Algorithm Development

In Part 2, we dive into the technical intricacies of developing robust algorithms for predicting optimal buy/sell signals. Here are the key technical aspects:

#### Technologies Used

Python: The primary programming language for algorithm implementation and system development.

TensorFlow and scikit-learn: Leveraged for modeling and evaluating various trading algorithms, including moving average crossover strategies, relative strength index (RSI), and advanced techniques like Long Short-Term Memory (LSTM) networks.

#### Novel Contributions
Advanced Algorithmic Techniques: Explored and implemented cutting-edge methodologies such as LSTM networks for more accurate and dynamic stock price predictions.

Custom Evaluation Metrics: Introduced novel performance evaluation metrics tailored to the specific requirements of algorithmic trading, providing deeper insights into trading strategy effectiveness.

### 2. Mock Trading Environment
To rigorously test and evaluate our algorithms, we created a simulated trading environment with a focus on technical sophistication:

#### Technologies Used

Python Scripting: Used for building the mock trading environment and managing portfolio operations.

MySQL Database: Integrated for seamless interaction between the trading environment and stored data.

#### Novel Contributions

Realistic Simulation: Developed a highly realistic mock trading environment that accurately simulates real-world trading scenarios, facilitating comprehensive algorithm testing and validation.

Dynamic Portfolio Management: Implemented dynamic portfolio management capabilities, allowing users to adjust strategies and holdings in response to market changes during simulation.

## Project Components

The project includes the following key files, each contributing to its technical depth and functionality:

tracker.py: Python script for algorithm implementation, portfolio management, and trading simulation.

model_training.py: Python script for training LSTM models for stock price prediction.

lstm.py: Python script containing functions for preprocessing stock data and initializing LSTM models.

## Usage

### Data Collection and Preprocessing:

Run the provided Python scripts to collect real-time stock data, store it in a MySQL database, and preprocess it for analysis.

### Algorithm Development:

Implement trading algorithms based on the provided guidelines and resources.

Experiment with different techniques such as moving averages, RSI, and LSTM networks for predicting stock prices.

### Mock Trading Environment:

Create portfolios using the tracker.py script, specifying initial funds and stock holdings.

Execute mock trades and evaluate algorithm performance using the same script.

View performance metrics and analyze trading strategies.

### Model Training:

Train LSTM models for stock price prediction using the model_training.py script.

## Conclusion
This project represents a culmination of advanced technical expertise and innovative approaches in the domain of real-time stock price analysis and algorithmic trading. By leveraging cutting-edge technologies and novel methodologies, it offers a powerful framework for developing, testing, and optimizing trading strategies in dynamic market environments. Whether you're a seasoned trader or a data scientist exploring financial markets, this project provides a comprehensive toolkit for driving informed decision-making and maximizing trading performance.

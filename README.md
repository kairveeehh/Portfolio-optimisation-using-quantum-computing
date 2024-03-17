# Portfolio Optimization using Quant Methods

it also required some previous infor about monte-carlo-simulation

This project focused on analyzing stocks and optimizing portfolios using quant computing  methods, including classical and quantum approaches. The analysis covered fetching real-time stock data, data processing, visualization, portfolio optimization, and Monte Carlo simulation for stock price forecasting.

## Table of Contents

1. [Introduction](#introduction)
2. [Libraries Used](#libraries-used)
3. [Data Collection](#data-collection)
4. [Data Processing and Analysis](#data-processing-and-analysis)
5. [Portfolio Optimization](#portfolio-optimization)
6. [Comparing Optimization Results](#comparing-optimization-results)
7. [Monte Carlo Simulation](#monte-carlo-simulation)
8. [Conclusion](#conclusion)

## Introduction

The project aimed to provide a comprehensive approach to analyzing stocks, optimizing portfolios, and forecasting future stock prices using both classical and quantum methods. The analysis covered a selected list of stocks, excluding 'FB', within a specific time frame.

## Libraries Used

For this analysis, I leveraged the following libraries:

- `yfinance` for fetching historical market data.
- `numpy` for numerical computing tasks.
- `pandas` for data manipulation and analysis.
- `qiskit` for quantum computing tasks.
- `matplotlib.pyplot` for creating plots and visualizations.
- `seaborn` for statistical data visualization.
- `time` for time-related operations.

## Data Collection

I began by collecting historical market data for the selected list of stocks using the `yfinance` library. The data covered the period from January 1, 2022, to January 1, 2023.

## Data Processing and Analysis

In this phase, I processed and analyzed the collected data:

- **'Adj Close' Focus:** I concentrated the analysis on the 'Adj Close' price for precise price tracking.
- **Percentage Change Calculation:** Daily percentage changes in stock prices were calculated to understand volatility.
- **Covariance and Correlation:** I computed covariance and correlation matrices to analyze relationships and diversification benefits between stock returns.
- **Expected Returns:** Mean returns (expected returns) for each stock were calculated.
- **Risk-Free Rate:** A risk-free rate of return was set for optimization.

## Portfolio Optimization

I explored portfolio optimization using both classical and quantum methods:

- **Quantum Portfolio Optimization:** I employed quantum computing techniques for portfolio optimization.
- **Classical Portfolio Optimization:** I utilized classical optimization approaches based on mathematical methods.

## Comparing Optimization Results

I compared the results obtained from classical and quantum portfo

##Author

Kairvee vaswani 

vkairvee@gmail.com

# Crypto Trading Algorithm

## Overview
This notebook explores a cryptocurrency trading algorithm using Python. It utilizes historical market data of Bitcoin to USD, performs analysis, and implements a simple trading strategy based on Moving Average Crossover.

## Requirements
Ensure you have the following libraries installed:
- yfinance
- pandas
- numpy
- matplotlib

You can install these libraries using pip:
```bash
pip install yfinance pandas numpy matplotlib
```

## Getting Started
1. Install the required libraries.
2. Open and run the notebook (`Crypto Trading Algorithm.ipynb`) in a Jupyter environment.

## Contents
- Installation instructions for necessary libraries.
- Retrieving and visualizing cryptocurrency market data.
- Implementing Simple Moving Averages (SMA).
- Creating a basic trading algorithm using SMA Crossover strategy.
- Backtesting the algorithm on historical Bitcoin data for the year 2020.
- Plotting performance comparison with a Buy and Hold strategy.

## Files
- `Crypto Trading Algorithm.ipynb`: Main notebook containing Python code and analysis.
- `README.md`: This file, providing an overview of the notebook.

## Usage
- Open the notebook in Jupyter.
- Run each cell sequentially to see data retrieval, analysis, and trading strategy implementation.
- Modify parameters like interval, start date, and end date for different analyses.
- Experiment with different Moving Average intervals (`short_interval` and `long_interval`) to see their effects on strategy performance.

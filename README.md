# Tanker Pitch Portfolio Optimization

## Overview
This project applies financial data analysis and portfolio optimization techniques to trade stocks of tanker shipping companies based on signals derived from Baltic Indexes.

## Features
- Used Baltic Dirty, Clean, and Dry Tanker Indexes to derive a composite "Baltic Tanker Index."
- Tested cointegrating relationships between Baltic Tanker Index and tanker shipping company stock prices using the Johansen test.
- Developed trading signals using short-term and long-term moving averages.

## Results
- Sharpe Ratio: 0.67 for Teekay Tankers (TNK) over 6 years.
- Implemented risk assessments for volatility and freight rate pass-through.

## Files
- `Tanker Pitch Finalized.ipynb`: Code for data analysis and portfolio optimization.
- `Tanker Pitch Writeup.pdf`: Detailed report on methodology and results.

## Next Steps
- Automate tanker company selection from NYSE.
- Experiment with optimized entry signals using training/test datasets.

## Technologies
- Python
- Jupyter Notebook
- Pandas, NumPy, and Matplotlib

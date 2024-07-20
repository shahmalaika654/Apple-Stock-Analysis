## Stock Trading Analysis Dashboard

Welcome to the Stock Trading Analysis Dashboard project. This repository offers a comprehensive analysis of historical stock prices, focusing on Apple Inc. (AAPL) from May 2014 to May 2020. It includes moving averages, buy and sell signals, and visualizations of significant trading events.

### Analysis Overview

This project explores Apple stock's historical performance to provide insights for traders and investors. The analysis includes:

**Calculating Moving Averages:**  
We compute the 30-day Simple Moving Average (SMA30) and the 100-day Simple Moving Average (SMA100) to smooth price data and identify trends.

**Visualizing Stock Prices and SMAs:**  
We create plots displaying Apple's historical adjusted close prices alongside SMA30 and SMA100, aiding stakeholders in understanding price trends relative to these moving averages.

**Buy and Sell Signal Logic:**  
We define a function to generate buy and sell signals based on the SMA30 and SMA100 relationship, tracking prices, holding status, and actions, reflecting past trading decisions.

**Applying Buy and Sell Signals:**  
We apply the buy and sell signal logic to our stock data, adding columns for "Buy Price," "Sell Price," "Hold," and "Actions," indicating transaction points based on moving averages.

### Key Observations

- Apple's adjusted close price generally follows SMA30 and SMA100 trends.
- Buy points are strategically placed to optimize market entry for potential gains.
- Profit and loss transactions validate the trading strategy's effectiveness.

### Conclusion

This analysis offers valuable insights into Apple's historical stock performance. By following the identified buy and sell points, traders and investors could have potentially achieved positive returns during the analyzed period.

### Getting Started

1. Clone this repository to your local machine.
2. Review the Jupyter Notebook with the code and analysis: `Stock_Trading_Analysis.ipynb`.
3. Ensure you have the necessary libraries installed (using pip or conda).
4. Run the Jupyter Notebook and explore the detailed analysis.


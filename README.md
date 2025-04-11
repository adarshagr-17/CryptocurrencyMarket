# Cryptocurrency Market Analysis

## Overview
This project analyzes cryptocurrency market data from December 2017, providing insights into market capitalizations, volatility, and the distribution of different cryptocurrency sizes in the ecosystem. Through visualization and data manipulation techniques, the project illuminates key characteristics of the cryptocurrency market during a period of significant interest and growth.

## Project Contents
The analysis includes:
- Examination of Bitcoin's market dominance relative to other cryptocurrencies
- Visualization of market capitalization for top cryptocurrencies
- Analysis of 24-hour and 7-day volatility patterns
- Classification of cryptocurrencies by market capitalization size
- Comparison of "winners" and "losers" in terms of price changes

## Requirements
- Python 3.6+
- pandas
- matplotlib
- Jupyter Notebook

## Installation
1. Clone this repository
2. Install the required packages:
```
pip install pandas matplotlib jupyter
```

## Usage
1. Launch Jupyter Notebook:
```
jupyter notebook
```
2. Open the `cryptocurrency_analysis.ipynb` file
3. Execute the cells sequentially to reproduce the analysis

## Dataset
The analysis uses data from CoinMarketCap from December 6, 2017, stored in `datasets/coinmarketcap_06122017.csv`. The dataset includes information on cryptocurrency market capitalization, price changes, and other metrics.

> **Note**: The public CoinMarketCap API used to obtain this data went private in 2020 and is no longer freely available.

## Key Insights
- Bitcoin maintained dominant market capitalization in December 2017
- Cryptocurrency markets demonstrate extreme volatility, with some coins showing dramatic price changes in short periods
- The majority of cryptocurrencies have very small market capitalizations
- Various categories of cryptocurrencies (Bitcoin forks, smart contract platforms, etc.) show different market behaviors

## Warning
This project is for educational purposes only and does not constitute investment advice. The cryptocurrency market is exceptionally volatile, and investments may lose significant value. Always conduct thorough research before making any investment decisions.

## Acknowledgments
- Data provided by CoinMarketCap (historical dataset from 2017)
- Analysis inspired by the growing significance of blockchain technology and digital assets

## License

This project is licensed under the [MIT License](./LICENSE).

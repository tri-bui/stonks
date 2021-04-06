# Dip Dive

This project will take a deep dive into stock market dips and corrections. A market decline of over 10% is considered a correction and a decline of over 20% is considered a bear market. [[3](https://www.schwab.com/resource-center/insights/content/market-correction-what-does-it-mean)] The goal is to gain a better understanding of market corrections so that we are better-equipped, if not prepared, for any future corrections. In this analysis, I will attempt to answer the following questions:

1. How often do corrections occur?
2. How long do they usually last?
3. Are there any early warning signs or patterns?
4. Are there any stocks that serve as an early indicator?
5. Can corrections be predicted?

## Data

This analysis uses historical trading data of 1,746 NASDAQ-listed stocks found on [Kaggle](https://www.kaggle.com/paultimothymooney/stock-market-data). The `stock_market_data/nasdaq/csv/` directory was downloaded from the source, renamed as `nasdaq/`, and added to this project's `data/` subdirectory. There are over 3,000 stocks listed with the NASDAQ [[2](https://www.investopedia.com/terms/n/nasdaq.asp)], but for the purposes of this analysis, more than half will suffice.

The (daily) historical data of each stock is contained in its own CSV file with the ticker symbol as the file name (e.g. `TSLA.csv`). Stocks that have been listed longer obviously have more historical data, so not every file has the same amount of data. Each file has 7 columns: `Date`, `Low`, `Open`, `Volume`, `High`, `Close`, and `Adjusted Close`.

## Sources

1. [Kaggle - Data](https://www.kaggle.com/paultimothymooney/stock-market-data)
2. [Investopedia - Nasdaq](https://www.investopedia.com/terms/n/nasdaq.asp)
3. [Schwab - Market Correction: What Does It Mean?](https://www.schwab.com/resource-center/insights/content/market-correction-what-does-it-mean)

## License

This repository is licensed under the MIT license.
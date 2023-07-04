# Building an Effective Trading Screener with Python and Tradingview


Trading screeners are indispensable tools for traders and investors seeking opportunities in the vast financial markets. By applying specific criteria and indicators to filter through a multitude of instruments, we can uncover potential trades with higher probabilities of success.

To accomplish this, we will leverage the `tradingview_ta` library, a powerful Python library that provides access to a wide range of updated and popular indicators used by traders worldwide. This ensures that we stay ahead of the game by incorporating the latest market insights into our screening process. We’ll also utilize the `yfinance` library to download historical quotes for our selected instruments effortlessly. This gives us a solid historical data foundation for comprehensive analysis and testing.

This article will focus on a practical application using Argentine ADRs (American Depositary Receipts). However, it’s important to note that the principles and techniques we explore can be applied to a wide range of instruments available on Tradingview. Whether you’re interested in stocks, futures, ETFs, cryptocurrencies, or any other tradable asset, this screener can adapt to your needs.

In the first part, we create a graph where we can visually see how many technical indicators give purchase or sale for each of the analyzed actions. 
![Indicators](https://github.com/facundoallia/Trading-Screener-with-Python-and-Tradingview/blob/main/Assets/indicators.png)


Then, in the second section, we download the detail of each of the technical indicators to filter and search for trading opportunities in specific assets.

![shares](https://github.com/facundoallia/Trading-Screener-with-Python-and-Tradingview/blob/main/Assets/adr_fil.png)

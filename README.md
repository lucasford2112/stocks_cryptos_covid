## Graph analysis for the evolution of stock markets, cryptocurrencies and Covid-19 cases and deaths

The discussion about up to what level do investors look into the real economy to make decisions is a much debated one. The positive and behavioral approaches -along with all their intersections- are research rabbit holes that seek to shed some light on the logic behind investment allocation decisions. However, no matter how far into one side or another one was standing, Covid-19 paralyzed the world. Therefore, it was discounted that the largest economic shock of our generation would be reflected in the forever record breaking stock market. But what about the crypto market? After the Bitcoin halving that took place in May 2020, a bull market was expected in the crypto universe. If history serves as a predictor of the future -another controversial debate-, 2021 was expected to be a reprise of the 2013 and 2017 bullish trends. 

With more than 18 months into the pandemic, we know that the stock market took an early hit, followed by a fast recovery that led to new all time highs. On the other hand, we saw that Covid was not enough to cancel the crypto-party expected for this year. To see how all these facts check out graphically, we are going to analyze the following series:

- Covid-19 daily evolution of cases and deaths for all 38 OECD countries combined
- The evolution of these stock markets: US 🇺🇸 (S&P500), Germany 🇩🇪 (DAX), Great Britain 🇬🇧 (FTSE 100), Japan 🇯🇵 (Nikkei 225), and Canada 🇨🇦 (S&P/TSX)
- The top 5 cryptocurrencies ranked by their market share: Bitcoin, Ethereum, Binance Coin, Cardano, Solana.

All the data is pulled either from a website or a specific python package. More specifically

- Covid data is downloaded directly from https://covid.ourworldindata.org/data/owid-covid-data.csv
- Stock data is pulled with the Yahoo Finance Python package
- Crypto data is pulled with the fast quant Python package.


# Fin Tech Project 1

---

## A price performance analysis for various crypto alt coins.
---
**Data** - Pulled from Coinbase Pro's API using the CBPRO library https://pypi.org/project/cbpro/ 

---

**Motivation** 
1. Shared interest in Crypto assets and their performance over time.
2. We sought to understand how closely alternative crypto assets (Alt Coins) performed compared to Bitcoin.
3. We also wanted to understand which alt coins performed as well, better or worse than Bitcoin historically.
4. Finally, we wanted to analyze a crypto portfolio to a comparable portfolio made up of the S&P500 stocks. 
---                 
**Questions we wanted to answer:**
1. Where can we find reliable historical data on crypto assets dating back at least two years?
2. Which alt coins performed best on a daily and cumulative basis?
3. Which alt coin prices are most closely correlated to Bitcoin price?
4. Which portfolio performed the best over the past 2 years? (slightly less due to data cleaning)
    * Portfolio 1 - 50% BTC, 50% even distribution of the altcoins mentioned above.
    * Portfolio 2 – 50% BTC, 25% ETH, 25% even distribution of remaining alt coins.
    * Portfolio 3 – Totally even distribution of alt coins and BTC. 1/13th per coin.
    * Portfolio 4 – Weighted Distribution based on the market cap percentage (of the total market cap of crypto) of each alt as of  
              09-18-2019. – This data was taken from https://www.coingecko.com/en 
    * Portfolio 5 – No BTC or ETH – Just an even distribution of other alt coins.
    * Portfolio 6 – S&P 500 Only, no crypto. Data extracted from https://finance.yahoo.com/ 

---

**Where can we find reliable historical data on crypto assets dating back at least two years?** 

  * We chose Coinbase due to the name recognition and probably the oldest data set in the United States.
  * We also wanted to use a platform that has a readily available and quick to learn API. While this API may not be ideal, the documentation was clear enough, and got the job done.

**Which alt coins performed best on a daily and cumulative basis?**
  * As seen from the plot below Chainlink (LINK) outperformed all crypto alt coins we analyzed. A close second was Ether (ETH)
  ![alt text](https://github.com/padibona/FinTechProject1/blob/main/Images/Cryptocumulative.png)
  * We also created this pie chart to show the overall performance in % gains:
  ![alt text](https://github.com/padibona/FinTechProject1/blob/main/Images/Cryptopie.png)
1. Alt coin prices were highly correlated with Bitcoin (BTC) price, which we had assumed was the case.
2. ETH and LTC were the two alt coins that correlated the closest to BTC price.
3. Of the 6 portfolios we analyzed, Portfolio 2 outperformed all other portfolios.
4. The worst performing portfolio was Portfolio 6 which consisted of S&P 500 Stocks. 





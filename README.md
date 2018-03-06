# crypto

## 0. Time Range: 20170101 - 20180131

## 1. Risk vs Daily Return analysis
*[Attachment: Result 0131_Sample.csv]*

  * [x] Sample size: 999 assets

  * [x] Asset Breakdown ('boundary': fixed in the sample; high volatility/return, more comparable with cryptos):
    - Bond_HY: 256 (26 points are on the 'boundary', with volatility >= 0.04 and return >= 0.001)
    - Bond_IG: 277 (12 points are on the 'boundary', with volatility >= 0.04 and return >= 0.001)
    - Equity: 261 (18 points are on the 'boundary', with volatility >= 0.04 and return >= 0.005)
    - Crypto: 30
    - Commodity: 22
    - Currency: 153 (can further reduce the number by removing 8 pegged USD currencies, which has 0 return & volatility)
  
  * [x] Fix a small list of assets: 
    - Reference points: AAPL US Equity, 700 HK Equity, 6502 JT Equity, ZAR Curncy, CL1 Comdty
    - Boundary points:
      - Bond_HY: 256 (26 points are on the 'boundary', with volatility >= 0.04 and return >= 0.001)
      - Bond_IG: 277 (12 points are on the 'boundary', with volatility >= 0.04 and return >= 0.001)

  * [x] Show Median stock & bond volatility

## 2. Liquidity analysis: Trading Turnover & Market cap data
*[Attachment: Trading Turnover and Marketcap_0131.xlsx ]*
  * [x] Turnover Crypto vs Stock 0131 tab: Comparison of Turnover for top 30 crypto, stock and currency
  * [x] Marketcap Crypto vs Stock 0131 tab: Comparison of Marketcap % (as of the total Marketcap for 30 crypto/30 stocks)

## 3. ICO vs Tech IPO comparison
*[Attachment: 1. Overview ICO & Tech IPO.xlsx ]*
  * [x] Return (IPO 30 Calendar days) tab: Day 30 return means return after a calendar month.
  * [x] Return (IPO 30 Trading days) tab: Day 30 return means return after 30 trading days
  * Selection Criteria for both Tech IPO & ICO:
    - Announced Date: Year 2017
    - Available Pricing Data Points: More than 90 days
    - Offer size: all greater than 10M USD
  * Data Source:
    - IPO: Bloomberg {IPO SU<GO>}
    - ICO: use the list from CoinDesk (https://www.coindesk.com/ico-tracker/) and with available 60, 90 days historical pricing information in (https://coinmarketcap.com)

## 4. Correlation
*[Attachment: correlation_assetclass_0131.xlsx]*
  * [x] Calculated daily return from 20170101 and cross-asset correlation (Pearson Linear Correlation)
  * [x] Asset selection: include 30 cryptos, 10 Curncy , 10 Equity indexes, 9 bond indexes and 22 Comdty (89 assets in total)

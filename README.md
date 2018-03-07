# crypto

## 0. Time Range: 20170901 - 20180302

## 1. Risk vs Daily Return analysis
*File: 1. Result 0302_Sample.csv*

  * [x] Sample size: 960 assets

  * [x] Asset Breakdown ('boundary': fixed in the sample; high volatility/return, more comparable with cryptos):
    - Bond_HY: 255 (45 points are on the 'boundary', with volatility >= 0.04 and return >= 0.001)
    - Bond_IG: 258 (8 points are on the 'boundary', with volatility >= 0.04 and return >= 0.001)
    - Equity: 242 (30 points are on the 'boundary', with volatility >= 0.04 and return >= 0.005)
    - Crypto: 30
    - Commodity: 22
    - Currency: 153 (can further reduce the number by removing 8 pegged USD currencies, which has 0 return & volatility)
  
  * File Annotation:
    - Column F: Asset Descriptive Name
    - Column G: Features
      - "Reference Point": 5 important Assets to highlight (AAPL US Equity, 700 HK Equity, 6502 JT Equity, ZAR Curncy, CL1 Comdty)
      - "Median_Bond" & "Median_Equity": Median tickers in terms of Volatility for Bond and Equity class (88947EAQ3 corp, WAB UN Equity)
      - "1": crypto currency
 
## 2. Liquidity analysis: Trading Turnover & Market cap data
*File: 2. Trading Turnover and Marketcap (Crypto, Equity, FX)_0302.xlsx*
  * [x] Turnover Crypto vs Stock 0302 tab: Comparison of Turnover for top 30 crypto, stock and currency
  * [x] Marketcap Crypto vs Stock 0302 tab: Comparison of Marketcap % (as of the total Marketcap for 30 crypto/30 stocks)

## 3. ICO vs Tech IPO comparison
*File: 3. Overview ICO & Tech IPO.xlsx*
  * [x] Return (90 days) tab: Include Day 1, Day 30, Day 60 and Day 90 return (xx times than initial offer price)
  * [x] Return (60 days) tab: Include Day 1, Day 30, Day 60 return (the ICO names change slightly, due to some ICO only has more than 60-days but less than 90-days pricing data 
  * Selection Criteria for both Tech IPO & ICO:
    - Announced Date: Year 2017
    - Available Pricing Data Points: More than 90 days / 60 days
    - Offer size: all greater than 10M USD
  * Data Source:
    - IPO: Bloomberg {IPO SU<GO>}
    - ICO: use the list from CoinDesk (https://www.coindesk.com/ico-tracker/) and with available 60, 90 days historical pricing information in (https://coinmarketcap.com)

## 4. Correlation
*File: 4. correlation_assetclass_0302.xlsx*
  * [x] Calculated daily return from 20170901 and cross-asset correlation (Pearson Linear Correlation)
  * [x] Asset selection: include 30 cryptos, 10 Curncy , 10 Equity indexes, 9 bond indexes and 22 Comdty (89 assets in total)

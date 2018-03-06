# crypto

0. Time Range: 20170101 - 20180131

1. Risk vs Daily Return analysis
[Attachment: Result 0131_Sample.csv]
•	Sample size: 999 assets
•	Asset Breakdown ('boundary': fixed in the sample; high volatility/return, more comparable with cryptos):
  o	Bond_HY: 256 (26 points are on the 'boundary', with volatility >= 0.04 and return >= 0.001)
  o	Bond_IG: 277 (12 points are on the 'boundary', with volatility >= 0.04 and return >= 0.001)
  o	Equity: 261 (18 points are on the 'boundary', with volatility >= 0.04 and return >= 0.005)
  o Crypto: 30
  o	Commodity: 22
  o	Currency: 153 (can further reduce the number by removing 8 pegged USD currencies, which has 0 return & volatility)
•	Fix a small list of popular stocks (e.g., Apple, Facebook, etc)
•	Median stock & bond volatility

2. Liquidity analysis: Trading Turnover & Market cap data
[Attachment: Trading Turnover and Marketcap_0131.xlsx ]
•	Turnover Crypto vs Stock 0131 tab: Comparison of Turnover for top 30 crypto, stock and currency
•	Marketcap Crypto vs Stock 0131 tab: Comparison of Marketcap % (as of the total Marketcap for 30 crypto/30 stocks)

3. ICO vs Tech IPO comparison
[Attachment: 1. Overview ICO & Tech IPO.xlsx ]
•	Return (IPO 30 Calendar days) tab: Day 30 return means return after a calendar month.
•	Return (IPO 30 Trading days) tab: Day 30 return means return after 30 trading days
•	Selection Criteria for both Tech IPO & ICO:
o	Announced Date: Year 2017
o	Available Pricing Data Points: More than 30 days
o	Offer size: all greater than 25M USD
•	Data Source:
o	IPO: Bloomberg {IPO SU<GO>}
o	ICO: use the list from CoinDesk (https://www.coindesk.com/ico-tracker/) and with available 60, 90 days historical pricing information in (https://coinmarketcap.com)

4. Correlation
[Attachment: correlation_assetclass_0131.xlsx]
•	Calculated daily return from 20170101 and cross-asset correlation (Pearson Linear Correlation)
•	Asset selection: include 30 cryptos, 10 Curncy , 10 Equity indexes, 9 bond indexes and 22 Comdty (89 assets in total)

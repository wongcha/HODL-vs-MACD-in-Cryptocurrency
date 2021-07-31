# Backtest for MACD vs HODL in cryptocurrency
Backtest of different MACD stretegies vs HODL in cryptocurrency

I'm always curious about the MACD if it really works because it makes sense but too simple to be work. And another thing that I want to know is about  the cut loss technique that said if the price drop down to X%, sell it no matter what the indicators say.

These are things that I want to know in this back test.
1. Is MACD stretegy better than HODL?
2. Is daily MACD + weekly MACD (MACD Mixed stretegy) is better than daily MACD only?
3. Is cut loss really helpful? If so, how much should we set.

******************************************************************************************************************************************************
# Key takeaway from the result

To make visualization easier, I built the dashboard to view the result.

https://public.tableau.com/app/profile/wongsatorn/viz/MACDvsHODLincryptocurrencybacktest/BacktestResult


Below are keys takeaway I found:
1. Simple daily MACD > 0 win most of the scenario
2. Include cut loss into stretegy "always" improve the result. In this backtest, cut loss will be activated when toay's closing price is lower than the lowest of yesterday by 10%
3. MACD-Signal do well in the coin that price didn't grow well (XRP in this case)
4. Mixed stretegy (daily + weekly) lose to daily stretegy in most case due to missed-opportunity.

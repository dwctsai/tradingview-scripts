# TradingView - Scripts for Indicators and Strategies

## About TradingView

TradingView is a trading platform that specializes in charts for stocks.  It uses [Pine Script](https://www.tradingview.com/pine-script-docs/welcome/), TradingView's custom programming language, to allow advanced traders to create their own trading tools.


## My Custom Indicators and Strategies

This repository is for custom Indicator and Strategy scripts which users can add to their TradingView Supercharts.

### Combo Indicator

The script for my "Combo Indicator" contains the following indicators:

#### Multi EMA ####

Set up to five Exponential Moving Average trails.  An EMA is a type of moving average that gives more weight to recent price data and less to older data, making it more responsive to price changes than a simple moving average (SMA).  EMAs can be used to determine trend direction, with a rising EMA suggesting an uptrend and a falling EMA indicating a downtrend.

Popular EMAs track the average price over the last 9, 21, 50, 100, or 200 time periods, depending on the trader's strategy.

#### Volume Weighted Average Price (VWAP) ####

A trading benchmark that reflects the average price of a security throughout a trading session, weighted by the volume of shares traded at different price levels.  It's calculated by summing the products of price and volume for each trade and dividing by the total volume for the period.

VWAP is only active for intraday charts (i.e. it won't work for daily charts or longer intervals).



### How to Use

1. From TradingView, open the Superchart.
2. Click the "Pine" button on the far-right vertical menu.
3. Copy/paste code from a Pine script into the empty web IDE text field.
4. Click the "Add to chart" button at the top.
5. The custom indicator should now appear on the chart.

# Trader Behavior vs Market Sentiment Analysis

## Overview
This project analyzes how market sentiment (Fear vs Greed) affects trader behavior and profitability.

## Datasets
- Fear & Greed Index dataset
- Hyperliquid historical trader data

## Setup

Install required libraries:

pip install pandas numpy matplotlib seaborn

## How to Run

1. Download datasets
2. Open notebook: trader_sentiment_analysis.ipynb
3. Run all cells to reproduce results

## Outputs

Charts showing:
- PnL vs sentiment
- trade frequency
- long/short behavior


## Methodology

1. Data cleaned and merged by date
2. Sentiment mapped to each trade
3. Trader behavior metrics calculated
4. Performance compared across sentiment regimes

## Insights

 Insight 1:
Average PnL is higher during Greed days, indicating traders perform better in bullish sentiment.

Insight 2:
Trade sizes increase significantly during Greed periods.

Insight 3:
Fear sentiment leads to more short positions.

## Strategy Recommendations

Strategy 1
Reduce leverage during Fear periods to avoid volatility losses.

Strategy 2
Increase long exposure during Greed periods when win rates improve.

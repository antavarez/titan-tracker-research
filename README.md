# VIX DCA Analysis

**Research question:** Does elevated market volatility (VIX > 25) create superior DCA entry points?

## Findings
- High VIX (>25): mean 3-month return = 4.55% (n=252)
- Normal VIX (15-25): mean 3-month return = 1.48% (n=652)
- T-statistic: 4.831 | p-value: <0.0001
- **Result: Statistically significant. High-VIX periods produce 3x better 3-month returns.**

## Data
24 years of weekly SPY and VIX data (2000–present) via yfinance

## Tools
Python, pandas, scipy, matplotlib, yfinance

## Notebook
View analysis: [Colab Notebook](https://colab.research.google.com/drive/1de4KCblR_Y6o9Hu7YVTm8_Pa7CdUirbU?authuser=1#scrollTo=87gSgXBv9VqF&line=1&uniqifier=1

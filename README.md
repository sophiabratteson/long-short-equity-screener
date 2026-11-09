# Long/Short Equity Screener: Online Advertising Platforms

A Python project that ranks online advertising companies on value, growth,
profitability and financial health to identify a long/short stock pair.
Built for a stock pitch to the Fairfield Hedge Fund Group (FHFG).

## The idea
Companies that sell the same thing (ads) should be comparable. By scoring each
one against its peers, I look for the most attractive company to buy (long)
and the least attractive to bet against (short).

## Companies covered
GOOGL, META, PINS, SNAP, RDDT, MTCH, IAC, YELP

## Status
- [x] Pull company data with yfinance
- [ ] Clean data and compute factor scores (z-scores)
- [ ] Valuation comparison (comps)
- [ ] Risk analysis (volatility, beta, drawdown)
- [ ] Final pitch

## Tools
Python, pandas, yfinance, Google Colab

*For educational purposes only. Not investment advice.*

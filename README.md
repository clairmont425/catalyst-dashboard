# Government Contract Catalyst Dashboard

Live small/mid-cap public-company government contract catalyst tracker. Data from USAspending.gov, SEC filings, and live market data. Auto-refreshed twice daily.

## Live dashboard

https://clairmont425.github.io/catalyst-dashboard/

Auto-refreshed twice daily (6:00 AM + 11:00 AM ET) from [USAspending.gov](https://api.usaspending.gov/), enriched with market cap (SEC) and price/volume/short-interest signals.

## How to read it

- **Conviction score** combines size of the catalyst (% of market   cap), recency of price action, volume confirmation, and short   interest. Higher = cleaner setup.
- **% Cap** = sum of all awards in the window as a percentage of   the recipient's market cap. Bigger = the contract should move   the stock more.
- **1d / 5d / 30d** = price change since the announcement window.   Big positive = catalyst likely already priced in.
- **VolX** = today's volume divided by 30-day average. >2× confirms   a real news-driven move.
- **SI%** = short interest as % of float (squeeze fuel).

## Disclaimer

Not financial advice. Data is informational only. Source filings are public; analysis is heuristic.

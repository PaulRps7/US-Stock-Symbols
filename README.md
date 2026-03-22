# US Stock Tickers

An aggregation of current US Stock Symbols in `json` and `txt` formats.  

Updated daily at midnight, EST.
## Exchanges Available

- NASDAQ
- NYSE
- AMEX


## How to use the data

Each exchange has three file types: 

`exchange_full_ticker.json` 

This is the raw data from NASDAQ list.  It is not a simple list of ticker symbols and contains full company name, ticker, last sale, net change, %change, volume, MC, county, IPO year, industry, sector and the URL.

`exchange_tickers.json` 

This is a `json` list of the ticker symbols on that exchange. Nothing more. 

`exchange_tickers.txt` 

This is a newline separated `txt` list of the ticker symbols on the exchange. Nothing more. 
## All Symbols
Some symbols (escpecially blue chip stocks) may overlap across multiple exchanges due to multi-listings. I highly recommend just using a singular exchange.

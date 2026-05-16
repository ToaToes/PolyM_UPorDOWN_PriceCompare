# getPrice_Poly.py

To get BTC current price every sec provided from BTC (Chainlink) which might be different from OKX or Binance<br>
But its where Poly gets data from<br>

To get UP and DOWN percentage, which just represents the price to bid in cents

To get Time left in 5min, or 15min, or 1Day

Price to beat is estimated from BTC current price with UP and DOWN percentage before 30 secs<br>
since its not possible to get Price to Beat directly from Poly which API not allowed

# fallback.py

Just for testing with API

# PriceCompare.py

For compare the price showing on Poly, with OKX and Binance platform, just for ur curiousity

# getPrice_Poly.py

To get BTC current price every sec provided from BTC (Chainlink) which might be different from OKX or Binance<br>
But its where Poly gets data from<br>

To get UP and DOWN percentage, which just represents the price to bid in cents

To get Time left in 5min, or 15min, or 1Day

Using last s 0:00 price as the price for next 5 min price to beat, error is controlled within 0.0026%, pretty accurate
cant make 100% accurate due to latency and time adjustment, or just tje distance from the server

# fallback.py

Just for testing with API

# PriceCompare.py

For compare the price showing on Poly, with OKX and Binance platform, just for ur curiousity

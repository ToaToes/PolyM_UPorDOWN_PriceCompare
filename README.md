# Polymarket BTC 5-Minute Window Tracker

实时监控 Polymarket BTC 5分钟涨跌窗口的价格和概率。

## 系统要求

- Python 3.8 或更高版本
- 稳定的网络连接（需要访问 Polymarket API 和 WebSocket）

## 安装步骤

1. **克隆或下载代码**

2. **创建虚拟环境（推荐）**
   ```bash
   python -m venv venv
   
   # Windows
   venv\Scripts\activate
   
   # Linux/Mac
   source venv/bin/activate


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

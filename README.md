# 🪙 Coinwatch

A terminal-based crypto tracker to monitor real-time prices, plot ASCII charts, and set price alerts. Built with Python and the CoinGecko API.

## Features
- Live coin prices
- Historical ASCII charts
- Threshold-based alerts
- Clean CLI interface

## Setup
```bash
git clone https://github.com/danielyoungkimball/coinwatch.git
cd coinwatch
pip install -r requirements.txt
```

## Usage
```bash
python cli.py --price btc eth
python cli.py --history btc --days 30
python cli.py --watch btc --above 50000
```

# Crypto Trading Sentiment Analysis

Analysis of trader behavior vs market sentiment (Fear & Greed) using Hyperliquid trading data.

## Quick Start
```bash
pip install pandas numpy matplotlib seaborn
python analysis.py
```
# Data Required
```bash
csv_files/fear_greed_index.csv - Market sentiment data
csv_files/historical_data.csv - Trading transactions (skipped uploading here due to github limit)
```
# Output
12 visualizations saved to outputs/ directory analyzing:

PnL by sentiment
Win rates & volume patterns
Contrarian vs herd behavior
Time-based trading edges
Risk-reward analysis

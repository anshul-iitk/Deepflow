# Market Sentiment & Trader Performance Analysis

This Task explores the relationship between **Bitcoin market sentiment** (Fear/Greed) and **trader performance** using real execution data.

## Dataset Sources
- [`historical_data.csv`](./data/historical_data.csv) - Trader execution data from Hyperliquid
- [`fear_greed_index.csv`](./data/fear_greed_index.csv) - Bitcoin sentiment index

## Key Findings
- Traders performed better on Greed days, especially with large trades.
- SELL trades consistently had higher win rates, especially during Fear.
- BUY trades showed higher profit under Fear sentiment, SELL trades under Greed.
- Greed days showed higher PnL volatility — indicating more aggressive risk behavior.

## Structure
- `notebooks/` – Jupyter notebook with full analysis
- `data/` – Input datasets
- `images/` – Generated plots
- `report/` – Final written insights



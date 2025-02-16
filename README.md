This project analyzes 90 days of historical trade data from multiple Binance accounts. The goal is to compute financial performance metrics, rank the accounts based on their trading success, and generate a top 20 ranked list.

Objectives
Load and clean the dataset for analysis.
Calculate key financial metrics:
ROI (Return on Investment)
PnL (Profit and Loss)
Sharpe Ratio
Maximum Drawdown (MDD)
Win Rate
Win Positions
Total Positions
Develop a ranking algorithm using weighted scores.
Generate insights and produce a final ranked list of top-performing accounts.
Dataset Information
The dataset consists of Binance trade histories containing:

Port_IDs: Unique account identifiers.
Trade History: Timestamps, assets, BUY/SELL actions, price, and other details.
quantity: Money involved in the trade.
qty: Coin amount traded.
realizedProfit: Profit or loss from the trade.
Methodology
1. Data Exploration & Cleaning
Loaded the dataset and handled missing values.
Standardized column names and data formats.
2. Feature Engineering
Classified trade positions based on side and positionSide.
Computed financial metrics for each account.
Applied a weighting system to score accounts effectively.
3. Ranking Algorithm
Designed a scoring model based on multiple financial indicators.
Ranked accounts based on their overall profitability and risk-adjusted returns.
4. Results & Deliverables
Jupyter Notebook containing the full data analysis and calculations.
CSV file with computed financial metrics for all accounts.
A ranked list of the top 20 accounts based on performance.
Summary report outlining the methodology, findings, and insights.

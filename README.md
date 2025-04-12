# Algorithmic Trading Strategy Development – BTC/USD

## Overview
This project focuses on developing and optimizing a quantitative trading strategy for the BTC/USD market. The aim is to build a reliable, backtestable system that identifies high-probability entry and exit zones using technical indicators and market structure analysis.

## Objectives
- Design a strategy that operates during low-liquidity time zones (10 PM to 2 AM IST).
- Integrate RSI confirmation with EMA crossovers and order block detection.
- Create a rule-based entry and exit framework.
- Test and optimize the strategy through historical performance analysis.
- Automate alerts and backtesting using TradingView (Pine Script).

## Tools & Technologies
- Trading Platform: TradingView
- Scripting Language: Pine Script
- Indicators: EMA (9, 21), RSI (14), Order Block Detector (LuxAlgo), Price Action Zones
- Data Analysis: Equity curve, Win/Loss ratio, Drawdown metrics
- Strategy Testing: Manual trades + Visual backtesting on 15m BTC/USD chart

## Strategy Logic
- **Entry Criteria**:
  - Price reclaims bullish order block
  - EMA 9 crosses above EMA 21 (momentum confirmation)
  - RSI > 50 and climbing
- **Exit Criteria**:
  - Hit predefined resistance zone
  - Stop-loss triggered (defined by recent swing low/high or order block)

## Performance Metrics (as of April 12, 2025)
- Total Trades: 25+
- Win Rate: ~60%
- Max Drawdown (per trade): ~2.5%
- Avg. Risk-Reward Ratio: 1:1.5

## Key Learnings
- Importance of liquidity zones and market timing for crypto
- Risk management through systematic SL/TP rules
- Challenges with emotional execution – countered by automation
- How market structure adapts around high-impact news events

## Future Enhancements
- Add volume profile confirmation
- Integrate sentiment analysis and macro triggers
- API-based execution via Python and broker (e.g., Exness/ANT)

## Repo Link / Access
[Private GitHub or Notion Workspace - available upon request]

---
For recruiters or collaborators: Please reach out for access to trade logs, code samples, and backtest visuals.


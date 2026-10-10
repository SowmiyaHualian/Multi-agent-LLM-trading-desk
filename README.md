# Multi-Agent LLM Trading Desk 🏴‍☠️

A research project where specialized LLM agents analyze a stock from different angles, debate, and reach a trading decision. **Status: in progress. Educational project, not financial advice.**

## Planned design
| Agent | Job |
|---|---|
| Fundamental analyst | Reads financial statements and key ratios |
| Sentiment analyst | Scores news and social text |
| Technical analyst | Reads price and indicator signals |
| Bull / Bear researchers | Argue opposite sides of the case |
| Trader | Weighs the debate and proposes an action |
| Risk manager | Checks position size and limits, can veto |

Inspired by the TradingAgents paper.

## Roadmap
- [ ] Data layer (prices, fundamentals, news)
- [ ] Individual analyst agents
- [ ] Debate loop between researchers
- [ ] Trader and risk-manager agents
- [ ] Backtest against a simple baseline (buy-and-hold)
- [ ] Results and limitations write-up

## Stack
Python · LLM API · pandas

## Disclaimer
This is for learning only. Nothing here is investment advice.

# Aurum AI - Trading Guide

## Overview
AI-powered desktop platform for gold market analysis with MetaTrader 5 integration.

## Architecture
`
Market Data --> AI Analysis --> Signal Generation --> MT5 Execution
     |              |                |                    |
  Gold Prices   LSTM/Prophet    Buy/Sell Signals    Auto Trading
  Indicators    Sentiment       Risk Management     Order Mgmt
`

## Setup
`bash
git clone https://github.com/Coretech001/Aurum-AI.git
cd Aurum-AI
pip install -r requirements.txt
`

## Features
| Feature | Description |
|---------|-------------|
| Market Analysis | Real-time gold price analysis |
| AI Models | LSTM, Prophet forecasting |
| MT5 Integration | Automated trade execution |
| Backtesting | Historical strategy testing |

## Risk Warning
Trading involves risk. Use paper trading first.

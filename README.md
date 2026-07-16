# exchange-engine-
# MercuryX

**MercuryX** is an educational simulation of an electronic stock exchange matching engine. Instead of building a trading app or predicting stock prices, this project focuses on the core system responsible for receiving orders, maintaining an order book, matching buyers and sellers, and executing trades.

The goal is to understand how modern exchanges process thousands of orders in real time using **price-time priority**, the matching logic used by many electronic markets.

## What this project is

* A simulation of a stock exchange's matching engine
* A real-time order book implementation
* A price-time priority order matching algorithm
* A market simulator with live order execution
* A dashboard for visualizing market activity and system performance

## What this project is not

* A stock prediction application
* A trading bot
* A broker like Zerodha or Groww
* A platform for real-money trading

## Features

* Buy and sell order placement
* Limit and market orders
* Order book management
* Partial and complete order execution
* Trade history
* Live order book updates
* Market replay simulation
* Performance metrics and analytics
* REST APIs and WebSocket support

## Tech Stack

### Backend

* Python
* FastAPI
* PostgreSQL
* SQLAlchemy
* WebSockets

### Frontend

* React
* TypeScript
* Tailwind CSS
* shadcn/ui
* Recharts

### Tools

* Docker
* Git
* Pytest

## Project Structure

```text
mercuryx/
├── backend/
│   ├── engine/
│   ├── api/
│   ├── database/
│   ├── websocket/
│   └── tests/
├── frontend/
├── docs/
└── README.md
```

## Why I built this

Most trading-related student projects focus on predicting stock prices or building trading dashboards. I wanted to understand what happens inside an exchange after a trader clicks **Buy** or **Sell**.

This project explores the engineering behind electronic markets by implementing the systems that receive orders, maintain an order book, match compatible orders, execute trades, and broadcast market updates in real time.

## Future Enhancements

* Multiple trading strategies
* Historical market replay
* Matching engine benchmarking
* Latency simulation
* Multi-symbol support
* Risk management module
* Stress testing with high order volumes
* Docker deployment
* Cloud hosting

## Learning Goals

* Market microstructure
* Order matching algorithms
* Data structures and algorithms
* Event-driven systems
* Real-time backend development
* WebSockets
* REST API design
* Performance optimization
* System design

# Quantier

A paper-trading platform for exploring market data, virtual portfolios, trading strategies, and AI-assisted financial research.

## Features

- Virtual portfolio and trade management
- Market data integration
- Portfolio analytics
- AI-assisted trading research
- REST API and web dashboard

## Tech Stack

- **Frontend:** React, Vite, TypeScript
- **Backend:** Python, FastAPI
- **Data:** SQLite, with optional PostgreSQL support

## Getting Started

### Prerequisites

- Python 3.11+
- Node.js and npm

### Backend

```powershell
Copy-Item .env.example .env
pip install -r service/requirements.txt
cd service/server
python main.py
```

### Frontend

In a separate terminal:

```powershell
cd service/frontend
npm install
npm run dev
```

Check `.env.example` and the project documentation for any additional configuration required.

## Disclaimer

Quantier is intended for educational purposes, research, and simulated trading. It does not provide financial advice.

## Acknowledgements

This project builds on [AI-Trader](https://github.com/Acceleratorer/AI-Trader). Please refer to the original project for its license and attribution requirements.

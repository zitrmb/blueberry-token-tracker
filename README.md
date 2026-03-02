# 🫐 Blueberry Token Tracker

[![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100%2B-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-compatible-5A4FCF?logo=opentelemetry&logoColor=white)](https://opentelemetry.io/)
[![Open Source](https://img.shields.io/badge/Open%20Source-Yes-success)](https://github.com/)

**Tagline:** Know exactly where your AI tokens go.

Blueberry Token Tracker is an open-source AI token usage analytics platform by **Blueberry Systems**. It helps teams track, control, and optimize AI token usage across agents, models, and sessions.

## What it does

- Real-time token monitoring for AI agents (starting with OpenClaw)
- Per-agent, per-model, per-session tracking
- Budget enforcement with weekly/monthly limits and alerts
- Delegation analytics (which agents delegate to cheaper models)
- A/B testing for model efficiency
- Predictive analytics and cost forecasting
- 60+ API endpoints, 173 tests

## Features

- 📊 Real-Time Dashboard
- 💰 Budget Enforcement & Alerts
- 🤖 Agent Delegation Tracking
- 🔬 A/B Testing
- 📈 Predictive Analytics
- 🔌 OTel-compatible (OpenTelemetry)

## Quick Start

1. Clone the repository and install dependencies:

   ```bash
   git clone https://github.com/blueberrysystems/blueberry-token-tracker.git
   cd blueberry-token-tracker
   pip install -r requirements.txt
   ```

2. Set required environment variables:

   ```bash
   export TOKEN_DB_PATH=./data/tokens.db
   export TOKEN_TRACKER_ENV=development
   export TOKEN_ALERT_EMAIL=ops@example.com
   ```

3. Run the application:

   ```bash
   python main.py
   ```

> Or use our managed cloud at **tokentracker.blueberrysystems.com** (coming soon).

## Architecture

Built with **FastAPI + SQLite + OTel receiver**. Deploy as a single binary-style service with no external infrastructure dependencies.

## Pricing (Managed Cloud)

- **Free:** €0/mo
- **Starter:** €3.99/mo
- **Pro:** €39.99/mo

Full pricing: https://tokentracker.blueberrysystems.com/pricing

## Tech Stack

- Python
- FastAPI
- SQLite
- OpenTelemetry
- Blueberry CSS Framework

## Contributing

Contributions are welcome.

- Open an issue for bugs, ideas, or feature requests
- Submit pull requests for fixes and improvements
- Keep changes focused and include tests where relevant

## License

**AGPL-3.0** — free to self-host, managed cloud available.

## Links

- Website: https://tokentracker.blueberrysystems.com
- Dashboard Demo: https://tokens.thinkyfy.com
- Blueberry Systems: https://blueberrysystems.com
- Discord: (placeholder)

# AssetOrbit AI

AI-powered asset management and equipment rental platform for service-heavy businesses, construction operators, rental fleets, and field asset teams.

AssetOrbit AI helps businesses track equipment, schedule maintenance, optimize utilization, and reduce operational downtime from one unified system.

## Why it matters

Most asset-heavy businesses lose value not because they lack equipment, but because asset operations are fragmented:

- equipment status is unclear
- rental schedules are manual
- maintenance is reactive instead of predictive
- utilization is invisible
- returns and handovers are poorly tracked
- service alerts arrive too late
- reporting is slow and inaccurate

AssetOrbit AI brings visibility, control, and forecasting into one operating layer.

## Product vision

AssetOrbit AI is an asset intelligence platform for businesses with:

- equipment tracking
- rental lifecycle management
- maintenance planning
- usage analytics
- downtime alerts
- AI-based utilization recommendations
- customer and asset documentation

## Core features

- asset inventory and fleet dashboard
- equipment lifecycle tracking
- rental and return workflows
- maintenance scheduling and alerts
- usage analytics and utilization reports
- service history and document storage
- AI recommendations for maintenance and utilization
- team and customer visibility

## Ideal customers

- equipment rental companies
- construction operations
- field service providers
- industrial asset teams
- contractors with mobile machinery
- operations-heavy service businesses

## Tech stack

- Backend: Python, FastAPI
- Frontend: Next.js, TypeScript, React
- Database: PostgreSQL-ready, SQLite for MVP
- Infra: Docker, Redis
- Integrations: Stripe-ready billing support

## Business model

- SaaS subscriptions
- per-asset or per-fleet pricing
- implementation and onboarding packages
- premium analytics and alerting
- custom workflow integrations

## Local development

### Backend

```bash
cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

### Frontend

```bash
cd frontend
npm install
npm run dev -- --host
```

### Docker

```bash
docker-compose up --build
```

## Project structure

```text
backend/
  app/
  requirements.txt
frontend/
  src/
docker-compose.yml
README.md
LICENSE
```

## Roadmap

- live asset tracking
- inventory health scoring
- predictive maintenance alerts
- rental optimization engine
- AI recommendations for utilization
- customer portal support
- integration with billing and operations workflows

## Contact

- Email: ki9521787@gmail.com
- GitHub: https://github.com/ki9521787ki9521787/assetorbit-ai

## License

This project is designed for commercial SaaS use and custom asset management workflows.

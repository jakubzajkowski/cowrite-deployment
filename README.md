# Co-Write Deployment

This repository contains the deployment configuration for the Co-Write notes application. It uses Docker Compose to orchestrate all necessary services including the frontend, backend APIs, database, and monitoring tools.

## Services

- **Frontend** - React web application served through Nginx
- **User Service** - Spring Boot application handling authentication and user management
- **AI Service** - Python/FastAPI service providing AI-powered chat functionality
- **PostgreSQL** - Database for storing application data
- **Prometheus** - Metrics collection and monitoring
- **Grafana** - Visualization and dashboards for monitoring data
- **Node Exporter** - System metrics exporter

## Getting Started

1. Clone this repository
2. Copy `.env.example` to `.env` and configure your environment variables
3. Run `docker-compose up -d` to start all services
4. Access the application at `http://localhost:3000`

## Configuration

Make sure to set up the following environment variables in your `.env` file:
- Database credentials
- JWT secrets and configuration
- API keys (e.g., Gemini API key)
- Service-specific settings

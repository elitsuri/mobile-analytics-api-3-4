# mobile-analytics-api-3

> Mobile Analytics API 3: Mobile analytics collection API with event batching and dashboards

##  Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Audit logging and activity history
- Background jobs for long-running workflows
- Admin analytics dashboard with operational metrics
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway
- Health checks, readiness checks, and structured logging
- Production-oriented environment configuration

##  Tech Stack
Flutter, Dart, Node.js, MongoDB, Firebase

##  Architecture
Three-tier architecture: Flutter, Dart backend, native frontend, PostgreSQL database. Containerized with Docker.

##  Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/mobile-analytics-api-3
cd mobile-analytics-api-3

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```

# Go Service Template by financenick

Production-ready template for building scalable backend services in Go.

Designed for fast project bootstrapping with clean architecture, REST API support, configuration management, structured logging, Docker integration, and extensible infrastructure components.

---

## Features

- Clean project structure
- REST API server
- Graceful shutdown
- Environment configuration (`.env`)
- Docker & Docker Compose support
- Structured logging
- Middleware support
- Ready for PostgreSQL / Redis / Kafka integration
- Dependency injection friendly
- Scalable architecture
- Production-oriented layout

---

## Tech Stack

- Golang
- net/http
- Docker
- Docker Compose
- PostgreSQL
- Redis
- Kafka
- Makefile

---

## Project Structure

```text
.
├── cmd/                # Application entrypoints
├── internal/           # Private application logic
│   ├── handler/        # HTTP handlers
│   ├── service/        # Business logic
│   ├── repository/     # Database layer
│   ├── middleware/     # HTTP middleware
│   └── config/         # Configuration
├── pkg/                # Shared packages
├── migrations/         # SQL migrations
├── docker/             # Docker files
├── .env
├── Makefile
└── docker-compose.yml

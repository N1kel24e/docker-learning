# Docker Learning Project

A practical project demonstrating containerization and CI/CD pipeline setup using Docker, Docker Compose, and GitHub Actions.

## Stack

- **Python** — application logic
- **Docker** — containerization
- **Docker Compose** — multi-service orchestration
- **GitHub Actions** — automated testing and CI/CD pipeline

## Project Structure
├── app.py               # Main application
├── test_app.py          # Unit tests
├── Dockerfile           # Container build instructions
├── docker-compose.yml   # Multi-service setup
├── requirements.txt     # Python dependencies
└── .github/workflows/   # CI/CD pipeline configuration

## Getting Started

### Prerequisites
- Docker
- Docker Compose

### Run locally

```bash
git clone https://github.com/N1kel24e/docker-learning
cd docker-learning
docker-compose up --build
```

### Run tests

```bash
docker-compose run app pytest test_app.py
```

## CI/CD

GitHub Actions pipeline automatically runs tests on every push to `main` branch, ensuring code quality and build integrity.

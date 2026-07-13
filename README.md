# OpportunityHub

> Enterprise-grade platform for discovering entry-level career opportunities across South Africa.

## Overview

OpportunityHub is a modern web platform that automatically aggregates internships, graduate programmes, learnerships, apprenticeships, bursaries, scholarships, vacation work, Work-Integrated Learning (WIL), and entry-level jobs from trusted company career pages, government portals, and university websites.

The platform centralizes opportunities into a single searchable application, helping students, graduates, and job seekers find relevant opportunities quickly while eliminating the need to browse hundreds of individual websites.

---

## Features

1. Automated opportunity aggregation from multiple trusted sources.
2. Intelligent duplicate detection using fingerprinting and fuzzy matching.
3. Advanced search, filtering, sorting, and pagination.
4. User authentication with JWT and role-based authorization.
5. Saved opportunities and personalized job alerts.
6. Company management and automatic company discovery.
7. Distributed Playwright scraping powered by RabbitMQ.
8. Dead-Letter Queue (DLQ) and scraper health monitoring.
9. Redirect gateway with click analytics.
10. Analytics dashboard for hiring trends.
11. POPIA-compliant data handling and security.

---

## Technology Stack

### Frontend

1. React
2. TypeScript
3. Vite
4. Tailwind CSS
5. TanStack Query
6. Zustand

### Backend

1. Java 21
2. Spring Boot
3. Spring Security
4. Spring Data JPA
5. JWT Authentication
6. Flyway

### Database

1. PostgreSQL

### Scraping

1. Playwright for Java
2. RabbitMQ
3. Jsoup

### Monitoring

1. Micrometer
2. Prometheus
3. Grafana

---

## Repository Structure

```text
OpportunityHub/
│
├── .ai/
├── docs/
├── backend/
├── frontend/
├── scraper-workers/
├── .github/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Development Roadmap

### Phase 1

1. Project setup
2. Authentication
3. Database design
4. User management

### Phase 2

1. Opportunity management
2. Search
3. Filtering
4. Saved opportunities

### Phase 3

1. Distributed scraper
2. RabbitMQ integration
3. Playwright workers
4. Duplicate detection

### Phase 4

1. Notifications
2. Admin dashboard
3. Link health monitoring

### Phase 5

1. Analytics
2. Redirect gateway
3. Hiring trends
4. Company auto-discovery

### Phase 6

1. AI recommendations
2. Mobile application
3. Employer portal

---

## Architecture

OpportunityHub follows modern enterprise software engineering principles.

1. Clean Architecture
2. Domain-Driven Design (DDD)
3. SOLID Principles
4. Configuration-driven scraping
5. Distributed worker architecture
6. Event-driven messaging
7. Secure REST APIs
8. Scalable backend services

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/<your-username>/OpportunityHub.git
```

### Backend

```bash
cd backend
```

### Frontend

```bash
cd frontend
```

### Scraper Workers

```bash
cd scraper-workers
```

---

## Project Status

🚧 Active Development

OpportunityHub is currently under active development as an enterprise portfolio project demonstrating modern full-stack software engineering, distributed systems, scalable web scraping, cloud-ready architecture, and secure application development.

---

## License

This project is licensed under the MIT License.

# OpportunityHub

OpportunityHub is an enterprise-grade web platform that aggregates entry-level career opportunities across South Africa into a single, searchable application. The platform automatically discovers internships, graduate programmes, learnerships, apprenticeships, bursaries, scholarships, vacation work, Work-Integrated Learning (WIL), and junior jobs from company career pages, government portals, and university websites.

Built with a modern distributed architecture, OpportunityHub combines a React frontend, Spring Boot backend, PostgreSQL database, Playwright-based scraping engine, RabbitMQ message queues, and advanced monitoring to provide a scalable, reliable, and high-performance solution for students, graduates, and job seekers.

## Key Features

1. Automatic opportunity aggregation from multiple trusted sources.
2. Distributed Playwright scraping with RabbitMQ workers.
3. Intelligent duplicate detection using fingerprinting and fuzzy matching.
4. Advanced search, filtering, sorting, and pagination.
5. User accounts with JWT authentication and role-based authorization.
6. Saved opportunities and personalized job alerts.
7. Company management and automatic company discovery.
8. Redirect gateway with click analytics.
9. Scraper health monitoring and Dead-Letter Queue (DLQ) recovery.
10. Link health validation for application URLs.
11. Analytics dashboard for hiring trends and platform insights.
12. POPIA-compliant data handling and enterprise-level security.

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
6. Flyway Database Migrations

### Database

1. PostgreSQL

### Scraping

1. Playwright for Java
2. Jsoup
3. RabbitMQ
4. Distributed Worker Architecture

### Monitoring

1. Micrometer
2. Prometheus
3. Grafana

## Project Goals

1. Simplify the job search process by collecting entry-level opportunities from multiple trusted sources into one centralized platform.
2. Reduce the time students, graduates, and job seekers spend searching across hundreds of company and government websites.
3. Provide fast, reliable, and intelligent search capabilities with filtering and personalized alerts.
4. Deliver a scalable distributed architecture capable of supporting thousands of concurrent users and automated scraping workers.
5. Ensure high code quality by following Clean Architecture, Domain-Driven Design (DDD), SOLID principles, and enterprise software engineering practices.
6. Maintain secure, reliable, and POPIA-compliant handling of user information.
7. Build a modern, maintainable platform that can evolve with AI-powered recommendations, analytics, and future employer integrations.

OpportunityHub is designed as a complete enterprise software solution, demonstrating modern full-stack development, distributed systems, automated web scraping, scalable backend architecture, and cloud-ready engineering practices.

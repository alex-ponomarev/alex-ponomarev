**English** | [Русский](README.ru.md)

# Alexander Ponomarev

### Backend Developer · PHP / Symfony

I'm a backend developer with **6+ years of commercial development experience**, focused primarily on PHP and Symfony.

I build backend services, REST APIs and integrations, including AI-powered systems, payment integrations, data-intensive services and asynchronous processing. I pay particular attention to clear service boundaries, maintainable code, predictable behavior and pragmatic architecture.

## Core stack

- **Backend:** PHP 8+, Symfony, Laravel
- **Databases:** PostgreSQL, MySQL, Redis
- **Messaging:** Kafka, RabbitMQ
- **Integrations:** REST APIs, payment systems, AI and speech services
- **Quality:** PHPUnit, PHPStan, automated testing
- **Infrastructure:** Docker, CI/CD
- **Additional experience:** Go, Java / Spring

## What I work with

- Backend services and REST APIs
- Business logic decomposition and implementation
- External service, payment and AI integrations
- Database design and query optimization
- Asynchronous and message-driven processing
- Legacy code refactoring
- Performance optimization
- Automated testing and code quality

---

## Featured projects

### Transport Education Platform — AI-powered training backend

A **team hackathon project** for interactive employee training. I was responsible for the **backend architecture and server-side implementation**; the repository below contains the backend part I worked on.

The platform runs nonlinear training scenarios where a player interacts with virtual passengers and can respond with text, actions or voice. The backend manages the full game lifecycle, AI dialogue, evaluation, results and integrations with the game client.

**Key backend areas:**

- Game sessions, scenario attempts and persisted dialogue history
- Multiple AI modes: Yandex Responses, Codex and OpenAI Realtime
- Voice/speech processing with SpeechKit and local Whisper support
- Unity WebGL integration through a dedicated REST API
- Player statistics, achievements and learning results
- Admin and HR functionality, server-side settings and reporting
- Dockerized environment, migrations and demo fixtures

**Tech:** PHP 8.3+ · Symfony 6.4 · Doctrine ORM · PostgreSQL 16 · Docker Compose · REST API · AI / speech integrations

> The repository is archived because the hackathon delivery is complete.

#### Backend data model and main components

![Transport Education Platform backend data model](assets/hackathon-data-model.svg)

[View Transport Education Platform backend →](https://github.com/alex-ponomarev/hackaton-transport-education)

---

### Symfony Payment Service

A REST API built with **PHP 8 and Symfony** for calculating product prices and processing payments.

The service handles product pricing, coupons, country-specific taxes and multiple payment processors while keeping business logic separated from HTTP and external integrations.

**Key points:**

- Request DTOs and validation with Symfony Validator
- Price calculation with discounts and country-specific taxation
- Extensible payment processor integration through a common interface and registry
- Doctrine ORM and PostgreSQL
- Separation of controller, application and integration logic
- Dockerized development environment
- PHPUnit test coverage

**Tech:** PHP · Symfony · Doctrine · PostgreSQL · Docker · PHPUnit

[View Symfony Payment Service →](https://github.com/alex-ponomarev/symfony-payment-service)

---

## Earlier Symfony projects

A set of earlier Symfony services from **2020–2021**:

- [Symfony Catalog Service](https://github.com/alex-ponomarev/symfony-catalog-service) — catalog import, persistence and Elasticsearch indexing
- [Symfony Product Service](https://github.com/alex-ponomarev/symfony-product-service) — product REST API and service-to-service communication
- [Symfony Category Service](https://github.com/alex-ponomarev/symfony-category-service) — category management and synchronization with the product service

---

## Engineering approach

I prefer solutions that are **simple enough to understand and maintain, but structured enough to evolve safely**.

For me, good backend code means clear responsibilities, explicit business rules, predictable error handling, testability and avoiding unnecessary complexity.

# Namratha Joshi 👋

### Full-Stack Software Engineer | Python | Django | FastAPI | React | Distributed Systems | AI Integration

Backend-focused full-stack software engineer with experience building and maintaining production applications using Python, Django, Django REST Framework, FastAPI, React, PostgreSQL, Redis, and Celery.

Focus areas: backend architecture, REST APIs, database design, distributed task processing, concurrency, security, production reliability, and AI-assisted workflows.

---

## Production Experience

### IIA Proposal Management System — IPS

**Organization:** Indian Institute of Astrophysics
**Role:** Project Associate I (Software Engineer)
**Tenure:** July 2024 – Present
**Live application:** [https://ips.iiap.res.in](https://ips.iiap.res.in)

IPS is a publicly accessible institutional platform supporting proposal and research workflows at the Indian Institute of Astrophysics, used by 1,400+ researchers across five telescope facilities.

Work includes:

- Developing and maintaining Python/Django REST Framework backend services
- Integrating React frontend functionality with REST APIs
- Migrating legacy PHP functionality toward Django REST Framework and React
- Working on database migrations, validation, and reconciliation
- Building Celery-based background processing and notification workflows
- Improving API security through access control and IDOR remediation
- Supporting production monitoring, structured logging, and reliability improvements
- Integrating AI-assisted workflows using LLM APIs
- Designing maintainable service and configuration patterns for production features

*Note: production source code and data are proprietary. The projects below are independent implementations demonstrating related engineering concepts.*

---

## What I Build

- Production backend services with Python and Django
- REST APIs using Django REST Framework and FastAPI
- React-based interfaces for operational and reporting workflows
- Background processing pipelines using Celery and Redis
- Reliable systems with retries, fallbacks, rate limiting, and circuit breakers
- Database-backed applications with PostgreSQL and MySQL
- Secure APIs with authentication, authorization, RBAC, and IDOR protection
- AI-assisted applications that separate deterministic logic from LLM-generated output
- Systems designed for correctness, maintainability, and operational reliability

---

## Featured Projects

### Fitness Studio Booking API

A FastAPI-based booking system for managing fitness classes and client reservations, focused on transaction safety and preventing double-booking under concurrent requests.

**Highlights:**
- FastAPI REST API
- PostgreSQL database
- JWT authentication
- Docker setup
- Timezone-aware class scheduling
- Booking validation
- PostgreSQL row-level locking using `SELECT FOR UPDATE`
- Concurrent booking validation using a 50-thread test

**Engineering focus:** database transaction handling, race-condition prevention, API design, data consistency, concurrent request handling

[View repository](https://github.com/Newton-hubs/Booking-API)

---

### Astro Time Machine

An interactive astronomy application that lets users explore the sky from different locations and points in time, combining deterministic astronomical calculations with AI-generated explanations.

**Highlights:**
- FastAPI, Celery, Redis, Claude API
- Astronomical calculations
- Moon phase and visibility information
- Planet visibility
- Cloud and weather information
- Circuit breaker for external AI failures
- Deterministic fallback when the AI service is unavailable
- Sliding-window Redis rate limiting
- Optional AI-generated narration and voice output

**Engineering focus:** separating reliable calculations from AI-generated content, external service failure handling, background processing, rate limiting, graceful degradation, API integration

[View repository](https://github.com/Newton-hubs/Astro-time-machine)

---

## Open Source

Contributed a fix to **FastCRUD** for a SQLAlchemy joined-table inheritance issue that prevented correct column generation in complex ORM models — improving inheritance handling and mapper traversal so ORM models generate expected columns correctly.

**Engineering focus:** SQLAlchemy internals, ORM inheritance, mapper traversal, debugging framework-level behavior, understanding and fixing an existing codebase

Actively growing my open-source contributions beyond this.

[View repository](https://github.com/Newton-hubs/FastCRUD)

---

## Technical Skills

### Languages
Python, SQL, JavaScript, TypeScript (learning)

### Backend
Django, Django REST Framework, FastAPI, Pydantic, REST API design, service-oriented architecture, object-oriented design, design patterns

### Frontend
React, JavaScript, HTML, CSS, data tables, reporting dashboards, client-side PDF export

### Databases and Storage
PostgreSQL, MySQL, MongoDB, SQLAlchemy, Redis

### Distributed Systems and Reliability
Celery, Redis task queues, background processing, scheduled jobs, concurrency handling, database locking, caching, rate limiting, circuit breakers, retry and fallback strategies, reconciliation workflows

### Security
Authentication and authorization, role-based access control, IDOR remediation, secure API design, encrypted identifiers, secure file-download endpoints

### DevOps and Infrastructure
Docker, Linux, AWS EC2, AWS S3, GitHub Actions, Prometheus, Grafana, structured logging, production monitoring

### AI and LLM Integration
Claude API, Ollama, Mistral, LLM-assisted workflows, AI-generated summaries, deterministic fallbacks, external API failure handling, prompt and model configuration patterns

---

## Production Engineering Themes

**Legacy System Migration** — Migrating functionality from a legacy PHP application toward Django REST Framework and React, considering data consistency, feature flags, shadow writes, validation, and reconciliation.

**Distributed Processing** — Building background workflows for scheduled tasks, bulk notifications, analytics, and other operations using Celery and Redis.

**Concurrency and Correctness** — Handling race conditions in database-backed applications and using PostgreSQL locking to maintain consistency under concurrent requests.

**Reliability** — Designing applications with circuit breakers, rate limiting, deterministic fallbacks, structured logging, and monitoring.

**Security** — Working on access control, RBAC, IDOR remediation, encrypted identifiers, and secure unauthenticated file-download flows.

**AI Integration** — Using LLMs where they add value while keeping core calculations, validation, and critical application behavior deterministic and reliable.

---

## Currently Deepening

- TypeScript and Node.js
- Distributed systems concepts (consensus, sharding, advanced system design)
- Production observability
- Open-source contribution cadence
- More reliable and maintainable AI application architecture

---

## Connect With Me

- **GitHub:** [https://github.com/Newton-hubs](https://github.com/Newton-hubs)
- **LinkedIn:** [https://www.linkedin.com/in/namratha-j](https://www.linkedin.com/in/namratha-j)
- **Live production application:** [https://ips.iiap.res.in](https://ips.iiap.res.in)

---

*The projects in this profile are independent public implementations demonstrating related engineering concepts and technical interests. The IPS production application is publicly accessible, but its source code, database, internal configuration, and operational data are proprietary.*

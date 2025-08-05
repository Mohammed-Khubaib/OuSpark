---
icon: octicons/stack-24
# hide:
#    - toc
---
# Technology Stack

## Overview

The OuSpark project leveraged a carefully selected technology stack to balance performance, scalability, and development efficiency.

## Frontend Technologies

| **Technology** | **Purpose** | **Benefits** |
|------------|---------|----------|
| **Flutter & Dart** | Cross-platform app development (Android, macOS, Windows) | Single codebase, native performance, rich UI components |
| **Figma** | UI/UX design and prototyping | Collaborative design and rapid iteration |
| **Lottie & Rive** | Animations and interactive graphics | Lightweight, smooth animations on all platforms |

## Backend Technologies

| **Technology** | **Purpose** | **Benefits** |
|------------|---------|----------|
| **Supabase (PostgreSQL)** | Backend as a service with database, authentication, and APIs | Fully managed, built-in JSONB support, scalable |
| **PL/pgSQL Functions** | Complex business logic inside the database | Fast execution, maintainable logic close to data |
| **Supabase Edge Functions** | Custom API endpoints & caching logic | Low latency, extend backend capabilities |

## Data Engineering Pipeline

| **Technology** | **Purpose** | **Benefits** |
|------------|---------|----------|
| **Python** | Core programming language for pipeline logic | Rich data processing libraries |
| **FastAPI** | API framework for pipeline services | Fast, asynchronous, excellent developer experience |
| **Pydantic** | Data validation and settings management | Ensures data integrity |
| **Pandas** | Data analysis and manipulation | Efficient processing of tabular data |
| **SQLAlchemy** | ORM for PostgreSQL interactions | Clean database access |
| **UV** | Python package manager | Manages python dependencies |

## Performance & Caching

| **Technology** | **Purpose** | **Benefits** |
|------------|---------|----------|
| **Redis (Upstash)** | Cache layer for search results | Reduces disk I/O, improves response time |
| **Firebase Analytics** | App usage tracking and analysis | Real-time feature usage metrics |

## Automation & Orchestration

| **Technology** | **Purpose** | **Benefits** |
|------------|---------|----------|
| **Kestra** | Workflow orchestration using YAML | Simplifies pipeline maintenance and UI |
| **Apache Airflow** | DAG-based workflow management | Mature, flexible, but resource-heavy |
| **Docker & Docker Compose** | Containerize services and pipeline | Easy deployment and environment consistency |

## Notifications & Hosting

| **Technology** | **Purpose** | **Benefits** |
|------------|---------|----------|
| **OneSignal** | Push notification service | User engagement via real-time notifications |
| **GitHub Pages** | Hosting static assets (banners, animations) | Cost-effective, reduces egress consumption |

---

!!!success "Optimized Tech Stack"
    The stack was chosen for rapid development, scaling flexibility, and straight forward integration.

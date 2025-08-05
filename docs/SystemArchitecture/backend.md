---
icon: octicons/database-24
# hide:
#    - toc
---
## Overview

OuSpark's backend relies on **Supabase**, providing a fully managed PostgreSQL database, authentication, and serverless functions. This enables a scalable, maintainable, and secure system.

## Database Design

- **12 core tables** to organize student results, departments, colleges, semesters, subjects, and user profiles
- Utilizes PostgreSQL's **JSONB** type to handle flexible subject data for students who elect different courses
- Strict relational integrity enforced with foreign keys and indexes
- Defined around **40 PL/pgSQL stored procedures** to implement complex logic near the data for speed and security

## API & Business Logic

- **Supabase Edge Functions** extend backend capabilities with custom APIs and caching strategies
- Use of **Firebase Analytics** to track app usage, feature hits, and user behavior
- __Cron jobs__ automate daily tracking and backend maintenance tasks

## Performance Optimizations

| **Technique** | **Description** |
|-----------|-------------|
| **Redis Caching (Upstash)** | Caches heavy read results reducing disk I/O by 90% |
| **Prewarming Cache** | Periodically refreshes cache to improve response times |
| **SQL Indexing & Query Optimization** | Ensures efficient data retrieval |

## Security

- Authentication using **Supabase Email Auth** and **Google OAuth Provider**
- Database row-level security and access policies
- Rate limiting on APIs to prevent abuse

## Scalability

- Horizontal scaling supported by managed Supabase infrastructure
- Stateless API functions enable load balancing
- Separated development and production databases for safety and fast iteration


---

!!! success "*This backend architecture ensures data integrity, security, and high performance with ease of management.*"

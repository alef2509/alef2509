# Hi, I'm Alef 👋

**Senior Software Engineer · Java / Spring · Solutions Architect (AWS)**

I design, build and run scalable backend systems with Java, Spring Boot and cloud
technologies. I care about clean code, software architecture and technical leadership:
mentoring teams, improving development workflows and making systems that are easy to
change and hard to break.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-alef--de--oliveira--inacio-0A66C2?logo=linkedin)](https://www.linkedin.com/in/alef-de-oliveira-inacio-ab7aba129)

## Portfolio

Each project is small enough to read in one sitting and complete enough to be taken
seriously: tests against real infrastructure (Testcontainers), CI on every push,
architecture decision records explaining the trade-offs, and a README you can run.

### Architecture

| Project | What it shows |
|---|---|
| [**hexagonal-architecture-banking-api**](https://github.com/alef2509/hexagonal-architecture-banking-api) | Ports & Adapters with a framework-free core verified by ArchUnit; idempotency keys, optimistic locking with ETags, RFC 9457 errors |
| [**clean-architecture-multimodule**](https://github.com/alef2509/clean-architecture-multimodule) | Clean Architecture where the dependency rule is enforced by the build (Maven modules + enforcer); use case boundaries, UnitOfWork port |
| [**cqrs-event-sourcing-account-ledger**](https://github.com/alef2509/cqrs-event-sourcing-account-ledger) | Event Sourcing and CQRS from scratch on PostgreSQL: append-only store, snapshots, upcasting, exactly-once projections, no skipped events under concurrency |

### Distributed systems and messaging

| Project | What it shows |
|---|---|
| [**ecommerce-microservices-kafka-saga**](https://github.com/alef2509/ecommerce-microservices-kafka-saga) ⭐ | Orchestrated saga over Kafka, transactional outbox with Debezium CDC, idempotent consumers, retry + circuit breaker, DLT, one trace across five services |
| [**event-driven-rabbitmq-retry-patterns**](https://github.com/alef2509/event-driven-rabbitmq-retry-patterns) | Choreographed saga on RabbitMQ 4, non-blocking retries with delay queues and parking lot, quorum queues, publisher confirms |
| [**redis-caching-strategies**](https://github.com/alef2509/redis-caching-strategies) | Two-level cache with Pub/Sub invalidation, cache stampede protection (XFetch), write-through, write-behind, Lua token-bucket rate limiting |

### Cloud and infrastructure (AWS)

| Project | What it shows |
|---|---|
| [**serverless-url-shortener**](https://github.com/alef2509/serverless-url-shortener) | Java 21 on Lambda with SnapStart priming, DynamoDB single-table design, EventBridge with DLQ and replay, Terraform tested in CI |
| [**terraform-aws-modules**](https://github.com/alef2509/terraform-aws-modules) | Reusable, tested modules (VPC, ALB, ECS Fargate, RDS, MSK Serverless, GitHub OIDC) with `terraform test`, tflint and checkov |
| [**aws-infra-live**](https://github.com/alef2509/aws-infra-live) | dev/prod environments deploying the Kafka platform: database per service, keyless CI with OIDC, S3 native state locking |

### Language

| Project | What it shows |
|---|---|
| [**modern-java-features**](https://github.com/alef2509/modern-java-features) | Java 21 → 25 LTS: virtual threads, structured concurrency, scoped values, pattern matching, gatherers, FFM, with tests and JMH benchmarks |

## Tech stack

**Backend** · Java · Spring Boot · Spring Data / JPA · REST · Microservices · DDD · SOLID · Clean Code<br>
**Messaging** · Apache Kafka · Debezium · RabbitMQ · Redis<br>
**Data** · PostgreSQL · Oracle · PL/SQL · DynamoDB<br>
**Cloud & DevOps** · AWS (ECS, Lambda, RDS, MSK, DynamoDB, EventBridge) · Terraform · Docker · Kubernetes · GitHub Actions · CI/CD<br>
**Quality** · JUnit · Testcontainers · ArchUnit · WireMock · OpenTelemetry<br>
**Also** · Angular · Delphi · Agile & Scrum · Technical leadership

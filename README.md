# Akmyrat — Backend Engineer (Go)

I design and build backend systems that stay fast and correct under load: microservices, distributed transactions, event-driven pipelines, and the observability needed to run them in production.

**Currently:** building Go services with a focus on concurrency, data consistency, and clean architecture.

## Experience Highlights

- **Short-video social platform:** designed and shipped microservices for content, users, and real-time features. Services talk over **gRPC** and **RabbitMQ**, and push real-time updates over **WebSockets**.
- **AuthN / AuthZ:** JWT-based authentication and policy-driven authorization (RBAC/ABAC) with **Casbin**.
- **Data layer:** modeled data across **PostgreSQL** (transactional), **Redis** (caching, rate limiting), and **ScyllaDB** (high-throughput, write-heavy feeds).
- **Observability:** centralized logging and monitoring with the **ELK stack**, plus structured logging across services.
- **Delivery:** containerized services with **Docker**, Linux-based deployments, and CI with GitHub Actions.

## Featured Projects

| Project | What it demonstrates |
|---|---|
| [saga-orchestration-go](https://github.com/Akmyrat03/saga-orchestration-go) | Distributed transactions across microservices using the orchestrated Saga pattern, with compensating actions |
| [wallet](https://github.com/Akmyrat03/wallet) | Wallet service with safe balance operations and transactional consistency |
| [avito_transaction_manager_example](https://github.com/Akmyrat03/avito_transaction_manager_example) | Transaction manager pattern that keeps the domain layer clean of DB transaction details |
| [concurrency_patterns](https://github.com/Akmyrat03/concurrency_patterns) | Go concurrency in practice: worker pools, fan-in/fan-out, pipelines, cancellation with `context` |
| [grpc-practice](https://github.com/Akmyrat03/grpc-practice) | gRPC services with Protobuf contracts, unary and streaming RPCs |
| [architecture](https://github.com/Akmyrat03/architecture) | Clean / hexagonal architecture layout for Go services |
| [logger](https://github.com/Akmyrat03/logger) | Reusable structured logging package |
| [monitoring](https://github.com/Akmyrat03/monitoring) | Observability stack setup for metrics and logs |

## Tech Stack

**Languages:** Go, SQL
**Communication:** gRPC, Protobuf, REST, WebSockets, RabbitMQ
**Data:** PostgreSQL, Redis, ScyllaDB
**Security:** JWT, Casbin
**Infra & Ops:** Docker, Linux, Git, GitHub Actions, ELK (Elasticsearch, Logstash, Kibana)
**Practices:** Clean Architecture, DDD, Saga, Transactional Outbox, concurrency patterns, testing

## GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Akmyrat03&show_icons=true&hide_border=true&theme=transparent" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Akmyrat03&layout=compact&hide_border=true&theme=transparent" />
</p>

## Contact

- Email: [backendprogrammer0@gmail.com](mailto:backendprogrammer0@gmail.com)
- Telegram: [@meredow03](https://t.me/meredow03)

I'm open to backend / Go engineering roles and collaboration on distributed systems.

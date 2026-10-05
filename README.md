# Hi, I'm Phuong Phung

### Backend Engineer · TypeScript / Node.js · AWS · Distributed Systems

I build backend services with a focus on transactional correctness, asynchronous workflows, and performance. My professional work includes reward processing, booking systems, and API optimization. Here, I explore the underlying engineering through backend projects and distributed systems labs.

[LinkedIn](https://www.linkedin.com/in/phuong-phungdh/) · [Email](mailto:hphuong1503@gmail.com) · [LeetCode](https://leetcode.com/u/hphuong1503/)

---

## Engineering focus

- **Correctness under concurrency:** atomic updates, database constraints, idempotency, and transaction boundaries.
- **Asynchronous processing:** event-driven workflows, retries, and recovery from partial failures.
- **Performance:** query optimization, caching, connection management, and load testing.
- **Distributed systems:** building a deeper understanding of coordination and fault tolerance through hands-on work in Go.

## Selected projects

### [FlashSale](https://github.com/hphuong1503/FlashSale)
**Concurrent purchasing · Java / Spring Boot · PostgreSQL · Redis**

A flash-sale backend exploring inventory and balance consistency during competing purchase requests. The purchase flow combines conditional stock reservation, a database constraint for duplicate purchases, balance deduction, and a transactional outbox. Includes Testcontainers-based concurrency test cases.

[Purchase flow](https://github.com/hphuong1503/FlashSale/blob/main/src/main/java/com/example/FlashSale/service/PurchaseService.java) · [Concurrency tests](https://github.com/hphuong1503/FlashSale/blob/main/src/test/java/com/example/FlashSale/service/PurchaseServiceConcurrentTest.java)

### [Chat-Scale](https://github.com/hphuong1503/Chat-Scale)
**Real-time messaging · Python / Django · Channels · Celery**

A chat backend experiment with asynchronous message persistence and WebSocket delivery. The repository includes architecture decision records for the write pipeline and WebSocket implementation, plus a k6 load-test script.

[Architecture decisions](https://github.com/hphuong1503/Chat-Scale/tree/develop/ADR) · [Load-test script](https://github.com/hphuong1503/Chat-Scale/blob/develop/k6-test.js)

### [Metric Tracking](https://github.com/hphuong1503/metric-tracking)
**Backend API · TypeScript / Express · PostgreSQL · TypeORM**

A metric-tracking API organized into controller, service, repository, and domain layers. Includes distance and temperature conversion strategies, Swagger API documentation, and a Docker Compose setup.

[Source code](https://github.com/hphuong1503/metric-tracking/tree/main/src)

## Distributed systems learning

I'm working through [MIT 6.5840 distributed systems labs](https://github.com/hphuong1503/mit-6.5840-distributed-systems) in Go, starting with MapReduce coordination, task scheduling, and worker failure recovery. This is independent study using the course materials.

I'm also exploring protocol fundamentals through the CodeCrafters [Redis in TypeScript](https://github.com/hphuong1503/redis-typescript) and [Kafka in Java](https://github.com/hphuong1503/kafka-java) challenges. Both are early-stage learning projects.

## Technologies

| Area | Technologies |
| --- | --- |
| Core backend | TypeScript, Node.js, SQL |
| Data | PostgreSQL, DynamoDB, Redis |
| AWS | Lambda, SQS, DynamoDB Streams, Step Functions, ECS, CDK |
| Project work | Java, Spring Boot, Python, Django, Docker, k6 |
| Currently studying | Go, distributed systems, network protocols |

---

Based in Vietnam. Interested in backend engineering, reliable workflows, and distributed systems.

For professional conversations, reach me on [LinkedIn](https://www.linkedin.com/in/phuong-phungdh/) or by [email](mailto:hphuong1503@gmail.com).

<h1 align="center">Hi 👋, I'm Juan Manuel Cerón</h1>

<p align="center">
  <strong>Senior Software Engineer</strong> · Go · Distributed Systems · AWS · Applied AI<br/>
  <sub>Medellín / Pasto, Colombia · Remote (GMT-5)</sub>
</p>

<p align="center">
  <a href="https://jmceron.com"><img src="https://img.shields.io/badge/Portfolio-jmceron.com-black?style=flat&logo=safari&logoColor=white"/></a>
  <a href="https://linkedin.com/in/juanmanuelceronaraujo"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.credly.com/users/juan-manuel-ceron-araujo.4f4e3e87"><img src="https://img.shields.io/badge/Credly-Certifications-FF6B00?style=flat&logo=credly&logoColor=white"/></a>
  <a href="mailto:juanceron256@gmail.com"><img src="https://img.shields.io/badge/Email-juanceron256@gmail.com-D14836?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

Senior Software Engineer with **5+ years of experience** architecting distributed, event-driven backend systems on AWS for high-traffic platforms (Disney Parks, Mercado Libre). 

Specialized in **Go (Golang)**, microservices, asynchronous event pipelines (Kinesis, SQS, SNS, EventBridge), and fault-tolerant architecture (circuit breakers, retries, fallbacks). Also the independent founder and engineer behind **[Optima](https://contratosoptima.com/)**, an end-to-end B2B SaaS platform that automates public procurement monitoring in Colombia.

---

## ⚡ Technical Highlights

- **Disney Parks (Globant)**: Architected Go microservices and event pipelines handling **30K+ daily state updates**; resolved Kinesis hot-sharding and deadlocks to cut latency by nearly 40% while doubling peak throughput.
- **Mercado Libre**: Built resilient event-driven Go backends handling **tens of thousands of daily events** via SQS/Kinesis; introduced circuit-breaker patterns that eliminated traffic-spike data loss.
- **Optima (B2B SaaS)**: Built and independently operate a multi-tenant platform for public procurement alerts with real-time scraping, sub-500ms hybrid search, and automated billing for paying business subscribers.
- **Pragma (Nequi)**: Improved service latency and resource efficiency across Java microservices through code-level performance tuning and non-blocking reactive patterns.

---

## 🚀 Featured Projects & Open Source

- **[Optima (B2B SaaS)](https://contratosoptima.com/)** — End-to-end platform automating SECOP II public procurement alerts in Colombia. Multi-tenant architecture serving active paying businesses.
- **[Earthquake Intelligence Engine (Hybrid RAG)](https://github.com/JuanCeron023/venezuela-colombia-earthquake-rag)** — Global emergency intelligence platform combining high-throughput Go ingestion pipelines, PostgreSQL + pgvector (HNSW), and DeepSeek AI verification.
- **[Forge](https://github.com/JuanCeron023/forge)** — Autonomous multi-agent software engineering skill that orchestrates architecture, implementation, automated verification, and clean delivery across 7 specialized phases.
- **[Atlas](https://github.com/JuanCeron023/atlas)** — Universal distributed systems knowledge base covering concurrency invariants, streaming patterns, context propagation, container CFS quotas, and backend reliability best practices.
- **[Booksy](https://github.com/JuanCeron023/booksy)** — Clean-architecture Go microservice platform for AI-powered card-based book distillations, preserving author voice, verbatim quotes, and original diagrams.
- **[Distributed Feature Flags (Raft Consensus)](https://github.com/JuanCeron023/raft-consensus-feature-flags)** — Fault-tolerant feature flagging powered by the Raft consensus algorithm with dynamic leader election and replicated state machines in Go.
- **[LSM-Tree Time-Series Database](https://github.com/JuanCeron023/lsm-timeseries-db-go)** — High-throughput append-only storage engine in Go with WAL, in-memory SkipList memtable, SSTables with sparse index, Bloom filters, and background compaction.

---

## 🛠️ Core Tech Stack

- **Languages**: Go (primary), Python, TypeScript, Java, SQL
- **Cloud & Infrastructure**: AWS (Lambda, Kinesis, ECS/Fargate, SQS, SNS, EventBridge, S3, ALB, DynamoDB), Docker, Kubernetes, Terraform
- **Databases & Storage**: PostgreSQL (pgvector), MongoDB, DynamoDB, Redis, LSM-Tree Engines
- **Architecture**: Distributed Systems, Event-Driven Architecture, Microservices, Hexagonal Architecture, DDD, Fault-Tolerant Design
- **Observability & Reliability**: OpenTelemetry, Datadog, Grafana, New Relic, CloudWatch, CI/CD (GitHub Actions, Jenkins)

---

## 💼 Professional Experience

### Senior Software Engineer — Globant (Disney Parks) `Aug 2024 – Present`
> Go · Python · AWS (Kinesis, Fargate, Lambda, SQS, SNS, EventBridge) · MongoDB · OpenTelemetry · Grafana · New Relic

- Led backend architecture for an 8+ engineer team, building decoupled Disney Parks services processing **30K+ updates daily** across entities.
- Architected 20+ Go and Python Lambdas using hexagonal architecture, DDD, and Terraform; resolved Kinesis hot-shard and deadlock bottlenecks, cutting latency by nearly 40% while roughly doubling peak throughput.
- Hardened critical services with retries, fallbacks, and rate limiting instrumented with OpenTelemetry and Grafana, cutting production incidents close to a third.
- Built real-time CDC data pipelines using MongoDB aggregations, Kinesis, SQS, and EventBridge at several thousand requests per second.

### Software Engineer II — Mercado Libre `Apr 2023 – Aug 2024`
> Go · AWS (SQS, Kinesis, Fargate) · Kubernetes · Terraform · Docker · Datadog · Grafana · OpenTelemetry

- Decoupled services on Kubernetes and Fargate using SQS and Kinesis with Terraform, streamlining independent service scaling.
- Introduced circuit-breaker and retry patterns across the event-driven architecture, **eliminating data loss during high-traffic spikes**.
- Automated customer support workflows and consolidated observability across Datadog, New Relic, and unified Grafana dashboards, cutting operational costs by roughly a quarter.
- Diagnosed and resolved concurrency bottlenecks using Go profiling tools, noticeably improving throughput under peak loads.

### Software Engineer — Pragma (Nequi) `Nov 2021 – Apr 2023`
> Java · Spring Boot · gRPC · AWS (Lambda, ECS Fargate, ALB) · PostgreSQL · Docker · Jenkins

- Optimized external service routing via ALB between microservices and right-sized Lambda/ECS workloads, reducing operational costs by about 15%.
- Improved response times and throughput on the Nequi credit platform by refactoring critical execution paths and adopting reactive (Spring WebFlux) non-blocking patterns.
- Accelerated deployment velocity by strengthening CI/CD practices across Jenkins and GitHub.

### Software Developer — Soporte Lógico `Oct 2020 – Nov 2021`
> Java · Spring Boot · JavaScript · Python · AWS Lambda · Docker · Jenkins

- Owned and scaled a platform serving **500+ Colombian companies**, applying SOLID principles to ensure maintainability.
- Noticeably reduced REST API latency through MySQL query profiling and index optimization.
- Mentored 2 backend developers on clean architecture, unit testing, and Git workflows to accelerate onboarding.

---

## 📜 Certifications

- **AWS Certified Solutions Architect – Associate** — Amazon Web Services · 2026
- **Claude with Amazon Bedrock** — Anthropic · 2026
- **IBM RAG and Agentic AI Professional Certificate** — IBM · 2026
- **MongoDB SI Architect Certification** — MongoDB · 2025
- **AWS Cloud Practitioner** — Amazon Web Services · 2023
- **Microsoft Certified: Azure Fundamentals (AZ-900)** — Microsoft · 2022
- **Scrum Foundation Professional Certificate (SFPC)** — CertiProf · 2021

---

## 🎓 Education

**B.S. Software Engineering** — Universidad Mariana, Pasto, Colombia · 2017 – 2022  
🏅 Full-tuition scholarship every semester awarded for highest GPA in cohort.

---

<p align="center">
  <sub>Find more details and interactive projects at <a href="https://jmceron.com">jmceron.com</a></sub>
</p>

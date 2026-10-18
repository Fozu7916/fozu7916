<div align="center">

# Aleksey Shikin

### Backend Developer · C# / .NET

Software Engineering student at Tomsk Polytechnic University.  
I build **APIs, real-time services and data-driven backend systems** on **ASP.NET Core**.  
Currently working on an offline-first messenger backend (idempotent delivery, server-side sync).  
**Next up: Go and cloud-native infrastructure (message brokers, Kubernetes, AWS).**

📧 **[Email](mailto:alekseylis211@mail.ru)** · 💬 **[Telegram](https://t.me/FozuZXC)** · 🌐 **[Portfolio](https://fozu-portfolio.netlify.app)** · 💻 **[LeetCode](https://leetcode.com/u/Fozuzzzxxxccc/)**

</div>

---

# 🏆 Highlights

- Finalist of 5 national math olympiads and 10+ computer science olympiads
- Job offer from Apogey 1C after a hackathon (≈60% of teams eliminated)
- 30+ conference talks, 2nd place at the "Leonardo" All-Russian conference
- English B2 (British Council)

---

# 🚀 Projects

### 💬 [Messenger backend](https://github.com/Fozu7916/Messenger1)

**Offline-first messenger: SignalR + REST, PostgreSQL, Redis backplane, S3 presigned uploads.**

- Idempotent message delivery: retries from the client never create duplicates
- Server-side sync cursor: a client that was offline gets exactly the messages it missed
- Integration tests against a real PostgreSQL and Redis in Docker

`ASP.NET Core` `SignalR` `PostgreSQL` `Redis` `Docker` `xUnit`

---

### 🛰️ [DroneLiDAR](https://github.com/Fozu7916/LidarMVP)

**Reproducible comparison of LAS/LAZ point-cloud epochs: cut/fill volumes, ICP registration, DEM, SHA-256 manifest.**

`C#` `.NET` `LAS/LAZ` `ICP` `DEM` `WebGL`

---

### ⚡ [HacatonProTechno](https://github.com/Fozu7916/HacatonProTechno)

**Content collection, analytics and publishing pipeline (VK / Telegram).** Hackathon project that led to a job offer from Apogey 1C.

`Python` `Telegram API` `VK API`

---

### 💙 [AlekseyBook](https://github.com/Fozu7916/AlekseyBook) *(legacy MVP)*

**Social network: profiles, friends, posts, real-time chat.** Early project built with ASP.NET Core.

`ASP.NET Core` `EF Core` `MySQL` `SignalR` `React`

---

# 🛠️ Tech Stack

### 🔷 Primary: C# / .NET

<p>
<img src="https://skillicons.dev/icons?i=cs,dotnet&perline=2" height="50"/>
</p>

**C# · .NET 8 · ASP.NET Core · Entity Framework Core · SignalR · LINQ · xUnit**

### 🗄️ Data & Infrastructure

<p>
<img src="https://skillicons.dev/icons?i=postgres,redis,docker,linux,git,githubactions&perline=6" height="50"/>
</p>

**PostgreSQL · Redis · Docker · Linux · Git · GitHub Actions**

---

# 🧭 Learning rigth now

I'm extending the stack from a single well-structured service to **distributed, observable and cloud-deployed systems**. The goal is to apply each step to a real project (first of all, the messenger backend), not just to read about it.

### 🐹 1. Go: concurrency and network services

<p>
<img src="https://skillicons.dev/icons?i=golang&perline=1" height="50"/>
</p>

Goroutines, channels, `context`, worker pools, HTTP/gRPC services. Plan: rewrite a performance-critical part of the messenger (e.g. a fan-out/notification service) in Go and compare it with the .NET version.


<p>
<img src="https://skillicons.dev/icons?i=kafka,rabbitmq&perline=2" height="50"/>
</p>

**Kafka** (partitions, consumer groups, delivery guarantees, outbox pattern) and **RabbitMQ** (exchanges, queues, retries, dead-letter queues). Plan: move message delivery events and notifications from in-process handling to a broker.

<p>
<img src="https://skillicons.dev/icons?i=nginx,mongodb&perline=2" height="50"/>
</p>

**Nginx** as a reverse proxy and load balancer (TLS, rate limiting, WebSocket proxying for SignalR). **MongoDB** for document-style data, to understand where it fits next to PostgreSQL.

<p>
<img src="https://skillicons.dev/icons?i=aws,kubernetes,terraform&perline=3" height="50"/>
</p>

**AWS** (EC2, S3, RDS, SQS/SNS, IAM), **Kubernetes** (deployments, services, ingress, probes, autoscaling) and **Terraform** for reproducible infrastructure.

<p>
<img src="https://skillicons.dev/icons?i=prometheus,grafana&perline=2" height="50"/>
</p>

**Prometheus + Grafana** for metrics and dashboards, **OpenTelemetry** for tracing across services, structured logging.

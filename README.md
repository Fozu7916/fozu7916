<div align="center">

# Aleksey Shikin
My site - [fozu-dev.site](https://fozu-dev.site)
### Backend Developer · C# / .NET

Software Engineering student at Tomsk Polytechnic University.  
I build **APIs, real-time services and data-driven backend systems** on **ASP.NET Core**.  
Currently working on an offline-first messenger backend (idempotent delivery, server-side sync).  
**Next up: Go and cloud-native infrastructure (message brokers, Kubernetes, AWS).**

📧 **[Email](mailto:alekseylis211@mail.ru)** · 💬 **[Telegram](https://t.me/FozuZXC)** ·  💻 **[LeetCode](https://leetcode.com/u/Fozuzzzxxxccc/)**

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

🛠️ Tech Stack
🔷 Primary: C# / .NET
<p> <img src="https://skillicons.dev/icons?i=cs,dotnet&perline=2" height="50"/> </p>

C# · .NET 8 · ASP.NET Core · Entity Framework Core · SignalR · LINQ · xUnit

🗄️ Data & Infrastructure
<p> <img src="https://skillicons.dev/icons?i=postgres,redis,docker,linux,git,githubactions&perline=6" height="50"/> </p>

PostgreSQL · Redis · Docker · Linux · Git · GitHub Actions

🎨 Frontend
<p> <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,vite&perline=6" height="50"/> </p>

HTML · CSS · JavaScript · TypeScript · React · Vite

🧭 Learning right now

Going from one well-structured service to distributed, observable, cloud-deployed systems, and applying every step to the messenger backend.

<p> <img src="https://skillicons.dev/icons?i=golang,kafka,rabbitmq,nginx,mongodb,aws,kubernetes,terraform,prometheus,grafana&perline=10" height="50"/> </p>
	Topic	What I'm doing with it
🐹	Go	Goroutines, channels, context. Rewriting the notification fan-out in Go to benchmark against .NET
📨	Kafka · RabbitMQ	Outbox pattern, consumer groups, retries, DLQ. Moving delivery events out of the process into a broker
🚦	Nginx · MongoDB	Reverse proxy + load balancing for SignalR WebSockets. Document storage next to PostgreSQL
☁️	AWS · Kubernetes · Terraform	EC2, S3, RDS, SQS/SNS, IAM. Deployments, ingress, autoscaling. Infrastructure as code
📊	Prometheus · Grafana · OpenTelemetry	Metrics, dashboards, tracing across services

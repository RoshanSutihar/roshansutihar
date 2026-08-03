# Hi there, I'm Roshan Sutihar 👋

Welcome to my GitHub profile! I'm a Software Engineer focused on building high-throughput backend systems, distributed architectures, and automated data pipelines using **Java**, **Go**, **Spring Boot**, **PostgreSQL**, and **Redis**.

---

## 🚀 About Me
- 🔭 **Currently Building:** High-performance microservices, background job workers, and real-time data synchronization pipelines.
- 🌱 **Deepening Knowledge:** Advanced distributed system design patterns, concurrency controls, Virtual Threads (Java 21), and cloud-native deployment architectures.
- 👯 **Looking to Collaborate On:** Open-source backend services, distributed execution engines, API middleware, and infrastructure tooling.
- 💬 **Ask Me About:** Spring Boot, Go channels/concurrency, Redis Lua scripting, transactional message queues, and POS system integrations.
- 🌐 **Portfolio/Website:** [roshansutihar.com.np](http://roshansutihar.com.np)
- 📫 **How to reach me:** [contact@roshansutihar.com.np](mailto:contact@roshansutihar.com.np)
- 😄 **Pronouns:** He/Him

---

## 🛠️ Tech Stack & Skills

- **Languages:** Java (21+), Go (1.22+), Python, Kotlin, SQL (PostgreSQL), JavaScript, PHP
- **Frameworks & Libraries:** Spring Boot, Spring Security, Spring Data JPA, Go Templ, HTMX, React
- **Databases & Caching:** PostgreSQL, Redis (Pub/Sub, Sorted Sets, Lua), DynamoDB
- **Distributed & Infrastructure:** Microservices, Docker, Docker Compose, Coolify, REST APIs, Retries & Dead-Letter Queues (DLQ)
- **Testing & Tools:** JUnit, Mockito, Git, GitHub Actions, Linux, Maven, Gradle

---

## 📂 Featured Projects

### ⚡ [TaskForge | Distributed Task Queue & Worker Engine](https://github.com/RoshanSutihar)
A high-throughput distributed background task execution engine built in **Go 1.22+**.
- Features priority queuing, exponential backoff retries, and atomic worker pools.
- Implements delayed execution via Redis Sorted Sets (ZSET) + Lua scripts and an automated worker timeout reaper.
- Includes a live observability dashboard built with Go Templ & HTMX, deployed via Coolify and Docker Compose.

### 🔄 [Resilient Webhook Delivery & Retry Engine](https://github.com/RoshanSutihar)
A resilient HTTP payload dispatching system built with **Java 21 & Spring Boot 3**.
- Leverages Spring Virtual Threads (`@Async`) and optimistic locking for safe concurrent dispatching.
- Ensures at-least-once delivery with HMAC-SHA256 signatures, indexed timestamp polling, and automated Dead-Letter Queue (DLQ) isolation.
- Integrated with an HTMX monitoring dashboard for manual retry triggers and status auditing.

### 🛡️ [Distributed Rate Limiter & API Gateway Middleware](https://github.com/RoshanSutihar)
A multi-tenant traffic throttling middleware built in **Java 21 & Spring Boot 3**.
- Enforces Sliding Window and Token Bucket algorithms using atomic Redis Lua scripts for sub-millisecond execution without race conditions.
- Features dynamic HTTP header injection (`X-RateLimit-Remaining`) and live traffic telemetry.

---

## 📈 GitHub Stats

![Roshan's GitHub Stats](https://github-readme-stats.vercel.app/api?username=RoshanSutihar&show_icons=true&hide_title=true&hide=prs&count_private=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RoshanSutihar&layout=compact&theme=radical)

---

Feel free to explore my repositories or reach out if you'd like to collaborate on backend systems! 🚀

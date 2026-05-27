<h1 align="center">Hi, I'm Hoàng Nguyễn 👋</h1>

<p align="center">
Backend Engineer • Distributed Systems • Realtime Monitoring • AI-assisted Proctoring
</p>

<p align="center">
  <a href="https://github.com/NguyenHonggHoang">
    <img src="https://komarev.com/ghpvc/?username=NguyenHonggHoang&label=Profile%20Views&color=0e75b6&style=flat" />
  </a>
</p>

---

# About Me

- Final-year Software Engineering student
- Backend-focused developer interested in:
  - Distributed Systems
  - Realtime Architectures
  - Authentication & Security
  - High-performance APIs
  - Event-driven systems
  - AI-assisted monitoring systems

- Currently building:
  - Online Exam Cheating Detection Platform
  - OAuth2 Authorization Infrastructure
  - Realtime Proctoring Pipeline
  - Kafka-based event systems

---

# Tech Stack

## Backend

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,postgres,redis,kafka,docker" />
</p>

- Spring Boot
- Spring Security
- Spring Authorization Server
- JPA / Hibernate
- WebSocket + STOMP
- Kafka / RabbitMQ
- Redis
- PostgreSQL
- Flyway

---

## Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind" />
</p>

- React
- Next.js
- NextAuth
- TailwindCSS

---

## AI / CV

<p>
  <img src="https://skillicons.dev/icons?i=python,tensorflow" />
</p>

- TensorFlow.js
- BlazeFace
- FaceMesh / Iris Tracking
- OpenCV
- Dlib

---

## DevOps & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=docker,linux,git,githubactions,prometheus,grafana" />
</p>

- Docker Compose
- Linux / WSL2
- GitHub Actions
- Prometheus
- Grafana
- MinIO

---

# Featured Project

## Online Exam Cheating Detection System

A distributed realtime proctoring platform for detecting suspicious behaviors during online examinations.

### Core Features

- Realtime face & gaze tracking
- Multi-face detection
- Browser tab-switch detection
- WebSocket realtime monitoring
- Incident scoring pipeline
- Kafka event-driven architecture
- OAuth2 + OIDC authentication
- Evidence snapshot/video pipeline
- Redis-based cooldown optimization

### Architecture

```text
React Client
    ↓
Next.js BFF
    ↓
Spring Authorization Server
    ↓
Microservices
 ├── User Service
 ├── Session Service
 ├── Incident Service
 ├── Admin Service
    ↓
Kafka + Redis + PostgreSQL
    ↓
LiveKit + MinIO

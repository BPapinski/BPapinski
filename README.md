<h1 align="center">Hey, I'm Bartosz 👋</h1>

<p align="center">
  <b>Junior Backend Python Developer</b> · Warsaw, Poland
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/BPapinski"><img src="https://img.shields.io/badge/LinkedIn-BPapinski-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:bartosz.papinski00@gmail.com"><img src="https://img.shields.io/badge/Email-bartosz.papinski00%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" /></a>
</p>

---

I'm a Python backend developer with hands-on experience building scalable microservices, RESTful APIs, and distributed systems. I specialize in designing event-driven architectures, implementing authentication systems, and deploying production-ready solutions on AWS. I'm passionate about clean code, system design, and building things that work reliably at scale.

Currently studying **Information Technology** (Information Systems Engineering) at Warsaw University of Life Sciences.

---

## 🎯 Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| **[User Management Service](https://github.com/BPapinski/user-management-service)** | Identity provider for distributed systems with JWT auth, role-based access control, and async database operations | FastAPI · SQLAlchemy · PostgreSQL · Redis · RabbitMQ · AWS S3 |
| **[Notification Service](https://github.com/BPapinski/notification-service)** | Event-driven microservice for email delivery and audit logging via RabbitMQ | FastAPI · RabbitMQ · MongoDB · AWS SES · Pydantic v2 |
| **[Randlab-Przetargowisko](https://github.com/BPapinski/Randlab-Przetargowisko)** | Full-stack tender management platform with integrated microservices | Django · DRF · React · PostgreSQL · Docker |
| **[AngularTinder](https://github.com/BPapinski/AngularTinder)** | Dating app clone with microservice architecture and real-time features | Django · Angular 17 · PostgreSQL · Docker Compose |

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Django REST](https://img.shields.io/badge/Django_REST-092E20?style=flat&logo=django&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)

**Databases & Caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=python&logoColor=white)

**Cloud, DevOps & Messaging**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

---

## 💼 Professional Experience

**Junior Backend Developer** — *SPRELLI Sp. z o.o.* · Feb 2026 – May 2026
> Architected and developed backend microservices for a tutor–student marketplace platform built from scratch. Implemented cloud deployment pipelines and infrastructure monitoring with production-grade observability tools. Collaborated on scalable API design patterns and distributed system communication.

**Junior Backend Developer Intern** — *Innowise Group* · Aug 2025 – Jan 2026
> Built 3+ Python microservices using FastAPI and Django with PostgreSQL and AWS integration. Designed async database operations using SQLAlchemy ORM, implemented event-driven communication via RabbitMQ, and deployed containerized applications on AWS infrastructure focusing on scalability and maintainability.

**Junior Fullstack Developer Intern** — *Randlab Software* · Jul 2025 – Aug 2025
> Developed full-stack tender management system using Django REST Framework and React. Implemented RESTful API endpoints, database schema design with PostgreSQL, and modern UI components. Integrated microservices architecture for authentication and notifications.

---

## 🚀 Key Projects

### 🏗️ Integrated Tender Management Platform

A distributed microservices-based system designed with event-driven architecture, enabling asynchronous communication between independent services. Each microservice handles a specific business domain and communicates through RabbitMQ message queues.

**Architecture Overview:**
- **Randlab-Przetargowisko** — Main business application (Django + React frontend)
- **User Management Service** — Centralized authentication, authorization, and user lifecycle management
- **Notification Service** — Event-driven email delivery and audit trail logging

**Key Design Patterns:** CQRS for event sourcing, async/await for non-blocking operations, JWT-based authentication, role-based access control (RBAC).

---

### 🔐 [User Management Service](https://github.com/BPapinski/user-management-service)

A dedicated microservice serving as the identity provider for distributed systems. Handles user registration, JWT authentication, role-based access control, and session management with Redis caching.

**Key Features:**
- JWT-based stateless authentication
- Async SQLAlchemy ORM with PostgreSQL
- Redis caching for session optimization
- AWS S3 integration for document storage
- Database migrations with Alembic
- CI/CD pipeline with GitHub Actions
- Docker containerization

**Stack:** Python 3.12 · FastAPI · SQLAlchemy (async) · PostgreSQL · Redis · RabbitMQ · AWS S3 · Alembic · Docker · GitHub Actions

---

### 📬 [Notification Service](https://github.com/BPapinski/notification-service)

An event-driven notification microservice that consumes domain events from RabbitMQ and delivers notifications via AWS SES. Maintains audit logs in MongoDB for compliance and debugging.

**Key Features:**
- Event-driven architecture with RabbitMQ consumers
- AWS SES email delivery integration
- MongoDB audit trail for all notifications
- Pydantic v2 for data validation
- Docker Compose for local development
- Automated testing and deployment via GitHub Actions

**Stack:** Python 3.12 · RabbitMQ (pika) · MongoDB · AWS SES · Pydantic v2 · Docker · GitHub Actions

---

### 📑 [Randlab-Przetargowisko](https://github.com/BPapinski/Randlab-Przetargowisko)

A full-stack tender management platform showcasing modern web application architecture with microservices integration. Users can create, manage, and track tenders through an intuitive interface.

**Key Features:**
- Tender creation, editing, and lifecycle management
- User authentication via User Management Service
- Real-time tender status updates
- RESTful API architecture with proper HTTP semantics
- PostgreSQL relational data modeling
- Docker Compose for development environment
- Integration with User Management and Notification services

**Stack:** Python · Django · Django REST Framework · React · PostgreSQL · Docker

---

### ❤️ [AngularTinder](https://github.com/BPapinski/AngularTinder)

A dating app clone demonstrating modern full-stack development with microservices architecture. Features a Django REST Framework backend and Angular 17 frontend with type-safe TypeScript.

**Key Features:**
- User profiles and matching algorithm
- Real-time notifications
- Responsive Angular UI with modern web standards
- PostgreSQL-backed persistence
- Docker Compose orchestration
- Code quality with Ruff linter

**Stack:** Python 3.12 · Django 5 · Django REST Framework · Angular 17 · TypeScript · PostgreSQL · Docker · Ruff

---

### 🗺️ SmartRoute *(Bachelor's Thesis — Work in Progress)*

A leisure planning application that generates optimized sightseeing routes based on user location and preferences. Integrates geolocation APIs to fetch tourist attractions and calculates efficient routes.

**Planned Features:**
- Route optimization algorithm
- Real-time location services
- Integration with mapping APIs
- Tourist attraction recommendations

**Stack:** Python · FastAPI · PostgreSQL · Docker · Geolocation APIs

> 🔒 Repository is private — project under active development as part of Bachelor's thesis.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BPapinski&show_icons=true&theme=default&hide_border=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BPapinski&layout=compact&theme=default&hide_border=true" height="160" />
</p>

---

## 🎓 Key Competencies

- **Microservices Architecture** — Event-driven systems, service communication patterns, distributed transactions
- **Backend Development** — RESTful APIs, database design, async/await patterns, ORM frameworks
- **Cloud & DevOps** — AWS services (S3, SES), Docker containerization, GitHub Actions CI/CD
- **Message Queues** — RabbitMQ event-driven communication, async task processing
- **Databases** — PostgreSQL schema design, MongoDB document modeling, Redis caching strategies
- **Code Quality** — Type hints, testing practices, code reviews, clean code principles

---

<p align="center">
  <i>🚀 Open to backend roles, system design challenges, and interesting collaborations.</i>
</p>

<p align="center">
  <i>Feel free to reach out on <a href="https://www.linkedin.com/in/BPapinski">LinkedIn</a> or via <a href="mailto:bartosz.papinski00@gmail.com">email</a>!</i>
</p>

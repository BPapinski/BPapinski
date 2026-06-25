<h1 align="center">Hey, I'm Bartosz 👋</h1>

<p align="center">
  <b>Junior Backend Python Developer</b> · Warsaw, Poland
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/BPapinski"><img src="https://img.shields.io/badge/LinkedIn-BPapinski-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:bartosz.papinski00@gmail.com"><img src="https://img.shields.io/badge/Email-bartosz.papinski00%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" /></a>
</p>

---

I'm a Python developer with hands-on experience from professional internships and university projects. I focus on backend systems, REST APIs, and microservices architecture. I enjoy building things that scale — from clean API design to cloud-deployed services.

Currently studying **Information Technology** (Information Systems Engineering) at Warsaw University of Life Sciences.

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Django REST](https://img.shields.io/badge/Django_REST-092E20?style=flat&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=python&logoColor=white)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

---

## 💼 Experience

**Junior Backend Developer** — *SPRELLI Sp. z o.o.* · Feb 2026 – May 2026
> Contributed to a tutor–student marketplace built from scratch. Developed backend microservices, worked with cloud deployment and infrastructure monitoring tools.

**Junior Backend Developer Intern** — *Innowise Group* · Aug 2025 – Jan 2026
> Built Python microservices with FastAPI and Django, integrated with PostgreSQL and AWS. Focused on scalable architecture and production-ready solutions.

**Junior Fullstack Developer Intern** — *Randlab Software* · Jul 2025 – Aug 2025
> Developed a fullstack tender management system using Django, Django REST Framework, PostgreSQL, and React.

---

## 🚀 Projects

### 🏗️ Integrated Tender Management Platform

The following repositories form a distributed microservices-based system developed around a tender management platform. Each service has a dedicated responsibility and communicates through asynchronous messaging and shared authentication mechanisms.

**Components:**
- Randlab-Przetargowisko — main business application
- User Management Service — authentication, authorization and user lifecycle management
- Notification Service — event-driven email delivery and audit logging

---

### 📑 [Randlab-Przetargowisko](https://github.com/BPapinski/Randlab-Przetargowisko)

A full-stack tender management platform developed during my internship at Randlab Software. The application allows users to create, manage and track tenders through a modern web interface. Built with a service-oriented architecture and integrated with dedicated authentication and notification services.

**Key features:**
- Tender creation and management
- User authentication and authorization
- RESTful API architecture
- PostgreSQL-backed data storage
- Integration with external microservices
- Dockerized development environment

**Stack:** Python · Django · Django REST Framework · React · PostgreSQL · Docker

### 🔐 [User Management Service](https://github.com/BPapinski/user-management-service)
A dedicated authentication and user management microservice that serves as the identity provider for the Tender Management Platform. Handles registration, JWT authentication, role-based access control, user groups and password recovery workflows. Communicates with Notification Service through RabbitMQ events.

**Stack:** Python 3.12 · FastAPI · SQLAlchemy (async) · PostgreSQL · Redis · RabbitMQ · AWS S3 · Alembic · Docker · GitHub Actions

---

### 📬 [Notification Service](https://github.com/BPapinski/notification-service)
An event-driven notification microservice that supports the Tender Management Platform ecosystem. Consumes password-reset and user-related events from RabbitMQ, stores audit information in MongoDB and delivers transactional emails through AWS SES.
**Stack:** Python 3.12 · RabbitMQ (pika) · MongoDB · AWS SES · Pydantic v2 · Docker · GitHub Actions

---

### ❤️ [AngularTinder](https://github.com/BPapinski/AngularTinder)
A full-stack dating app clone inspired by Tinder. Microservice architecture with a Django REST Framework backend and an Angular 17 frontend, containerised with Docker Compose. Includes a Django admin panel, Swagger docs, and pre-commit hooks with Ruff for code quality.

**Stack:** Python 3.12 · Django 5 · Django REST Framework · Angular 17 · TypeScript · PostgreSQL · Docker · Ruff

---

### 🗺️ SmartRoute *(Bachelor's Thesis — Work in Progress)*
A leisure planning application that generates optimised sightseeing routes based on the user's current location or a chosen starting point. The system fetches nearby tourist attractions, accounts for travel time between them, and builds a personalised itinerary that fits the available time window.

> 🔒 Repository is private — the project is currently under active development as part of a Bachelor's thesis.

**Stack:** Python · FastAPI · PostgreSQL · Docker · Maps / Geolocation APIs

---

> 💡 **Architecture note:**  
> Randlab-Przetargowisko, User Management Service and Notification Service were designed to work together as a distributed system. Authentication and user management are handled by User Management Service, while Notification Service processes asynchronous events and email delivery for the platform.

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BPapinski&show_icons=true&theme=default&hide_border=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BPapinski&layout=compact&theme=default&hide_border=true" height="160" />
</p>

---

<p align="center">
  <i>Open to backend roles and interesting collaborations. Feel free to reach out!</i>
</p>

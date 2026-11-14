<h1 align="center">Hi, I'm Mahammad Faizal 👋</h1>

<h3 align="center">Python Backend Engineer | FastAPI • Async Systems • LLMs / RAG • n8n Automation • Docker</h3>

<p align="center">
  <a href="https://linkedin.com/in/mfaizalf72">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:mfaizalf72@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://my-portfolio-seven-gamma-93.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://github.com/mfaizalf72">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

## 👨‍💻 About Me

I am a **Backend Engineer** based in Mangalore, India, specializing in **Python, asynchronous backend architectures, and intelligent automation systems**. I build high-concurrency RESTful APIs, transactional relational database backends, automated webhook pipelines, and secure Retrieval-Augmented Generation (RAG) applications.

With a polyglot engineering foundation in both **Python and Java/Spring Boot**, I focus on clean layered architecture, database-level concurrency control (`SELECT FOR UPDATE`), containerized deployments with **Docker**, and event-driven automation via **n8n**.

- 🔭 Currently building **[Evently](https://github.com/mfaizalf72/Evently)** — A high-concurrency event & ticket booking platform with database-level locking, n8n automations, and an AI policy support assistant.
- 🤖 Engineering **AI & RAG systems** with custom document ingestion, vector embeddings, chunk-level RBAC filtering, and LLM integrations.
- ⚙️ Automating business workflows and webhook pipelines using **n8n** and transactional outbox patterns.
- 🐳 Containerizing microservices and environments with **Docker & Docker Compose**.
- 📍 Based in **Mangalore, India**.

---

## 🛠 Tech Stack & Tools

### Backend & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### AI, LLM & Workflow Automation
![LLMs](https://img.shields.io/badge/LLM_Integration-FF6F00?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Architecture-4B0082?style=for-the-badge)
![n8n](https://img.shields.io/badge/n8n_Automations-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Webhooks](https://img.shields.io/badge/Webhooks_&_Events-107C41?style=for-the-badge)

### Databases & Migrations
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic_Migrations-2B2D42?style=for-the-badge)

### DevOps, Cloud & Testing
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

### Frontend (Complementary)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)

---

## 🚀 Featured Projects

### 1. [Evently 🎟️](https://github.com/mfaizalf72/Evently)
**Production-Grade Event Management & Ticket Platform with Database-Level Concurrency Control**
- Engineered an asynchronous backend in **FastAPI** with **SQLAlchemy 2.0 (asyncpg)** and **PostgreSQL**.
- Solved race conditions and ticket overbooking under heavy load using atomic conditional updates, database constraints, and `SELECT FOR UPDATE` pessimistic locking.
- Built clean layered architecture (API Controllers, Services, Repositories, Domain Models, Pydantic v2 schemas).
- Integrated **n8n automated workflows** via webhooks for payment verification, automated ticket generation, and notifications.
- Integrated an **AI-powered RAG assistant** to answer attendee queries strictly grounded in event & refund policies.

> **Tech Stack:** Python 3.11+, FastAPI, PostgreSQL, SQLAlchemy (Async), Alembic, Pydantic v2, n8n, RAG, Pytest, Docker

---

### 2. [Enterprise RAG & AI Query Intelligence (LLM-Logging)](https://github.com/mfaizalf72/LLM-Logging)
**Secure AI Query Logging, Audit Trail & Document Retrieval System**
- Architected an Enterprise RAG system featuring semantic document search, embedding ingestion, and vector retrieval.
- Implemented **Role-Based Access Control (RBAC)** at the chunk level, ensuring unauthorized document chunks are never leaked to the context layer.
- Added comprehensive AI audit logging, token consumption metrics, latency tracking, and query citation generation.

> **Tech Stack:** Python / Node.js, Vector Search, RAG Architecture, RBAC, JWT, SQLite, Express.js, React.js

---

### 3. [Team Task Manager](https://github.com/mfaizalf72/team-task-manager-backend)
**Full-Stack Distributed Task Management System with RBAC**
- Engineered backend services using **Java & Spring Boot** with stateless **JWT authentication**.
- Designed role-based permissions (Admin vs. Member), priority scheduling queues, timeline tracking, and RESTful CRUD endpoints.
- Connected to a responsive React.js & Tailwind CSS dashboard.

> **Tech Stack:** Spring Boot, Spring Security, JWT, MySQL, React.js, Tailwind CSS, REST APIs  
> **Links:** [Backend Repo](https://github.com/mfaizalf72/team-task-manager-backend) | [Frontend Repo](https://github.com/mfaizalf72/team-task-manager-frontend)

---

### 4. [DevOps & Containerized Infrastructure](https://github.com/mfaizalf72/devops-internship-assignment)
**Automated CI/CD Pipelines, Multi-Stage Docker Builds & Configuration Management**
- Implemented multi-stage Docker builds to optimize image footprints for backend runtime environments.
- Configured automated continuous integration and testing workflows with GitHub Actions.

> **Tech Stack:** Docker, Docker Compose, Linux, CI/CD, Git

---

## 💼 Experience

### Full Stack Developer Intern  
**ExcelR Solutions | Bengaluru, India**
- Built scalable REST APIs, relational schemas, and integrated frontend applications.
- Implemented authentication, authorization filters, query optimization, and structured unit/integration testing.
- Managed collaborative version control workflows using Git and GitHub.

### Project Planning Engineer  
**PlantTech - Saudi Aramco Project | Riyadh, Saudi Arabia**
- Handled engineering tracking systems, operational KPI dashboards, and structured milestone reporting.
- Coordinated cross-functional workflows under strict quality and timeline SLAs.

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mfaizalf72&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Faizal's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mfaizalf72&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

## 📌 Currently Deep-Diving Into

- 🧠 **Agentic AI & Advanced RAG**: GraphRAG, hybrid vector/keyword retrieval, and guardrailed multi-agent tool execution.
- ⚡ **Workflow Orchestration**: Advanced n8n pipelines, webhook listeners, and event-driven automation.
- 🐳 **Microservices & DevOps**: Docker orchestration, Redis caching, and message queues.
- 📐 **High-Scale System Design**: Database sharding, read-replicas, and distributed concurrency patterns.

---

## 📫 Connect With Me

- 🌐 **Portfolio:** [my-portfolio-seven-gamma-93.vercel.app](https://my-portfolio-seven-gamma-93.vercel.app)
- 💼 **LinkedIn:** [linkedin.com/in/mfaizalf72](https://linkedin.com/in/mfaizalf72)
- 📧 **Email:** [mfaizalf72@gmail.com](mailto:mfaizalf72@gmail.com)
- 🐙 **GitHub:** [github.com/mfaizalf72](https://github.com/mfaizalf72)

---

<p align="center">
  <b>Open to Python Backend Engineer, Full-Stack Developer, and AI/Automation Systems roles.</b>
</p>

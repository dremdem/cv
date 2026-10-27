# VLADIMIR YAKOVENKO
## Senior Python Backend Engineer · data pipelines & system integrations

## Contact

- Email: dremdem@gmail.com
- Telegram: dremdem
- LinkedIn: https://www.linkedin.com/in/vladimir-yakovenko-7b666686
- Portfolio: https://www.dremdem.ru
- Languages: Russian (native), English (B2, daily work with English-speaking teams since 2018)
- Location: Thailand (GMT+7), fully remote, any time zone (EU or US hours overlap)
- Contract: independent contractor; invoicing or EOR

---

## Professional Summary

Python backend engineer with 8+ years on remote product teams (Flask, Django, FastAPI), after 15 years of enterprise ERP consulting (Oracle E-Business Suite) for mining, energy and logistics companies. I build APIs, data pipelines (Airflow, pandas) and integrations with third-party systems, and keep the delivery side healthy: Docker images, CI on GitHub Actions, dependency upgrades. I am comfortable on the business side too: requirements, specifications, user training.

---

## Technical Skills

**Languages:** Python, SQL, PL/SQL, Bash; TypeScript and JavaScript (working knowledge)

**Backend:** Flask, Django, Django REST Framework, FastAPI, SQLAlchemy, GraphQL, REST APIs, OpenAPI, Pydantic

**Data & ETL:** pandas, NumPy, PyArrow, Airflow, Dash, data validation, Jupyter-to-production

**Databases & search:** MySQL, PostgreSQL, MS SQL Server, MongoDB, Oracle, Elasticsearch (basic)

**Cloud & infrastructure:** AWS (ECS Fargate, Lambda, S3, ECR), Google Cloud (GKE), Docker, Docker Compose, multi-stage images, Kubernetes (basic), Terraform

**Queues:** Celery, Redis (light)

**Build, test & CI/CD:** GitHub Actions, pytest, Poetry, uv, dependency management, container registries (GHCR, Docker Hub, ECR)

**Frontend:** React, Next.js (working knowledge, AI-assisted)

**Tools:** Git, GitHub, Jira, Linux

---

## Professional Experience

### Senior Python Developer | Causify
**December 2022 - Present** | Remote

Causify (formerly ParticleOne; I rejoined after working there in 2020–2021) builds a causal-AI platform for predictive analytics on market data. I worked on the data, application and infrastructure side, supporting the quant team.

- Built a dependency-update pipeline for Docker images across 4–5 repositories, including a monorepo with several images: GitHub Actions rebuilds the multi-stage images with pinned Python dependencies (Poetry, later uv), runs the full test suite against them, and opens a PR with the updated `pyproject.toml` for an admin to approve; approved images are pushed to GitHub Container Registry, Docker Hub and AWS ECR. This turned rare, painful upgrades (dependency conflicts, behaviour changes in pandas, NumPy, PyArrow) into a routine semi-automated release
- Maintained and optimized Airflow DAGs that collect and clean data from crypto exchanges, stock markets and commodity prices and launch the quant team's compute jobs
- Turned research Jupyter notebooks into production Dash applications that stakeholders could use without running code
- Built a modular platform on top of these apps (React, TypeScript, Next.js, largely AI-assisted): each app became a module that could be enabled per customer, so customers could assemble their own application, with a subscription model in view
- Ran services on AWS (Fargate, Lambda, S3) in Docker, with CI on GitHub Actions and pytest

**Technologies:** Python, Flask, FastAPI, Dash, Airflow, pandas, NumPy, PyArrow, pytest, Poetry, uv, Docker, GitHub Actions, AWS (Fargate, Lambda, S3, ECR), React, TypeScript, Next.js

### Python Backend Developer | SXOPE
**May 2022 - December 2022** | Remote

SXOPE is a healthcare platform automating physicians' daily workflows.

- Developed Django APIs for the platform's medical document flows (prescriptions, insurance documents)
- Implemented search on Elasticsearch: indexed the data, wrote queries and fixed slow ones
- Worked with the MySQL schema behind these features
- Managed workloads on Google Kubernetes Engine (deploying and restarting pods) and added Terraform for the GCP access permissions the services needed

**Technologies:** Python, Django, MySQL, Elasticsearch, Docker, Kubernetes (GKE), Google Cloud, Terraform

### Python Backend Developer | Zentist
**August 2021 - May 2022** | Remote

Zentist automates insurance revenue cycle management for dental practices.

- Developed GraphQL APIs on Flask for the insurance claims and billing workflows
- Wrote and optimized MySQL queries and designed database models for billing data
- Covered my features with unit and integration tests (pytest)
- Deployed services to Kubernetes in Docker

**Technologies:** Python, Flask, GraphQL, MySQL, pytest, Docker, Kubernetes

### Python Developer | ParticleOne
**September 2020 - August 2021** | Remote

ParticleOne (renamed Causify later) provides machine-learning analytics on financial market data.

- Wrote the Python client library for the company's REST API: it started as my one-week hiring assignment, and I kept extending it after joining
- Built ETL loaders and data validation for exchange data: currency rates and crypto prices
- Wrote Airflow DAGs to schedule the loading and processing jobs
- Refactored the data science team's model training pipelines
- Worked with MongoDB and Docker-based services

**Technologies:** Python, pandas, Airflow, MongoDB, Docker, REST

### Freelance Python Developer | Upwork
**2017 - 2020** | Remote, short contracts alongside ERP consulting

- AutoCruitment: REST API for matching patients with clinical trials (Django, OpenAPI, PostgreSQL, MongoDB)
- Plantix (PEAT GmbH, Berlin): Flask API for a crop-disease diagnosis mobile app, serving ML model predictions
- Orbeliani: Django backend, initiative workflows and sponsor payments for a crowdfunding platform
- JELT: rebuilt a scraper-backed web application, backend and frontend (Flask, MongoDB)

### Earlier career: Enterprise ERP Consultant (Oracle E-Business Suite)
**15 years** | IBM Global Business Services, BDO Unicon and other consultancies

- Implemented Oracle EBS modules (Enterprise Asset Management, Purchasing, Sourcing, Order Management, Inventory) and Oracle Utilities CC&B for a large mining company (Kazakhstan), a national postal operator and energy retailers
- Gathered requirements and wrote functional and technical specifications (Oracle AIM / OUM)
- Wrote PL/SQL procedures, reports and ETL scripts to migrate and clean data at go-live
- Trained key users and end users

---

## Projects & Open Source

**Personal projects:**

- [django-oebs-eam](https://github.com/dremdem/django-oebs-eam) - Django tool that reads Oracle EBS Enterprise Asset Management tables and visualizes how maintenance models are built, which Oracle's own screens show poorly; used in my consulting work and shared with colleagues
- [Stupid Chat Bot](https://stupidbot.dremdem.ru) | [GitHub](https://github.com/dremdem/stupid_chat_bot) - AI-powered Telegram chatbot with a web interface
- [CV Profile](https://dremdem.ru) | [GitHub](https://github.com/dremdem/cv_profile) - personal site deployed by a CI/CD pipeline (GitHub Actions, Docker, VPS)

**Open source:**

- [pytest-monitor-backend](https://github.com/dremdem/pytest-monitor-backend) - Flask and MongoDB backend for pytest-monitor
- [tldr-pages](https://github.com/tldr-pages/tldr) - Russian translations, merged upstream

**Take-home assignments:**

- [FastAPI microservice with Celery](https://github.com/dremdem/fastapi_celery_xml) - asynchronous XML processing
- [Site monitoring over Kafka](https://github.com/dremdem/site_checker) - website health checker with a message broker
- [Serverless Kanban board backend](https://github.com/dremdem/kanban-board-backend) - AWS Lambda API

**Certification:** Oracle E-Business Suite Purchasing (earlier career)

# ВЛАДИМИР ЯКОВЕНКО
## Senior Python Backend Engineer · пайплайны данных и интеграции систем

## Контакты

- Email: dremdem@gmail.com
- Telegram: dremdem
- LinkedIn: https://www.linkedin.com/in/vladimir-yakovenko-7b666686
- Портфолио: https://www.dremdem.ru
- Языки: русский (родной), английский (B2, ежедневная работа с англоязычными командами с 2018 года)
- Локация: Таиланд (GMT+7), полностью удалённо, любой часовой пояс (пересечение с часами Европы или США)
- Формат: независимый подрядчик; работа по инвойсу или через EOR

---

## О себе

Python backend-инженер: 8+ лет в удалённых продуктовых командах (Flask, Django, FastAPI), до этого 15 лет консалтинга по внедрению ERP (Oracle E-Business Suite) для горнодобывающих, энергетических и логистических компаний. Разрабатываю API, пайплайны данных (Airflow, pandas) и интеграции со сторонними системами, слежу за поставкой: Docker-образы, CI на GitHub Actions, обновление зависимостей. Свободно работаю и с бизнес-стороной: требования, спецификации, обучение пользователей.

---

## Технические навыки

**Языки:** Python, SQL, PL/SQL, Bash; TypeScript и JavaScript (рабочий уровень)

**Backend:** Flask, Django, Django REST Framework, FastAPI, SQLAlchemy, GraphQL, REST API, OpenAPI, Pydantic

**Данные и ETL:** pandas, NumPy, PyArrow, Airflow, Dash, валидация данных, перевод Jupyter-ноутбуков в продакшн

**Базы данных и поиск:** MySQL, PostgreSQL, MS SQL Server, MongoDB, Oracle, Elasticsearch (базовый уровень)

**Облака и инфраструктура:** AWS (ECS Fargate, Lambda, S3, ECR), Google Cloud (GKE), Docker, Docker Compose, многоэтапные образы, Kubernetes (базовый уровень), Terraform

**Очереди:** Celery, Redis (немного)

**Сборка, тесты и CI/CD:** GitHub Actions, pytest, Poetry, uv, управление зависимостями, реестры контейнеров (GHCR, Docker Hub, ECR)

**Frontend:** React, Next.js (рабочий уровень, с помощью AI)

**Инструменты:** Git, GitHub, Jira, Linux

---

## Опыт работы

### Senior Python Developer | Causify
**Декабрь 2022 – настоящее время** | Удалённо

Causify (ранее ParticleOne; я вернулся в компанию после работы в ней в 2020–2021) делает платформу каузального AI для предиктивной аналитики рыночных данных. Отвечал за данные, приложения и инфраструктуру, поддерживал команду квантов.

- Построил пайплайн обновления зависимостей Docker-образов для 4–5 репозиториев, включая монорепозиторий с несколькими образами: GitHub Actions пересобирает многоэтапные образы с зафиксированными Python-зависимостями (Poetry, позже uv), прогоняет на них все тесты и открывает PR с обновлённым `pyproject.toml` на утверждение администратору; утверждённые образы публикуются в GitHub Container Registry, Docker Hub и AWS ECR. Редкие и болезненные обновления (конфликты зависимостей, изменения поведения pandas, NumPy, PyArrow) превратились в рутинный полуавтоматический релиз
- Поддерживал и оптимизировал DAG-и Airflow, которые собирают и очищают данные с криптобирж, фондовых рынков и цен на сырьё и запускают вычисления команды квантов
- Перевёл исследовательские Jupyter-ноутбуки в продакшн-приложения на Dash, которыми пользуются без запуска кода
- Собрал на основе этих приложений модульную платформу (React, TypeScript, Next.js, в основном с помощью AI): каждое приложение стало модулем, который подключается конкретному клиенту, так что клиент собирает своё приложение из модулей; платформа готовилась к модели подписки
- Запускал сервисы в AWS (Fargate, Lambda, S3) в Docker, CI на GitHub Actions и pytest

**Технологии:** Python, Flask, FastAPI, Dash, Airflow, pandas, NumPy, PyArrow, pytest, Poetry, uv, Docker, GitHub Actions, AWS (Fargate, Lambda, S3, ECR), React, TypeScript, Next.js

### Python Backend Developer | SXOPE
**Май 2022 – декабрь 2022** | Удалённо

SXOPE — медицинская платформа, автоматизирующая ежедневную работу врачей.

- Разрабатывал Django API для работы платформы с медицинскими документами (рецепты, страховые документы)
- Реализовал поиск на Elasticsearch: индексировал данные, писал запросы и исправлял медленные
- Работал со схемой MySQL под эти функции
- Управлял нагрузками в Google Kubernetes Engine (деплой и перезапуск подов) и добавлял в Terraform права доступа GCP, нужные сервисам

**Технологии:** Python, Django, MySQL, Elasticsearch, Docker, Kubernetes (GKE), Google Cloud, Terraform

### Python Backend Developer | Zentist
**Август 2021 – май 2022** | Удалённо

Zentist автоматизирует работу стоматологических клиник со страховыми выплатами.

- Разрабатывал GraphQL API на Flask для страховых заявок и биллинга
- Писал и оптимизировал запросы MySQL, проектировал модели данных для биллинга
- Покрывал свой код unit- и интеграционными тестами (pytest)
- Деплоил сервисы в Kubernetes в Docker

**Технологии:** Python, Flask, GraphQL, MySQL, pytest, Docker, Kubernetes

### Python Developer | ParticleOne
**Сентябрь 2020 – август 2021** | Удалённо

ParticleOne (позже переименована в Causify) — аналитика финансовых рынков на машинном обучении.

- Написал Python-клиент для REST API компании: он начался как моё недельное тестовое задание при найме, и после прихода в компанию я продолжал его развивать
- Разрабатывал ETL-загрузчики и проверку данных бирж: курсы валют и цены криптовалют
- Писал DAG-и Airflow для расписания загрузки и обработки
- Рефакторил пайплайны обучения моделей команды data science
- Работал с MongoDB и сервисами в Docker

**Технологии:** Python, pandas, Airflow, MongoDB, Docker, REST

### Python-разработчик на фрилансе | Upwork
**2017 – 2020** | Удалённо, короткие контракты параллельно с ERP-консалтингом

- AutoCruitment: REST API для подбора пациентов в клинические исследования (Django, OpenAPI, PostgreSQL, MongoDB)
- Plantix (PEAT GmbH, Берлин): Flask API мобильного приложения для диагностики болезней растений, выдача предсказаний ML-модели
- Orbeliani: Django-бэкенд краудфандинговой платформы, процессы подачи инициатив и платежи спонсоров
- JELT: переписал веб-приложение на основе скрейпера, бэкенд и фронтенд (Flask, MongoDB)

### Ранее: консультант по внедрению ERP (Oracle E-Business Suite)
**15 лет** | IBM Global Business Services, BDO Unicon и другие консалтинговые компании

- Внедрял модули Oracle EBS (Enterprise Asset Management, Purchasing, Sourcing, Order Management, Inventory) и Oracle Utilities CC&B для крупной горнодобывающей компании (Казахстан), национального почтового оператора и энергосбытовых компаний
- Собирал требования и писал функциональные и технические спецификации (Oracle AIM / OUM)
- Писал процедуры, отчёты и ETL-скрипты на PL/SQL для миграции и очистки данных при запуске
- Обучал ключевых и конечных пользователей

---

## Проекты и open source

**Личные проекты:**

- [django-oebs-eam](https://github.com/dremdem/django-oebs-eam) - инструмент на Django: читает таблицы Oracle EBS Enterprise Asset Management и наглядно показывает, из чего состоят модели ремонтов, что в самом Oracle видно плохо; использовал в консалтинге и показывал коллегам
- [Stupid Chat Bot](https://stupidbot.dremdem.ru) | [GitHub](https://github.com/dremdem/stupid_chat_bot) - Telegram-бот на AI с веб-интерфейсом
- [CV Profile](https://dremdem.ru) | [GitHub](https://github.com/dremdem/cv_profile) - личный сайт с CI/CD-деплоем (GitHub Actions, Docker, VPS)

**Open source:**

- [pytest-monitor-backend](https://github.com/dremdem/pytest-monitor-backend) - бэкенд на Flask и MongoDB для pytest-monitor
- [tldr-pages](https://github.com/tldr-pages/tldr) - переводы на русский, приняты в основной репозиторий

**Тестовые задания:**

- [Микросервис на FastAPI с Celery](https://github.com/dremdem/fastapi_celery_xml) - асинхронная обработка XML
- [Мониторинг сайтов через Kafka](https://github.com/dremdem/site_checker) - проверка доступности сайтов с брокером сообщений
- [Serverless-бэкенд Kanban-доски](https://github.com/dremdem/kanban-board-backend) - API на AWS Lambda

**Сертификат:** Oracle E-Business Suite Purchasing (во время работы в ERP)

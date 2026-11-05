<h1 align="center">Hi there! I'm Agustín Teta 👋</h1>
<p align="center"><b>Informatics Engineering student · Python Backend Developer · Applied AI & LLMs</b></p>

<p align="center">
  <a href="https://www.linkedin.com/in/agustinteta/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-agustinteta-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:agustinteta@hotmail.com"><img src="https://img.shields.io/badge/Email-agustinteta%40hotmail.com-0078D4?style=for-the-badge" alt="Email"/></a>
</p>

## 🧠 About me

I'm an **Informatics Engineering student** at Universidad Atlántida Argentina with **5+ years of
professional experience as a backend developer**. My career has grown alongside my degree: I started
building Django and Flask apps as a junior developer while studying, and today I design and maintain
**FastAPI microservices** in production.

The two paths meet in **Artificial Intelligence applied to real products**. My final thesis project,
Mango, brings what I do every day at work (APIs, databases, Docker) together with LLMs,
conversational agents, and evaluating how well they actually perform.

- 💼 Currently: **Python Developer at Invera**, backend team (FastAPI, PostgreSQL, Redis, Celery, AWS)
- 🎓 Finishing: **Informatics Engineering**, final thesis project in progress
- 🤖 Focus: LLM integration, AI agents, OCR and speech-to-text pipelines
- 🤝 Used to agile, multidisciplinary teams, technical decision-making and sprint planning

## 🥭 Featured project — Mango (final thesis project)

**Mango** is a personal finance app that uses AI to automate expense capture, categorization and
analysis. Instead of just showing charts, it includes a **conversational financial agent** that
answers questions in natural language, spots spending trends and suggests saving strategies.

**How expenses get in:**

| Mode | How it works |
|---|---|
| 📷 **Receipt photo (OCR)** | OpenCV/Pillow preprocessing (orientation, lighting, blur) → Tesseract OCR → amount, date and merchant extraction. Supports iPhone `.heic` photos. |
| 🎙️ **Voice** | Browser recording → OpenAI `gpt-4o-mini-transcribe` with a domain prompt → entity extraction with an LLM. |
| ✍️ **Free text (NLP)** | *"I spent $1500 at the supermarket"* → structured expense via LLM. |
| 🏷️ **Auto-categorization** | Two layers: user rules first, LLM as fallback. |

**AI highlights**

- 🤖 **Conversational agent** built with **LangChain 1.x / LangGraph** (`create_agent`), with 6 query tools over the user's data, custom middlewares (global deadline, tool tracking) and chat history persisted in PostgreSQL.
- 📊 **Evaluation harnesses** for every AI component (OCR, speech-to-text, text extraction, voice → expense end to end, categorization) using real annotated data, plus cost per run.
- 🔌 **Provider-agnostic design**: LLM provider, model and reasoning effort are configurable, and the OCR engine is pluggable (Tesseract / RapidOCR).

**Tech stack**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/Tesseract_OCR-3A7BD5?style=flat-square" alt="Tesseract OCR"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest"/>
</p>

- **Backend:** FastAPI · SQLAlchemy 2 · Alembic · PostgreSQL · JWT auth (PyJWT + Argon2id)
- **AI:** OpenAI (LLM + speech-to-text) · LangChain / LangGraph · Tesseract OCR · OpenCV · Pillow
- **Frontend:** React · Vite
- **DevOps & quality:** Docker Compose · pytest with coverage · Git-Flow

> 🔒 The repository is private for now — happy to show it or give a demo on request.

## 🧭 Journey

| Period | 💼 Work | 🎓 University |
|---|---|---|
| **2025 – today** | **Python Developer · Invera** — FastAPI microservices and REST APIs; async jobs with Celery and Redis; AWS. | **Informatics Engineering** (expected 2026) — final thesis project: Mango, an AI-powered finance app. |
| **2023 – 2025** | **Python Developer · Dowl** — backend solutions with Django and FastAPI, documented REST APIs (Swagger, API contracts), technical decisions and sprint planning, production maintenance. | Advanced Informatics Engineering coursework. |
| **2022 – 2023** | **RPA Developer · Enta Consulting** — Blue Prism automations, operations and maintenance for an oil & gas client. | **University Technician in Computer Systems** (2018 – 2024). |
| **2021 – 2023** | **Python Developer Jr · Dowl** — Django and Flask apps, APIs and database optimization, Git and CI/CD in agile teams. | Artificial Intelligence (fuzzy inference systems) and programming courses: Java + MySQL and Node.js + MongoDB systems (see projects below). |
| **2018** | | Started Informatics Engineering at Universidad Atlántida Argentina. |

## 🎓 Other AI & university projects

- **[Fuzzy Inference System (Mamdani)](https://github.com/agustinteta/IA-FISMamdani)** — *Artificial Intelligence course.* Fuzzy logic inference system in Python with scikit-learn, pandas and matplotlib.
- **[Virus simulator](https://github.com/agustinteta/virus-simulator)** — Agent-based model in Python with [Mesa](https://mesa.readthedocs.io/) that simulates how a virus spreads across university spaces (classroom, cafeteria, auditorium), with real-time visualization.
- **[Sales system](https://github.com/agustinteta/sistema-de-ventas)** — *Programming 3.* Java + JPA + MySQL on the cloud, MVC. Suppliers, products, sales orders, customers, users with encrypted passwords, sales points and PDF generation.
- **[Supplier system](https://github.com/agustinteta/sistema-de-proveedores)** — *Visual Programming & Interfaces.* Node.js + MongoDB Atlas + Bootstrap, MVC with middlewares.
- **[Turn manager](https://github.com/agustinteta/AppTurnos)** — *Programming 3.* General-purpose appointment manager in Java + MySQL.

## 👨‍💻 Technologies and tools

**AI & Data**

<p>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" alt="Seaborn"/>
</p>

**Languages, frameworks & tools**

<p>
  <img src="https://skillicons.dev/icons?i=py,fastapi,django,flask,java,js,react,nodejs,html,css,bootstrap&perline=11" alt="Languages and frameworks"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,docker,aws,azure,git,github,githubactions&perline=11" alt="Databases and tools"/>
</p>

## 📈 GitHub stats

<p>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=agustinteta&theme=github" alt="Profile details" width="100%"/>
</p>
<p>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=agustinteta&theme=github" alt="Stats" width="49%"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=agustinteta&theme=github" alt="Most commit language" width="49%"/>
</p>

<!---
agustinteta/agustinteta is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->

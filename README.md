# 👋 Hi, I'm Priyanshu Kumar

**B.Tech, Computer Science and Technology** · SAGE University, Indore · 2026–2030

Software Engineering • Backend Systems • Full-Stack Development • AI/LLM Applications • Voice AI

---

## 🧑‍💻 About

I'm a Computer Science student who learns by building. I like taking an idea and turning it into a working system, whether that's a full-stack app, a backend service or an AI experiment.

Right now I'm focused on backend engineering and AI systems, especially how to let an LLM do useful work without giving it unsafe access to your data.

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **Languages** | Python · C++ · JavaScript · SQL · HTML/CSS |
| **Frontend** | React · Next.js |
| **Backend** | FastAPI · Pydantic · REST APIs · Next.js Route Handlers · JWT · bcrypt · HMAC webhook verification |
| **Databases** | PostgreSQL (Supabase) · SQLite · Redis |
| **Automation & AI** | n8n · structured LLM extraction · webhooks |
| **Cloud & DevOps** | Docker · AWS EC2 · GitHub Actions · Linux · Caddy |
| **Tools** | Git · GitHub · Firebase · Recharts |
| **Concepts** | DSA · OOP · API design · authentication & authorization · layered architecture · system design |

---

## 🚀 Featured Projects

### ☎️ AI Voice Sales System
`Python` `FastAPI` `PostgreSQL / Supabase` `Redis` `n8n` `Pydantic`

A backend for an AI voice agent that handles property inquiries, qualifies leads, checks inventory and processes call data after each call.

The main design idea: **the AI agent never touches the database directly.** It can only act through two validated FastAPI tools (`check_inventory` and `transfer_call`), so everything it does is controlled and easy to audit.

**What's built**
- Layered FastAPI backend (router → service → repository → database) with a connection pool and environment-based config
- Inventory search, lead management and call lifecycle APIs on PostgreSQL / Supabase
- Retell-compatible webhook endpoint secured with HMAC signature verification
- Redis token-bucket rate limiting
- n8n post-call workflow: structured lead extraction, phone/budget normalization, existing-lead matching, create-or-update (it only fills empty fields, never overwrites), and call-to-lead linking
- Tested end to end locally: FastAPI → n8n → Supabase

**What's next:** Retell production integration, Exotel telephony with real call transfer, WhatsApp follow-ups, deployment, monitoring and more automated tests.

📂 [Repository](https://github.com/priyanshu-kumar952/ai-voice-sales-system)

---

### 💊 Mithila Medico: Pharmacy E-Commerce & Management Platform
`Next.js` `React` `JavaScript` `SQLite` `JWT` `Docker` `AWS`

A full-stack platform built around how a neighborhood pharmacy actually works: ordering, staff operations, batch-level inventory, billing, analytics and audit logging in one app.

**Highlights**
- Customer, Staff and Owner/Admin workflows with JWT auth, bcrypt hashing, HTTP-only sessions and role-based authorization
- Batch-level inventory with stock and expiry tracking, plus low-stock and expiry alerts
- Billing based on the batch picked at fulfillment
- Sales analytics: daily trends, top-selling medicines, date-range analysis
- Order and inventory audit logging
- Relational SQLite schema with foreign keys, indexes, transactions, WAL mode and migrations
- Dockerized and deployed on AWS EC2 with CI/CD through GitHub Actions, GitHub Container Registry, AWS OIDC/IAM and Systems Manager

📂 [Repository](https://github.com/priyanshu-kumar952/medico-an-e-commerce-web-application)

---

### 🔎 Internshala Internship Automation
`Python` `Playwright` `SQLite`

A Python tool that finds internships on Internshala, scores each one against my technical profile and explains the score (matched, partial and missing skills). Results are stored in SQLite, exported to CSV and shown in an HTML dashboard with a ranked Top 10.

It never auto-submits applications and does not automate logins or CAPTCHAs.

📂 [Repository](https://github.com/priyanshu-kumar952/internshala-internship-automation)

---

## 🔬 AI Research (experimental)

### 🌌 AI Soul-Cycle Research
An independent, conceptual research project exploring computational models of emotion, memory, identity, personality evolution and ethics in artificial systems. It is experimental and does **not** claim that these simulations are conscious or sentient.

- **🧠 AI Soul Core**: the foundational prototype. It covers dynamic emotional states, emotional decay, episodic and emotionally tagged memory, moral alignment, identity evolution and memory inheritance across lifecycles.
- **🌱 SoulGenesis**: an expanded simulation engine with life → death → rebirth cycles, cross-life memory persistence, personality development, environmental interaction and ethical development.

---

## 🎯 Interests

AI agents · Voice AI · Conversational AI · LLM applications · AI memory systems · Backend engineering · System architecture · Database engineering · Cloud & DevOps

---

## 📫 Contact

- 📧 krpriyanshu952@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/anshu-kumar-8735ba377)
- 🐙 [GitHub](https://github.com/priyanshu-kumar952)

*Building software. Exploring AI. Understanding systems.*

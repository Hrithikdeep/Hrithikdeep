# Hi, I'm Hrithik 👋
### Software Engineer — Full Stack, Backend & Agentic AI Systems

I build production-grade software — backend infrastructure, full-stack applications, and multi-agent AI systems — from architecture through deployment.

---

## ⚙️ What I Work On

- Backend architecture & distributed systems
- Multi-agent AI orchestration (LangGraph)
- RAG pipelines & retrieval systems
- Full-stack production applications
- AI-native infrastructure & automation

---

## 🛠 Tech Stack

| Category | Technologies |
|---|---|
| Languages | TypeScript, JavaScript, Python, SQL |
| Backend | Node.js, Express, NestJS, FastAPI, REST APIs |
| Frontend | React, Next.js, Tailwind CSS |
| Databases | PostgreSQL, pgvector, Redis, MongoDB |
| AI / Agents | LangChain, LangGraph, OpenAI API, Multi-Agent Orchestration, RAG, Vector Search |
| Queues / Infra | BullMQ, Redis, Docker, Railway, Vercel |
| Tools | Git, GitHub, Prisma, SQLAlchemy |

---

## 🚀 Featured Projects

### 🔧 Relay — AI-Native Background Job Processing Platform
A distributed job queue with AI-driven routing and self-healing retry logic — when a job fails, an AI agent analyzes the failure and corrects the retry strategy automatically instead of failing silently.

- Full backend: job queue, worker system, multi-step workflow execution engine
- AI Chat agent with 13 real tools, streaming responses, and human-in-the-loop approval before destructive actions (cancel job, pause queue)
- Multi-step Workflows engine — sequential execution across queues with automatic failure halting
- Production deployment: Railway (backend + Postgres + Redis) + Vercel (frontend)

**Stack:** Node.js · TypeScript · Express · PostgreSQL · Prisma · Redis · BullMQ · LangChain/OpenAI · Next.js
**Repo:** https://github.com/Hrithikdeep/relay

---

### 🧠 Oracle — Multi-Agent Financial Research System
A 10-component agentic system — 7 LLM reasoning agents plus 3 deterministic services — that investigates a company, cross-verifies every claim against retrieved evidence, and flags findings it can't substantiate instead of guessing.

- Real evidence retrieval (Tavily + SEC EDGAR) with chunking, embeddings, and hybrid search over pgvector
- Dedicated Verification Engine that challenges its own findings before they reach the output
- Full traceability — every risk/finding links back to its source evidence or financial data
- LangGraph-orchestrated workflow, persisted to Postgres (survives server restarts)

**Stack:** Python · FastAPI · LangGraph · PostgreSQL + pgvector · SQLAlchemy · Next.js
**Repo:** [ADD LINK]

---

### ⚡ AI Workflow Studio — No-Code AI Automation Platform
A visual workflow builder where users compose automations from drag-and-drop nodes — including AI Agent nodes — backed by a real job execution engine with retries and logging.

- Visual node editor with 12+ node types (HTTP, Gmail, Slack, AI Agent, and more)
- Redis/BullMQ-backed execution engine with retry logic and structured logs
- Production deployment with CI/CD

**Stack:** Next.js · Node.js · NestJS · PostgreSQL · Redis · BullMQ · LangChain
**Repo:** [ADD LINK]

---

## 📈 Currently Exploring

- Advanced multi-agent orchestration patterns
- Production RAG & retrieval architectures
- AI infrastructure & evaluation systems

---

## 📫 Reach Me

📧 hrithikdeep243@gmail.com
💼 [LinkedIn](https://in.linkedin.com/in/hrithikdeep)
💻 [GitHub](https://github.com/Hrithikdeep)

**Open to:** Backend Engineer · AI/Agentic Engineer · Founding Engineer · Forward Deployed Engineer — Remote (India / USA)


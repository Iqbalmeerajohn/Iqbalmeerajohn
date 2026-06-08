# Sheik Iqbal Meera John

**Software Engineer — I build AI-powered, data-driven products end to end, from backend systems to deployed ML.**

[LinkedIn](https://linkedin.com/in/sheik-iqbal-meera-john-056191253) · [GitHub](https://github.com/Iqbalmeerajohn) · [Email](mailto:iqbalmeerajohn1@gmail.com)

📍 Hyderabad / Visakhapatnam, India · Open to remote & relocation
🎯 Actively seeking **Software Engineer / Full-Stack / AI-ML** roles (fresher)

---

## 🚀 Flagship Project — GUMMY OS

> A solo-built, memory-first, multi-tenant AI backend — the foundation of a personal "AI operating system."

GUMMY OS is a production-grade backend for a multi-tenant, memory-first AI assistant: every conversation reads from **and** writes to a durable, per-user long-term memory, behind strict, database-enforced tenant isolation. Built with FastAPI + PostgreSQL/pgvector and verified by **200+ automated tests across 8 delivery milestones.**

**Implemented capabilities**
- **Long-term Memory Engine** — categorized, scored memories (importance + confidence), immutable versioning, and recall-based reinforcement.
- **Semantic Search** — pgvector (HNSW cosine) + Postgres full-text, blended into a hybrid ranking over similarity, importance, recency, and confidence.
- **Conversation System** — persistent, resume-anywhere threads; each reply grounded in recent history + a rolling summary + retrieved long-term memories within a token budget.
- **Memory Extraction** — consent-gated pipeline that distills durable facts from chats and stores them through the Memory Engine, with full provenance back to the source conversation.
- **JWT Authentication** — HS256 token verification at the edge; tenant context published before any database work.
- **Row-Level Security (RLS)** — fail-closed, database-enforced isolation on every tenant table, under a dedicated non-bypass Postgres role, so isolation can't be bypassed by an app bug. Verified live by a Postgres-gated test suite.
- **Multi-Tenant Architecture** — multi-tenant from day one; stateless services over a stateful Postgres store for trivial horizontal scale-out; versioned REST API + OpenAPI docs.

**Stack:** Python 3.12 · FastAPI · Pydantic v2 · SQLAlchemy 2.0 (async) · Alembic · PostgreSQL (Supabase) · pgvector · Anthropic Claude · sentence-transformers · pytest · ruff · mypy · Docker

> Built first as a personal backend, with a deliberate path toward a multi-user SaaS platform. Multi-agent orchestration and domain agents are the **next phase — not yet implemented.**

---

## 🔭 Current Focus
- Extending GUMMY OS from its memory + conversation substrate toward an agent framework (orchestrator + domain agents).
- Deepening backend engineering: async workers, test coverage, and migration discipline.
- Sharpening DSA fundamentals and shipping deployable full-stack projects.

---

## 📌 Featured Projects

**GUMMY OS — Multi-Tenant AI Backend** · `Python` `FastAPI` `PostgreSQL` `pgvector` _(private — access on request)_
Memory-first AI backend: Memory Engine, hybrid semantic search, memory-aware conversations, consent-gated memory extraction, JWT auth, fail-closed Row-Level Security. 200+ tests, 11 Alembic migrations.

**[Speech Emotion Recognition](https://github.com/Iqbalmeerajohn/emotion-recognition-speech)** · `AI/ML` `Deep Learning` `FastAPI`
92% accuracy on RAVDESS via Multi-Head Attention + Federated Learning. FastAPI backend + Streamlit frontend. Top 30 / ~350 at the GITAM 2026 technical poster presentation.

**KAFA — Cinematic Café Platform** · `Next.js` `TypeScript` `Tailwind` _(in development)_
Premium, mobile-first café & restaurant platform for a real Visakhapatnam venue — Next.js 15, TypeScript, Tailwind CSS, Framer Motion. _(Live demo available on request.)_

**[Retail Sales Prediction & ML Portfolio](https://github.com/Iqbalmeerajohn/Cong-Data-Science-task)** · `Machine Learning` `Python`
Retail sales forecasting (85%+ accuracy), credit-card fraud detection (0.96 ROC-AUC with SMOTE + XGBoost), EDA on 10K+ records.

**[Analytics Dashboard Portfolio](https://github.com/Iqbalmeerajohn/analytics-dashboard-portfolio)** · `Power BI` `Business Intelligence`
Interactive Power BI dashboards for customer churn, diversity & inclusion, and call-center performance — DAX measures, KPI design, Power Query ETL.

---

## 🛠️ Skills
**Languages:** Python · TypeScript · JavaScript · SQL · HTML · CSS
**Backend:** FastAPI · SQLAlchemy (async) · Alembic · REST APIs · JWT auth · PostgreSQL · pgvector · Row-Level Security
**Frontend:** React · Next.js · Tailwind CSS
**AI/ML:** TensorFlow · scikit-learn · sentence-transformers · librosa · XGBoost · Streamlit
**Data:** Pandas · NumPy · Power BI
**Tools:** Git · Docker · Vercel · Supabase · Postman · pytest · ruff · mypy

---

## 🎓 Education & Certifications
**B.Tech, Computer Science & Engineering (Data Science)** — GITAM (Deemed) University, Visakhapatnam · 2022–2026

AWS Data Engineering Virtual Internship (EduSkills) · Alteryx Data Analytics & Process Automation (EduSkills) · Software Engineering Job Simulation (J.P. Morgan / Forage) · Python Data Structures (University of Michigan)

---

## 📫 Connect
📧 iqbalmeerajohn1@gmail.com · 💼 [LinkedIn](https://linkedin.com/in/sheik-iqbal-meera-john-056191253) · 💻 [GitHub](https://github.com/Iqbalmeerajohn)

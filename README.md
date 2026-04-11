# Hi, I'm Ziyi 👋

🎓 Computer Science @ University of Leeds
💻 Backend & AI Systems Engineer
🌍 Leeds, UK

I build production-grade backend systems and AI-powered applications — from RAG pipelines and agentic frameworks to concurrent game servers and serverless edge deployments.

---

## 🚀 Featured Projects

### 🔍 [AI Research Agent](https://github.com/ziyi170/ai_research_agent) — RAG + Agentic Pipeline
An intelligent academic research assistant powered by retrieval-augmented generation and an agentic planning layer.
- Agentic intent classification routes queries to arXiv search, FAISS vector retrieval, or direct LLM generation
- OpenAI embeddings + FAISS `IndexFlatIP` with overlapping chunking (512 chars, 64 overlap) for sub-millisecond semantic search
- Session-based sliding-window memory for coherent multi-turn conversation
- Async FastAPI backend with `asyncio.gather` for parallel embedding calls
- `temperature=0.2` to minimise hallucination in factual Q&A
> **Stack:** Python · FastAPI · FAISS · OpenAI · arXiv API · PostgreSQL · AWS

---

### 📄 [PDF Reader — AI Document Assistant](https://github.com/ziyi170/pdf_reader)
Upload any PDF, select text, and instantly ask AI questions, translate passages, or save highlights.
- Select text → ask GPT-4o-mini to explain, or translate between Chinese/English
- Persistent notes sidebar with full CRUD
- Fully containerised with Docker Compose; pytest test suite included
> **Stack:** FastAPI · PyMuPDF · OpenAI · React 18 · Docker

---

### 🤖 [Quantitative Trading System](https://github.com/ziyi170/quant_system)
End-to-end, event-driven quantitative investment system combining AI analysis, statistical factor models, portfolio optimisation, and simulated execution.
- Event streaming layer (Kafka/Redis) → AI intelligence layer (NLP sentiment, LLM reasoning) → factor models → CVaR risk engine → walk-forward backtesting → paper trading execution
- Portfolio optimisation via mean-variance and risk parity; tracks Sharpe, Sortino, max drawdown, and Calmar ratio
- React dashboard with TradingView charts and AI explainer component
> **Stack:** Python · FastAPI · OpenAI · Redis · Kafka · PostgreSQL · React · Docker

---

### ☁️ [Cloudflare AI Chat Memory Assistant](https://github.com/ziyi170/cf_ai_chat_memory_assistant)
Serverless AI chat assistant with persistent conversation memory, running on Cloudflare's global edge network.
- Cloudflare Durable Objects store and retrieve per-session conversation history with no traditional backend
- Worker handles request routing, prompt construction, and memory coordination; frontend served via Cloudflare Pages
- Demonstrates stateful AI behaviour on a fully serverless, globally distributed architecture
> **Stack:** Cloudflare Workers · Durable Objects · Cloudflare Pages · TypeScript · Llama 3.3 (Workers AI) · Wrangler

---

### ⚙️ [Java Multiplayer Game Server](https://github.com/ziyi170/Java_game_server)
Concurrent backend supporting 50+ simultaneous clients over raw TCP sockets.
- Custom multithreading model with synchronisation primitives to prevent race conditions
- Thread-safe architecture with zero data corruption under concurrent load
> **Stack:** Java · TCP Sockets · Multithreading

---

### 📓 [Notes App](https://github.com/ziyi170/notes_app) · [Daily Reflection](https://github.com/ziyi170/DailyReflection) · [Tuoci App](https://github.com/ziyi170/tuoci_app)
A collection of iOS productivity apps built with SwiftUI.
- MVVM architecture, Core Data persistence, async UI with Swift concurrency
- Iterated on real user feedback — reduced key task flows from 4 → 2 steps

---

## 🛠 Tech Stack

| | |
|---|---|
| **Languages** | Python · Java · TypeScript / JavaScript · Swift · SQL |
| **Backend** | FastAPI · Flask · REST APIs · Cloudflare Workers |
| **Frontend** | React · SwiftUI · HTML / CSS |
| **Databases** | PostgreSQL · SQLite · Redis |
| **Cloud & DevOps** | AWS (EC2, S3) · Cloudflare (Workers, Durable Objects, Pages) · Docker |
| **AI / ML** | RAG · FAISS · LangChain · OpenAI API · HuggingFace · spaCy |

---

## ⚡ Interests

- Scalable backend & distributed systems
- AI-powered applications and agentic frameworks
- Serverless and edge computing architectures
- System design and performance optimisation

---

## 📫 Contact

📧 ziyiy5661@gmail.com
🔗 [github.com/ziyi170](https://github.com/ziyi170)

---

⭐ Always open to internships and placement opportunities

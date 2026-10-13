
# Hey, I'm Abdullah Syed 👋

### AI / ML Engineer · Backend Engineer · LLM Systems & Local AI

**I build the engineering around AI (not just the model call.)**

My work spans document ingestion, retrieval and reranking, self-hosted LLM inference, multimodal video processing, background workers, and the APIs that hold everything together. I'm especially interested in what happens *after* a prototype works: accuracy, latency, hardware constraints, data privacy, and failure recovery.

📍 Lahore, Pakistan · 🌍 Collaborating with teams internationally

[**Email me**](mailto:asyed12.ss@outlook.com?subject=Let%27s%20work%20together) · [**LinkedIn**](https://www.linkedin.com/in/abdz128/) · [**Portfolio**](https://abdz128.edgeone.app) · [**More about my work →**](./aboutme.md)

---

## What I've been building

**🔎 Enterprise RAG & document intelligence — PowerAI**

Built ingestion and AI services for PDF, Word, Excel, CSV, and text. The retrieval stack combines **Docling + OCR, embeddings, Qdrant, BM25, reciprocal rank fusion, and reranking**, with role-aware filtering and source citations. Also deployed a **self-hosted, quantized LLM inference stack** using llama.cpp and ONNX-based embedding/reranking services.

**🎬 Multimodal video → short-form content — Content Repurposing Engine**

Architected a FastAPI/Celery workflow that transcribes, analyzes, scores, and renders clips for **12 publishing channels**. Separated analysis from rendering so edited timestamps can be re-rendered without reprocessing the original video. Added provider fallbacks, structured-output validation, and versioned channel outputs.

**🏠 Data pipelines & AI-assisted investment research — ForeclosureAI**

Developed an ingestion and reporting backend using **FastAPI, DuckDB, SFTP/Parquet, and S3**. Built scheduled incremental processing, an auditable property-status inference system, and LLM-assisted risk analysis with asynchronous execution and validation.

**🖥️ Desktop AI, privacy & integrations — Lonix AI / Legal AI R&D**

Worked on Electron desktop features, Google OAuth, auth/session reliability, PII redaction, and LLM evaluations. Separately researched a **local-first legal AI architecture** using Tauri, a Python sidecar, and llama.cpp, with a focus on offline inference and device constraints.

> Much of my professional work lives in private client repositories. I'm happy to discuss architecture, implementation decisions, and the trade-offs behind these systems.

## The tools I reach for

| Area | Technologies |
| --- | --- |
| **AI / retrieval** | PyTorch, Hugging Face, LangGraph, LangChain, Qdrant, BM25, reranking, llama.cpp, ONNX Runtime |
| **Backend / data** | Python, FastAPI, Celery, RabbitMQ, Kafka, PostgreSQL, DuckDB, SQLAlchemy |
| **Systems / deployment** | Docker, AWS (ECS/EKS/Bedrock), GCP, Linux, Rust, Tauri, Electron |
| **ML / evaluation** | scikit-learn, XGBoost, LightGBM, CatBoost, MLflow, SHAP, Langfuse |
| **Frontend when needed** | TypeScript, React, Next.js |

## Problems I'd love to work on

- **AI engineering:** RAG, document intelligence, agent workflows, multimodal pipelines, evaluation, and inference optimization.
- **Backend & platform engineering:** asynchronous processing, data pipelines, APIs, microservices, and reliable deployment.
- **Local / edge AI:** quantization, resource-aware inference, offline-first applications, and AI systems that protect sensitive data.

## Let's talk

If you're building an AI product and need someone who can work from **model/runtime constraints all the way to backend architecture and delivery**, I'd love to hear what you're working on.

**[✉️ Start a conversation](mailto:asyed12.ss@outlook.com?subject=AI%20Engineering%20Opportunity)** · [Connect on LinkedIn](https://www.linkedin.com/in/abdz128/)

<sub>For a deeper look at my background and projects, read <a href="./aboutme.md">aboutme.md</a>.</sub>

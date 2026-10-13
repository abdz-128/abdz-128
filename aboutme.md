
# About me — Abdullah Syed

**AI / ML Engineer | Backend Systems | Applied LLMs | Local-First AI**

I'm a computer engineer working at the intersection of **machine learning, backend engineering, and AI systems design**. Since 2023, I've worked on client products that turn unstructured documents, video, and business data into usable workflows.

The part I enjoy most is making the entire system work—not just getting a good answer from an LLM. That means deciding how data is parsed and indexed, how retrieval is evaluated, when to run models locally versus through hosted APIs, what happens when a background job fails, and how users can verify an AI-generated result.

I'm based in **Lahore, Pakistan**, and have worked with distributed teams and US-based clients.

## What I specialize in

### 1. LLM applications with traceable outputs

I've built and worked on retrieval systems where quality depends on more than embeddings:

- Structure-aware document parsing with **Docling, RapidOCR, and ONNX Runtime**.
- **Dense retrieval + BM25 + reciprocal rank fusion + reranking** with Qdrant and supporting services.
- Metadata- and role-aware retrieval, source citations, streaming responses, and controlled context windows.
- Structured-output validation, provider fallbacks, prompt evaluation, and reliability checks.

I care about whether an answer is grounded in the right source—not simply whether it sounds convincing.

### 2. Inference that respects real hardware

I'm interested in making capable models useful when compute, RAM, or privacy requirements rule out a straightforward hosted approach.

I've worked with **quantized GGUF models, llama.cpp, ONNX-based models, and self-hosted embedding/reranking services**. I've also researched offline legal-document AI with **Tauri + Rust + Python sidecars**, focusing on how model choice, quantization, memory, and deployment architecture shape what's feasible on a user's machine.

My longer-term technical interests include **computer architecture, parallel computing, and efficient AI inference**.

### 3. Backend engineering beyond the AI layer

I've built services that handle ingestion, processing, persistence, and integration—not just inference endpoints:

- **FastAPI** APIs and Python services with background execution through **Celery, RabbitMQ, Redis, and Kafka**.
- Data storage and analytics using **PostgreSQL, DuckDB, DynamoDB, DocumentDB, and S3-compatible storage**.
- Containerization, service migration, and deployment work across **Docker, AWS ECS/EKS, and GCP**.
- Auth, OAuth integrations, session handling, structured logging, schema migrations, and asynchronous processing.

I try to design around what happens when something breaks: retries, partial results, duplicate jobs, invalid model output, and recoverable state.

## A few projects that represent my work

### PowerAI — enterprise document intelligence

Contributed to a FastAPI-based microservice platform for ingesting and answering questions over documents. My work covered document ingestion, OCR, chunking, embedding, hybrid retrieval, reranking, access-aware filtering, and a self-hosted model-serving stack.

**The engineering challenge:** building a path from messy source documents to answers with evidence, while keeping retrieval and inference components independently manageable.

### Content Repurposing Engine — multimodal media processing

Architected a service that turns long-form video into short-form content across **12 channels**. It uses speech transcription, scene/video processing, multimodal model analysis, asynchronous queues, and FFmpeg rendering.

**The engineering challenge:** performing expensive analysis once, then allowing review, timestamp correction, and repeated rendering without rerunning the entire pipeline.

### ForeclosureAI — data ingestion and investment analysis

Developed ingestion and analytics services that process SFTP-delivered Parquet data into DuckDB, support incremental updates, and produce investor-facing reports. The system includes scheduled polling, auditable foreclosure-status logic, and LLM-based analysis with retries and post-processing checks.

**The engineering challenge:** reconciling data freshness, explainable rules, and AI-assisted interpretation in a repeatable workflow.

### Lonix AI — desktop integrations and data privacy

Worked across an Electron desktop application and FastAPI backend: OAuth and session flows, integrations, data preprocessing and memory pipelines, PII redaction, and evaluation workflows.

**The engineering challenge:** making a desktop AI application dependable across authentication, local app lifecycle, integrations, and data-handling boundaries.

## How I approach engineering

1. **Understand the constraints first.** Privacy, available hardware, operating cost, latency, accuracy, and deployment environment all influence the design.
2. **Use the simplest architecture that meets the requirement.** An orchestrated multi-agent system isn't automatically better than a well-designed pipeline.
3. **Evaluate the whole workflow.** A strong model cannot rescue broken ingestion, retrieval, or downstream validation.
4. **Design for investigation and recovery.** Useful logs, clear state transitions, idempotent work where appropriate, and auditable outputs matter.
5. **Document decisions.** Architecture is more useful when another engineer can understand why a trade-off was made.

## Background

- **Education:** BSc Electrical Engineering (Computer Engineering specialization), FAST-NUCES, Lahore (2023).
- **Professional experience:** ML engineering, backend services, desktop AI, document intelligence, multimodal processing, and analytics applications.
- **Current interests:** self-hosted and edge LLMs, inference efficiency, systems architecture, and computer architecture.

## Let's build something useful

I'm interested in connecting with **engineering teams, founders, recruiters, and researchers** working on difficult AI or backend problems—especially where model behavior, data infrastructure, and systems constraints intersect.

If that sounds relevant, send me a short note about the problem you're solving. I'd be glad to discuss the approach, technical challenges, and where I could contribute.

**[Email me](mailto:asyed12.ss@outlook.com?subject=Hello%20Abdullah)** · **[LinkedIn](https://www.linkedin.com/in/abdz128/)** · **[Portfolio](https://abdz128.edgeone.app)** · **[GitHub](https://github.com/abdz128-scale8up)**

[← Back to my GitHub profile README](./README.md)

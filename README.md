# Arthur Diaz — Senior .NET Developer (Remote, Canada) 🇨🇦
**Backend-focused engineer building reliable C#/.NET services and AI-102-aligned Azure AI implementations: Vision (Image Analysis 4.0), Video Indexer, and GenAI observability.**

---

## About Me

I’m a **Senior .NET Developer** based in **Canada**, working **remotely**. My core focus is **backend engineering**: designing APIs and services with **C# / .NET**, with strong emphasis on **performance**, **maintainability**, **observability**, and **safe delivery**.

I’m currently going deeper into **Azure** and **Azure AI**, turning each study topic into a **small, operable backend project**, aligned with the **AI-102** certification.

**What I value in engineering:** clear code, measurable decisions, data over opinions, and systems that are easy to operate in real life.

---

## 🧭 How I Study & Build (AI-102)

My workflow is intentionally simple and repeatable:

1. **Topic Extraction** → Identify weak exam areas and extract study-ready topics  
2. **Focus** → Study one capability deeply (no multitasking)  
3. **Practice** → Answer exam-style questions and implement the capability  
4. **Consolidation** → Document learnings, add edge cases, and convert to reusable notes

This keeps learning practical, measurable, and aligned with real-world backend work.

---

## 🧰 Tech Stack

### Backend
- **C#**, **.NET**, **ASP.NET Core**
- REST APIs, background processing, integration services
- **Entity Framework Core**, Dapper (when appropriate)
- Authentication / Authorization (JWT, OAuth concepts)
- Performance tuning, caching patterns, async/await best practices

### Cloud & AI
- **Microsoft Azure**
- App hosting & compute (App Service / Functions)
- Storage patterns (Blob Storage)
- **Azure AI Services (AI-102 track)**
  - **Azure AI Language** (text analysis, custom classification, NER, Q&A, CLU)
  - **Azure AI Vision** (image analysis, detection, classification)
  - **Azure AI Document Intelligence** (structured document extraction)
  - **Azure AI Search + embeddings** (RAG fundamentals, retrieval patterns)
  - **Azure AI Content Safety** (content filtering and policy decisions)

### Tools & Practices
- Git / GitHub
- CI/CD basics
- Clean Architecture (pragmatic use)
- Testing mindset (unit + integration)
- Observability mindset (logging, diagnostics, monitoring)

---

## 🚀 Featured Projects (AI-102 Practice Snapshots)

> Projects listed here are practice snapshots aligned to the AI-102 exam. Focus shifts based on retake priorities.

| Project | Status | Focus | Repo |
|---|---|---|---|
| [Text Intelligence API](https://github.com/adiazjohnson213/TextIntelligenceApi) | ⏸️ Paused | Azure AI Language (NLP basics) | https://github.com/adiazjohnson213/TextIntelligenceApi |
| Vision Intelligence API | 🧭 Planned | Image Analysis 4.0 + 429 resilience | TBD |
| Video Indexer Orchestrator | 🧭 Planned | ARM token + async workflow + insights | TBD |
| GenAI Observability Toolkit | 🧭 Planned | telemetry + tracing + feedback loop | TBD |

### 1) [Text Intelligence API](https://github.com/adiazjohnson213/TextIntelligenceApi) *(Paused)*
[![Project Status: Inactive](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)

A REST API for core **Azure AI Language** text analysis capabilities, designed as an AI-102 practice service with clean contracts and predictable outputs.

**Current study focus:**  
- Analyze text with **Azure AI Language**

**What I’m practicing:**  
- Language detection  
- Sentiment analysis  
- Key phrase extraction  
- Prebuilt entity recognition  

**Maintenance note:**  
This project is paused and kept as a reference snapshot. Enhancements will resume later.

**Tech:** .NET, ASP.NET Core, Azure AI Language  
**Status:** ⏸️ Paused (not actively maintained)

---

### 2) Vision Intelligence API *(Active — Exam Track)*
A .NET REST API wrapper for **Azure AI Vision Image Analysis 4.0**, focused on correct SDK usage, REST feature flags, defensive parsing, and throttling resilience (429).

**What I’m practicing:**
- AnalyzeAsync overloads (Uri vs BinaryData) + correct parameter order
- VisualFeatures flags (Caption | Read | Objects) mapping from requirements
- REST `features=` requests + parsing nullable/empty fields
- 429 throttling: exponential backoff + jitter + concurrency limiting

**Tech:** .NET, ASP.NET Core, Azure AI Vision (Image Analysis 4.0)  
**Status:** 🛠️ Active

---

### 3) Video Indexer Orchestrator *(Planned — Exam Track)*
A backend workflow for Azure Video Indexer: **ARM access token generation**, async upload/index, polling, and insights parsing.

**What I plan to practice:**
- ARM `generateAccessToken` (POST) + permissionType + scope (Account/Project/Video)
- Async state machine: token → upload/index → poll → insights
- Time-based outputs: segments/timestamps + keyword filtering
- Defensive parsing for null/empty lists in insights

**Tech:** .NET, Azure AI Video Indexer (ARM), Azure Storage (optional)  
**Status:** 🧭 Planned

---

### 4) GenAI Observability Toolkit *(Planned — Exam Track)*
A minimal telemetry/tracing approach for GenAI workloads: correlation, latency, token usage, trace records, and feedback loop.

**What I plan to practice:**
- Minimum viable telemetry: latency, tokens, correlation/request-id, alerts
- TraceRecord persistence: prompt/params/output/feedback
- Tracing with Azure Monitor / Application Insights (OpenTelemetry)

**Tech:** .NET, Azure Monitor / Application Insights, Azure OpenAI  
**Status:** 🧭 Planned

---

## 📌 Planned Projects (Backlog — AI-102)

> Backlog ideas for end-to-end AI-102 systems. Implementation timing is TBD.

### 1) Foundry Prompt Flow & Evaluation Lab *(Planned)*
A focused lab to practice **prompt flow**, **prompt templates**, and **evaluation flows/metrics** (quality, groundedness, safety checks) using repeatable datasets.

**Focus:** **Prompt Flow** + **Evaluation (models & flows)** + **Prompt Templates**  
**Tech:** Azure AI Foundry, Prompt Flow, Azure OpenAI, Azure Monitor / Application Insights (optional)

---

### 2) Safe Enterprise Knowledge Assistant *(Planned)*
A grounded RAG assistant that answers from curated content while enforcing safety policies.

**Focus:** **RAG** + **Azure AI Search grounding** + **Azure OpenAI prompting** + **Content Safety**  
**Tech:** .NET, Azure AI Search, Azure OpenAI, Azure AI Content Safety, Blob Storage

---

### 3) Task-Oriented AI Agent Backend *(Planned)*
A backend-first agent that selects tools, executes tasks, and returns structured results with observability and safe tool usage.

**Focus:** **Agents (tool calling)** + **Orchestration** + **Retrieval tool** + **Observability**  
**Tech:** .NET, Azure OpenAI, Azure AI Search, Functions / App Service

---

### 4) Moderated Multimodal Intake API *(Planned)*
A backend API that accepts text + images and returns **Allow / Review / Reject** decisions with consistent policy rules.

**Focus:** **Content Safety policy** + **Vision inputs** + **Allow/Review/Reject decisions**  
**Tech:** .NET, Azure AI Vision, Azure AI Content Safety, Azure OpenAI (optional)

---

### 5) Intelligent Document Review Pipeline *(Planned)*
A pipeline that ingests documents and produces structured extraction + semantic insights + summaries.

**Focus:** **Document Intelligence extraction** + **Vision enrichment** + **Summarization**  
**Tech:** .NET, Azure AI Document Intelligence, Azure AI Vision, Azure AI Language, Azure OpenAI, Blob Storage

---

## 🎯 Current Focus

### 📌 Now (EN)
- AI-102 retake preparation focused on my weakest areas:
  - Vision: Image Analysis 4.0 (SDK + REST)
  - Video Indexer (ARM tokens + async indexing workflow)
  - GenAI observability (telemetry + tracing + feedback loop)
- Building backend-first implementations: clean contracts, defensive parsing, and resiliency (429)

---

## 📚 Learning & Certifications

### ✅ Completed
- AZ-900 *(Azure Fundamentals)*

### 🟡 In Progress
- **AI-102** *(Azure AI Engineer Associate)*

---

## 📫 Contact & Links

- **GitHub:** https://github.com/adiazjohnson213
- **LinkedIn:** https://www.linkedin.com/in/arthur-diaz-johnson/
- **Location:** Canada 🇨🇦 (Remote)

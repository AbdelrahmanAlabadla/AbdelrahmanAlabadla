<div align="center">

# Abdelrahman Alabadla

### Applied AI Engineer

**LLM Systems · RAG · Agentic Workflows · Retrieval · Evaluation**

I build practical AI systems around **document intelligence, retrieval, LLM orchestration, validation, and reliability**.

📍 UAE   •   🎓 Computer Science & AI Student   •   💼 Open to AI Engineering Opportunities

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/abdelrahman-alabadla/)
[![GitHub](https://img.shields.io/badge/GitHub-Projects-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/AbdelrahmanAlabadla)

</div>

---

## About Me

I'm an **AI Engineer focused on applied LLM systems**.

Most of my work is around the engineering problems that happen **before and after the LLM call**:

* How should documents be processed and chunked?
* How do we retrieve the correct evidence?
* How should multiple LLM steps share state?
* How do we detect incorrect outputs?
* Can we repair only the failed part?
* How do we measure whether a change actually improved the system?

My main areas of interest are **RAG, agentic workflows, retrieval, LLM reliability, and evaluation**.

```text
Documents
   ↓
Processing & Chunking
   ↓
Retrieval
   ↓
Planning / Orchestration
   ↓
LLM Generation
   ↓
Validation & Repair
   ↓
Evaluation
```

---

# Featured Projects

<table>
<tr>
<td width="50%" valign="top">

## 📘 DraftWork

**AI Exam Generation Platform**

DraftWork converts educational documents into structured, configurable exams using a multi-stage LLM workflow.

### Architecture

```text
PDF
 ↓
Document Processing
 ↓
Chunking & Retrieval
 ↓
Exam Planning
 ↓
Question Generation
 ↓
Validation
 ↓
Targeted Repair
 ↓
Revalidation
 ↓
Evaluation
```

### Engineering Highlights

* Parent-child document chunking
* Dense + sparse retrieval
* Qdrant + RRF fusion
* Stateful LangGraph workflow
* Structured LLM outputs
* Multiple exam models
* Stable question IDs
* Deterministic + LLM validation
* Field-level targeted repair
* JSON and count repair
* Evaluation telemetry

<p align="center">
<a href="https://github.com/AbdelrahmanAlabadla/DraftWork">
<img src="https://img.shields.io/badge/View_DraftWork-181717?style=for-the-badge&logo=github&logoColor=white">
</a>
</p>

</td>

<td width="50%" valign="top">

## 🎓 EduBot AI

**University RAG Assistant**

EduBot is a multi-tenant AI assistant designed to answer student questions using information retrieved from university documents.

### Architecture

```text
Documents
 ↓
Parsing & Cleaning
 ↓
Chunking
 ↓
Embeddings
 ↓
Hybrid Retrieval
 ↓
Reranking
 ↓
Context Building
 ↓
Generation
 ↓
Grounding
```

### Engineering Highlights

* Document ingestion
* Structure detection
* Hierarchical chunking
* Metadata extraction
* Query rewriting
* Dense + sparse retrieval
* RRF fusion
* Reranking
* Context reconstruction
* Citation validation
* FastAPI backend
* Multi-institution architecture

> 🚧 **Work in Progress**
>
> The current focus is redesigning **chunking and retrieval** to build a more general system that works across different document structures without document-specific rules.

<p align="center">
<a href="https://github.com/AbdelrahmanAlabadla/EduBot-AI">
<img src="https://img.shields.io/badge/View_EduBot_AI-181717?style=for-the-badge&logo=github&logoColor=white">
</a>
</p>

</td>
</tr>
</table>

---

# Tech Stack

<div align="center">

### Core Engineering

<img src="https://skillicons.dev/icons?i=python,fastapi,postgres,git,docker">

<br><br>

### AI Engineering

![LLMs](https://img.shields.io/badge/LLMs-111111?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-6C63FF?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-111111?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge\&logo=huggingface\&logoColor=black)

</div>

<br>

| **LLM Systems**    | **Retrieval**   | **Reliability** | **Backend** |
| ------------------ | --------------- | --------------- | ----------- |
| Structured Outputs | Embeddings      | Validation      | Python      |
| Agentic Workflows  | Semantic Search | Targeted Repair | FastAPI     |
| Tool Calling       | Sparse Search   | Revalidation    | REST APIs   |
| Shared State       | RRF             | JSON Repair     | PostgreSQL  |
| ReAct Patterns     | Reranking       | Eval Telemetry  | SQL         |

---

# Current Engineering Focus

### 🔎 Retrieval Evaluation

I'm moving toward **evaluation-driven retrieval development** instead of assuming that adding more RAG components automatically improves performance.

```text
Question
   ↓
Known Relevant Evidence
   ↓
Retriever
   ↓
Top-K Results
   ↓
Evaluation
```

Current areas of interest:

**Recall@K · Precision@K · MRR · Reranking · Hybrid Search**

---

### 🧩 General-Purpose Chunking

One of my current challenges is building a chunking strategy that works across **different types of uploaded documents**.

The goal is:

```text
Different Documents
        ↓
Structure Understanding
        ↓
General Chunking Strategy
        ↓
Consistent Searchable Chunks
```

instead of continuously creating special rules for individual documents.

---

### 🛡️ Reliable LLM Workflows

I am also continuing to explore systems where failures can be detected and repaired without regenerating everything.

```text
Generate
   ↓
Validate
   ↓
Pass? ───────────► Final Output
   │
   No
   ↓
Identify Failure
   ↓
Targeted Repair
   ↓
Revalidate
```

---

# What I'm Looking For

I'm currently interested in opportunities as a:

<div align="center">

### **Junior AI Engineer · Applied AI Engineer · LLM Engineer · Generative AI Engineer**

</div>

Especially teams working with:

<div align="center">

`LLMs`   `RAG`   `Agents`   `Retrieval`   `Evaluation`   `AI Platforms`

</div>

I want to continue building real AI systems while strengthening my experience in **production deployment, infrastructure, monitoring, and scalable AI engineering**.

---

<div align="center">

# Let's Connect

If you're working on **LLM systems, RAG, agentic AI, retrieval, or applied AI engineering**, feel free to connect.

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdelrahman_Alabadla-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/abdelrahman-alabadla/)

<br><br>

### `Build → Measure → Find the Failure → Improve`

</div>

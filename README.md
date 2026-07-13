<div align="center">

# Kona Bharath Vamshidhar Reddy

### AI/ML Engineer · Agentic Systems · RAG · Synthetic Data · Multimodal AI

*Building production-grade AI systems — not notebooks — that hold up under real scrutiny*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kona-bharath-vamshidhar-reddy/)
[![GitHub](https://img.shields.io/badge/GitHub-Stevemeg-181717?style=for-the-badge&logo=github)](https://github.com/Stevemeg)
![Open to Work](https://img.shields.io/badge/Open%20to%20Work-00AA00?style=for-the-badge)

</div>

---

## About Me

I'm an AI/ML Engineer who builds complete, end-to-end systems — multi-agent architectures, RAG pipelines, generative models, and multimodal transformers — and I ship them with the parts most portfolios skip: test suites, evaluation harnesses, honest limitations sections, and real deployed demos.

I don't just train models. I design the architecture around them: how signals get ingested, how retrieval gets fused, how a system explains its own decisions, and how it fails safely when it's wrong.

Currently building:
- Agent-orchestrated platforms with explainability and human-in-the-loop review baked in, not bolted on
- Career-intelligence pipelines that turn a resume and a live job market into explainable, honest recommendations
- RAG systems that ground every answer in cited sources and refuse to answer what they can't support
- Advanced synthetic data pipelines spanning medical imaging, tabular, and genomic modalities

---

## Tech Stack

### Core Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### ML & Deep Learning Frameworks
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Agentic & LLM Systems
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-4A90D9?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-4A90D9?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge)

### Generative AI
![GANs](https://img.shields.io/badge/GANs-FF6B6B?style=for-the-badge)
![VAEs](https://img.shields.io/badge/VAEs-FF6B6B?style=for-the-badge)
![Diffusion%20Models](https://img.shields.io/badge/Diffusion%20Models-FF6B6B?style=for-the-badge)
![Transformers](https://img.shields.io/badge/Transformers-FF6B6B?style=for-the-badge)

### Synthetic Data Frameworks
![SDV](https://img.shields.io/badge/SDV-4A90D9?style=for-the-badge)
![TVAE](https://img.shields.io/badge/TVAE-4A90D9?style=for-the-badge)
![CopulaGAN](https://img.shields.io/badge/CopulaGAN-4A90D9?style=for-the-badge)
![TabDDPM](https://img.shields.io/badge/TabDDPM-4A90D9?style=for-the-badge)

### Backend & Infrastructure
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### Data & Visualization
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Featured Projects

###  [SentinelAI — Agent-Orchestrated Assessment-Integrity Platform](https://github.com/Stevemeg/SentinelAI)
An eleven-agent platform that ingests behavioral, browser, screen, and code-activity signals during technical assessments, correlates them into an explainable risk score, and routes uncertain cases to human review rather than auto-deciding. Built on a Ports & Adapters (hexagonal) architecture, with every agent wrapping an already-tested domain service. Migrated from a linear nine-module pipeline to a fully orchestrated agent runtime — with the migration itself documented as a first-class architecture decision.

**Highlights:** 11 implemented agents · TreeSHAP-based explainability on every decision · Keycloak OAuth2 PKCE + Vault Transit-signed JWTs · 1,287 backend test cases passing · 13 formal Architecture Decision Records · CI/CD with 8-stage pipeline (lint → tests → security scan → canary → soak/load)

`Python` `FastAPI` `React/TypeScript` `PostgreSQL` `Keycloak` `Vault` `OpenTofu` `Kubernetes` `Multi-Agent Systems`

---

###  [Universal AI Job Acquisition Agent](https://github.com/Stevemeg/ai-job-agent)
A career-intelligence platform that parses a resume, scores it honestly across six explainable dimensions, sources real jobs from legal ATS APIs (Greenhouse + Ashby), and ranks them with a fully decomposed, explainable weighted score — then tailors a resume per job through a deterministic hallucination validator that catches fabricated tools or metrics before they ship.

**Highlights:** 3,875 deduplicated real jobs sourced from legal ATS APIs · 91/100 Resume Health Score on test profile · hallucination validator with 0 false positives on truthful rewrites · dual LLM backend (Ollama locally, Groq in production) · 68-test suite, green in CI · 13 REST endpoints

`Python` `FastAPI` `PostgreSQL` `Streamlit` `Ollama` `Groq` `Docker` `sentence-transformers`

---

###  [Medical AI Copilot — RAG Clinical Assistant](https://github.com/Stevemeg/medical-ai-copilot) · [Live Demo](https://medical-ai-copilot-usov2kkptkqwcbpgzappudd.streamlit.app/)
A retrieval-augmented clinical assistant that answers questions strictly from indexed medical guidelines (NICE, WHO, MoH, CDC), fuses hybrid FAISS + BM25 retrieval via Reciprocal Rank Fusion, cites page-level sources for every answer, and writes every interaction to a tamper-evident, hash-chained audit log.

**Highlights:** dual-index retrieval (clinical vs. anatomy) selected per-query · self-contradiction fix verified with a before/after eval set · relevance gate that skips the LLM call entirely for out-of-scope questions · deployed on Streamlit Community Cloud

`Python` `LangChain-style RAG` `FAISS` `BM25` `Groq (Llama 3.1)` `Streamlit` `SQLite`

---

###  [Synthetic Medical Data Generation Suite](https://github.com/Stevemeg/Synthetic-Data)
An end-to-end synthetic data pipeline spanning three medical data modalities — imaging (DCGAN/cGAN for MRIs, X-rays, skin lesions), clinical tabular data (TabDDPM, CopulaGAN), and genomic gene-expression profiles (TVAE) — generating privacy-safe data with zero real patient information, evaluated with SSIM and SDV Quality/Diagnostic reports.

**Highlights:** synthetic data generated across all 9 source datasets · SDV-validated distribution and feature-correlation matching · downstream models trained on synthetic data performed comparably to real data

`Python` `PyTorch` `SDV` `TVAE` `CopulaGAN` `TabDDPM` `DCGAN`

---

###  [Deep Multimodal VQA](https://github.com/Stevemeg/Deep-Multimodal-VQA)
A Visual Question Answering system with a custom cross-attention fusion architecture built from scratch — frozen CLIP vision features and fine-tuned DistilBERT language features refined across three cross-attention layers — trained and evaluated on the VQA v2 benchmark, with per-answer-type accuracy breakdown and attention heatmap visualization for interpretability.

**Highlights:** ~65% Top-5 accuracy on VQA v2 subset · CLS-to-patch attention heatmaps for model interpretability · structured failure-analysis logging, not just an accuracy number · production-style CLI inference tool

`Python` `PyTorch` `CLIP` `DistilBERT` `Cross-Attention` `OpenCV`

---

## Certifications

| Certificate | Issuer | Date | Verify |
|---|---|---|---|
| **ML Statistical Foundations Professional Certificate** | Wolfram Research / LinkedIn Learning | Nov 2025 | ID: d57615d3 |
| Data Analysis with Tableau | Tableau / Coursera | Nov 2024 | [✓ Verify](https://coursera.org/verify/0UUM3W2VA43K) |
| Intro to Operating Systems & Hardware | Illinois Tech / Coursera | Dec 2024 | [✓ Verify](https://coursera.org/verify/BQNC0VCW4T7T) |
| Programming Fundamentals in Kotlin | Meta / Coursera | Nov 2024 | [✓ Verify](https://coursera.org/verify/XWMQH4BRHS2N) |
| Learn JavaScript | Scrimba / Coursera | Mar 2024 | [✓ Verify](https://coursera.org/verify/F89MKQZW7RFE) |
| Python for Beginners | Coursera | Jan 2024 | [✓ Verify](https://coursera.org/verify/DNYB4HNC9QH3) |

---

## What I'm Currently Learning

- Production patterns for multi-agent orchestration — event buses, tool registries, human-approval chains
- Fine-tuning LLMs with LoRA/QLoRA on domain-specific datasets
- MLflow & Weights and Biases for experiment tracking
- Cloud deployment of full-stack AI systems (Kubernetes, OpenTofu/Terraform)
- Advanced GAN architectures: StyleGAN, Conditional GANs, Diffusion Models

---

## Specializations

```
Agentic AI & Multi-Agent Orchestration    Retrieval-Augmented Generation (RAG)
Explainable AI & Human-in-the-Loop        Multimodal AI & VQA
Synthetic Data Generation                 Medical Image Synthesis (GANs)
Genomic & Tabular Data Modeling           Career/Job-Intelligence Systems
```

---

## Goal

> *"To build large-scale AI systems that are as trustworthy as they are capable — grounded, explainable, and honest about their own limitations — while solving real-world data bottlenecks with generative AI."*

---

<div align="center">

**Let's connect and build something impactful.**

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kona-bharath-vamshidhar-reddy/)

</div>

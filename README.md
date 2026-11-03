
# Madhav Mohan

### Senior Machine Learning Engineer @ Quantiphi | NVIDIA Certified | GenAI • LLMs • AI Infrastructure

Building production-grade AI systems, distributed GenAI infrastructure, LLM gateways, event-driven RAG pipelines, and multi-agent architectures.

<p align="left">
  <a href="https://linkedin.com/in/mohan60">
    <img src="https://img.shields.io/badge/LinkedIn-Madhav_Mohan-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:madhavm60@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/maddy333">
    <img src="https://img.shields.io/badge/GitHub-maddy333-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=900&lines=Senior+Machine+Learning+Engineer;Production+AI+%26+GenAI+Systems;LLM+Infrastructure+%7C+Agentic+AI;Distributed+RAG+%7C+LLMOps;AWS+%7C+Kubernetes+%7C+Terraform" />
</p>

---

# About Me

I am a **Senior Machine Learning Engineer at Quantiphi**, focused on engineering scalable, production-ready AI and Generative AI systems.

I am an **NVIDIA NCA-GENL Associate certified professional**, with interests spanning machine learning, large language models, distributed systems, AI infrastructure, and intelligent autonomous systems.

My engineering focus includes:

- Production-grade LLM applications and inference infrastructure.
- Self-hosted LLM inference, gateways, semantic caching, and FinOps.
- Event-driven RAG pipelines with Kubernetes-native autoscaling.
- Multi-agent orchestration with durable execution and human-in-the-loop controls.
- Fine-tuning open-source LLMs using QLoRA and PEFT.
- Cloud-native AI infrastructure and Infrastructure as Code.
- Distributed data processing, retrieval systems, and model-serving optimization.

I enjoy working at the intersection of **machine learning, distributed systems, and software infrastructure**, transforming AI capabilities into reliable production applications.

---

# Professional Experience

### Senior Machine Learning Engineer
**Quantiphi**

Currently working on machine learning and AI engineering, with a focus on building and deploying intelligent systems.

Core professional domain:

- Machine Learning Engineering
- Generative AI and LLM Applications
- AI Systems Engineering
- Production AI Infrastructure
- Model Deployment and Optimization

*Specific project responsibilities and measurable business outcomes can be added as they are confirmed.*

---

# Technical Impact

| Metric | Result |
|---|---:|
| LLM Inference Latency (12M+ users) | **Sub-15ms P99** |
| LLM Vendor Cost Eliminated | **$3,000/month** |
| Environment Provisioning Time | **5 hrs → Under 2 min** |
| JSON Schema Compliance | **65% → 98%** |
| Video Retrieval Accuracy | **96%** |
| Production Uptime | **99.9% over 18 months** |

*Metrics represent the respective projects and systems described in this profile, not necessarily Quantiphi deliverables.*

---

# Featured Projects

## 1. Distributed RAG Pipeline
### Event-Driven Ingestion with KEDA Autoscaling

Production-oriented RAG ingestion architecture decoupling document uploads from AI processing using Kafka and Kubernetes event-driven autoscaling.

**Highlights**
- FastAPI ingestion gateway.
- Kafka event streaming and semantic chunking.
- Kubernetes and KEDA autoscaling based on consumer lag.
- Dead-letter queues for fault tolerance.
- Terraform and Helm deployment.

**Stack**

`Python` `FastAPI` `Apache Kafka` `Kubernetes` `KEDA` `Qdrant` `Terraform` `Helm`

**Repository:** https://github.com/maddy333/kafka-keda-rag-pipeline

---

## 2. GenAI Gateway
### Multi-Region Active-Active LLM Routing

Enterprise-oriented LLM gateway architecture with semantic caching, per-tenant budget enforcement, and circuit-breaker failover.

**Highlights**
- SHA-256-based caching.
- Per-tenant FinOps budget enforcement.
- Circuit-breaker failover between self-hosted vLLM and OpenAI.
- Asynchronous architecture using pooled HTTPX clients.
- OpenTelemetry and Prometheus observability.

**Stack**

`Python` `FastAPI` `Redis` `HTTPX` `OpenTelemetry` `Prometheus`

**Repository:** https://github.com/maddy333/gateway

---

## 3. Agentic AI
### Autonomous Multi-Agent Control Plane (HITL)

Multi-agent orchestration framework using Temporal.io for durable execution and LangGraph for structured agent workflows.

**Highlights**
- Temporal.io durable, crash-resilient workflows.
- LangGraph agents as structured state machines.
- Human-in-the-loop safety overrides.
- Multi-tenant PostgreSQL audit logging.

**Stack**

`Python` `Temporal.io` `LangGraph` `FastAPI` `SQLAlchemy` `PostgreSQL`

**Repository:** https://github.com/maddy333/agentic_AI

---

## 4. Fencing-LLM
### QLoRA Fine-Tuning for Edge Inference

Fine-tuned and optimized LLM deployment for resource-constrained environments.

**Results**

| Metric | Before | After |
|---|---:|---:|
| JSON Compliance | 65% | 98% |
| VRAM Usage | 5.8 GB | 1.6 GB |
| Throughput | 22 tok/s | 45 tok/s |

**Stack**

`QLoRA` `LoRA` `PEFT` `CUDA` `MLflow` `Transformers`

**Repository:** https://github.com/maddy333/fencingllm

---

## 5. Vector
### Distributed Real-Time Retrieval Engine

Distributed retrieval architecture using CDC ingestion, hybrid dense and sparse search, and live embedding-model migration.

**Highlights**
- Debezium → Kafka CDC ingestion.
- Qdrant dense vector search.
- OpenSearch BM25 retrieval.
- Reciprocal rank fusion.
- Zero-downtime embedding-model migration.

**Stack**

`Python` `Kafka` `Debezium` `Qdrant` `OpenSearch` `FastAPI` `asyncpg`

**Repository:** https://github.com/maddy333/vector

---

## 6. Terraform AI Platform
### Production AI Infrastructure Blueprint

Modular Terraform infrastructure for production AI workloads on AWS.

**Highlights**
- EKS, RDS, Redis, and Application Load Balancer.
- IAM security and private networking.
- Multi-tenant environment separation.
- GitOps-ready Helm deployment framework.

**Results**
- 90% faster infrastructure provisioning.
- 15% infrastructure cost savings.

**Stack**

`Terraform` `AWS EKS` `RDS` `Redis` `ALB` `IAM`

**Repository:** https://github.com/maddy333/terraform-aws-ai-platform

---

# Technical Expertise

### AI / Machine Learning

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow" />
</p>

- Machine Learning and Deep Learning
- Generative AI and LLM Applications
- Agentic AI and Multi-Agent Systems
- Retrieval-Augmented Generation (RAG)
- Hybrid and Semantic Search
- LangGraph and LangChain
- Qdrant, FAISS, ChromaDB, OpenSearch
- OpenAI and Anthropic APIs

### LLM Engineering & LLMOps

- vLLM and Ollama
- LLM Inference Optimization
- QLoRA, LoRA, and PEFT
- Fine-Tuning Open-Source LLMs
- CUDA and GPU Optimization
- MLflow and Weights & Biases
- RAGAS and LLM Evaluation
- Semantic Caching and Model Routing

### Cloud & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=aws,kubernetes,docker,terraform,linux,githubactions" />
</p>

- AWS EKS and Cloud Infrastructure
- Kubernetes, KEDA, and HPA
- Docker and Helm
- Terraform and Infrastructure as Code
- Apache Kafka
- Temporal.io
- Redis
- Prometheus and Grafana
- OpenTelemetry
- CI/CD and GitOps

### Data Engineering & Backend

- Apache Spark
- Apache Kafka
- Debezium and CDC
- SQL and PostgreSQL
- FastAPI
- Async Python
- Databricks
- Azure

---

# Certifications

<p>
  <img src="https://img.shields.io/badge/NVIDIA-NCA--GENL_Associate-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-Data_Engineer_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft-DP--203-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
</p>

- NVIDIA NCA-GENL Associate
- AWS Data Engineer Associate
- Microsoft DP-203: Azure Data Engineer Associate

---

# GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=maddy333&show_icons=true&count_private=true&theme=tokyonight" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maddy333&layout=compact&theme=tokyonight" />
</p>

---

# Current Focus

- Advanced LLM Systems Engineering
- Agentic AI and Multi-Agent Orchestration
- Distributed RAG Infrastructure
- LLM Gateways and Cost-Aware Routing
- Model Fine-Tuning and Inference Optimization
- Kubernetes-Native AI Platforms
- AI Evaluation, Observability, and Reliability
- Scalable Production Machine Learning Systems

---

<p align="center">
  <b>Building intelligent systems. Engineering for scale. Turning AI into production.</b>
</p>

<p align="center">
  <a href="https://linkedin.com/in/mohan60">LinkedIn</a> •
  <a href="https://github.com/maddy333">GitHub</a> •
  <a href="mailto:madhavm60@gmail.com">Email</a>
</p>

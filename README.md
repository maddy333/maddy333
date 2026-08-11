<div align="center">

# Madhav Mohan

### AI Engineer • GenAI Engineer • LLM Engineer • AI Platform Engineer

Production GenAI infrastructure: LLM gateways, event-driven RAG pipelines, and multi-agent systems serving millions of users at sub-15ms latency.

<p>
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

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=900&lines=Production+AI%2FGenAI+Engineer;LLM+Gateways+%7C+Agentic+Systems;Event-Driven+RAG+at+Scale;Fine-Tuning+Open-Source+LLMs;AWS+%7C+Kubernetes+%7C+Terraform" />

</div>

---

# About Me

I build the infrastructure that takes GenAI systems from notebooks to production, at scale.

- Self-hosted LLM inference & gateways (vLLM, semantic caching, FinOps cost control)
- Event-driven RAG pipelines with Kubernetes-native autoscaling (KEDA/HPA)
- Multi-agent orchestration with durable execution & human-in-the-loop controls
- Fine-tuning open-source LLMs with QLoRA/PEFT for edge deployment
- Infrastructure as Code on AWS/Kubernetes (Terraform, Helm)

---

# Impact

<div align="center">

| Metric | Result |
|----------|----------|
| LLM Inference Latency (12M+ users) | **sub-15ms P99** |
| LLM Vendor Cost Eliminated | **$3,000/month** |
| Environment Provisioning Time | **5 hrs → under 2 min** |
| JSON Schema Compliance | **65% → 98%** |
| Video Retrieval Accuracy | **96%** |
| Production Uptime | **99.9% over 18 months** |

</div>

---

# Featured Projects

## Distributed RAG Pipeline
### Event-Driven Ingestion with KEDA Autoscaling

Production-grade RAG ingestion platform decoupling document uploads from AI processing using Kafka and Kubernetes event-driven autoscaling — the open-source blueprint behind a 12M-user, sub-15ms production pipeline.

#### Highlights
- FastAPI ingestion gateway
- Kafka event streaming + semantic chunking
- Kubernetes + KEDA autoscaling on consumer lag
- Dead-letter queue for fault tolerance
- Terraform + Helm deployment

#### Stack
`Python` `FastAPI` `Apache Kafka` `Kubernetes` `KEDA` `Qdrant` `Terraform` `Helm`

🔗 https://github.com/maddy333/kafka-keda-rag-pipeline

---

## GenAI Gateway
### Multi-Region Active-Active LLM Routing

Enterprise LLM gateway with semantic caching, per-tenant budget enforcement, and circuit-breaker failover — the blueprint behind a $3K/month cost-elimination result.

#### Highlights
- SHA-256 semantic caching ($0 cost on repeat queries)
- Per-tenant FinOps daily budget enforcement
- Circuit-breaker failover: self-hosted vLLM ↔ OpenAI
- Async architecture on pooled HTTPX client
- OpenTelemetry + Prometheus observability

#### Stack
`Python` `FastAPI` `Redis` `HTTPX` `OpenTelemetry` `Prometheus`

🔗 https://github.com/maddy333/gateway

---

## Agentic AI
### Autonomous Multi-Agent Control Plane (HITL)

Production-grade orchestrator for autonomous agent fleets, built on Temporal.io for durable execution with human-in-the-loop safety overrides.

#### Highlights
- Temporal.io durable, crash-resilient workflows
- LangGraph agents as structured state machines
- Async human-in-the-loop safety overrides
- Multi-tenant PostgreSQL audit logging

#### Stack
`Python` `Temporal.io` `LangGraph` `FastAPI` `SQLAlchemy` `PostgreSQL`

🔗 https://github.com/maddy333/agentic_AI

---

## Fencing-LLM
### QLoRA Fine-Tuning for Edge Inference

Optimized Llama deployment for resource-constrained environments.

#### Results

| Metric | Before | After |
|----------|----------|----------|
| JSON Compliance | 65% | 98% |
| VRAM Usage | 5.8 GB | 1.6 GB |
| Throughput | 22 tok/s | 45 tok/s |

#### Stack
`QLoRA` `LoRA` `PEFT` `CUDA` `MLflow` `Transformers`

🔗 https://github.com/maddy333/fencingllm

---

## Vector
### Distributed Real-Time Retrieval Engine

Zero-downtime CDC ingestion feeding hybrid dense + BM25 search, with live embedding-model migration.

#### Highlights
- Debezium → Kafka CDC ingestion pipeline
- Hybrid search: Qdrant (dense/HNSW) + OpenSearch (BM25)
- Reciprocal rank fusion
- Zero-downtime embedding-model migration

#### Stack
`Python` `Kafka` `Debezium` `Qdrant` `OpenSearch` `FastAPI` `asyncpg`

🔗 https://github.com/maddy333/vector

---

## Terraform AI Platform
### Production AI Infrastructure Blueprint

Modular Terraform IaC for production AI workloads on AWS.

#### Highlights
- EKS cluster, RDS, Redis caching, ALB
- Zero-trust IAM, private networking
- Multi-tenant environment separation
- GitOps-ready, Helm deployment framework

#### Results
- 90% faster provisioning
- 15% infrastructure cost savings

#### Stack
`Terraform` `AWS EKS` `RDS` `Redis` `ALB` `IAM`

🔗 https://github.com/maddy333/terraform-aws-ai-platform

---

# Tech Stack

### AI / GenAI

<p>
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow" />
</p>

LangGraph • LangChain • RAG (Hybrid & Semantic) • Agentic AI • Qdrant • OpenSearch • FAISS • ChromaDB • OpenAI • Anthropic

---

### LLMOps

vLLM • Ollama • QLoRA • LoRA • PEFT • MLflow • RAGAS • W&B • CUDA

---

### Cloud & Infrastructure

<p>
<img src="https://skillicons.dev/icons?i=aws,kubernetes,docker,terraform,linux,githubactions" />
</p>

AWS EKS • Kubernetes (KEDA/HPA) • Helm • Terraform • Kafka • Temporal.io • Redis • Prometheus • Grafana • OpenTelemetry

---

### Data Engineering

Spark • Kafka • Databricks • SQL • FastAPI • Azure

---

# Certifications

<p>
<img src="https://img.shields.io/badge/AWS-Data_Engineer_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Microsoft-DP--203-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
</p>

---

# GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=maddy333&show_icons=true&count_private=true&theme=tokyonight"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maddy333&layout=compact&theme=tokyonight"/>

</div>

---

# Current Focus

- LLM Gateways & Cost-Aware Routing
- Agentic AI Systems (Temporal.io, LangGraph)
- Event-Driven RAG Infrastructure
- Kubernetes-Native AI Platforms
- Evaluation & Observability

---

<div align="center">

### Open to AI Engineer • GenAI Engineer • LLM Engineer • AI Platform Engineer Opportunities

Netherlands (HSM-visa eligible) • Chennai • Bangalore • Hyderabad • Remote

</div>

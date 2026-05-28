<div align="center">

# Bahaeddine Slama

### AI / GenAI Engineer

*Building production agentic AI systems*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/baha-slama1)
[![Email](https://img.shields.io/badge/Email-0078D4?style=flat&logo=microsoft-outlook&logoColor=white)](mailto:slama.bahaeddine@outlook.com)
[![Location](https://img.shields.io/badge/Tunis%2C%20Tunisia-open%20to%20relocation-brightgreen?style=flat)](https://linkedin.com/in/baha-slama1)

</div>

---

2 years engineering production AI systems at a pan-African development finance institution. I work across the full GenAI stack from hybrid retrieval architecture and stateful LangGraph agents to QLoRA fine-tuning and LLM-as-judge evaluation pipelines. Every system I've shipped runs in a regulated banking environment where retrieval accuracy and grounding aren't optional.

---

## What I've shipped in production

| System | What it does | Key result |
|--------|-------------|------------|
| **Agentic RAG Document Intelligence** | Hybrid pgvector + BM25 retrieval, stateful LangGraph agents, VLM-based PDF ingestion over 200+ page financial contracts | 80%+ retrieval accuracy · ~40% debug time reduction |
| **Financial Document Extraction** | Layout-aware chunking via Docling, 5 async prompt templates per clause category, Kafka-parallelized across contract corpora | 35% accuracy gain over OCR baseline · 40% compliance review time saved |
| **LLM Fine-tuning Pipeline** | QLoRA/PEFT fine-tuning of Llama 3 & Mistral 7B on 100K+ domain samples, 8-class intent router | ~90% NL-to-SQL accuracy · ~30% financial terminology gain · −45% misdirected queries |
| **Intelligent Client360 Agent** | MCP protocol connecting LLM to CRM, DWH, and loan databases via AWS Bedrock for real-time client analytics | ~60% reduction in analyst report prep time |
| **African News Analytics Platform** | Async scraping pipeline (500+ articles/day, 20+ sources), sentiment analytics, geopolitical risk monitoring | Real-time bank reputation tracking across African markets |

---

## Technical focus areas

**Agentic RAG & Retrieval**
Hybrid dense-sparse retrieval · Reciprocal Rank Fusion · LangGraph stateful agents · HyDE query rewriting · Multi-turn context management · Retrieval evaluation (RAGAS, LLM-as-judge)

**LLM Fine-tuning & Adaptation**
QLoRA / LoRA / PEFT · SFT on domain corpora · NL-to-SQL · Intent classification · HuggingFace Transformers · Llama 3 · Mistral 7B

**Document Intelligence**
VLM-based PDF parsing (Gemini on Vertex) · Layout-aware chunking · Docling · AWS Textract · Contextual retrieval anchors

**Observability & Evaluation**
Langfuse · LangSmith · RAGAS · LLM-as-judge pipelines · Production retrieval graders · Span-level tracing

**Infrastructure & Deployment**
AWS (Bedrock, Textract, S3, Lambda, RDS) · GCP (Vertex AI) · Kafka · FastAPI · Docker · PostgreSQL + pgvector · asyncpg

---

## Stack

```
Agents & Orchestration   LangGraph · LangChain · LlamaIndex · Google ADK · MCP Protocol
LLM Fine-tuning          QLoRA · LoRA · PEFT · HuggingFace Transformers · SFT
Vector & Search          pgvector · BM25 · OpenSearch · Neptune DB · MongoDB · DynamoDB
Cloud                    AWS Bedrock · AWS Textract · S3 · Lambda · RDS · GCP Vertex AI
Serving & APIs           FastAPI · Docker · Kafka · Flask
Observability            Langfuse · LangSmith · RAGAS
Languages                Python · SQL
```

---

## Repositories

> Production source code is proprietary. These repos document the architecture, design decisions, and evaluation methodology of systems I built — including sequence diagrams, ADRs, retrieval ablations, and failure mode analysis.

| Repo | What's inside |
|------|--------------|
| [Agentic-RAG-Document-Intelligence](https://github.com/BahaSlama1/Agentic-RAG-Document-Intelligence) | System architecture · LangGraph agent design · Hybrid retrieval implementation · LLM-as-judge eval pipeline · 5 ADRs |
| [LLM-Finetuning-Pipeline](https://github.com/BahaSlama1/LLM-Finetuning-Pipeline) | QLoRA training walkthrough · Benchmark results · Config-driven pipeline · Model comparison |
| [Financial-Document-Extraction](https://github.com/BahaSlama1/Financial-Document-Extraction) | Async Kafka architecture · Prompt template design · Docling + Textract pipeline |



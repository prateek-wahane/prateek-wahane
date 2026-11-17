# Prateek Wahane

Solution architect with 16 years in enterprise commerce platforms (Java/Spring, microservices, AWS/GCP), now building **hands-on, measurable generative-AI systems**: RAG, agents and evaluation.

Every project below is small enough to run on a laptop, uses synthetic or public data, and reports **measured** quality, latency and cost. Each one also includes architecture decision records and a path-to-production plan.

## Portfolio

| Project | Problem | What it shows | Status |
|---|---|---|---|
| [**ShopAssist: evaluation-driven RAG**](https://github.com/prateek-wahane/shopassist-agentic-rag) | *Operating* RAG: how do you prove each change made answers better? | Versioned golden datasets, saved runs, before/after comparison, hybrid BM25 + dense retrieval with reranking, CI eval gate | Built, results being recorded |
| [**RAG Eval Workbench**](https://github.com/prateek-wahane/rag-eval-workbench) | *Designing* RAG: which choices matter, and what does quality cost? | Chunking × embedding study, validated citations, "I don't know" on unanswerable questions, Claude vs free local model on quality, latency and $ | Published; answer-quality results in progress |
| [**Payment Architecture Portfolio**](https://github.com/prateek-wahane/payment-architecture-portfolio) | Checkout that survives retries, duplicates and partial provider failure | Seven case studies: idempotency, ledger, reconciliation, observability, remediation runbooks | Published |
| **Agentic Data Assistant** | Analysts need governed natural-language access to inventory data | LangGraph flow: routing → schema retrieval → validated read-only queries → explanation; PII masking, approvals, tracing | Planned |
| **PR Review Agent** | Code review is slow and inconsistent | Planner / reviewer / security agents in GitHub Actions, Semgrep, tool allowlists, prompt-injection tests | Planned |
| **QLoRA Attribute Extractor** | Extract product attributes from free text cheaply | QLoRA fine-tune of a 1.5B model vs prompting baseline: accuracy, latency, cost | Planned |

## How I build

- **Evidence first:** every claim in a README links to a results file that anyone can regenerate.
- **Architecture as a deliverable:** ADRs, trade-offs, security and cost are written down, not implied.
- **Runs anywhere:** a free local-model path (Ollama) plus a hosted-model path (Claude / Groq).

## Stack

Python · LangGraph / LangChain · Claude · Ollama · FAISS / Qdrant · fastembed · FastAPI · PostgreSQL · Docker · GitHub Actions · AWS · GCP · Java / Spring Boot · Kafka · Kubernetes

## Certifications

Google Cloud Professional Cloud Architect · AWS Solutions Architect – Associate · TOGAF 9.2 · Certificate in Generative AI (IIT Delhi)

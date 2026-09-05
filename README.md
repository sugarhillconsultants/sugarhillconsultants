## Sugar Hill Consultants — MLOps & Security-AI Portfolio

Seven projects, each deployed and verified against live infrastructure — not just written and assumed to work. Every repo documents the real production incidents hit along the way, with root cause and fix, rather than presenting a cleaned-up version of events.

### 🤖 Multi-Agent Security Operations Platform

The capstone — ties the other six projects together as real, live tools.

An orchestrator delegating to specialist agents that call Projects 1, 5, and 6 as real MCP tools, gated by a pre-dispatch authorization layer that decides whether to even attempt a request — not just filtering results after the fact. Includes a real, Claude-API-based prompt-injection guardrail and agent-reasoning layer.

View repo → · 11 documented incidents, including live integrations with three other projects in this portfolio, all resolved

### 🔒 Secure Data Fusion Platform

Cell-level security enforcement (Apache Accumulo) proven against a real Spark-fused threat intelligence pipeline — ZooKeeper, HDFS, Accumulo, and Spark, surviving genuine VM restarts with zero manual intervention, plus a live, non-simulated proof that a restricted analyst account sees exactly the data it's cleared for.

View repo → · 26 documented incidents, all resolved

### 🔍 Enterprise RAG Platform

Hybrid BM25 + vector retrieval with cross-encoder reranking, deployed live with real semantic search — since extended with per-document security classification (U/S/TS) to support the Multi-Agent Platform's Threat Intel Agent, with the full clearance boundary proven against live, ingested data.

View repo → · 10 documented incidents, all resolved

### 🚀 Log Anomaly Detection Platform

JWT-secured FastAPI service serving a fine-tuned Hugging Face model, with async persistence and a live canary rollout (10%→50%→100%) gated on real-time Application Insights telemetry, with automatic rollback. Also feeds the Model Observability Dashboard and, more recently, the Multi-Agent Platform's Log Analysis Agent.

Try the live API → · 11 documented incidents, all resolved

### 📊 Model Observability & Drift Detection Dashboard

Population Stability Index drift detection and a Streamlit dashboard monitoring the classifier deployed above, with a scheduled job that auto-triggers retraining via cross-repo repository_dispatch when drift crosses threshold.

View repo → · Corrected a real model-schema mismatch found before it reached production

### 🧪 Reproducible Fine-Tuning Pipeline

LoRA fine-tuning with dataset versioning, an F1-gated model registry, and verified ONNX/PyTorch parity. Includes a real experiment showing dataset size alone doesn't improve model quality — the reason this pipeline gates on F1, not accuracy.

View repo → · 6 documented incidents, all resolved

### 🔧 Multi-Cloud MLOps Showcase

Credential-free CI/CD (OIDC) deploying one container to Azure Container Apps, Hugging Face Spaces, and an Azure ML managed endpoint via Bicep.

View repo → · 5 documented incidents, all resolved

Why these seven, together

The first six show the parts of MLOps that actually determine whether a system is trustworthy in production: infrastructure that deploys without a single stored credential, a fine-tuning pipeline that can reject its own output, a service with a real rollback mechanism instead of a hopeful deploy, monitoring that closes the loop back into retraining, retrieval that can prove what it will and won't surface, and a data platform that enforces classification at the cell level against a real distributed cluster.

The seventh asks a different question: what happens when an AI agent is the one calling all of this? Multi-agent systems are usually demoed with unrestricted tool access and no defense against manipulated inputs. This one is built the other way around — every tool call is authorized before it's dispatched, using the exact same access-control logic already proven in the Secure Data Fusion Platform, and every piece of retrieved content passes through a real, Claude-verified injection screen before it ever reaches the orchestrator's reasoning.

Across all seven repos: real deployed infrastructure, real API calls, real distributed systems — and roughly 90 total documented incidents, each one found by actually running the thing against live infrastructure and reading what it said, not assumed away.

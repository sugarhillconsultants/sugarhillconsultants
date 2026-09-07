<div align="center">

# Romeo Peay

### MLOps & Security-AI Engineer

Building production-shaped ML, LLM, and multi-agent security systems — verified against real, live infrastructure, not left as design docs.

[![Portfolio](https://img.shields.io/badge/Portfolio-8_Projects-blueviolet?style=flat-square)](https://github.com/sugarhillconsultants)
[![Incidents Documented](https://img.shields.io/badge/Incidents_Documented-~100-orange?style=flat-square)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](#)

</div>

---

Every project below is deployed against real infrastructure and documents the actual production incidents hit along the way — root cause and fix, not a cleaned-up version of events. See each repo's `docs/incidents.md` for the full, honest account.

**Core stack:**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

---

## 🔐 Security & Multi-Agent AI Systems

The most current, differentiated work — agentic systems with real defenses, and a dedicated project that attacks those defenses to prove they hold.

### [Multi-Agent Security Operations Platform](https://github.com/sugarhillconsultants/multi-agent-security-platform)
Orchestrates specialist agents that call three other projects in this portfolio as real MCP tools, gated by a pre-dispatch authorization layer that decides *whether to even attempt* a request — not just filtering results after the fact. Includes a live, Claude-verified prompt-injection guardrail and agent-reasoning layer.

![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-blue?style=flat-square)
![Claude API](https://img.shields.io/badge/Claude_API-live-D97757?style=flat-square)
![Status](https://img.shields.io/badge/Status-Verified_Live-brightgreen?style=flat-square)
![Incidents](https://img.shields.io/badge/Incidents-11_documented-orange?style=flat-square)

### [AI Red-Teaming / Adversarial AI Testing Platform](https://github.com/sugarhillconsultants/ai-redteam-platform)
Three-tier adversarial testing platform built on Microsoft's real PyRIT framework — OWASP-taxonomy testing, obfuscation attacks, the published Crescendo multi-turn technique, and agent-manipulation testing against a real planner. Found a genuine planner-level vulnerability; confirmed the target's defense-in-depth design fully contained it.

![PyRIT](https://img.shields.io/badge/PyRIT-Microsoft-5C2D91?style=flat-square)
![OWASP](https://img.shields.io/badge/OWASP-LLM_Top_10-000000?style=flat-square)
![Status](https://img.shields.io/badge/Status-Verified_Live-brightgreen?style=flat-square)
![Incidents](https://img.shields.io/badge/Incidents-12_documented-orange?style=flat-square)

### [Secure Data Fusion Platform](https://github.com/sugarhillconsultants/secure-data-fusion-platform)
Cell-level security enforcement (Apache Accumulo) proven against a real Spark-fused threat intelligence pipeline. A live, non-simulated proof that a restricted analyst account sees exactly the data it's cleared for — nothing more.

![Accumulo](https://img.shields.io/badge/Apache_Accumulo-cell--level_security-D22128?style=flat-square)
![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/HDFS-66CCFF?style=flat-square)
![Status](https://img.shields.io/badge/Status-Verified_Live-brightgreen?style=flat-square)
![Incidents](https://img.shields.io/badge/Incidents-26_documented-orange?style=flat-square)

---

## 🧠 LLM & Retrieval Engineering

Core language-model engineering: retrieval quality, evaluation, and reproducible fine-tuning.

### [Enterprise RAG Platform](https://github.com/sugarhillconsultants/enterprise-rag-platform)
Hybrid BM25 + vector retrieval with cross-encoder reranking, deployed live. Extended with per-document security classification (U/S/TS) to support the Multi-Agent Platform's Threat Intel Agent, with the full clearance boundary proven against live, ingested data.

![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-FF6F00?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-vector_search-0467DF?style=flat-square)
![Hugging Face](https://img.shields.io/badge/🤗_Hugging_Face-Spaces-FFD21E?style=flat-square)
![Status](https://img.shields.io/badge/Status-Verified_Live-brightgreen?style=flat-square)
![Incidents](https://img.shields.io/badge/Incidents-10_documented-orange?style=flat-square)

### [Reproducible Fine-Tuning Pipeline](https://github.com/sugarhillconsultants/reproducible-finetuning-pipeline)
LoRA fine-tuning with dataset versioning, an F1-gated model registry, and verified ONNX/PyTorch parity. A real experiment shows dataset size alone doesn't improve model quality — the reason this pipeline gates on F1, not accuracy.

![PEFT](https://img.shields.io/badge/PEFT-LoRA_%2F_QLoRA-FF6F00?style=flat-square)
![ONNX](https://img.shields.io/badge/ONNX-verified_parity-005CED?style=flat-square)
![Status](https://img.shields.io/badge/Status-Verified_Live-brightgreen?style=flat-square)
![Incidents](https://img.shields.io/badge/Incidents-6_documented-orange?style=flat-square)

---

## ⚙️ MLOps & Production Infrastructure

The foundation: deployment, canary rollouts, drift monitoring, and credential-free multi-cloud CI/CD.

### [Log Anomaly Detection Platform](https://github.com/sugarhillconsultants/log-anomaly-platform)
JWT-secured FastAPI service serving a fine-tuned Hugging Face model, with a live canary rollout (10%→50%→100%) gated on real-time Application Insights telemetry and automatic rollback.

[**Try the live API →**](https://ca-log-anomaly.jollymushroom-46a3b9a7.eastus.azurecontainerapps.io/docs)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Azure Container Apps](https://img.shields.io/badge/Azure_Container_Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live_Demo-brightgreen?style=flat-square)
![Incidents](https://img.shields.io/badge/Incidents-11_documented-orange?style=flat-square)

### [Multi-Cloud MLOps Showcase](https://github.com/sugarhillconsultants/multi-cloud-mlops-showcase)
Credential-free CI/CD (OIDC) deploying one container to Azure Container Apps, Hugging Face Spaces, and an Azure ML managed endpoint via Bicep — zero stored secrets.

![OIDC](https://img.shields.io/badge/OIDC-zero_stored_secrets-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Bicep](https://img.shields.io/badge/Bicep-IaC-0078D4?style=flat-square)
![Status](https://img.shields.io/badge/Status-Verified_Live-brightgreen?style=flat-square)
![Incidents](https://img.shields.io/badge/Incidents-5_documented-orange?style=flat-square)

### [Model Observability & Drift Detection Dashboard](https://github.com/sugarhillconsultants/model-observability-dashboard)
Population Stability Index drift detection and a Streamlit dashboard monitoring the classifier deployed above, auto-triggering retraining via cross-repo `repository_dispatch` when drift crosses threshold.

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![PSI](https://img.shields.io/badge/PSI-drift_detection-lightgrey?style=flat-square)
![Status](https://img.shields.io/badge/Status-Verified_Live-brightgreen?style=flat-square)

---

## Why these eight, together

The foundational projects show what actually determines whether an ML system is trustworthy in production: infrastructure that deploys without a single stored credential, a fine-tuning pipeline that can reject its own output, a service with a real rollback mechanism, monitoring that closes the loop back into retraining, retrieval that can prove what it will and won't surface, and a data platform that enforces classification at the cell level against a real distributed cluster.

The security projects ask a harder question: **what happens when an AI agent is the one calling all of this — and can its defenses actually withstand attack?** The Multi-Agent Security Platform is built with authorization checked *before* dispatch, not after. The Red-Teaming Platform then attacks it for real, using the same tooling (PyRIT, Microsoft's published Crescendo technique) the AI security industry uses in 2026 — and found a genuine vulnerability, which the layered defense contained anyway.

Roughly 100 documented incidents across all eight repos, several of which are the projects catching *their own* mistakes — false positives, flawed test controls, overclaimed results — before trusting them. That self-correcting discipline is the actual point, more than any individual technology choice.

<div align="center">

### 📊 Certifications

![Microsoft](https://img.shields.io/badge/Microsoft-AI/ML_Engineering-737373?style=flat-square&logo=microsoft&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-ML_%2F_AI_Specialization-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![ISC2](https://img.shields.io/badge/ISC²-CISSP-CC2229?style=flat-square)
![CompTIA](https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=flat-square&logo=comptia&logoColor=white)

</div>

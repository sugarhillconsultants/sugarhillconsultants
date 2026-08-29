Sugar Hill Consultants — MLOps Portfolio

Four projects, each deployed and verified against live infrastructure — not just written and assumed to work. Every repo documents the real production incidents hit along the way, with root cause and fix, rather than presenting a cleaned-up version of events.

🚀 Log Anomaly Detection Platform

The flagship — ties the other three projects together in production.

JWT-secured FastAPI service serving a fine-tuned Hugging Face model, with async persistence and a live canary rollout (10%→50%→100%) gated on real-time Application Insights telemetry, with automatic rollback.

Try the live API → · 11 documented production incidents, all resolved

🔧 Multi-Cloud MLOps Showcase

Credential-free CI/CD (OIDC) deploying one container to Azure Container Apps, Hugging Face Spaces, and an Azure ML managed endpoint via Bicep.

5 documented production incidents, all resolved.

🧪 Reproducible Fine-Tuning Pipeline

LoRA fine-tuning with dataset versioning, an F1-gated model registry, and verified ONNX/PyTorch parity. Includes a real experiment showing dataset size alone doesn't improve model quality — the reason this pipeline gates on F1, not accuracy.

6 documented production incidents, all resolved.

📊 Model Observability & Drift Detection Dashboard

Population Stability Index drift detection and a Streamlit dashboard monitoring the classifier deployed above, with a scheduled job that auto-triggers retraining via cross-repo repository_dispatch when drift crosses threshold.

Corrected a real model-schema mismatch found before it reached production.

Why these four, together

Most portfolios show one pipeline that "just worked." These four show the parts of MLOps that actually determine whether a system is trustworthy in production: infrastructure that deploys without a single stored credential, a fine-tuning pipeline that can reject its own output, a service with a real rollback mechanism instead of a hopeful deploy, and monitoring that closes the loop back into retraining — plus 32 total documented incidents across all four repos, each one found by actually running the thing against live infrastructure and reading what it said.

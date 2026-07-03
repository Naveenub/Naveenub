<div align="center">

### **Naveen Badiger**
#### `DevOps · Cloud · AI/ML · ZK Cryptography · Web3 Infrastructure`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naveen-badiger-6822b221b)
[![Portfolio](https://img.shields.io/badge/Notion-Portfolio-black?style=for-the-badge&logo=notion&logoColor=white)](https://trail-bramble-8d5.notion.site/Naveen-Badiger-DevOps-Cloud-Engineer-300b680e255b80618978c2654214a6c6)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:badigernaveen2@gmail.com)

📍 Bengaluru, Karnataka, India

</div>

---

## 🧠 Who I Am

I'm a **DevOps & Cloud Engineer** (~3 years production infra) actively crossing the frontier into **AI/ML engineering** and **ZK cryptography / Web3 infrastructure**. I build systems with CI/CD, typed code, modular architecture, and real infrastructure — not prototypes. Currently operating across:

- 🔐 **ZK Cryptography & Web3** — Groth16 provers, Circom circuits, ZK mixnets, on-chain governance, trusted setup ceremonies
- 🤖 **AI/ML & LLM Systems** — RAG pipelines, multi-agent orchestration, LLM-native DevOps, semantic retrieval
- 🗜️ **Data Engineering** — extreme-density vaults, ML-driven compression, encryption at rest, Merkle integrity
- ☁️ **Cloud & DevOps** — GCP/AWS-native, Kubernetes, Terraform, full CI/CD pipelines
- 🛒 **Product Engineering** — full-stack e-commerce platforms on GKE with Next.js + FastAPI

---

## ⚙️ Tech Stack

| Domain | Tools |
|---|---|
| ☁️ **Cloud** | GCP (GKE · Cloud Run · BigQuery) · AWS (EC2 · S3 · Lambda · API Gateway · Step Functions · CodePipeline · Rekognition) |
| 🔧 **DevOps** | Docker · Kubernetes · Helm · Terraform · GitHub Actions · ArgoCD · Jenkins · Ansible |
| 🐍 **Languages** | Rust · Python · TypeScript · Solidity · Circom · Bash · JavaScript |
| 🤖 **AI/ML** | LangChain · RAG · FAISS · ChromaDB · Claude API · HuggingFace · LoRA · MLOps |
| 🔐 **ZK / Crypto** | Groth16 · Circom · Poseidon Hash · snarkjs · Hermez Trusted Setup · Sphinx Packets · Cashu Ecash · Noise Protocol |
| 🗜️ **Data** | MsgPack · Zstd-L22 · AES-256-GCM · SHA3-256 Merkle · 39× compression |
| 🗄️ **Backend** | FastAPI · Next.js 14 · PostgreSQL · Redis · Kafka · asyncio · Celery |
| 📊 **Monitoring** | Prometheus · Grafana · ELK Stack · CloudWatch · Structured Logging |

---

## 🚀 Projects

### 🔄 Active Builds

---

#### 🔸 [zkproof-api-main](https://github.com/Naveenub/zkproof-api-main) — *Updated Jul 2026*
> **ZK Cryptography / SaaS** | Zero-Knowledge Proof Generation API Platform

FastAPI-based ZK proof-as-a-service platform with full Stripe monetization — metered PAYG billing, overage credit packs, multi-seat teams, circuit marketplace with Stripe Connect Express payouts, dunning/retention flows, and referrals. Recently shipped batched on-chain verifier calldata generation (`POST /proofs/verify-onchain/batch`) and a critical proof-verification bug fix.

`Python` `FastAPI` `Stripe` `PostgreSQL` `Redis` `ZK Proofs` `SaaS`

#### 🔸 [zksn](https://github.com/Naveenub/zksn) `v1.2.0-pre` — *Updated Apr 2026*
> **ZK Cryptography** | Zero-Knowledge Sovereign Network

Jurisdictionally-agnostic, cryptographically-sovereign P2P mixnet. Groth16 verifier with Poseidon hashing, depth-20 Merkle circuit (1M+ member cap), pot28 Hermez trusted setup via GitHub Actions, Yggdrasil 200::/7 enforced at the socket layer, anonymous on-chain governance. Audit preparation documents complete. NixOS hardware testing in progress.

![Tests](https://img.shields.io/badge/tests-227%20passing-brightgreen?style=flat-square) `Rust` `Solidity` `Circom` `Groth16` `Poseidon` `Yggdrasil` `NixOS`

---

#### 🔸 [quantum-pulse](https://github.com/Naveenub/quantum-pulse) `v1.1.3` — *Updated Mar 2026* [![PyPI](https://img.shields.io/pypi/v/quantum-pulse?style=flat-square)](https://pypi.org/project/quantum-pulse)
> **Data Engineering** | Extreme-Density Encrypted LLM Data Vault

Compress-then-encrypt vault purpose-built for LLM training sets. MsgPack + Zstd-L22 + AES-256-GCM + SHA3-256 Merkle integrity. S3 and GCS backends. **39× compression ratio** with full encryption and tamper detection at rest.

![Tests](https://img.shields.io/badge/tests-297%20passing-brightgreen?style=flat-square) ![Coverage](https://img.shields.io/badge/coverage-79%25+-blue?style=flat-square) `Python` `FastAPI` `MongoDB` `MsgPack` `Zstd` `AES-256-GCM` `S3` `GCS`

---

#### 🔸 [NullPhantom](https://github.com/Naveenub/null-phantom) `v0.2.0-alpha`
> **AI/RAG** | Enterprise RAG with Content-Addressable Integrity

Enterprise RAG system with SHA-256 content-addressable snapshot hashing, two-stage retrieval pipeline (BM25 → Claude semantic reranker → SHA-256 integrity gate), phantom detector, and append-only audit log. Grounded retrieval with provable integrity.

`Python` `LangChain` `BM25` `Claude API` `FAISS` `SHA-256`

---

#### 🔸 [GearForge](https://github.com/Naveenub/gearforge)
> **Product Engineering** | Premium Two-Wheeler Safety Accessories Platform

Full-stack e-commerce platform targeting Bengaluru — certification gate enforcing ECE 22.06 / Snell M2025 / SHARP 5-star standards only, daily freshness expiry rotation via Celery, GearCoin loyalty system, anti-counterfeit QR verification. Enterprise monorepo on GKE.

`Next.js 14` `FastAPI` `Celery` `GKE` `Terraform` `Kubernetes` `Prometheus` `Grafana`

---

#### 🔸 [forge](https://github.com/Naveenub/forge) — *Updated Feb 2026*
> **Platform** | 15-Agent AI Software Factory

Ship production software without writing a single line. Deploys 15 Claude AI agents across Architecture → Dev → Testing → Security → DevOps. Every stage governed, every artifact immutable, every decision traceable.

`Python` `FastAPI` `React` `PostgreSQL` `Redis` `Kafka` `Kubernetes` `Claude API`

---

### ✅ Complete

---

#### 🔹 [sovereign](https://github.com/Naveenub/sovereign)
> **Automation** | YouTube/Instagram Content Pipeline (novus.forge)

7-module Python automation system for faceless content: trend hunting → Claude-powered script generation → edge-tts voice synthesis → MoviePy video assembly → dual-platform upload. Powers the novus.forge content brand.

`Python` `Claude API` `MoviePy` `edge-tts` `YouTube API` `Instagram API`

---

#### 🔹 [FaceGuard](https://github.com/Naveenub/faceguard)
> **Privacy** | Biometric Privacy Shield

Biometric privacy app with liveness detection (Laplacian texture variance + EAR blink detection), hash-chained audit log, and full Vitest test suite.

`TypeScript` `face-api.js` `Vitest` `Biometrics`

---

#### 🔹 [ai-co-workspace](https://github.com/Naveenub/ai-co-workspace) — *Feb 2026*
> **AI Platform** | CodeAct Multi-Agent Dev Workspace

FastAPI backend with four specialized agent classes (Planner, Coder, Tester, Debugger), Docker sandbox executor, WebSocket streaming, and Next.js Monaco-based IDE frontend.

`Python` `FastAPI` `WebSocket` `Docker` `Next.js` `Monaco`

---

#### 🔹 [agentic-devops](https://github.com/Naveenub/agentic-devops) — *Feb 2026*
> **Flagship** | AI Agent for DevOps Incident Response

Local-first AI agent that diagnoses Kubernetes and CI/CD failures using real logs, cluster state, LLM reasoning, and RAG. Cost-aware AWS insights + automated Terraform remediation.

`Python` `LangChain` `RAG` `FAISS` `Kubernetes` `AWS` `Apache 2.0`

---

#### 🔹 [AULCE](https://github.com/Naveenub/AULCE) — *Feb 2026*
> **Research-Grade** | Adaptive Universal Lossless Compression Engine

ML-driven universal lossless compression with multi-stage pipelines, intelligent strategy selection, explainable RAG reasoning, and live evaluation benchmarks.

`Python` `ML` `RAG` `Compression Pipelines` `MIT`

---

#### 🔹 [Open-NanoScale-LLM](https://github.com/Naveenub/Open-NanoScale-LLM) — *Feb 2026*
> **Production-Minded** | Nano-Scale LLM System

Clean-room open-source nano LLM — training, RAG augmentation, tool use, evaluation harness, live demos. Grounded generation through retrieval and deterministic pipelines.

`Python` `HuggingFace Transformers` `LoRA` `RAG` `Apache 2.0`

---

#### 🔹 [Open-IoT-Industry-Security](https://github.com/Naveenub/Open-IoT-Industry-Security) — *Feb 2026*
> **IoT Security** | Industrial Edge Security Platform

Real-time, safety-first industrial IoT security system. Raspberry Pi-ready, fully Dockerized, production-grade open-source.

`Python` `Raspberry Pi` `Docker` `MQTT` `Apache 2.0`

---

#### 🔹 [MultiDoc-RAG-QA](https://github.com/Naveenub/MultiDoc-RAG-QA) — *Feb 2026*
> **Research-Grade** | Multi-Document Intelligence

Full-stack RAG QA across multiple documents. PDF/DOCX/TXT ingestion, vector DB retrieval, LLM-powered answers, explainable reasoning, evaluation metrics.

`Python` `LangChain` `FAISS` `ChromaDB` `FastAPI` `Apache 2.0`

---

#### 🔹 [Serverless-Image-Recognition](https://github.com/Naveenub/Serverless-Image-Recognition) — *Nov 2025*
> **AWS Serverless** | Lambda + Step Functions Image Pipeline

Serverless image recognition using AWS Lambda, Step Functions orchestration, and Amazon Rekognition.

`JavaScript` `AWS Lambda` `Step Functions` `Rekognition` `Apache 2.0`

---

#### 🔹 [aws-CodePipeline-s3-codedeploy-Linux](https://github.com/Naveenub/aws-CodePipeline-s3-codedeploy-Linux) — *Mar 2025*
> **AWS DevOps** | Full CI/CD Deployment Pipeline

End-to-end AWS deployment pipeline: CodePipeline → S3 → CodeDeploy on Linux. Zero-downtime deployments.

`HTML` `AWS CodePipeline` `S3` `CodeDeploy` `Apache 2.0`

---

## 📊 GitHub Stats

<div align="center">

![Naveen's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Naveenub&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&cache_seconds=86400&rank_icon=github)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Naveenub&layout=compact&theme=tokyonight&hide_border=true&cache_seconds=86400&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=Naveenub&theme=tokyonight&hide_border=true)

</div>

---

## 📫 Reach Me

| | |
|---|---|
| 🔗 **Portfolio** | [Notion Resume](https://trail-bramble-8d5.notion.site/Naveen-Badiger-DevOps-Cloud-Engineer-300b680e255b80618978c2654214a6c6) |
| 💼 **LinkedIn** | [naveen-badiger-6822b221b](https://www.linkedin.com/in/naveen-badiger-6822b221b) |
| 📧 **Email** | badigernaveen2@gmail.com |
| 📍 **Location** | Bengaluru, Karnataka, India |

---

<div align="center">

*Building in public. Shipping with proof. Owning the stack.*

</div>

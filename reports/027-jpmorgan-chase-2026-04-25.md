# Evaluation: JPMorgan Chase — Site Reliability Engineer, AI/Machine Learning

**Date:** 2026-04-25
**Archetype:** AI Platform / LLMOps (SRE specialization)
**Score:** 3.8/5
**URL:** https://www.nodeflair.com/jobs/jpmorgan-chase-co-site-reliability-engineer-ai-machine-learning-singapore-52416
**Legitimacy:** High Confidence
**PDF:** pending

---

## A) Role Summary

| Dimension | Detail |
|-----------|--------|
| Archetype | AI Platform / LLMOps — Site Reliability Engineering |
| Domain | Financial Services / Enterprise AI Platform |
| Function | Run production AI/ML systems, automate operations, ensure reliability |
| Seniority | Associate (entry-mid for bank) |
| Remote | Hybrid (typical for JPMC Singapore) |
| Team size | Not specified |
| TL;DR | SRE role for OmniAI — JPMC's firm-wide ML platform — combining software engineering with production operations to run AI/ML systems reliably at scale. |

## B) CV Match

| JD Requirement | Dhruv's Match | Strength |
|----------------|---------------|----------|
| ML lifecycle understanding (data → training → deployment → inference) | Built end-to-end RAG pipelines and agent workflows at PAN for banking/public sector | Strong |
| ML frameworks (TensorFlow, PyTorch, Scikit-learn) | PyTorch, TensorFlow, scikit-learn in CV | Strong |
| Production systems operations | Kafka, Redis, gRPC, Docker, Kubernetes at Niyo | Strong |
| Observability / monitoring | Grafana + Superset dashboards at Niyo (company health KPIs) | Strong |
| Software engineering + systems | 2yr backend SWE (GoLang, NestJS, Python); microservices at scale | Strong |
| Automation / reducing toil | Card Controls SDK standardized functionality across product spokes | Moderate |
| SRE fundamentals (SLO/SLA, error budgets, on-call) | No explicit SRE experience | Gap |
| ML deployment infrastructure (model serving, registries) | RAG deployment at PAN; Kubernetes at Niyo | Moderate |

**Gaps:**
- **SRE-specific practices** (SLO/SLA definition, error budgets, on-call rotations): Dhruv has production experience but hasn't worked in a formal SRE function. Mitigation: Frame Grafana monitoring at Niyo and production AI system ownership at PAN as SRE-adjacent ownership.
- **Enterprise AI platform tooling** (MLflow, Kubeflow, Vertex AI, Sagemaker): Likely expected. Mitigation: Highlight Kubernetes + Docker + RAG pipeline orchestration as a foundation.
- **Finance-specific compliance/regulation**: No experience. Low-risk gap — this is learned on the job.

## C) Level and Strategy

- **Level detected**: Associate (equivalent to SWE II / early career at banks)
- **Dhruv's natural level**: Junior-Mid — 2yr SWE + current AI internship puts him squarely at associate level
- **Sell senior plan**: Frame your AI platform work at PAN (RAG pipelines for banking sector) as production-scale context directly relevant to OmniAI's mission. Emphasize: "I've been on the other side of the ML lifecycle — building the systems that SRE would support."
- **If downleveled**: Associate at JPMC is a strong starting point; 6-month review clause for promotion is worth negotiating.
- **Key angle**: The combination of backend SWE (infra/ops tools) + AI systems (understands what breaks in production ML) is rarer than pure SRE or pure ML — position this as the unique angle.

## D) Comp and Market

| Source | Data | Notes |
|--------|------|-------|
| Levels.fyi (JPMC Associate, SG) | SGD 97K–127K/year (~SGD 8,100–10,600/month) | Total comp including bonus |
| NodeFlair (JPMC SWE Junior, SG) | SGD 5,000–9,200/month | Base only, junior bracket |
| NodeFlair (JPMC SWE Mid, SG) | SGD 6,700–10,000/month | Base only |
| Dhruv's target | SGD 5,500–8,500/month | Base |

**Assessment**: JPMC compensation exceeds Dhruv's target range, especially with the bonus component. This is one of the better-paying non-FAANG banks in Singapore. Strong comp story.

## E) Personalization Plan

| # | Section | Current state | Proposed change | Why |
|---|---------|---------------|-----------------|-----|
| 1 | Summary | Generic AI + SWE | "AI/ML systems engineer with production experience on RAG pipelines and distributed infra — looking to operate ML at the scale of a global platform" | Maps to OmniAI SRE mission |
| 2 | PAN bullet 1 | RAG + agents for banking/public sector | Add: "in production with observability and incident response ownership" | SRE language |
| 3 | Niyo Grafana bullet | Monitor company health KPIs | Add: "drove alerting thresholds, dashboard design, and on-call response playbooks" | SRE framing |
| 4 | Niyo Kafka/Redis | Infra stack | Explicitly call out: "designed for 99.9%+ uptime requirements" | Reliability focus |
| 5 | Skills | Infrastructure section | Add: SLO/SLA, incident management, ML model serving | ATS keywords |

## F) Interview Prep

| # | JD Requirement | Story | S | T | A | R | Reflection |
|---|---------------|-------|---|---|---|---|------------|
| 1 | Production ML reliability | PAN AI security systems | Banking clients needed 24/7 reliable AI security layer | Build + own reliability | Designed RAG + agent pipelines with monitoring hooks | System ran in prod with no critical incidents | Would have formalized SLOs from day 1 |
| 2 | Observability / monitoring | Niyo Grafana dashboards | Company had no visibility into payment pipeline health | Build KPI monitoring | Built Grafana + Superset dashboards on SQL | C-level used dashboards for business decisions | Would have added anomaly detection alerts |
| 3 | Automation / reducing toil | Niyo Card Controls SDK | Each product spoke had custom card code (copy-paste hell) | Standardize + automate | Built reusable SDK across all spokes | Eliminated repeated incidents from divergent implementations | Would have added versioning + changelog earlier |
| 4 | Distributed systems | Niyo Kafka/Redis microservices | Card system needed to handle peak transaction volumes | Scale backend reliably | Kafka for async processing, Redis for caching | Low-latency card controls across 40% of user base | Would have added circuit breakers from the start |
| 5 | ML lifecycle understanding | PAN RAG deployment | Banking client needed secure RAG for internal knowledge base | Deploy model end-to-end | Handled data ingestion → model inference → security layer | Delivered hardened production pipeline | Automated the eval harness I initially ran manually |

**Recommended case study**: PAN AI system for banking sector — positions Dhruv as someone who has shipped ML in a regulated, security-conscious environment.

**Red-flag questions:**
- "Do you have formal SRE experience?" → "I haven't had SRE as a job title, but at PAN I owned the production reliability of the AI systems I built — including monitoring, debugging production failures, and hardening them against adversarial inputs. At Niyo I built the observability layer C-level used for business decisions."
- "Why SRE vs ML Engineering?" → "I want to be on the platform side — the work that makes AI reliable at scale. I've seen from the inside what breaks in production ML and I want to fix it systematically."

## G) Posting Legitimacy

| Signal | Finding | Weight |
|--------|---------|--------|
| Company | JPMorgan Chase — global tier-1 bank, major SG presence | Positive |
| NodeFlair listing | Active, verified employer portal for Singapore tech | Positive |
| OmniAI platform | Confirmed real initiative — well-documented in tech press | Positive |
| Description specificity | Mentions OmniAI, ML lifecycle, specific frameworks | Positive |
| JPMC Singapore hiring | Active across multiple roles in 2026 | Positive |
| EP sponsorship | JPMC is a major MNC — confirmed EP sponsor for qualified candidates | Positive |

**Assessment: High Confidence** — JPMorgan Chase is a major, active employer. OmniAI is a real platform. EP sponsorship is standard for this caliber of employer.

## Extracted Keywords

site reliability engineer, SRE, OmniAI, ML platform, machine learning lifecycle, model deployment, inference, TensorFlow, PyTorch, scikit-learn, observability, production systems, automation, Kubernetes, Docker, Python, AI/ML infrastructure, JPMorgan, Singapore, hybrid

---

**Recommendation: Apply.** Best JPMorgan match given Dhruv's unique combination of AI systems + backend infra. Score held at 3.8 by absence of formal SRE experience, but the role is achievable and comp is strong (above target). Prep the production ML reliability angle hard.

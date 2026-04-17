# Evaluation: Grab — Lead Machine Learning Platform Engineer

**Date:** 2026-04-17
**Archetype:** AI Platform / LLMOps
**Score:** 3.0/5
**URL:** https://www.grab.careers/en/jobs/744000104833132/lead-machine-learning-platform-engineer/
**Legitimacy:** High Confidence
**PDF:** pending

---

## A) Role Summary

| Dimension | Detail |
|-----------|--------|
| Archetype | AI Platform / LLMOps |
| Domain | ML Infrastructure / MLOps |
| Function | Build MLOps pipelines, CI/CD for ML, model deployment tooling |
| Seniority | Lead (5+ years required) |
| Remote | On-site, Singapore |
| Team size | Not specified |
| TL;DR | Own the ML platform that Grab's DS/MLE teams build on — CI/CD, data versioning, model deployment, container infra at scale |

---

## B) CV Match

| JD Requirement | CV Match | Source |
|----------------|----------|--------|
| 5+ years ML/software experience | ❌ Gap — 2+ years (SWE + AI intern) | cv.md |
| CI/CD for ML (GitLab CI, Kubeflow, MLflow) | ⚠️ Partial — used Docker; no explicit Kubeflow/MLflow listed | cv.md |
| Model versioning + containerization (Docker) | ✅ Docker in Technical Skills | cv.md |
| Cloud deployment (AWS/GCP/Azure) | ✅ AWS in Technical Skills | cv.md |
| Build data pipelines for model training | ✅ RAG pipelines + agent workflows at PAN | cv.md, article-digest.md |
| Mentor engineers, code/design reviews | ⚠️ Partial — TA at NUS (mentored 100+ students), not engineering context | cv.md |
| Partner with modeling engineers | ✅ Collaborated cross-functionally at PAN | cv.md |
| Production ML systems | ✅ Production AI systems at PAN for banking/public sector | cv.md |
| Kafka / streaming data | ✅ Kafka at Niyo (SDUI framework) | cv.md, article-digest.md |

**Gaps:**
1. **5+ years experience (hard gap)** — Dhruv is 3 years short. Lead = Staff-equivalent at Grab.
2. **MLflow/Kubeflow explicitly** — Not in CV. Adjacent experience exists (Docker, AWS, pipelines) but not specifically ML workflow tooling.
3. **Scale** — Grab's ML platform serves hundreds of engineers. Dhruv's production systems at PAN are enterprise-grade but smaller scale.

**Mitigation:**
- MLflow/Kubeflow: Can learn and demonstrate in a quick side project before applying.
- Scale: Frame PAN work as "built and operated production ML pipelines for banking and public sector clients."
- Experience gap: Hardest to bridge. Lead roles at Grab typically expect IC3/IC4 equivalent (5-7yr). This is a stretch.

---

## C) Level and Strategy

**Level detected:** Lead (Grab IC3–IC4, likely 5-7yr equivalent).
**Dhruv's natural level:** IC1–IC2 (2yr total exp). 2-3 levels below Lead.

**"Sell senior without lying":**
- Lead with: "Built and shipped production AI systems (RAG, agents) at Palo Alto Networks while simultaneously completing an MS in AI."
- Emphasize: Cross-functional scope at PAN (built, secured, and demoed AI systems to clients).
- Frame: "I operate at the level of someone 3-4 years more experienced because I've been on production AI systems from day one at PAN."

**"If downleveled":** If Grab has a Senior MLE Platform role, that's a better target. Check for Senior MLE (Business Observability and Insights) — 744000104834130 — as a realistic alternative.

---

## D) Comp and Market

| Source | Range (SGD/month) | Notes |
|--------|-------------------|-------|
| Glassdoor — MLE at Grab SG | SGD 7,000–11,000 | Senior band |
| Glassdoor — Lead/Senior DS at Grab | SGD 9,000–13,000 | Lead band |
| Levels.fyi — Grab SWE | SGD 115K–332K/yr | Full TC range |
| Dhruv's target | SGD 5,500–8,500/mo | Below Lead band |

Lead-level comp at Grab is above Dhruv's stated target — but the level requirement is the real barrier.

---

## E) Personalization Plan

| # | Section | Current state | Proposed change | Why |
|---|---------|---------------|-----------------|-----|
| 1 | Summary | AI security + RAG focus | Add "production MLOps, CI/CD for ML pipelines" framing | Matches platform engineer expectations |
| 2 | PAN bullet 1 | RAG pipelines / adversarial attacks | Split into two: (1) ML pipeline design, (2) security evaluation | Separates the platform work from security work |
| 3 | Technical Skills | Generalist list | Move Docker, AWS, Kafka, Redis to top group labeled "ML Infrastructure" | Makes infra depth visible immediately |
| 4 | NUS TA | Teaching context | Reframe as "mentored and guided 100+ engineers/students in data-driven systems" | Addresses mentorship expectation |
| 5 | Niyo SDUI | Backend framing | Add "built Kafka-backed event streaming pipeline" | Shows data pipeline skills |

---

## F) Interview Prep

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|----------------|--------------|---|---|---|---|------------|
| 1 | Build ML deployment infrastructure | PAN RAG pipeline | Banking/public sector needed secure, production-grade AI | Deploy end-to-end AI system for real clients | Designed RAG + agent workflow pipeline with security layers | Production system serving banking clients | Would have added MLflow-style experiment tracking from day one |
| 2 | CI/CD for ML | Niyo SDUI + Kafka | Manual deployments were blocking feature velocity | Build server-driven UI with streaming backend | Architected Kafka event streaming + Firebase state system | Eliminated app redeployment cycle for UI changes | Would apply same CI/CD principle to model versioning |
| 3 | Partner with modeling engineers | PAN cross-functional | AI security team needed both builder and red-teamer | Collaborate with different PAN product teams | Built systems AND ran adversarial evaluations for the same clients | Delivery + security feedback in one workflow | Would invest more in shared documentation to accelerate handoffs |
| 4 | Design and code review | NUS TA | 100+ student cohort, diverse skill levels | Maintain code quality across submissions | Ran technical reviews, identified common errors, created feedback templates | Students improved measurably over semester | Engineering code reviews require more depth than academic; seek mentor who does this well |

**Case study to present:** PAN production RAG pipeline — "Here's how I'd design an ML platform for a client: data ingestion, pipeline orchestration, deployment, monitoring, and security evaluation."

**Red-flag questions:**
- *"You have 2 years of experience but this is a Lead role. Why should we consider you?"* → "I've had production ML system ownership from day one at PAN, not just academic work. The timeline is compressed, but the depth is real."
- *"Why isn't MLflow/Kubeflow in your CV?"* → "I used equivalent tooling. I'm adding a hands-on Kubeflow/MLflow project to demonstrate this gap is low risk."

---

## G) Posting Legitimacy

| Signal | Finding | Weight |
|--------|---------|--------|
| Posting age | Not precisely dated; URL active, search results current Apr 2026 | Neutral |
| Apply button | Active on grab.careers | Positive |
| JD specificity | Names GitLab CI, Kubeflow, MLflow, Docker, AWS/GCP — specific tools | Positive |
| Company hiring signals | No Grab layoff signals in platform/infra teams | Positive |
| Reposting | No prior history in scan-history.tsv | Neutral |
| Role market context | Lead MLOps roles take longer to fill — niche combination of ML + infra | Explains any age |

**Assessment: High Confidence**

Active listing with technically specific JD. Grab is actively building ML platform infrastructure for its growing DS/MLE org. No red flags.

---

## Extracted Keywords

MLOps, CI/CD for ML, GitLab CI, Kubeflow, MLflow, model versioning, Docker, containerization, AWS, GCP, data pipelines, model deployment, feature store, experiment tracking, ML infrastructure, Airflow, Kafka, Python, Scala, production ML, monitoring, model serving

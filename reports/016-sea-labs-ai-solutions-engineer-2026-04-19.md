# Evaluation: Sea Labs — AI Solutions Engineer (Engineering Infrastructure)

**Date:** 2026-04-19
**Archetype:** AI Platform / LLMOps + Agentic AI
**Score:** 4.3/5
**URL:** https://career.sea.com/position/J00291233
**Legitimacy:** High Confidence
**PDF:** pending

---

## A) Role Summary

| Field | Detail |
|-------|--------|
| Archetype | AI Platform / LLMOps + Agentic AI |
| Domain | Engineering infrastructure — AI agent workflows replacing traditional ops |
| Function | Build + operate AI agent platform and infrastructure |
| Seniority | Junior-Mid ("2+ years OR fresh grads with strong fundamentals") |
| Remote | Onsite — Singapore (Sea's headquarters) |
| Team size | Engineering Infrastructure team, Sea Labs |
| TL;DR | Build the platform that makes AI agents replace manual engineering operations — RAG systems, vector stores, agent frameworks, reliability infra. Python-first, Go a plus. Accessible to Dhruv. |

---

## B) CV Match

| JD Requirement | CV Evidence | Strength |
|----------------|-------------|----------|
| Python (primary language) | Python at PAN, NTU, StoreMyStuff — primary AI language | ✅ Perfect |
| LangChain / LangGraph / agent frameworks | LangChain-style tooling at PAN; agent workflows in production | ✅ Strong |
| RAG systems + vector stores | Production RAG pipelines for banking/public sector at PAN | ✅ Strong |
| Backend cloud-ready services | Niyo: microservices, Kafka, Redis, Docker, Kubernetes | ✅ Strong |
| Go (bonus) | GoLang primary at Niyo (backend microservices) | ✅ Strong |
| Agent workflow design | Multi-agent orchestration at PAN | ✅ Strong |
| Platform reliability + observability | Grafana dashboards at Niyo; observability mindset from PAN security work | ✅ Strong |
| Middleware + caching (Redis, queues) | Redis + Kafka at Niyo | ✅ Strong |
| Capacity + resource management at scale | Not explicitly demonstrated | ❌ Minor gap |
| CS fundamentals (algorithms, networking, systems) | CS degree + MS in AI + production engineering | ✅ Strong |
| Problem-solving mindset | Hackathon win, adversarial ML, StoreMyStuff pivot | ✅ Strong |

**Gaps:**
1. **Capacity/resource management at scale:** Infra scaling at Sea's level (hundreds of services) is larger than Dhruv's experience. Minor gap — entry-level expectation.
2. **Vector store specifics:** Pinecone, Weaviate, pgvector etc. not explicitly named in CV. Implied from RAG work.

**Key insight:** This role description reads like a job posting written for Dhruv. Every major requirement maps directly to his PAN + Niyo experience. Python + LangChain + RAG + Go + agent orchestration + observability — all present and production-validated.

---

## C) Level and Strategy

**Level detected:** Entry-Mid (the JD explicitly says "2+ years OR fresh grads"). One of the most accessible well-aligned roles in this batch.
**Dhruv's level:** 2.5 years SWE + AI specialization. Above minimum requirement.

**"Sell senior" plan:**
- Frame PAN as "I've already been building exactly this." The role is about replacing ops with agents — Dhruv has done this for enterprise clients.
- Go background at Niyo is a genuine differentiator (listed as a bonus requirement).
- Observability angle: "I built and monitored production systems — I know what good observability looks like from the engineering side AND the security review side."

**Positioning statement:**
> "I built production RAG pipelines and multi-agent workflows for banking and government clients at Palo Alto Networks. I ran adversarial attacks against them to find failure modes, and I monitored them with production-grade observability. Sea Labs wants to bring that to engineering infrastructure at scale — that's the next level of what I've been building."

---

## D) Comp and Market

| Source | Data |
|--------|------|
| Nodeflair (Sea SWE Singapore) | SGD 5,700–12,500/month |
| Levels.fyi (Sea SWE Singapore) | SGD 60.8K–120K+/year |
| AI Engineer Singapore (Second Talent) | SGD 9,000–22,000+/month |
| Dhruv's target | SGD 5,500–8,500/month |

Sea's range covers Dhruv's target. AI/LLMOps premium likely pushes toward higher end. Negotiate based on PAN experience and AI specialization.

---

## E) Personalization Plan

| # | Section | Change | Why |
|---|---------|--------|-----|
| 1 | Summary | "Built production RAG pipelines and agent workflows for enterprise clients at Palo Alto Networks; shipped backend microservices at Niyo. Python + Go. Looking to build the infra that makes AI agents production-grade." | Exactly what Sea Labs is hiring for |
| 2 | PAN bullet 1 | Add "multi-agent orchestration, vector retrieval, production RAG" | Matches role's core requirements |
| 3 | PAN bullet 2 | Add "reliability engineering mindset: tested system failure modes via adversarial attacks" | Reliability + observability signal |
| 4 | Niyo | Highlight Go microservices, Redis, Kafka, Grafana observability | Matches infra/backend requirements |
| 5 | Skills | Lead with Python, GoLang — move to top of list | Python-first role, Go is bonus |

---

## F) Interview Prep

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|----------------|--------------|---|---|---|---|------------|
| 1 | Build agent workflows | **PAN multi-agent for banking** | Banking client needed multi-step AI automation | Design reliable multi-agent pipeline | Built orchestration with HITL, fallback chains, error recovery | Running in production | HITL isn't overhead — it's the architecture that makes agents safe for regulated sectors |
| 2 | RAG systems + vector stores | **PAN RAG pipeline** | Client needed AI assistant over proprietary data | Build secure RAG with enterprise guardrails | Full pipeline: ingest → chunk → embed → retrieve → generate → validate | Production for public sector client | Retrieval quality determines 80% of RAG output quality; embeddings and chunking matter more than the LLM |
| 3 | Observability | **Niyo Grafana dashboards** | Credit card team had no visibility into ops health | Build monitoring for all card KPIs | Designed Grafana dashboard used by team and C-level | Team made faster decisions; prevented 2 outages early | Observability is not a post-launch add-on — it's a design constraint |
| 4 | Backend infra | **Niyo Server-Driven UI** | Dynamic UI without app redeployments | Build SDUI POC using Kafka + Firebase | Architected event-driven rendering system | POC adopted; eliminated deploy cycle for UI changes | Infrastructure that eliminates repetitive work compounds value over time |
| 5 | Problem-solving mindset | **PAN adversarial ML** | Production AI system with unknown attack surface | Systematically find and close failure modes | Red-teamed own system across 3 attack categories | All exploitable paths mitigated before production | The engineer who can break systems is the most valuable person to have on the build team |

**Case study to present:** PAN production RAG + agent workflow — end-to-end, enterprise, adversarially hardened.

**Red-flag questions:**
- *"Sea Labs is research-heavy — you're more engineering."* → "AI Solutions Engineer is explicitly in Engineering Infrastructure. I'm building systems, not writing papers — and I have production proof points."
- *"You're a student."* → "I've been full-time at Palo Alto Networks since March 2026, building and shipping production AI systems. The student pass is administrative — my output has been engineering."

---

## G) Posting Legitimacy

**Assessment: High Confidence**

| Signal | Finding | Weight |
|--------|---------|--------|
| Official Sea careers portal | career.sea.com — authoritative | Positive |
| Foundit Indonesia mirror | Role found indexed on Foundit — evidence it's been posted and visible | Positive |
| "Engineering Infrastructure" specificity | Detailed scope: agent adoption, vector stores, RAG, observability | Positive |
| Sea AI Labs (SAIL) is a real org | SAIL is Sea's publicly known AI research and engineering arm | Positive |
| No layoff signals | Sea Group has been stabilizing and growing; no recent SG AI layoffs | Positive |
| Requirement realism | "2+ years OR fresh grads" is refreshingly honest about level | Positive |

Real, active, well-defined role. One of the strongest signal postings in this batch.

---

## Extracted Keywords

AI agent, LangChain, LangGraph, RAG, vector store, retrieval system, Python, Go, Golang, agent workflows, engineering infrastructure, platform reliability, observability, backend services, cloud, Kubernetes, Docker, Redis, Kafka, LLM, production AI, Sea Labs, SAIL, NLP, multi-agent

# Evaluation: Palantir — Backend Software Engineer

**Date:** 2026-05-01
**Archetype:** Software Engineer / AI Platform (Infrastructure)
**Score:** 3.0/5
**URL:** https://jobs.lever.co/palantir/0b2dbe51-0d9f-47ee-9f24-82bff4654048
**Legitimacy:** Proceed with Caution
**PDF:** pending

---

## A) Role Summary

| Field | Detail |
|-------|--------|
| Archetype | Software Engineer (Infrastructure) — Adjacent |
| Domain | Enterprise AI/data platform infrastructure |
| Function | Build (distributed systems, databases, app infrastructure) |
| Seniority | Mid-level (not new grad; ~2–5 years expected) |
| Location | **Unconfirmed** — general Palantir posting, may be US or multiple offices |
| Remote | Onsite preferred |
| Team | Infrastructure teams: database, distributed systems, security, app infra |
| TL;DR | Mid-level backend engineer building the lowest layers of Palantir's stack — distributed systems, databases, security primitives — underpinning Foundry and Gotham. |

---

## B) CV Match

| JD Requirement | CV Evidence | Strength |
|----------------|-------------|----------|
| Java, C++, Python, Rust | Python + Go strong; Java listed; C++ and Rust not in CV | Moderate |
| Storage + data processing systems | MongoDB/MySQL at Niyo; Kafka for data streaming (PP6) | Moderate |
| Cloud infrastructure | AWS, Docker, Kubernetes in Skills | Moderate |
| Distributed systems depth | Kafka/Redis/gRPC at Niyo — product-level, not infra-level | Weak |
| Security systems knowledge | PAN: AI security layer design, data ingestion → inference (PP2) | Moderate |
| Database technologies | MySQL, MongoDB listed; no deep database internals work | Moderate |
| Performant, scalable systems | Niyo credit card systems (real transactions) but smaller scale | Moderate |
| Application infrastructure | Docker/Kubernetes at Niyo and PAN | Moderate |

**Gaps:**
1. **C++ and Rust** — Both likely needed for Palantir infra. Hard gap; not closable short-term. Mitigation: lead with Python + Go which Palantir also accepts.
2. **Distributed systems depth** — Dhruv's work is product/application layer. Palantir infrastructure teams build the primitives. This is a significant mismatch in depth.
3. **Database internals** — Uses MySQL/MongoDB but hasn't built database systems.
4. **Location unknown** — Without Singapore confirmation, this could require relocation.

---

## C) Level and Strategy

**Level detected:** Mid-level Backend SWE. Dhruv has 2 years but mostly product SWE (not infrastructure). This is a notable gap in depth.

**Recommendation:** This role sits at the edge of Dhruv's current profile. The infrastructure focus is not his primary trajectory (AI/ML, AI Security, LLMOps). Better to invest application energy in roles that play to his strengths.

**If pursued:**
- Lead with PAN security layer work (closest to infrastructure thinking: "secured the full stack from data ingestion to inference")
- Frame Kafka + Redis at Niyo as distributed systems exposure
- Acknowledge infrastructure gap directly and position MS in AI as compensating depth in ML systems

---

## D) Comp and Market

| Source | Data |
|--------|------|
| Palantir Backend SWE Singapore (est.) | SGD 7,500–10,000/month |
| JD disclosed | Not mentioned |
| Dhruv's target | SGD 5,500–8,500/month |

**Assessment:** Comp likely meets target if Singapore-based. But location unconfirmed.

---

## E) Personalization Plan

| # | Section | Current State | Proposed Change | Why |
|---|---------|---------------|-----------------|-----|
| 1 | PAN bullet 2 | Security layer description | Reframe: "designed security architecture spanning data ingestion, storage, training, deployment, and inference layers" | Infrastructure-thinking vocabulary |
| 2 | Niyo bullet | Kafka mention buried | Promote: "built event-streaming pipeline using Kafka; designed Redis caching layer" | Surfaces distributed systems experience |
| 3 | Skills | AWS, Kubernetes listed | Add: "distributed systems (Kafka, Redis, gRPC)" explicitly | Makes infra skills scannable |
| 4 | Summary | AI-security focus | Add: "strong foundation in backend systems and distributed infrastructure" | Bridges the infra gap |
| 5 | Cover | N/A | "The infrastructure team builds the foundation everything else runs on — I want to be close to that foundation." | Shows intentional application |

---

## F) Interview Prep

| # | JD Requirement | Story | S | T | A | R | Reflection |
|---|----------------|-------|---|---|---|---|------------|
| 1 | Systems design | PAN AI security layer | Enterprise needs AI system that's secure at every layer | Design the whole stack, not just the model | Mapped data ingestion → training → deployment → inference security controls | Full-stack security coverage for banking client | Security is easier to bake in than bolt on |
| 2 | Working with storage systems | Niyo credit card data | Live financial transactions across 4 banks | Zero data errors | Designed DB schema, validation logic, audit trails | Months of error-free card transaction processing | Financial data demands defensive coding at every layer |
| 3 | Distributed systems | Niyo SDUI (Kafka + Firebase) | UI deploys costing engineer time for every change | Decouple UI from backend | Kafka for event streaming, Firebase for state sync, backend rendering | Eliminated deploy cycle for UI changes | Understand the failure modes of your messaging layer before you rely on it |
| 4 | Scalable backend | Niyo microservices | Multi-bank credit card system | One change must not break another bank's integration | Designed isolated service boundaries per bank + SDK unifying them | 4-bank system in production with independent deploys | Isolation is the key; shared state is the source of most production fires |
| 5 | Security + infra | PAN adversarial attacks | Tested AI systems with real attacks | Find vulnerabilities before attackers do | Ran prompt injection, data poisoning, model evasion against own systems | Found exploitable vulnerabilities in 3 categories | Red-teaming your own system is the fastest way to find the holes |

---

## G) Posting Legitimacy

**Assessment: Proceed with Caution**

| Signal | Finding | Weight |
|--------|---------|--------|
| Apply button | Active lever.co | Positive |
| JD specificity | Reasonable — names specific infra domains | Positive |
| Location | **Not specified** — could be US/UK/other | Concerning |
| Company health | Palantir profitable, growing | Positive |
| Role fit for candidate | Infrastructure depth not Dhruv's primary trajectory | Neutral |
| Posting freshness | Unknown; Palantir runs rolling infra hiring | Neutral |

**Recommendation:** Lower priority in this batch. Confirm Singapore location via recruiter before investing. If Singapore-confirmed, apply as a stretch.

---

## Extracted Keywords

`backend engineer`, `distributed systems`, `database systems`, `Java`, `C++`, `Python`, `Rust`, `Foundry`, `Gotham`, `infrastructure`, `security`, `application infrastructure`, `scalable systems`, `storage`, `cloud infrastructure`, `Kubernetes`, `Palantir`

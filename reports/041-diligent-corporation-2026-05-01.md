# Evaluation: Diligent Corporation — AI Engineer II (Python, AWS)

**Date:** 2026-05-01
**Archetype:** AI Platform / LLMOps
**Score:** 3.2/5
**URL:** https://job-boards.greenhouse.io/diligentcorporation/jobs/5543875004
**Legitimacy:** Proceed with Caution
**PDF:** pending

---

## A) Role Summary

| Field | Detail |
|-------|--------|
| Archetype | AI Platform / LLMOps |
| Domain | Enterprise SaaS (GRC — Governance, Risk, Compliance) |
| Function | Build + scale production ML/LLM systems |
| Seniority | Mid-level (Engineer II, ~3–5 years) |
| Location | **Unconfirmed** — likely India or Singapore |
| Remote | Hybrid (≥50% onsite) |
| Team | Bridges Applied Scientists, AI Central, and Product Engineering |
| TL;DR | Mid-level AI engineer building and scaling production LLM systems for Diligent's governance platform using Python, AWS Bedrock, and agentic frameworks. |

---

## B) CV Match

| JD Requirement | CV Evidence | Strength |
|----------------|-------------|----------|
| Production ML/LLM systems | RAG pipelines + agent workflows at Palo Alto Networks | Strong |
| Agentic workflows / MCP-style servers | Multi-agent orchestration, MCP tooling at PAN (article-digest.md PP1) | Strong |
| Python | Listed in Skills; used throughout PAN work | Strong |
| AWS (general) | Listed in infrastructure skills | Moderate |
| End-to-end AI lifecycle (exp → prod → monitor) | PAN: data ingestion → deployment → inference security coverage | Strong |
| Collaboration w/ Applied Scientists | NUS HPE research collaboration (PP10) | Moderate |
| AWS CDK (Infrastructure-as-code) | Not in CV | **Gap** |
| Amazon Bedrock | Not in CV | **Gap** |
| LLM evaluation / prompt evaluation frameworks | Not explicitly mentioned | **Gap** |
| Reusable AI libraries / patterns | Card Controls SDK at Niyo (PP4) — adjacent | Moderate |

**Gaps:**
1. **AWS CDK** — Hard gap; Dhruv uses AWS (general) but not CDK specifically. Mitigation: frame Kafka/Docker IaC usage at Niyo; 1-week CDK spike project would close the gap.
2. **Amazon Bedrock** — Hard gap; Dhruv used open-source/enterprise LLM tooling at PAN. Mitigation: note experience with equivalent tools (LangChain, MCP), note learning speed.
3. **LLM eval frameworks** — Moderate gap; PAN work implies this but it's not explicit. Mitigation: reference adversarial attack testing as a form of LLM evaluation.

---

## C) Level and Strategy

**Level detected:** Engineer II (~3–5 years). Dhruv has ~2 years SWE + active AI internship + MS.

**Sell senior without lying:**
- Lead with PAN work: building *and* red-teaming production AI systems is more advanced than typical Engineer I work
- Emphasize end-to-end ownership: "owned from problem definition through deployment and monitoring at PAN"
- MS in AI adds theoretical depth that justifies the II level

**If downleveled:**
- Engineer I at Diligent in SG/India is still a good brand name in GRC-tech
- Negotiate 6-month review with explicit Engineer II criteria (AWS CDK certification, first system shipped to prod)

---

## D) Comp and Market

| Source | Data |
|--------|------|
| Diligent SG/India (Glassdoor) | No specific data for AI Engineer II; Software Engineer II India ranges ~₹15–25 LPA |
| Singapore AI/LLMOps Engineer II (market) | SGD 6,500–9,000/month |
| JD disclosed | Not mentioned |

**Assessment:** If this is a Singapore role, comp likely meets Dhruv's SGD 5,500–8,500 target. If India-based, significantly below target. Location confirmation is critical before investing time.

---

## E) Personalization Plan

| # | Section | Current State | Proposed Change | Why |
|---|---------|---------------|-----------------|-----|
| 1 | Summary | "Built production RAG pipelines and AI security systems" | Add: "and designed agentic workflows with MCP-style tooling at enterprise scale" | Matches JD vocabulary |
| 2 | PAN bullet 1 | Generic RAG + agent mention | Add explicit: "production ML/LLM systems covering data ingestion, training, deployment, and inference" | Mirrors JD lifecycle phrasing |
| 3 | Skills | AWS listed | Highlight: "AWS (CDK learning, Bedrock-compatible tooling)" | Shows awareness of gap + initiative |
| 4 | Niyo SDK bullet | Mentions reusable SDK | Frame as: "designed reusable AI library pattern across 4 integrations" | Matches "reusable AI libraries/patterns" requirement |
| 5 | Cover letter | N/A | Frame Diligent GRC context: "AI security for governance workflows is an emerging intersection I've built directly in at PAN" | Product-narrative connection |

---

## F) Interview Prep

| # | JD Requirement | Story | S | T | A | R | Reflection |
|---|----------------|-------|---|---|---|---|------------|
| 1 | Production ML/LLM deployment | PAN RAG pipeline for banking | Banking client needs secure AI; built RAG from scratch | Build production-grade end-to-end | Designed ingestion → retrieval → inference pipeline | Delivered working system for client demo | Would add eval harness from day 1 next time |
| 2 | Agentic workflows / orchestration | PAN multi-agent system | Complex client workflow requiring multiple AI agents | Orchestrate reliably with HITL checkpoints | Designed agent graph with LangChain-style tooling + MCP | Agents handled complex multi-step tasks | Reliability > speed in production agent systems |
| 3 | Reusable AI frameworks | Niyo Card Controls SDK | 4 banks, 4 different APIs, one feature | Build once, work everywhere | Designed common interface absorbing per-bank differences | SDK eliminated N-bank separate pushes | Abstraction is only worth it if variation is real |
| 4 | Monitoring/iteration | Grafana dashboards at Niyo | Credit card team needed ops visibility | Track KPIs in real-time | Built dashboards in Grafana + Superset | C-level visibility into card ops | Start with the decision it needs to enable, not the metric |
| 5 | End-to-end ownership | StoreMyStuff SaaS | Solo founder, every layer | Ship an entire SaaS | React + NestJS + MongoDB + payments | Real users, real blockers identified | Know when to stop; liability kill was correct call |

**Case study to lead:** PAN RAG pipeline for banking/public sector — shows production LLM systems in a governance-adjacent domain (banking compliance).

**Red-flag questions:**
- *"Why no AWS CDK experience?"* → "My AWS usage has been through Docker + service configs, not CDK. I've been studying CDK for this transition; the patterns are familiar from Terraform/IaC concepts."
- *"This role is mid-level — are you ready?"* → "My work at PAN is more senior than my title suggests: I own end-to-end AI system design for enterprise clients, not just feature work."

---

## G) Posting Legitimacy

**Assessment: Proceed with Caution**

| Signal | Finding | Weight |
|--------|---------|--------|
| Apply button | Accessible Greenhouse link | Positive |
| JD specificity | High — names AWS CDK, Bedrock, MCP-style servers, agentic workflows | Positive |
| Location | **Not specified in posting title** — similar roles on Naukri show Bengaluru | Concerning |
| Company layoffs | No recent layoff news for Diligent engineering in 2026 | Positive |
| Role market fit | GRC + AI = growing niche; Diligent is AI-investing heavily | Positive |
| Seniority realism | Engineer II requirements match description | Positive |

**Context notes:** Diligent has 17+ Singapore roles on Glassdoor (Apr 2026), so a SG-based AI Engineer II is plausible. However, similar "Software Engineer II - Python+React+AWS" postings appear on Naukri.com (India). Verify Singapore location *before* applying. Email recruiting directly: is this role based in Singapore?

---

## Extracted Keywords

`LLM systems`, `RAG pipeline`, `Amazon Bedrock`, `AWS CDK`, `agentic workflows`, `MCP`, `production ML`, `prompt evaluation`, `LLM evaluation`, `AI platform`, `observability`, `infrastructure-as-code`, `Python`, `AI lifecycle`, `Applied Science`, `model deployment`, `monitoring`, `LLMOps`, `agentic AI`, `GRC`

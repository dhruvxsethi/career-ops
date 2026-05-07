# Evaluation: OpenAI — Forward Deployed Engineer (Singapore)

**Date:** 2026-05-07
**Archetype:** AI Forward Deployed
**Score:** 3.8/5
**URL:** https://jobs.ashbyhq.com/openai/823fe212-7774-4387-a24b-b52f54c25fa3
**Legitimacy:** High Confidence
**PDF:** pending

---

## A) Role Summary

| Attribute | Value |
|-----------|-------|
| Archetype | AI Forward Deployed (FDE) |
| Domain | Enterprise LLM deployment |
| Function | Build + Deploy + Client-facing technical advisory |
| Seniority | Mid-Senior (5+ years required) |
| Location | Singapore, hybrid (3 days/week in office) |
| Travel | ~50% expected |
| Team | OpenAI Forward Deployed Engineering |
| TL;DR | FDE role leading end-to-end production deployments of OpenAI models alongside APAC enterprise customers — owns discovery, scoping, system design, build, and production rollout; measures success through workflow adoption and eval-driven product feedback. |

---

## B) CV Match

| JD Requirement | CV Evidence | Verdict |
|----------------|-------------|---------|
| 5+ years engineering including customer-facing work | ~2.5 years total (Niyo 18mo + GE 6mo + PAN 2mo ongoing) | ⚠️ Significant gap |
| Built/deployed LLM-powered production systems | PAN: RAG pipelines, agent workflows for banking/public sector | ✅ Strong |
| Complex system delivery in fast/ambiguous environments | PAN: end-to-end AI security systems for banking under internship constraints | ✅ |
| Customer-facing technical work | PAN Technical Solutions: demos and advisory to banking/public sector clients | ✅ |
| Understanding of model behavior → product effects | MS in AI + adversarial ML at PAN (prompt injection findings affect model output) | ✅ |
| Eval-driven feedback loops | PAN: adversarial evaluation of AI systems | ✅ (adjacent) |
| TypeScript / Python | TypeScript ✅ (Niyo: NestJS), Python ✅ | ✅ |

**Gaps:**
1. **Years of experience (5+ vs 2.5)** — The most significant gap. Requirement is nearly double Dhruv's actual experience. This is a filter risk, not a performance risk.
2. **Proven track record of scoping and delivering complex deployments** — Dhruv has 1 relevant project (PAN internship). Senior FDEs have 3–5 such projects.

**Mitigation:**
- Frame PAN Technical Solutions as "FDE role before it was called FDE" — same function: discover customer needs, build AI system, deploy to production, advise client.
- Compress framing: 2 years of foundational SWE (Niyo/GE) + current production AI deployment (PAN) is dense experience for 2.5 years total.
- Apply anyway — OpenAI Singapore office is new and growing. APAC FDE team may have different flexibility than US roles. OpenAI offers relocation assistance, suggesting they are actively building the Singapore team.

---

## C) Level and Strategy

**Level detected:** FDE / L4–L5 (mid-senior)
**Dhruv's natural level:** Entry-mid (L3)

**Sell senior without lying:**
- "I run end-to-end AI deployments for banking and public sector clients at PAN — discovery, design, build, client presentation. That's the FDE job description."
- "My scars are from real production AI systems: prompt injection, data poisoning, model evasion. I know where LLM deployments break in production because I've broken them."
- "2.5 years of experience across fintech backend at scale, AI research (NUS), and now production AI deployment — each transition was deliberate and fast."

**If downleveled:** Accept L3/Associate FDE if offered. The learning at OpenAI at any level outweighs the level label. Negotiate for a 6-month promotion review. Minimum acceptable comp: SGD 14,000+/month.

---

## D) Comp and Market

| Data Point | Value | Source |
|-----------|-------|--------|
| OpenAI FDE Singapore (Glassdoor employer data) | ~USD 18,000–22,000/month total comp (SGD ~24,000–30,000) | Glassdoor |
| Dhruv's target range | SGD 5,500–8,500/month | profile.yml |
| Delta | Role pays ~3x above Dhruv's target | — |
| EP sponsorship | Very likely — relocation assistance offered; Singapore is a priority market | Job description |

This is one of the highest-paying FDE roles available in Singapore. Even an entry/associate FDE at OpenAI likely pays above Dhruv's target ceiling.

---

## E) Personalization Plan

| # | Section | Current | Proposed | Why |
|---|---------|---------|---------|-----|
| 1 | Summary | Generic AI/ML | "Deployed production AI systems for banking and public sector clients at PAN Technical Solutions — RAG, agents, adversarial hardening, client advisory." | Maps to FDE job description exactly |
| 2 | PAN bullet 1 | General | Rewrite: "Owns end-to-end AI deployment for banking/public sector clients: discovery → system design → RAG/agent build → adversarial validation → production release" | FDE language, shows full lifecycle ownership |
| 3 | PAN bullet 2 | "Designed end-to-end AI security layers" | Add: "Presented technical findings and security posture to client stakeholders" | Shows the client-facing advisory component |
| 4 | Skills | Mixed | Lead with: Python, TypeScript, LangChain, RAG, agent workflows, adversarial ML | FDE ATS keywords |
| 5 | Case study URL | None | Add storemystuff.in as "shipped AI-assisted product from scratch" | Shows fast-ship ability |

---

## F) Interview Prep

| # | JD Requirement | Story | S | T | A | R | Reflection |
|---|----------------|-------|---|---|---|---|------------|
| 1 | End-to-end production deployment | PAN: RAG pipeline for banking client | Banking client needed secure document Q&A on internal data | Built from scratch: chunking strategy, embedding layer, retrieval, LLM call, response guardrails | Ran adversarial tests (prompt injection, data extraction attempts) before sign-off | System deployed to production; vulnerabilities caught pre-deployment | The deployment isn't done when it runs — it's done when it's been attacked |
| 2 | Customer-facing technical advisory | PAN: Presenting AI security findings | Technical Solutions team presents to banking/public sector partners | Had to communicate attack findings and system hardening to non-technical client stakeholders | Built executive-facing demo: "here's the attack, here's the detection, here's the fix" | Clients engaged and validated the approach | Translating technical depth into business risk language is a learnable skill |
| 3 | Complex system in ambiguous env | PAN: Agent workflow for public sector | No playbook for agentic workflows in government security context | Designed multi-agent orchestration with HITL checkpoints and failure handling | Iterated on agent design based on real failure modes found in adversarial testing | Agents deployed with reliable HITL integration | HITL is not an afterthought — it determines whether the agent is usable |
| 4 | Fast-moving delivery | Niyo: Server-Driven UI POC | Product team needed to ship UI changes without app releases | Designed SDUI framework (Kafka + Firebase + backend-defined rendering) solo | Delivered working POC in short window, drove entire technical design | Eliminated full deploy cycle for UI changes | Architecture decisions made fast under pressure need to be made deliberately |
| 5 | Technical breadth under constraints | Niyo: Card Controls SDK | 4 bank integrations each with different feature sets, needed unified interface | Designed SDK that abstracted per-bank differences behind common interface | Built in GoLang; handled N-bank extensibility without N separate code paths | Deployed across all 4 bank integrations; one change propagates everywhere | Abstraction is about protecting the caller from the mess, not hiding the mess |

**Recommended case study:** PAN internship — "From discovery to production: how I deployed a secure RAG system for a banking client."

**Red-flag questions:**
- "You don't have 5 years" → "I have 2.5 years of dense experience: 2 years building fintech backend systems at production scale, and now deploying production AI systems for banking clients at one of the world's leading cybersecurity firms. The FDE job is exactly what I'm doing at PAN today. The years compress when the work is right."
- "Why OpenAI specifically?" → "I've been building on top of frontier models and seeing where they fail in production. I want to be on the team that shapes how they're deployed — not just a customer of that knowledge."

---

## G) Posting Legitimacy

**Assessment: High Confidence**

| Signal | Finding | Weight |
|--------|---------|--------|
| Posting age | First seen 2026-04-22 in scan history (~15 days ago) | Positive |
| Apply button | Active on jobs.ashbyhq.com (Ashby = OpenAI's ATS) | Positive |
| JD specificity | Very specific: TypeScript/JS, 50% travel, hybrid schedule, APAC market | Positive |
| Company signals | OpenAI actively expanding Singapore office; no layoffs in Singapore team | Positive |
| Relocation offered | Job description mentions relocation assistance → actively building team | Positive |
| Reposting | Single occurrence in scan-history.tsv | Positive |

**Context:** OpenAI has been aggressively expanding its Singapore presence throughout 2025–2026. This is a genuine active opening. Apply immediately — FDE roles at OpenAI fill quickly.

---

## Extracted Keywords

forward deployed engineer, FDE, enterprise LLM deployment, production AI systems, LLM, RAG, agentic workflows, system design, customer-facing, TypeScript, Python, JavaScript, evaluation, evals, model behavior, discovery, scoping, production rollout, workflow automation, APAC, OpenAI, GPT, API integration, enterprise customers, stakeholder management

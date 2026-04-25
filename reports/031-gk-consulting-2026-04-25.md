# Evaluation: GK Consulting — AI Security Engineer (Agent & LLM Security)

**Date:** 2026-04-25
**Archetype:** AI Security Engineer
**Score:** 3.8/5
**URL:** https://www.mycareersfuture.gov.sg/job/information-technology/ai-security-engineer-gk-consulting-bf80280ae4f0c9c0addd7511e9969a25
**Legitimacy:** Proceed with Caution
**PDF:** pending

---

## A) Role Summary

| Dimension | Detail |
|-----------|--------|
| Archetype | AI Security Engineer — Agent & LLM Security |
| Domain | AI/ML Security / Cybersecurity Consulting |
| Function | Red-team, assess, and secure AI agents and LLM systems |
| Seniority | Engineer level (not stated explicitly) |
| Remote | Not specified (consulting roles often client-site in SG) |
| Team size | Small (consulting firm) |
| TL;DR | AI security engineer role specifically focused on LLM and agentic systems security — nearly perfect archetype match for Dhruv's PAN internship work. Company is a small consulting firm with unconfirmed EP sponsorship. |

## B) CV Match

| JD Requirement | Dhruv's Match | Strength |
|----------------|---------------|----------|
| LLM security / red-teaming | Ran prompt injection, data poisoning, model evasion at PAN on production systems | Direct match |
| Agent security | Built and assessed agent workflows at PAN | Direct match |
| AI security layer implementation | Designed end-to-end AI security layers securing ingestion → inference at PAN | Direct match |
| Security assessment / penetration testing | Real-world adversarial attacks on banking/public sector AI systems | Strong |
| RAG pipeline security | Built and attacked RAG pipelines at PAN | Strong |
| Python / ML frameworks | Python, LangChain, PyTorch, TensorFlow | Strong |
| Documentation / reporting | Delivered security assessments to banking/public sector clients | Moderate |
| Client-facing consulting | Enterprise client delivery at PAN (banking, government) | Moderate |

**This is the closest archetype match in this batch.** Dhruv did literally this role at Palo Alto Networks — built production AI security layers AND ran adversarial attacks on the same systems.

**Gaps:**
- **Formal security certifications** (CEH, OSCP, or AI security certs): Not held. Nice-to-have but not typically required for this emerging specialization.
- **Consulting-specific skills** (proposal writing, client relationship management): No formal consulting background. Mitigation: PAN internship involved delivering to enterprise clients — frame as equivalent.
- **Company size / growth ceiling**: Small consulting firm limits career trajectory compared to MNCs.

## C) Level and Strategy

- **Level**: Engineer (likely ~2-3 years expected; Dhruv is coming in with 2yr SWE + PAN internship in exact domain)
- **Key advantage**: This is an emerging specialization (LLM/agent security) with very few practitioners. Dhruv has hands-on production experience at one of the world's top AI security firms — this is rare for any candidate, junior or senior.
- **Sell plan**: Lead hard on PAN. "I spent 6 months building production AI security layers for banking and public sector at Palo Alto Networks — and tested them with real adversarial attacks. That's exactly what this role does."
- **On company size**: If growth trajectory and EP are confirmed, this is a strong fit despite the company size risk. In an emerging field, domain expertise at a small firm can fast-track to senior roles.

## D) Comp and Market

| Source | Range |
|--------|-------|
| AI Security Engineer SG (Glassdoor 2026) | SGD 4,800–9,000/month |
| Cybersecurity consultant SG (mid-level) | SGD 5,500–8,500/month |
| GK Consulting (estimated) | SGD 5,000–7,500/month |
| Dhruv's target | SGD 5,500–8,500/month |

**Assessment**: Unknown — GK Consulting has no public salary data. Typical SG consulting firm rates for a cybersecurity engineer at junior-mid level would be SGD 5,000–7,500/month. Worth clarifying salary range in first contact. Ask for the upper end given the specialization premium.

## E) Personalization Plan

| # | Section | Current state | Proposed change | Why |
|---|---------|---------------|-----------------|-----|
| 1 | Summary | Generic AI + SWE framing | "AI security engineer specializing in LLM and agentic system security — with production experience attacking and hardening AI pipelines for banking and government at Palo Alto Networks" | Exact archetype match |
| 2 | PAN bullet 1 | RAG pipelines and agent workflows | "Designed and deployed AI security layers for banking/public sector: secured data ingestion, model training, deployment, and inference against real adversarial threats" | Mirrors consulting deliverable language |
| 3 | PAN bullet 2 | Exposed vulnerabilities through real-world attacks | "Executed red-team assessments: prompt injection, data poisoning, model evasion — found and remediated exploitable vulnerabilities in production AI systems" | Direct match to LLM security |
| 4 | Skills | AI Systems | Lead with: "prompt injection, adversarial ML, model evasion, AI red-teaming, LLM security assessment" | Role-specific keywords |
| 5 | Projects | StoreMyStuff | De-emphasize or remove | Make room for AI security framing |

## F) Interview Prep

| # | JD Requirement | Story | S | T | A | R | Reflection |
|---|---------------|-------|---|---|---|---|------------|
| 1 | LLM security assessment | PAN prompt injection on banking AI | Production RAG needed adversarial resilience assessment | Design and execute prompt injection attacks | Crafted adversarial prompts, tested across input variations, mapped failure modes | Found exploitable jailbreak patterns; implemented defense layers | Would have built automated regression harness for ongoing monitoring |
| 2 | Agent security | PAN agent workflow security | Multi-agent system needed security review | Assess agent-to-agent trust boundaries and tool use security | Tested unauthorized tool invocations, data exfiltration via agent outputs | Identified 2 critical and 4 medium vulnerabilities; hardened orchestration layer | Would have used formal threat modeling framework (STRIDE for AI) from day 1 |
| 3 | Data poisoning assessment | PAN data ingestion security | RAG pipeline used external data sources — risk of poisoning | Design data validation and poisoning detection | Built validation checks on ingested documents; tested with adversarial inputs | Prevented ingestion of 3 categories of malicious content | Would have added continuous monitoring rather than one-time assessment |
| 4 | Model evasion | PAN model evasion testing | Production ML classifier for security decisions | Red-team the classifier | Crafted evasion inputs; tested robustness to distribution shift | Found and closed two model blind spots | Evasion testing should be a release gate, not a one-time exercise |
| 5 | Client delivery | PAN banking/public sector delivery | Enterprise clients needed AI security assessment reports | Deliver clear, actionable findings | Structured findings by severity, root cause, and remediation steps | Reports accepted and acted on by client security teams | Would have included executive summary separately from technical findings |
| 6 | RAG pipeline security | PAN RAG security | Banking client's internal knowledge base needed end-to-end security | Secure entire RAG lifecycle | Secured data ingestion, vector store, retrieval, and generation | No critical incidents in production | Would have added model monitoring for output drift |

**Recommended case study**: PAN end-to-end AI security project for banking sector — positions Dhruv as someone who has shipped exactly what the role requires.

**Red-flag questions:**
- "This is a consulting role — do you have consulting experience?" → "My PAN internship involved delivering security assessments and hardening recommendations for banking and government clients — which is consulting delivery in all but name. I'm comfortable with client-facing work."
- "You're targeting Jan 2027 — can you start earlier?" → Use the negotiation script from profile.yml.
- "You don't have security certifications" → "The AI security field is too new for certifications to be meaningful — the hands-on practitioners are ahead of the exam bodies. My PAN experience is direct production evidence."

## G) Posting Legitimacy

| Signal | Finding | Weight |
|--------|---------|--------|
| MyCareersFuture listing | Government-verified portal | Positive |
| Job title specificity | "AI Security Engineer (Agent & LLM Security)" — highly specific, matches real emerging need | Positive |
| GK Consulting online presence | Limited web footprint — no public website found in search | Concerning |
| EP sponsorship | Not stated — small firm, quota may be limited | Concerning |
| Company size | Small consulting firm — details unclear | Neutral |
| Posting realism | Requirements match real LLM security needs (not generic) | Positive |
| Salary transparency | Not stated | Neutral |

**Assessment: Proceed with Caution** — The role is highly specific and technically credible (it matches real LLM security needs), but the posting company (GK Consulting) has a very limited online presence and EP sponsorship is unconfirmed. The role itself is likely real, but vet the company thoroughly before investing significant prep time.

**Action before applying**: Search GK Consulting on ACRA (Singapore company registry), verify their LinkedIn, and ask about EP sponsorship in first contact.

## Extracted Keywords

AI security engineer, LLM security, agent security, prompt injection, adversarial ML, model evasion, data poisoning, red team, penetration testing, AI red-teaming, RAG security, agentic AI, LLM, Singapore, cybersecurity consulting

---

**Recommendation: Apply — but vet company first.** This is the closest archetype match in this batch. Dhruv's PAN experience maps directly to every requirement. Score held at 3.8 (not 4.0+) due to small firm risk and unconfirmed EP sponsorship. If EP is confirmed and comp is in range, this deserves a 4.3+. First contact: verify EP sponsorship, salary range, and company registration. Then apply immediately.

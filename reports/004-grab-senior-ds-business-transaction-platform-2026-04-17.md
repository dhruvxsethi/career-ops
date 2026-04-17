# Evaluation: Grab — Senior Data Scientist (Business & Transaction Platform)

**Date:** 2026-04-17
**Archetype:** AI/ML Engineer (LLM-focused) + LLMOps
**Score:** 3.5/5
**URL:** https://www.grab.careers/en/jobs/744000088522025/senior-data-scientist-business-transaction-platform/
**Legitimacy:** High Confidence
**PDF:** pending

---

## A) Role Summary

| Dimension | Detail |
|-----------|--------|
| Archetype | AI/ML Engineer (LLM-focused) — hybrid with Agentic |
| Domain | Merchant enablement / business analytics |
| Function | Build ML + LLM applications helping merchants run their businesses |
| Seniority | Senior (PhD or Master's + 2yr experience) |
| Remote | On-site, Singapore |
| Team size | Business & Transaction Platform team |
| TL;DR | Apply RAG, LLM fine-tuning, and recommendation models to give Grab merchants data-driven insights and tools; the team deploys LLMs in a production commerce context |

---

## B) CV Match

| JD Requirement | CV Match | Source |
|----------------|----------|--------|
| PhD or Master's in CS/AI/related | ✅ MS in AI at NTU (graduating 2026-2027) | cv.md |
| 2+ years relevant work experience in DS | ✅ 2yr SWE + PAN AI intern | cv.md |
| Python, PyTorch | ✅ Both listed in Technical Skills | cv.md |
| SQL, Spark | ✅ SQL (Niyo dashboards); Spark ❌ not listed | cv.md |
| RAG experience | ✅ Built production RAG pipelines at PAN for banking/public sector | cv.md, article-digest.md |
| Prompt Engineering | ✅ Implicit in RAG/LLM work at PAN | article-digest.md |
| LLM fine-tuning | ⚠️ Partial — ran adversarial attacks + worked with LLMs at PAN, but no explicit fine-tuning work documented | article-digest.md |
| Recommendation Systems | ❌ Not in CV or article-digest.md | |
| Time-series / predictive modeling | ❌ Not explicitly listed | |
| Decompose business problems into DS hypotheses | ✅ PAN: translated security requirements into ML system designs | article-digest.md |
| Communicate to non-technical stakeholders | ✅ Client-facing demos at PAN Technical Solutions; C-level Grafana dashboards at Niyo | cv.md, article-digest.md |

**Gaps:**
1. **Recommendation systems (significant)** — The JD says "at least two key domains: Recommendation Systems and Time-Series/Predictive Modeling." Dhruv has neither of these documented.
2. **LLM fine-tuning (partial)** — PAN work involves running models and security testing, not training/fine-tuning. Adjacent but not identical.
3. **Spark (minor)** — Easy to add; Kafka at Niyo shows distributed systems instinct.

**Mitigation:**
- RAG + prompt engineering is a strong match and the JD explicitly lists this.
- The Master's + 2yr entry bar is exactly Dhruv's profile — this is the lowest bar of all 8 roles evaluated.
- Recommendation systems gap: Frame retrieval in RAG as "ranking and relevance modeling" — genuine overlap at the conceptual level.
- Spark: One hands-on project or PySpark tutorial + project would close this gap quickly.

---

## C) Level and Strategy

**Level detected:** Senior DS at Grab (IC2-IC3 equivalent). PhD or Master's + 2yr — this matches Dhruv almost exactly.

**Dhruv's natural level:** IC2. This is the one role in this batch where the level is a genuine fit.

**"Sell senior without lying":**
- Lead with: "MS in AI (graduating Jan 2027) + production RAG pipelines for banking and public sector at PAN."
- Emphasize: "I've built, evaluated, and secured LLM systems in production — most candidates at this level have only academic exposure."
- Frame: The dual builder + attacker mindset (understand both how LLMs work and how they fail) is a genuine differentiator for a team deploying LLMs in commerce.

**"If downleveled":** This is already the entry-level Senior role. If they want to hire at a junior level, there may be no path. However, the January 2027 start aligns with Grab's hiring cycle — apply now and the timeline usually works.

---

## D) Comp and Market

| Source | Range (SGD/month) | Notes |
|--------|-------------------|-------|
| Glassdoor — Data Scientist at Grab | SGD 7,000–10,000 | Base + bonus |
| Glassdoor — Senior DS at Grab | SGD 9,000–13,000 | Total comp |
| Levels.fyi — G3 DS at Grab SG | SGD 75K–124K/yr (≈ SGD 6,200–10,300/mo) | |
| Dhruv's target | SGD 5,500–8,500/mo | Within range for entry of Senior band |

The Senior DS base at Grab aligns well with Dhruv's target. This is one of the financially realistic matches in this batch.

---

## E) Personalization Plan

| # | Section | Current state | Proposed change | Why |
|---|---------|---------------|-----------------|-----|
| 1 | Summary | AI security + backend SWE | Lead with "MS in AI + production RAG and LLM systems for enterprise clients" | Directly mirrors JD language |
| 2 | PAN bullet 1 | RAG pipelines + adversarial attacks | Split: (1) "Built production RAG pipelines and agent workflows for banking/public sector" (2) "Evaluated LLM systems via prompt injection and adversarial testing" | Shows both build and evaluation depth |
| 3 | Technical Skills | Generic list | Add "Prompt Engineering, RAG, LLM fine-tuning" explicitly | JD names these as requirements |
| 4 | Niyo SQL dashboards | Generic | "Designed ETL pipelines and dashboards over large transaction datasets" | Positions as data pipeline and analytics experience |
| 5 | NUS Research | Generic | "Conducted controlled experiments on deep learning models in collaboration with HPE" | Frames as ML research methodology |

**LinkedIn changes:**
- Headline → "MS in AI @ NTU | RAG + LLM Systems | AI Security | Open to Jan 2027"
- Featured → PAN case study / demo if available
- About section → mirror the JD framing: "builds and evaluates LLM systems in production for enterprise clients"

---

## F) Interview Prep

| # | JD Requirement | STAR+R Story | S | T | A | R | Reflection |
|---|----------------|--------------|---|---|---|---|------------|
| 1 | Build LLM/RAG applications for business | PAN RAG pipelines | Banking client needed intelligent document retrieval for compliance workflows | Design and deploy production RAG pipeline | Built RAG with ingestion, chunking, retrieval, and response generation. Added adversarial evaluation layer. | Production system for banking sector at PAN | Should have added automated evals from the start — manual red-teaming doesn't scale |
| 2 | Prompt Engineering + LLM fine-tuning | PAN LLM attack + defense | AI system had jailbreak vulnerabilities that bypassed safety filters | Identify and mitigate prompt injection attack surface | Designed prompt injection attack suite, found edge cases, proposed hardened system prompts | Security posture improved for client delivery | Fine-tuning for alignment was the right long-term fix; prompt engineering is a band-aid |
| 3 | Merchant business problem → DS hypothesis | Niyo hackathon | 40% of Niyo user base were students but product wasn't tailored to them | Identify a data-backed product gap and ship it | Analyzed user segments, identified students as underserved, built Student Mode in 4 days | Won hackathon; feature shipped to prod serving 40% of user base | Better framing: this is "decompose business problem (retention) into DS insight (segment)" — what this JD wants |
| 4 | Communicate complex results to non-technical stakeholders | PAN Technical Solutions / Niyo C-level dashboards | Banking clients needed to understand AI security posture | Translate ML vulnerability findings into business risk language | Built visual dashboards + presented security findings in non-technical terms to clients | Clients could make informed decisions about deployment | Would now produce a one-page executive summary in every engagement |
| 5 | End-to-end model deployment | PAN production AI systems | Client needed AI system from data ingestion to serving | Own the full ML lifecycle | Designed ingestion → training → deployment → inference security layer at PAN | Production system securing full ML lifecycle | Would instrument latency/throughput from day one |

**Case study:** PAN production RAG pipeline — walk through architecture, data ingestion, retrieval quality, adversarial testing, and deployment. Maps directly to the JD.

**Red-flag questions:**
- *"Do you have recommendation systems experience?"* → "Not directly, but RAG is fundamentally retrieval and ranking — the same principles. I've implemented and optimized retrieval pipelines in production."
- *"Your fine-tuning experience seems limited — can you walk us through it?"* → "At PAN my LLM work was focused on evaluation and security (red-teaming, prompt injection). I understand the mechanics of SFT and alignment, and I'm actively building a fine-tuning project to complement my evaluation experience."
- *"Can you start before Jan 2027?"* → Use the negotiation script from profile: "My internship at PAN runs through September 2026, and I'm finishing my MS coursework. Jan 2027 is my target — does that align with your hiring cycle?"

---

## G) Posting Legitimacy

| Signal | Finding | Weight |
|--------|---------|--------|
| Posting age | URL active; no exact post date found — URL ID (744000088522025) is mid-sequence for Grab postings | Neutral |
| Apply button | Active on grab.careers | Positive |
| JD specificity | Very specific: names RAG, prompt engineering, fine-tuning, PyTorch, SQL, Spark, recommender systems | Positive |
| PhD/Master's + 2yr requirement | Specific and realistic educational bar | Positive |
| Company hiring signals | Grab merchant platform is an active product investment; no signals of freeze | Positive |
| Reposting | No prior appearance in scan-history.tsv | Neutral |
| Role market context | Senior DS with LLM specialization is in high demand in SG; fills in 6-8 weeks typically | Normal |

**Assessment: High Confidence**

Technically specific JD with a realistic and unusual entry bar (Master's + 2yr). The LLM focus (RAG, fine-tuning, prompt engineering) is a real, active investment area for Grab. No ghost job signals. Most likely a genuine active opening.

---

## Extracted Keywords

RAG, retrieval-augmented generation, LLM, large language models, prompt engineering, fine-tuning, recommendation systems, time-series modeling, Python, PyTorch, SQL, Spark, ETL, merchant analytics, business intelligence, data science, machine learning, NLP, model deployment, production ML

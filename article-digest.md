# Article Digest — Dhruv Sethi
# Compact proof points for use in CV summaries, cover letters, and evaluations.
# The evaluation system reads this file at evaluation time — never hardcode these metrics.

---

## Palo Alto Networks — AI Security Intern (Mar 2026–Present)
**Team:** Technical Solutions (AI Security)
**Context:** 6-month internship (Mar–Sep 2026). Role involves building AI security systems for banking and public sector and presenting to clients.
**Note:** Work is ongoing — proof points here reflect the direction and scope of the role. Update with specifics as they're completed.

### Proof Point 1: AI Security for Banking/Public Sector (In Progress)
- **What:** Building enterprise AI systems (RAG pipelines, agent workflows) for banking and public sector, then running adversarial attacks against them (prompt injection, data poisoning, model evasion), then securing them using PANW products
- **Stack:** RAG, multi-agent orchestration, MCP, LangChain-style tooling, enterprise AI security layers
- **Signal:** Rare builder + attacker mindset; understands both how AI systems fail and how to harden them

### Proof Point 2: AI Security Layer Design (In Progress)
- **What:** Designing end-to-end AI security layers using enterprise tools, covering the full pipeline: data ingestion → model training → deployment → inference
- **Signal:** Systematic security thinking across the entire ML lifecycle, not just inference

### Proof Point 3: Client-Facing Technical Solutions Role
- **What:** Technical Solutions team — involves demoing AI security platforms to partners and clients, not just internal engineering
- **Signal:** FDE-style exposure: builds and presents; strong communication + technical combined

---

## Niyo Global — Software Engineer (Aug 2023–Feb 2025)
**Context:** India's leading student/travel neobank; 4 bank partnerships; youngest engineer on the team.

### Proof Point 4: Card Controls SDK (4-bank integration)
- **What:** Built a single SDK unifying card control functionality across 4 bank integrations (SBM, DCB, and 2 others) — previously required separate deployments per bank. SDK accounts for each bank's unique feature set while exposing a common interface.
- **Impact:** Eliminated N separate pushes for card feature changes; one change propagates to all 4 banks
- **Signal:** Designed for extensibility under real constraints — each bank had different underlying features, unified without losing individual bank capabilities

### Proof Point 5: Student Mode — Hackathon Win
- **What:** Built Student Mode feature in a 4-day company hackathon. Won based on the insight that 40% of Niyo's user base were students — built features specifically targeting their needs.
- **Impact:** Feature was implemented into production; served 40% of Niyo's active user base
- **Signal:** Product thinking + fast execution; shipped something real in 4 days that made it to prod

### Proof Point 6: Server-Driven UI (SDUI) Framework
- **What:** POC of a Server-Driven UI system — backend controls frontend rendering, so UI changes ship without app redeployments. Stack: Kafka for event streaming, Firebase for state, backend-defined rendering logic
- **Learning:** Full-stack learning across Kafka, Firebase, dynamic rendering — drove entire POC solo
- **Signal:** Architect-level thinking on a junior budget; eliminated deploy cycle for UI changes

### Proof Point 7: Grafana + Superset Credit Card Dashboard
- **What:** Built and managed dashboards monitoring the entire credit card team's KPIs and operations health
- **Users:** Internal credit card team; C-level visibility into ops metrics
- **Signal:** Data-driven engineering; built tooling that other teams relied on for decisions

### Proof Point 8: "Youngest engineer, do everything" culture
- **What:** Joined as intern at 21, converted full-time at 22. As the youngest engineer, handled frontend (Flutter), backend (GoLang/NestJS), DevOps, and SQL analytics — whatever needed fixing.
- **Signal:** Extreme ownership; breadth of full-stack experience built under real production pressure

---

## NUS — Teaching Assistant & Research Intern (Jun–Jul 2023)
**Context:** Selected from 100-150 applicants to TA the Data Analytics using Deep Learning course (NUS × HPE × AWS).

### Proof Point 9: Competitive TA Selection → LOR → NTU Admission
- **What:** Out of 100-150 candidates, selected as TA for the NUS Deep Learning course. Managed 100+ student cohort; got a Letter of Recommendation from NUS professor. LOR was a significant factor in NTU MS in AI admission.
- **Signal:** External validation of teaching quality and technical depth; NUS → NTU career arc

### Proof Point 10: HPE Research Collaboration
- **What:** Conducted research in Data Analytics using Deep Learning in collaboration with HPE; explored emerging approaches in the space
- **Signal:** Early exposure to enterprise research partnerships; beyond coursework from day 1

---

## StoreMyStuff — Founder (Oct–Nov 2024)
**URL:** https://www.storemystuff.in/
**Context:** SaaS marketplace connecting people who need temporary storage with local providers.

### Proof Point 11: Built and launched a SaaS in weeks using AI tools
- **What:** Full-stack SaaS (React + NestJS + MongoDB) with payment gateway integration, invoice generation, and booking management — built quickly with AI-assisted development
- **Reach:** Piloted with college society and friends; reached initial users
- **Lesson learned:** Two real blockers identified: (1) marketing — strong on engineering, hadn't planned go-to-market; (2) liability — if stored goods get damaged, no clear legal framework. Killed the project on valid grounds, not failure of execution.
- **Signal:** Ships fast; product instinct; knows when to stop (liability kill was the right call)

---

## Meta-skills (across all roles)

### Fast tech adoption
- Consistently picks up new frameworks/tools quickly — LangChain, Kafka, Flutter, GoLang, Firebase all picked up on the job
- Daily follower of AI news, tries new tools on release day
- Strong pattern: given a new technology → produces something useful in it fast

### Youngest-person-on-the-team pattern
- NUS: selected from crowd as TA at 21
- Niyo: youngest full-time engineer, handled everything
- PAN: building production AI systems as intern while doing MS
- Pattern: performs above expected level in every environment

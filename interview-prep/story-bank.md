# Story Bank — Master STAR+R Stories

This file accumulates your best interview stories over time. Each evaluation (Block F) adds new stories here. Instead of memorizing 100 answers, maintain 5-10 deep stories that you can bend to answer almost any behavioral question.

## How it works

1. Every time `/career-ops oferta` generates Block F (Interview Plan), new STAR+R stories get appended here
2. Before your next interview, review this file — your stories are already organized by theme
3. The "Big Three" questions can be answered with stories from this bank:
   - "Tell me about yourself" → combine 2-3 stories into a narrative
   - "Tell me about your most impactful project" → pick your highest-impact story
   - "Tell me about a conflict you resolved" → find a story with a Reflection

## Stories

<!-- New stories from evaluations get appended below. Seed stories added 2026-04-17. -->

---

### [AI Security / Systems] Build-and-Attack Bank AI Demo — PAN
**Source:** Seed — Palo Alto Networks internship
**S:** At PAN I needed to show enterprise clients (banks, public sector) their real AI security exposure and how a PANW-integrated stack defends it.
**T:** Build a realistic bank AI system, attack it with real adversarial techniques, then show the defense — for live partner/client demos.
**A:** Built multi-agent RAG pipeline with MCP integration simulating a bank AI assistant. Ran prompt injection, data poisoning, and model evasion attacks against it, documented each vector, then integrated PANW security products at every layer (ingestion → training → deployment → inference) and ran the demo end-to-end.
**R:** Demo is used in live partner and client engagements. Gave clients a concrete before/after rather than a theoretical slide.
**Reflection:** The hardest part was making attacks realistic enough to be credible but safe enough to demo. That tension taught me more about threat modeling than any coursework — "real enough to be scary, controlled enough to be safe" is actually a design constraint.
**Best for:** AI Security Engineer, LLMOps, Agentic AI, "complex system you built", "client-facing technical work"

---

### [Security / DevSecOps] MLSecOps CI/CD Integration — PAN
**Source:** Seed — Palo Alto Networks internship
**S:** Most enterprises add AI security after deployment. The real risk window starts at training and model ingestion — before prod.
**T:** Demonstrate how Prisma AI integrates into CI/CD pipelines so AI security checks run automatically on every push.
**A:** Mapped which pipeline stages introduce AI-specific risk. Integrated Prisma AI checks as pipeline gates at model loading, data ingestion, pre-deployment validation, and inference config. Built a demo pipeline that fails builds on detected vulnerabilities with structured developer output.
**R:** Working demo used in client presentations; gives enterprises a concrete shift-left path rather than a vague recommendation.
**Reflection:** Most security engineers think about AI as an API call. Framing it as a supply chain problem changes both the tools and the ownership — CISOs respond to that framing differently.
**Best for:** AI Security, DevSecOps, LLMOps, "how would you approach AI security at scale"

---

### [Engineering / Platform] Card Controls SDK — 4-Bank Unification — Niyo
**Source:** Seed — Niyo Global
**S:** Niyo had 4 bank partners, each with different card control features. Any feature change required separate deploys per bank — fragile and slow.
**T:** Build a unified SDK with a common interface that routes to bank-specific implementations under the hood.
**A:** Mapped every card control feature across all 4 banks. Designed an abstraction layer with common interface (pause, freeze, set limits) plus explicit feature flags per spoke so callers know what each bank supports. Coordinated integration with 4 internal product teams simultaneously.
**R:** 4 teams integrated. One deploy now propagates card feature changes to all 4 banks. No more N separate pushes per feature.
**Reflection:** Initially tried to paper over feature gaps with silent no-ops (if Bank B doesn't support "pause card", just do nothing). That caused downstream bugs. The right answer was explicit feature discovery — let the caller know what's supported. Abstractions that hide real differences are more dangerous than ones that expose them.
**Best for:** System design, backend engineering, platform work, "technical decision you're proud of"

---

### [Product / Execution] Student Mode Hackathon Win — Niyo
**Source:** Seed — Niyo Global
**S:** Company-wide 4-day hackathon. I was one of the youngest engineers.
**T:** Build something in 4 days that solves a real problem.
**A:** Looked at user base data: 40% of Niyo's users were students — the largest single segment, with no student-specific product features. Built Student Mode in 4 days: student onboarding flow, budget tools aligned with student spending, university partnership hooks. Presented with a data-backed narrative.
**R:** Won the hackathon. Feature shipped to production, serving 40% of the active user base.
**Reflection:** Most people in hackathons try to build the most impressive tech. I looked for the biggest gap between what existed and what users needed. That reframe — user gap over technical complexity — is the move I'd repeat.
**Best for:** Product thinking, fast execution, "identify a user need", innovation, "tell me about impact beyond your role"

---

### [Architecture] Server-Driven UI POC — Niyo
**Source:** Seed — Niyo Global
**S:** Shipping a UI change at Niyo took 2-4 weeks minimum due to app store submission cycles.
**T:** POC a Server-Driven UI system where backend controls frontend rendering — eliminating app redeployments for UI changes.
**A:** Designed architecture: backend defines UI layout in JSON, frontend is a generic renderer. Chose Kafka for event-driven state updates, Firebase for real-time delivery to app. Built the rendering engine. Discovered a failure mode mid-POC: bad backend deploy could break all UI with no client-side rollback — added fallback spec (last known good config).
**R:** POC proved the concept. Architecture knowledge — Kafka + Firebase + dynamic rendering — became a strong design reference for future projects.
**Reflection:** The more powerful the abstraction, the more catastrophic the failure mode when it breaks. Discovered this in testing and added a rollback mechanism before it became a prod incident.
**Best for:** Architecture decisions, "built from scratch", senior technical thinking, "what's something you learned on the job"

---

### [Leadership / Teaching] NUS TA Selection from 100-150 Candidates
**Source:** Seed — NUS
**S:** After completing the NUS Data Analytics using Deep Learning course (NUS × HPE × AWS), professors selected TAs from the entire cohort.
**T:** Get selected from 100-150 applicants, then run the course for the next cohort.
**A:** Applied by focusing on what I could specifically add as someone who just went through the course. Managed 100+ students across lectures, grading, and doubt-clearing sessions. Coordinated between NUS professors and AWS professionals on curriculum gaps.
**R:** Selected from 100-150 applicants. Got LOR from NUS professor. That LOR was cited by NTU as a significant factor in MS AI admission.
**Reflection:** Being good at a thing and being good at explaining it are different skills. Rebuilding mental models to teach others made me better at the content than when I just consumed it.
**Best for:** Leadership, communication, impact beyond role, "tell me about a time you taught something"

---

### [Growth] I Dive Into Code Too Fast — Honest Growth Story
**Source:** Seed — StoreMyStuff / general pattern
**S:** I have a recurring pattern: I start coding within the first hour of getting a problem. It's fast, but it's caused real mistakes — most notably StoreMyStuff, where I built a full platform before thinking through marketing, liability, or unit economics.
**T:** (Ongoing) Develop the discipline to slow down before building, without losing the execution speed.
**A:** Now explicitly force a "what am I building and why" step before any project — even 30 minutes of writing down the problem, use cases, and failure modes. The Kafka/SDUI project is an example of when I did this right (read the failure modes first, then built). StoreMyStuff is when I didn't.
**R:** The pattern is improving. I'm faster at recognizing when I'm rushing to code vs. when speed is the right call.
**Reflection:** The speed is also an asset — I prototype faster than most people I've worked with. The growth is knowing when to deploy it versus when to think first. Being a fast builder is only valuable if you're building the right thing.
**Best for:** "What's your biggest weakness", "tell me about a mistake", growth mindset, authenticity

# Ashutosh Gandhi

**Generative AI Engineer · Agentic Systems · Forward-Deployed AI**

I build AI systems that connect **enterprise data, tools, and business workflows** — from agent orchestration and evaluation to backend APIs, cloud deployment, guardrails, and production troubleshooting.

My recent work is centered on enterprise agentic analytics: LangGraph orchestration, capability-based routing, schema-grounded NL2SQL, retrieval, model evaluation, human-in-the-loop controls, and AWS/Azure delivery. Earlier work spans computer vision, speech, NLP, and serverless ML systems.

**~6 years in applied AI / Python engineering** · New Delhi, India  
[LinkedIn](https://www.linkedin.com/in/ashutosh-gandhi-cloud/) · [Email](mailto:gandhiashutosh14@gmail.com)

> **In plain English:** I help organisations put AI to work on their own data and systems, safely.
> Most of my projects answer one question: *what has to be true before an AI system is allowed to
> act on real business data?* In practice that means clear limits on what an AI agent may do,
> evidence that it behaves correctly when things go wrong, and a record a person can check.

---

## Selected projects

| Project | What it demonstrates | Stack / evidence |
|---|---|---|
| **[Governed Agent Orchestrator](https://github.com/gandhiashutosh14/governed-agent-orchestrator)** | A bounded runtime for tool-using agents: capability contracts, plan validation, parallel-wave execution, argument constraints, shared execution budgets, effect classes, human approval, fallbacks, DecisionTrace, policy memory, FastAPI and SSE. | LangGraph · FastAPI · Python · **27 offline tests** · committed guard demo |
| **[ASTERION](https://github.com/gandhiashutosh14/asterion-rehearsal)** | Deployment rehearsals for enterprise agents: a customer acceptance contract becomes bounded failure-mode rehearsals (outages, stale data, duplicate events, tenant boundaries), a Witness-Coverage Gate keeps untested obligations from counting as passed, and human approval binds to an exact evidence digest. Reference and native LangGraph engines share the same nodes. | LangGraph · FastAPI · Pydantic · SQLite · Docker · Terraform · **73 tests, 0 skipped** on Python 3.11–3.13 · container and Terraform checks in CI · synthetic local prototype |
| **[SENTINEL](https://github.com/gandhiashutosh14/sentinel-verify)** | Verification scheduling under freshness decay: Beta beliefs that age toward a prior, free feed evidence kept separate from costly noisy verification, decisions from an asymmetric loss table, and a scheduler that ranks checks by expected reduction in *decision* loss per unit cost. Compared with entropy, score-sorted, oldest-first, random and never on two seeded synthetic worlds; the README reports where it wins (scarce budget) and where it loses (larger budgets) and why. | Python · no runtime dependencies · **10 tests** · committed simulation reports · simulation only |
| **[Retention Uplift](https://github.com/gandhiashutosh14/retention-uplift)** | Budget-constrained retention targeting for a telco churn case: a data audit that finds sure things and lost causes from counts, a calibrated churn model, honest interval bounds on an observational discount flag (no demonstrated effect), an exact knapsack across save-rate scenarios, a learn-while-earning control group, and a governed pipeline whose critic vetoes lists that break the budget or target customers who churn regardless. | Python · scikit-learn · scikit-uplift · **8 tests** · committed run with memo, offer list and decision trace · synthetic case-study data |
| **[REGIMEFORGE](https://github.com/gandhiashutosh14/regimeforge)** | Decision replay under rule change: records rule/input dependencies, conservatively selects potentially affected decisions, then replays into `unchanged`, `flipped`, or `needs-evidence` against an independent full-replay reference. | Python · zero runtime dependencies · **142 tests** · 9 scenarios + 120-seed randomized check |
| **[NL2SQL Agent](https://github.com/gandhiashutosh14/nl2sql-agent)** | Schema-grounded NL-to-SQL with FK join-path resolution, read-only SQL validation, bounded repair, execution limits, evidence traces, and deterministic result matching. | Python · sqlglot · SQLite · Transformers · **50 tests** · 24/30 measured model result match + 30/30 oracle-harness check |
| **[NOESIS](https://github.com/gandhiashutosh14/noesis)** | Inspectable adaptive-agent experimentation: multi-judge evaluation, step-level reward components, Thompson/UCB/ε-greedy strategy selection, prompt-version tracking, policy updates, rollback, and persistent SQLite state. | Python · asyncio · Pydantic · SQLite · offline end-to-end loop + evidence report |
| **[SCHEMAMORPH bench](https://github.com/gandhiashutosh14/schemamorph-bench)** | A schema-drift benchmark that separates structural validity, round-trip consistency, and semantic correctness — including a counterexample where a mapping round-trips perfectly while carrying the wrong meaning. | Python · no runtime dependencies · seeded transformations · reproducible benchmark report |
| **[ShopNova Agent](https://github.com/gandhiashutosh14/shopnova-agent)** | Cloud-native support agent with Gemini function calling, four Cloud Functions, Firestore memory, Pub/Sub hand-off, bounded looping, and a server-side refund approval boundary that model-supplied input cannot bypass. | Flask · Gemini · Cloud Functions · Firestore · Pub/Sub · CI-backed approval-bypass regression test |
| **[Contract Clause Extraction](https://github.com/gandhiashutosh14/contract-clause-extraction)** | Source-traceable LLM extraction of audit and inspection clauses from contracts, with lexical gating, defensive parsing, and reviewer-ready Excel output. | Transformers · FLAN-T5 · Mistral · pandas · public SEC-filed sample · 8/8 target clauses found, 1 false positive |
| **[Customer Service RAG](https://github.com/gandhiashutosh14/customer-service-rag-chatbot)** | PDF-grounded support Q&A plus a deterministic complaint state machine and validated FastAPI service; the LLM routes intent while tested code owns validation and state. | Streamlit · LangChain · FAISS · FastAPI · SQLite |
| **[MORD House Image Similarity](https://github.com/gandhiashutosh14/MORD_House_image_similarity_sample)** | Earlier applied-computer-vision work: image-similarity screening of field-survey photographs for a government housing-scheme fraud-detection workflow. | Python · computer vision |

> **Portfolio principle:** reported results are tied to reproducible commands or committed reports, and synthetic / mocked experiments are labeled as such inside the relevant repository.

### The problem each project solves, in plain English

| Project | The business problem, in one sentence | Who typically has this problem |
|---|---|---|
| [Governed Agent Orchestrator](https://github.com/gandhiashutosh14/governed-agent-orchestrator) | An AI agent that can use tools might send the wrong report, run too many actions or do something irreversible without sign-off; this project shows how to set hard limits and keep a checkable record. | Any team giving AI agents access to internal data and systems |
| [ASTERION](https://github.com/gandhiashutosh14/asterion-rehearsal) | Before an AI agent goes live for a customer, both sides need proof that it copes with outages, stale data and duplicate events, and a sign-off tied to exactly that proof. | Enterprise software vendors and customer-facing engineering teams |
| [SENTINEL](https://github.com/gandhiashutosh14/sentinel-verify) | Security and compliance teams have far more findings than they can re-check; this decides which check is worth the limited budget next. | Security operations and field-verification teams |
| [Retention Uplift](https://github.com/gandhiashutosh14/retention-uplift) | A small retention budget is wasted on customers who would stay anyway or leave anyway; this targets the customers an offer can actually change. | Telecom, subscription and banking retention teams |
| [REGIMEFORGE](https://github.com/gandhiashutosh14/regimeforge) | When a rule or policy changes, which past automated decisions would now come out differently, and which need more evidence? | Lenders, insurers, claims processors and compliance teams |
| [NL2SQL Agent](https://github.com/gandhiashutosh14/nl2sql-agent) | Business users want to ask data questions in plain words without letting an AI run unsafe, expensive or wrong database queries. | Analytics and business-intelligence teams |
| [NOESIS](https://github.com/gandhiashutosh14/noesis) | Teams that change an AI agent need to know whether it really got better, and whether the automated judges scoring it can be trusted. | AI platform and evaluation teams |
| [SCHEMAMORPH bench](https://github.com/gandhiashutosh14/schemamorph-bench) | Data pipelines keep "working" after a partner renames or swaps a column, yet deliver wrong numbers; this benchmark measures that failure. | Data engineering and integration teams |
| [ShopNova Agent](https://github.com/gandhiashutosh14/shopnova-agent) | A support assistant that can look up orders and issue refunds must never approve money movements on its own. | E-commerce and customer-support teams |
| [Contract Clause Extraction](https://github.com/gandhiashutosh14/contract-clause-extraction) | Finding specific obligations, such as audit rights, across contracts is slow by hand; AI extraction has to point back to the exact paragraph. | Legal, procurement and compliance teams |
| [Customer Service RAG](https://github.com/gandhiashutosh14/customer-service-rag-chatbot) | A support chatbot must answer from the company's own documents and record complaints correctly, without inventing policies. | Customer-support teams |
| [MORD House Image Similarity](https://github.com/gandhiashutosh14/MORD_House_image_similarity_sample) | Programmes that pay out on photo evidence can be gamed with duplicate or reused photos; this screens for look-alike images at scale. | Public programmes and insurers that rely on photo evidence |

**How to read each repository:** every project README opens with the problem in plain English, an executive summary and an end-to-end diagram, then the technical detail, and closes with a SWOT analysis, industry use cases, a glossary and annotated further reading.

**Industries this work applies to:** financial services and insurance, telecom and subscription businesses, e-commerce and retail, healthcare administration, the public sector, security operations, and any company building data platforms or AI products for enterprise customers.

---

## What I bring to a forward-deployed / technical lead role

| Area | What I work on |
|---|---|
| **Customer problem → working system** | Translate ambiguous workflows into typed APIs, agent/tool contracts, validations, measurable acceptance paths, and deployable services. |
| **Agentic AI with controls** | LangGraph, capability catalogs, agent registries, human approval, bounded execution, structured outputs, evaluation, MCP/tool integration, persistent traces. |
| **Data + retrieval** | Schema-grounded NL2SQL, vector/hybrid RAG, embeddings, metadata filtering, reranking, semantic caching, pgvector, ChromaDB, Azure AI Search. |
| **Backend + cloud** | Python, FastAPI, PostgreSQL, AWS, Azure, GCP, Docker, GitHub Actions, Terraform, streaming and event-driven APIs. |
| **Production ownership** | Integration debugging, security hardening, model/provider benchmarking, observability, performance work, production RCA, and client/SME delivery. |

## Current portfolio direction

I am exploring the systems problems that appear **after agents become useful enough to act**: bounded authority, decision replay after rules change, evaluation reliability, integration/schema drift, and deployment evidence.

The goal is not to collect chatbot demos; it is to build **small, inspectable systems with explicit failure boundaries, measurable behavior, and reproducible evidence**.

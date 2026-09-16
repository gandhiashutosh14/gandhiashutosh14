# Ashutosh Gandhi

**Generative AI Engineer · Agentic Systems · Forward-Deployed AI**

I build AI systems that connect **enterprise data, tools, and business workflows** — from agent orchestration and evaluation to backend APIs, cloud deployment, guardrails, and production troubleshooting.

My recent work is centered on enterprise agentic analytics: LangGraph orchestration, capability-based routing, schema-grounded NL2SQL, retrieval, model evaluation, human-in-the-loop controls, and AWS/Azure delivery. Earlier work spans computer vision, speech, NLP, and serverless ML systems.

**~6 years in applied AI / Python engineering** · New Delhi, India  
[LinkedIn](https://www.linkedin.com/in/ashutosh-gandhi-cloud/) · [Email](mailto:gandhiashutosh14@gmail.com)

---

## Selected projects

| Project | What it demonstrates | Stack / evidence |
|---|---|---|
| **[Governed Agent Orchestrator](https://github.com/gandhiashutosh14/governed-agent-orchestrator)** | A bounded runtime for tool-using agents: capability contracts, plan validation, parallel-wave execution, argument constraints, shared execution budgets, effect classes, human approval, fallbacks, DecisionTrace, policy memory, FastAPI and SSE. | LangGraph · FastAPI · Python · **27 offline tests** · committed guard demo |
| **[REGIMEFORGE](https://github.com/gandhiashutosh14/regimeforge)** | Decision replay under rule change: records rule/input dependencies, conservatively selects potentially affected decisions, then replays into `unchanged`, `flipped`, or `needs-evidence` against an independent full-replay reference. | Python · zero runtime dependencies · **142 tests** · 9 scenarios + 120-seed randomized check |
| **[NL2SQL Agent](https://github.com/gandhiashutosh14/nl2sql-agent)** | Schema-grounded NL-to-SQL with FK join-path resolution, read-only SQL validation, bounded repair, execution limits, evidence traces, and deterministic result matching. | Python · sqlglot · SQLite · Transformers · **50 tests** · 24/30 measured model result match + 30/30 oracle-harness check |
| **[NOESIS](https://github.com/gandhiashutosh14/noesis)** | Inspectable adaptive-agent experimentation: multi-judge evaluation, step-level reward components, Thompson/UCB/ε-greedy strategy selection, prompt-version tracking, policy updates, rollback, and persistent SQLite state. | Python · asyncio · Pydantic · SQLite · offline end-to-end loop + evidence report |
| **[SCHEMAMORPH bench](https://github.com/gandhiashutosh14/schemamorph-bench)** | A schema-drift benchmark that separates structural validity, round-trip consistency, and semantic correctness — including a counterexample where a mapping round-trips perfectly while carrying the wrong meaning. | Python · no runtime dependencies · seeded transformations · reproducible benchmark report |
| **[ShopNova Agent](https://github.com/gandhiashutosh14/shopnova-agent)** | Cloud-native support agent with Gemini function calling, four Cloud Functions, Firestore memory, Pub/Sub hand-off, bounded looping, and a server-side refund approval boundary that model-supplied input cannot bypass. | Flask · Gemini · Cloud Functions · Firestore · Pub/Sub · CI-backed approval-bypass regression test |
| **[Contract Clause Extraction](https://github.com/gandhiashutosh14/contract-clause-extraction)** | Source-traceable LLM extraction of audit and inspection clauses from contracts, with lexical gating, defensive parsing, and reviewer-ready Excel output. | Transformers · FLAN-T5 · Mistral · pandas · public SEC-filed sample · 8/8 target clauses found, 1 false positive |
| **[Customer Service RAG](https://github.com/gandhiashutosh14/customer-service-rag-chatbot)** | PDF-grounded support Q&A plus a deterministic complaint state machine and validated FastAPI service; the LLM routes intent while tested code owns validation and state. | Streamlit · LangChain · FAISS · FastAPI · SQLite |
| **[MORD House Image Similarity](https://github.com/gandhiashutosh14/MORD_House_image_similarity_sample)** | Earlier applied-computer-vision work: image-similarity screening of field-survey photographs for a government housing-scheme fraud-detection workflow. | Python · computer vision |

> **Portfolio principle:** reported results are tied to reproducible commands or committed reports, and synthetic / mocked experiments are labeled as such inside the relevant repository.

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

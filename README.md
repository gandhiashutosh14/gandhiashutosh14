# Ashutosh Gandhi

**Generative AI Engineer · Agentic Systems · Forward-Deployed AI**

I build AI systems that connect **enterprise data, tools, and business workflows** — from agent orchestration and evaluation to backend APIs, cloud deployment, guardrails, and production troubleshooting.

My recent work is centered on enterprise agentic analytics: LangGraph orchestration, capability-based routing, schema-grounded NL2SQL, retrieval, model evaluation, human-in-the-loop controls, and AWS/Azure delivery. Earlier work spans computer vision, speech, NLP, and serverless ML systems.

**~6 years in applied AI / Python engineering** · New Delhi, India  
[LinkedIn](https://www.linkedin.com/in/ashutosh-gandhi-cloud/) · [Email](mailto:gandhiashutosh14@gmail.com)

---

## Start here

### [Governed Agent Orchestrator](https://github.com/gandhiashutosh14/governed-agent-orchestrator)
**A bounded runtime for tool-using agents.** Capability contracts, plan validation, shared execution budgets, argument constraints, effect classes, human approval, fallbacks, SSE traces, and policy memory over a deterministic demo domain.

**Why it matters:** shows how I think about letting agents *act* inside enterprise systems without making the prompt the security boundary.

### [REGIMEFORGE](https://github.com/gandhiashutosh14/regimeforge)
**Decision replay under rule change.** Records which rules and inputs shaped a decision, conservatively selects what a rule change could affect, replays those decisions, and classifies the result as `unchanged`, `flipped`, or `needs-evidence` against an independent full-replay reference.

**Why it matters:** a research-oriented prototype for the second-order problem created when automated decisions outlive the rules that produced them.

### [NL2SQL Agent](https://github.com/gandhiashutosh14/nl2sql-agent)
**Schema-grounded natural-language-to-SQL with bounded repair.** FK join-path grounding, read-only SQL validation, execution limits, evidence traces, deterministic result matching, and a 30-question evaluation harness.

**Why it matters:** demonstrates the difference between “the model generated SQL” and a system that checks, executes, repairs, and measures it.

---

## More engineering artifacts

- **[NOESIS](https://github.com/gandhiashutosh14/noesis)** — inspectable agent experimentation loop with a multi-judge jury, step-level reward components, strategy selection, prompt-version tracking, rollback, and SQLite policy state.
- **[SCHEMAMORPH bench](https://github.com/gandhiashutosh14/schemamorph-bench)** — schema-drift benchmark that separates structural validity, round-trip consistency, and semantic correctness; includes the counterexample where a mapping round-trips perfectly while carrying the wrong meaning.
- **[Contract Clause Extraction](https://github.com/gandhiashutosh14/contract-clause-extraction)** — source-traceable LLM extraction of audit/inspection clauses with a public SEC-filed sample, measured output, and an Excel review artifact.

These repositories are intentionally explicit about **what was actually run, what is synthetic or mocked, and what is not yet claimed**. Where a result is reported, the corresponding report or reproducible command lives in the repository.

---

## What I bring to a forward-deployed / technical lead role

- **Customer problem → working system:** translate ambiguous workflows into typed APIs, agent/tool contracts, validations, and measurable acceptance paths.
- **Agentic AI with controls:** LangGraph, capability catalogs, agent registries, human approval, bounded execution, structured outputs, evaluation, and MCP/tool integration.
- **Data + retrieval:** schema-grounded NL2SQL, vector/hybrid RAG, metadata filtering, reranking, semantic caching, pgvector/ChromaDB/Azure AI Search.
- **Backend + cloud:** Python, FastAPI, PostgreSQL, AWS, Azure, GCP, Docker, CI/CD, Terraform, event-driven and streaming APIs.
- **Production ownership:** integration debugging, security hardening, model/provider benchmarking, observability, performance work, and client/SME delivery.

## Current portfolio direction

I am exploring the systems problems that appear **after agents become useful enough to act**: bounded authority, decision replay after rules change, evaluation reliability, integration/schema drift, and deployment evidence. The goal is not to collect chatbot demos; it is to build small, inspectable systems with clear failure boundaries and reproducible evidence.

# Ashutosh Gandhi

**Generative AI engineer. I build agentic systems that answer business questions over real data: LLM orchestration, retrieval, NL-to-SQL, evaluation, and the backend and cloud work that makes them shippable.**

Currently a Generative AI Developer on an enterprise agentic-analytics platform for life-sciences clients (LangGraph orchestration, capability-based agent registry, schema-grounded NL2SQL, enterprise RAG, Azure to AWS migration, client-hosted IP protection). Before that: production computer vision, speech and NLP systems at Unicloud Labs, and an Amazon Bedrock course for CloudInstitute.

New Delhi, India · [LinkedIn](https://www.linkedin.com/in/ashutosh-gandhi-cloud) · gandhiashutosh14@gmail.com

## Selected projects

| Project | What it shows | Stack |
|---|---|---|
| [nl2sql-agent](https://github.com/gandhiashutosh14/nl2sql-agent) | Schema-grounded NL-to-SQL: foreign-key join-path resolution, a read-only SQL guard that feeds errors back into a bounded repair loop, evidence traces, and an evaluation harness with deterministic result matching. Measured on a 30-question golden set with a local 1.5B model on a laptop GPU. | Python, sqlglot, SQLite, Transformers |
| [governed-agent-orchestrator](https://github.com/gandhiashutosh14/governed-agent-orchestrator) | A capability catalog with typed contracts, a plan validator, an LLM-then-heuristic planner cascade, parallel-wave execution with fallbacks, a DecisionTrace journal, governed policy memory, and a LangGraph runtime that interrupts for human approval. FastAPI with SSE. | LangGraph, FastAPI, Python |
| [noesis](https://github.com/gandhiashutosh14/noesis) | A self-improving agent framework: multi-judge jury, gated step-level rewards, Thompson-sampled strategy selection, prompt evolution with rollback, all persisted in an inspectable SQLite policy. Runs and tests offline. | Python, asyncio, Pydantic, SQLite |
| [shopnova-agent](https://github.com/gandhiashutosh14/shopnova-agent) | A Tier-1 support agent on Google Cloud: Gemini function calling over four Cloud Functions, Firestore memory, Pub/Sub human hand-off, and a server-side refund guardrail the model cannot talk its way past. | Flask, Gemini, Cloud Functions, Firestore, Pub/Sub |
| [contract-clause-extraction](https://github.com/gandhiashutosh14/contract-clause-extraction) | LLM extraction of audit and inspection clauses from contracts, traced to source paragraphs, measured on a public SEC-filed agreement: 8 of 8 clauses found, 1 false positive, on a laptop CPU. | Transformers, FLAN-T5, Mistral, pandas |
| [customer-service-rag-chatbot](https://github.com/gandhiashutosh14/customer-service-rag-chatbot) | Grounded answers over a PDF knowledge base plus a validated slot-filling complaint flow backed by a FastAPI service. The LLM routes intent; tested code owns state and validation. | Streamlit, LangChain, FAISS, FastAPI |
| [MORD_House_image_similarity_sample](https://github.com/gandhiashutosh14/MORD_House_image_similarity_sample) | A sample from a government housing-scheme fraud-detection system: image-similarity screening of field survey photos. | Python, computer vision |

Every repository above has a `docs/DEVELOPMENT_NOTES.md` that records how it was built and verified.

## Areas

- **Agentic systems**: LangGraph, multi-agent orchestration, capability catalogs, agent registries, human-in-the-loop, MCP, structured outputs, streaming APIs
- **Retrieval**: vector and hybrid RAG, embeddings, metadata filtering, reranking, semantic caching, ChromaDB, pgvector, Azure AI Search
- **LLM engineering**: schema-grounded NL2SQL, validation and repair loops, LLM-as-judge evaluation, guardrails, QLoRA distillation
- **Backend and cloud**: Python, FastAPI, PostgreSQL, AWS, Azure, GCP, Docker, GitHub Actions
- **Applied ML foundation**: PyTorch, TensorFlow, computer vision, speech, NLP

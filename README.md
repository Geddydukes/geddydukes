# Hi, I’m Geddy Dukes

**AI & ML Systems Engineer** building reliable, production-grade AI systems from first principles.

I specialize in systems that combine **probabilistic machine learning with deterministic decision logic**. My work focuses on making AI **auditable, debuggable, and correct**, especially in real-world and regulated environments where hallucinations and silent failures are unacceptable.

From training language models from scratch on consumer hardware to building decision engines and compliance systems, I build AI that survives contact with production.

---

## Featured Projects

### [TinyLLM](https://github.com/Geddydukes/tiny_llm)
**Language model trained from scratch under extreme compute constraints**

A 67M-parameter transformer trained end-to-end on a 24GB Mac Mini to explore the efficient frontier of small models.
- **Architecture:** Implemented GPT-style architecture with **RoPE, RMSNorm, and SwiGLU**.
- **Performance:** Achieved **93.94% exact-match accuracy** on natural language → CLI command generation.
- **Reliability:** Designed **continual learning** with replay buffers and regression gating to prevent degradation.
- **Infrastructure:** Custom Apple Silicon (MPS) optimization for consumer hardware training.

**Tech:** PyTorch, NumPy, Transformers

### [Policy & Claims Decision Engine](https://github.com/Geddydukes/Policy-and-Claims-Decision-Engine)
**Deterministic decision system for regulated workflows**

A neuro-symbolic engine designed for high-precision audit and insurance workflows, where correctness and explainability matter more than model confidence.
- **Architecture:** Decoupled the "extraction layer" (LLM) from the "decision layer" (Deterministic) to ensure 100% auditability.
- **Safety:** Implemented strict **Pydantic** validation layers that flag ambiguous data for human review rather than guessing.
- **Traceability:** Produces fully traceable explanations for every decision outcome, suitable for compliance audits.
- **Hybrid Design:** ML-assisted classification feeds symbolic decision logic without leaking uncertainty.

**Tech:** Python, FastAPI, Pydantic, Docker

### [Research Discovery Agent](https://github.com/Geddydukes/Research_Agent)
**Provenance-tracked knowledge graph system**

A neuro-symbolic research discovery system that prioritizes truthfulness and citation over fluency.
- **Auditability:** Enforces **100% provenance**—every extracted node links directly to a source citation.
- **Quality Control:** Validation pipeline automatically rejects low-confidence claims (<75%) before graph ingestion.
- **Scale:** Extracted **119 entities and 187 relationships** into a structured, queryable knowledge graph.
- **Interface:** Interactive graph UI with drill-down into claims, confidence, and source context.

**Tech:** TypeScript, Node.js, PostgreSQL, Gemini 2.5

### [agentFT](https://github.com/Geddydukes/agent-ft)
**Agent reliability and evaluation framework**

An open-source framework for treating agent behavior like testable software.
- **Verification:** Task and scenario abstractions with **deterministic verification** adapters.
- **Resilience:** Async execution with retries, fail-fast modes, and rate limiting.
- **Observability:** Composite judging, trace logging, and JSONL/HTML artifacts for deep failure analysis.
- **Goal:** Designed to detect regressions and measure improvement over time.

**Tech:** Python, AsyncIO, Jinja2

---

## Technical Focus

| Domain | Technologies |
| :--- | :--- |
| **Machine Learning** | PyTorch, Transformers, Self-Supervised Learning, Continual Learning, MPS Optimization |
| **AI Systems** | RAG, Vector Search, Neuro-Symbolic Reasoning, Multi-Agent Orchestration |
| **Evaluation** | Regression Gating, Deterministic Verification, Trace Logging, Failure Analysis |
| **Engineering** | Python, TypeScript, Node.js, FastAPI, PostgreSQL, Redis, Docker, AWS |

---

## Engineering Philosophy

I treat AI outputs as **inputs to systems**, not answers to users.

My work follows three principles:
1. **First Principles:** Understand the math, training dynamics, and failure modes beneath abstractions.
2. **Constraint-Driven Design:** Efficiency forces discipline in architecture, data pipelines, and evaluation.
3. **Auditability Over Fluency:** In real systems, a traceable answer beats a confident one every time.

---

## Background

- **Production Systems:** Built and maintained fintech and decision systems with strict correctness, auditability, and latency requirements.
- **ML Research Engineering:** Implemented and trained models from research papers (JEPA, CPC, transformers) end-to-end.
- **Open Source:** Published and maintain agent runtimes and evaluation frameworks used in real systems.

**Education**
- **M.S. Analytics (Computational Data)**, Georgia Tech *(Expected 2027)*
- **B.S. Business Administration**, WGU *(2024)*
- **Software Engineering Immersive**, General Assembly *(2020)*

---

## Connect

- [geddydukes@gmail.com](mailto:geddydukes@gmail.com)
- [LinkedIn](https://linkedin.com/in/geddy-dukes)
- [Geddydukes.com](https://geddydukes.com)

**Open to:** ML Systems Engineering, Applied AI, and Full Stack roles.

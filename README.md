### Nishad Dhakephalkar

I build production-oriented AI systems - RAG, agents, evaluation, and safety. Computer Engineering student at I²IT Pune (Grad 2027), based in Pune, India.

I care more about the parts of an AI system that decide whether it actually works - retrieval quality, evaluation, safety, and orchestration - than about model hype. Most of what I build is an attempt to make LLM behaviour reliable and measurable rather than just demo-able.

---

### Selected work

| Project | What it does | Stack | Live |
|---|---|---|---|
| **[ServiceBench](https://github.com/Ndhakeph/servicebench-env)** | OpenEnv-compatible environment for training LLM agents to orchestrate calls across three interconnected backend services. The agent has to traverse user → order → inventory foreign keys in the right order, not just call one tool in isolation. Dense reward shaping with milestone and completion bonuses. *(Meta × Hugging Face × PyTorch hackathon)* | Python, FastAPI, Docker, HF Spaces | [🤗 Space](https://huggingface.co/spaces/Tacitus7/servicebench-env) |
| **[AI Evaluation Platform](https://github.com/Ndhakeph/ai-eval-platform)** | LLM-as-judge that scores outputs on a rubric with per-criterion reasoning, plus pairwise A/B comparison that runs **both** orderings to catch the judge's own position bias and flags when the two disagree. | Next.js, TypeScript, FastRouter, Supabase | [Live](https://ai-eval-platform.vercel.app) |
| **[RAG Knowledge Assistant](https://github.com/Ndhakeph/ai-rag-knowledge-assistant)** | Local-first document Q&A that runs fully offline - Ollama/Gemma for inference, Supabase pgvector (HNSW) for retrieval, hybrid reranking. No API keys, nothing leaves the machine. | Next.js, LangChain.js, Ollama, pgvector | — |
| **[AI Safety Harness](https://github.com/Ndhakeph/ai-safety-harness)** | Red-team platform that probes LLM guardrails with 30+ adversarial prompts across 5 attack categories (jailbreaks, prompt injection, and more) and scores how the model holds up, with audit logging. | Python, FastAPI, Docker, PostgreSQL | — |
| **[Multi-Agent Content Pipeline](https://github.com/Ndhakeph/ai-content-pipeline)** | Four coordinated agents - researcher → writer → fact-checker → polisher - with quality gates and revision loops between stages. | Next.js, LangChain, Gemini, Tavily | — |
| **[GST Shield](https://github.com/Ndhakeph/khatabook-GSTshield)** | Scans receipts with Claude Vision to extract GSTINs, then validates them **deterministically** (format, state code, mod-36 checksum) instead of trusting the model's output. *(hackathon)* | Next.js, Claude Vision, Supabase | [Live](https://khatabook-gst-shield.vercel.app) |

---

### Stack

**Languages** Python · TypeScript · JavaScript · SQL
**AI / LLM** RAG · multi-agent orchestration · LLM-as-judge evaluation · red-teaming / AI safety · agent environments (OpenEnv) · prompt engineering
**Tooling** LangChain · Ollama · OpenAI SDK · Claude (Vision) · Gemini · FastRouter · Tavily
**Backend & data** FastAPI · Next.js · Pydantic · PostgreSQL · Supabase · pgvector · Docker

---

### Currently

Deepening the evaluation and agent-eval work (single-output scoring, pairwise judging, bias mitigation) and reading into retrieval-quality metrics for RAG.

### Reach me

[ndhakeph@gmail.com](mailto:ndhakeph@gmail.com) · [LinkedIn](https://linkedin.com/in/nishaddhakephalkar) · [Hugging Face](https://huggingface.co/Tacitus7)

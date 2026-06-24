# Nishad Dhakephalkar

**AI/GenAI engineer** building production-oriented AI systems - RAG, agents, evaluation, and safety.
Computer Engineering @ I²IT Pune · Grad 2027 · Pune, India

I care more about the parts of an AI system that decide whether it actually works - retrieval quality, evaluation, safety, and orchestration - than about model hype. Most of what I build is an attempt to make LLM behaviour reliable and measurable, not just demo-able.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

---

## Selected work

**[AI Evaluation Platform](https://github.com/Ndhakeph/ai-eval-platform)** · [live demo ↗](https://ai-eval-platform.vercel.app)
An LLM-as-judge that scores outputs against a rubric with per-criterion written reasoning, plus pairwise A/B comparison that runs *both* orderings (A-B and B-A) to neutralise the judge's own position bias and flags when the two disagree.
`Next.js` · `TypeScript` · `FastRouter` · `Supabase`

**[ServiceBench](https://github.com/Ndhakeph/servicebench-env)** · [live on 🤗 Spaces ↗](https://huggingface.co/spaces/Tacitus7/servicebench-env)
An OpenEnv-compatible environment for training LLM agents to orchestrate calls across three interconnected backend services. The agent has to traverse `user → order → inventory` foreign keys in the right order, not just call one tool in isolation, with dense reward shaping over milestones and completion. Built for the Meta × Hugging Face × PyTorch hackathon.
`Python` · `FastAPI` · `Docker` · `HF Spaces`

**[RAG Knowledge Assistant](https://github.com/Ndhakeph/ai-rag-knowledge-assistant)**
Local-first document Q&A that runs fully offline - Ollama/Gemma for inference, Supabase pgvector (HNSW) for retrieval, and a hybrid reranker that blends vector similarity with keyword, position, and recency signals. No API keys, nothing leaves the machine.
`Next.js` · `LangChain.js` · `Ollama` · `pgvector`

**[AI Safety Harness](https://github.com/Ndhakeph/ai-safety-harness)**
A red-team platform that runs adversarial prompts through a five-layer guardrail pipeline - jailbreaks, prompt injection, harmful content, role manipulation, encoding tricks - and scores which layer caught or missed each attack, with incident logging.
`Python` · `FastAPI` · `Docker` · `PostgreSQL`

**[Multi-Agent Content Pipeline](https://github.com/Ndhakeph/ai-content-pipeline)**
Four coordinated agents - researcher → writer → fact-checker → polisher - with quality gates and a revision loop where the fact-checker can send a draft back to the writer under a bounded retry budget.
`Next.js` · `LangChain` · `Gemini` · `Tavily`

**[GST Shield](https://github.com/Ndhakeph/khatabook-GSTshield)** · [live demo ↗](https://khatabook-gst-shield.vercel.app)
Scans receipts with Claude Vision to extract GSTINs, then validates them *deterministically* - format, state code, and mod-36 checksum - instead of trusting the model's raw output. Built at a hackathon.
`Next.js` · `Claude Vision` · `Supabase`

---

## Currently

Deepening the evaluation and agent-eval work - single-output scoring, pairwise judging, position-bias mitigation - and digging into retrieval-quality metrics for RAG.

## Reach me

[ndhakeph@gmail.com](mailto:ndhakeph@gmail.com) · [LinkedIn](https://linkedin.com/in/nishaddhakephalkar) · [🤗 Hugging Face](https://huggingface.co/Tacitus7)

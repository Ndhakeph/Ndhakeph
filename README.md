# Hi, I'm Nishad 👋

Third-year Computer Engineering student at I²IT, Pune. I build AI systems — retrieval pipelines, multi-agent orchestration, safety testing tools, and evaluation platforms.

Most of my recent work focuses on understanding what makes AI applications reliable in practice: how to retrieve the right context for a RAG system, how to systematically test whether guardrails actually catch adversarial prompts, and how to evaluate LLM output quality beyond "looks fine."

## 🔧 What I've Built

**[RAG Knowledge Assistant](https://github.com/Ndhakeph/ai-rag-knowledge-assistant)** — Local document Q&A with multi-stage retrieval and hybrid reranking. Runs entirely on Ollama (no API costs). The interesting part is the reranking pipeline — vector similarity alone misses a lot, so I built a weighted scoring system combining semantic similarity, keyword overlap, position, and recency.

**[AI Safety Testing Harness](https://github.com/Ndhakeph/ai-safety-harness)** — Red-team testing platform for evaluating LLM guardrails. Runs adversarial prompts through a 5-layer detection pipeline and measures which attacks get caught. Python/FastAPI backend, Next.js frontend, PostgreSQL audit logging. [Dockerized](https://github.com/Ndhakeph/ai-safety-harness).

**[AI Evaluation Platform](https://github.com/Ndhakeph/ai-eval-platform)** · [Live Demo](https://ai-eval-platform.vercel.app/) — LLM-as-Judge scoring system. Upload test cases via CSV, get rubric-based evaluations on accuracy, clarity, and completeness. Built to replace manual review with systematic quality assessment.

**[Multi-Agent Content Pipeline](https://github.com/Ndhakeph/ai-content-pipeline)** — 4-agent system (Researcher → Writer → Fact-Checker → Polisher) with automated revision loops. The orchestration layer handles retries, quality gates, and full pipeline observability via Supabase.

**Hackathon Projects:**
- **[GST Shield](https://github.com/Ndhakeph/khatabook-ai-hackathon)** · [Live Demo](https://khatabook-ai-hackathon.vercel.app/) — AI compliance tool that validates vendor GST status before payment. Built in 24 hours at AI Boomi Buildathon. Uses Claude Vision for receipt parsing.
- **[Agentic Honeypot](https://github.com/Ndhakeph/Agentic-Honeypot)** — Counter-scam system that wastes scammers' time with an adaptive AI persona while extracting threat intelligence. Built at India AI Impact Buildathon.

## 💻 Stack

**Languages:** Python, TypeScript, JavaScript, SQL  
**AI/LLM:** LangChain, Ollama, OpenAI SDK, Gemini API, FastRouter, Tavily  
**Backend:** FastAPI, Next.js API Routes, Pydantic  
**Frontend:** Next.js, React, Tailwind CSS  
**Data:** PostgreSQL, Supabase, pgvector (HNSW), Docker  

## 📫 Contact

ndhakeph@gmail.com · [LinkedIn](https://linkedin.com/in/nishaddhakephalkar)

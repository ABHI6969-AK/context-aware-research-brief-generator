# context-aware-research-brief-generator
An AI-powered research assistant that generates structured, evidence-linked research briefs with LangGraph and LangChain, supporting follow-up queries and multiple interfaces.
# Context-Aware Research Brief Generator (LangGraph + LangChain)

An AI-powered research assistant that generates **structured, evidence-linked research briefs** for any given topic, using:
- **LangGraph** for workflow orchestration
- **LangChain** for LLM & tool abstraction
- **Pydantic** schemas for strict validation
- **Follow-up query support** via persistent context
- **REST API** (FastAPI) & **CLI** interface

---

## 🚀 Features
- **LangGraph Orchestration** with typed state, modular nodes, and retry logic.
- **Structured Outputs** enforced with Pydantic in all LLM calls.
- **Context Summarization** for follow-up questions, preserving user history.
- **Multiple LLMs**: high-quality synthesis (OpenAI GPT‑4 / GPT‑4o) + cost-efficient planning steps.
- **Search Integration** via SerpAPI tool.
- **Interfaces**:
  - FastAPI REST endpoint (`POST /brief`)
  - CLI for local usage
- **Deployment Ready** for Render, Hugging Face Spaces, Railway, etc.
- **Observability**: LangSmith tracing.
- **Testing** with unit + E2E tests.

---

## 📂 Project Structure

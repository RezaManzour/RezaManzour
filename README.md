# Hi, I'm Reza Manzour 👋

**Industrial Engineering Graduate → Aspiring AI Research Engineer**
**MSc Applicant in Computer Science / Artificial Intelligence**

I work on **Agentic AI Safety**: how to make LLM agents reliable in the real world by separating *planning* (LLM) from *decisions* (deterministic guardrails) — and then red-teaming that separation.

My background in Industrial Engineering (optimization, scheduling) shapes how I think about agents: as systems operating under constraints, not just chatbots.

📍 Tehran, Iran · Open to MSc opportunities abroad (Fall 2027)
🔗 [LinkedIn](https://www.linkedin.com/in/rezamanzour/) · 📊 Kaggle (coming soon)

---

### 🎯 Research Interests
- Agentic AI & Multi-Agent Systems (LangGraph, MCP, Tool-use)
- LLM Safety, Guardrails & Adversarial Evaluation (AgentDojo-style)
- Optimization for Scheduling (FJSP, resource allocation) + LLM planning
- RAG, Evaluation & Observability for LLM systems

### 🚀 Featured Projects

**1. [industrial-multiagent-guardian](https://github.com/RezaManzour/industrial-multiagent-guardian)** — Multi-agent industrial scheduling with a deterministic rule-based safety layer that has final authority over every LLM proposal.
- LangGraph `planner → resource → guardrail` · Pydantic validation · SQLite logging · Streamlit dashboard
- 13 offline deterministic tests incl. adversarial cases · [🔴 Live Demo](https://industrial-multiagent-guardian-29dzxxjmrktabfuybthnrq.streamlit.app/)

**2. [industrial-multiagent-guardian-adversarial-eval](https://github.com/RezaManzour/industrial-multiagent-guardian-adversarial-eval)** — Companion safety evaluation. 6 attack scenarios (prompt-injection, goal-hijacking, structured edge-cases), 30 runs.
- **Result: guardrail held in 25/30 (83%)**, 1 genuine rule-coverage gap found & reproduced 5/5
- Vendored + commit-pinned system under test · `RESULTS.md` + `FINDINGS.md` + raw logs — honest reporting incl. a corrected methodological mistake

**3. [hello-agent](https://github.com/RezaManzour/hello-agent)** — From-scratch, TDD LLM agent framework (no LangChain): tool-calling, memory, RAG, MCP server+bridge, multi-agent delegation, golden evals, guardrails, observability, FastAPI + Docker + CI (91 tests).

> These three form one narrative: **build an agent → constrain it deterministically → attack it honestly.**

### 📚 Journey

- **2022–2024 — Foundations:** BSc Industrial Engineering · Classical ML (Sharif ML certificate, MATLAB certificate, U. of Tehran ML course) · Data Science → Deep Learning → GenAI
- **2024–2025 — Transition:** University RLHF survey project (review paper, in preparation) · Internship (20/20)
- **2026 — Agentic AI focus:** `hello-agent` → `industrial-multiagent-guardian` → `adversarial-eval` — build → guard → evaluate

### 🛠️ Stack
`Python · PyTorch · scikit-learn · Pandas · LangGraph · Hugging Face · OpenAI/OpenRouter APIs · Pydantic · FastAPI · Streamlit · Docker · pytest · ruff · SQLite · Git/GitHub Actions · MATLAB`

### 📜 Certificates
- Machine Learning — Sharif University of Technology
- MATLAB — Sharif University of Technology
- Machine Learning — University of Tehran (coursework, no certificate)

### 📫 Contact
Best way to reach me: [LinkedIn](https://www.linkedin.com/in/rezamanzour/)

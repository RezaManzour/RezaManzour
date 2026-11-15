# Reza Manzour

M.Sc. student in Computer Science (Artificial Intelligence), with a B.Sc. in Industrial Engineering.

I work on making LLM agents safe to use in industrial operations: checking the actions an agent proposes
before they run, and measuring how often those checks fail. Alongside that I use classical machine
learning for industrial data such as predictive maintenance.

## Selected projects

| Project | What it does |
|---|---|
| [netagent-guard](https://github.com/RezaManzour/netagent-guard) | Gates the actions of an LLM network-operations agent with a rule gateway, an intent check and a digital-twin consequence check. Evaluated on a synthetic network with held-out attacks, bootstrap confidence intervals, McNemar tests and ablations. |
| [industrial-multiagent-guardian](https://github.com/RezaManzour/industrial-multiagent-guardian) | LangGraph scheduling pipeline in which an LLM only proposes and a deterministic guardrail decides. Includes an adversarial evaluation that found a rule gap, the fix, and a replay that checks it. |
| [industrial-predictive-maintenance](https://github.com/RezaManzour/industrial-predictive-maintenance) | Classical ML vs a PyTorch network on AI4I 2020 under one leakage-safe protocol, with cost-aware thresholds and a tool-replacement policy learned by Q-learning and checked against the exact solution. |
| [hello-agent](https://github.com/RezaManzour/hello-agent) | A small LLM agent framework written from scratch with test-driven development: tool calling, memory, RAG, MCP, multi-agent delegation and evaluation. |

## Tools I use

Python · PyTorch · scikit-learn · pandas · LangGraph · FastAPI · NetworkX · Streamlit · pytest · Docker · GitHub Actions

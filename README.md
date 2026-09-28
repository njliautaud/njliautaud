# Nicholas Liautaud

Design engineer by day (aerospace components, ANSYS Fluent CFD, additive manufacturing, embedded telemetry). Quant ML engineer and agentic-AI builder by night.

I build systems end to end: from order-book deep learning on a multi-node GPU cluster, to a 24/7 autonomous AI agent that runs my research and ops, to flight hardware and the telemetry that flies with it.

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[Lvl3Quant](https://github.com/njliautaud/Lvl3Quant)** | Quant ML research platform on CME Level-3 (market-by-order) data: CNN-Mamba / PatchTST / event-transformer models, a Rust feature and tensor pipeline, RL and gradient-boosted execution policies, walk-forward and out-of-time validation, paper/live harnesses, plus options, ETF and prediction-market research. Many strategies documented as closed negative, with reasons. | PyTorch, LightGBM/XGBoost, Rust, Ray, MLflow, Optuna |
| **[jupiter-autonomous-agent](https://github.com/njliautaud/jupiter-autonomous-agent)** | A 24/7 autonomous personal AI agent built on Claude Code: a shared memory bus for all agents (CLI + HTTP API), a usage-tier governor enforced through hooks, self-review evals with an adversarial reviewer agent, a phone-first control plane, a fallback provider framework, a local GenAI router on an RTX 3090, and LLM trading agents. | Claude Code, Python, Node.js, MCP, LiteLLM |
| **[TravelBoard](https://github.com/njliautaud/TravelBoard)** | Early prototype of a travel app (journal map, flight/points deals board) that grew into a larger product. | Next.js, TypeScript, Postgres/Supabase, Capacitor |

## Other work

- **AeroForge**: aerospace analysis platform (airfoil and CFD workflows, stability, trim, weight and balance). *Private.*
- **[MacroStrategy](https://github.com/njliautaud/MacroStrategy)**: macro-structural alpha engine: regime-aware symbolic regression (genetic programming) over cross-asset flow, macro and commodity-linkage features, with walk-forward validation.
- **[QuantTimeCloud](https://github.com/njliautaud/QuantTimeCloud)**: multi-node ES Level-3 (MBO) research suite: Databento ingest, Ray cluster, cross-platform node management, auto-sync, and Prometheus/Grafana monitoring. The precursor to Lvl3Quant.
- **[AI-HedgeFund](https://github.com/njliautaud/AI-HedgeFund)**: multi-agent equity research framework: investor-persona agents, quant strategies, portfolio optimization, risk analytics and an LLM decision layer (2025).
- **[AI-HedgeFund-2](https://github.com/njliautaud/AI-HedgeFund-2)**: agentic LLM market-research console: LangChain manager/worker agents, 20+ data tools, a catalyst-driven swing-trading pipeline and ML/RL experiments (2025).
- **[cda3103Bonus](https://github.com/njliautaud/cda3103Bonus)**: cache simulator in C (computer organization coursework).

## Toolbox

**ML / quant:** PyTorch, LightGBM, XGBoost, scikit-learn, NumPy, pandas, polars, Optuna, MLflow, Ray
**AI agents:** Claude Code, Claude API, MCP servers, subagent orchestration, eval rubrics
**Engineering:** ANSYS Fluent, Autodesk Inventor, SolidWorks, 3D printing, embedded C/Python, telemetry
**Infra:** Linux, multi-node GPU clusters, Tailscale, Docker, Git

[LinkedIn](https://www.linkedin.com/in/nicholas-liautaud-710934274)

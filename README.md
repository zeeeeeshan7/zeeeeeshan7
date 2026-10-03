### Hi, I'm Zeeshan

I build the parts of LLM systems that keep them correct and running, and I've shipped AI agents to customers as a founder.

**What I'm working on**

- **[switchyard](https://github.com/zeeeeeshan7/switchyard)**: an OpenAI-compatible LLM gateway in Go. It fails over between Anthropic, OpenAI, Gemini and Bedrock, and in chaos tests under load it failed 0 of ~82,000 requests. It also enforces per-tenant budgets and idempotency, and traces every provider attempt with OpenTelemetry.
- **[arena-evals](https://github.com/zeeeeeshan7/arena-evals)**: a CI gate for LLM agents. It blocks a pull request only when a quality drop is statistically real, at about $0.95 a run. [Live demo](https://zeeeeeshan7.github.io/arena-evals).
- **[harness](https://github.com/zeeeeeshan7/harness)**: a runner that wraps an agent loop with step and dollar budgets and checkpoint/resume. Early, v0.1.
- **[EvoWerk](https://evowerkintelligence.com)**: manufacturing and inventory software I founded. The code is private. It includes an agent that works over live data and asks before it changes anything.

**Stack:** Python, Go, TypeScript, PostgreSQL, Redis, OpenTelemetry, FastAPI, React.

**Research:** presented "Invariance-Oriented Representation Learning for Behavioural Identity in Football Event Data" at ICCSAM 2026.

Reach me at zeeshan560ali@gmail.com.

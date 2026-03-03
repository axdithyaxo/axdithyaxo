# Aadithya Vishnu Sajeev

I see patterns in the noise before the noise knows it's a pattern.

I'm from Kerala. I live in Dublin. I build things because I can't not build them.

On November 11, 2024, I wanted to build something like PyTorch — but for agents. Not a wrapper. Not another LangChain. A ground-up rethink of what agentic infrastructure should actually be.

109 days later I had Lár, Lár-JEPA, DMN, and a compliance architecture mapped to the EU AI Act. I didn't plan most of it. The ideas emerged as I followed the logic of the problem wherever it led.

That's how I build everything.

---

## The Work

### [Lár](https://github.com/snath-ai/lar) — The Glass-Box Agent Engine
*The PyTorch for Agents.*

Most agent frameworks are black boxes. When they fail in production you get a 100-line stack trace and no idea what happened, why, or how much it cost. I built Lár because I think that's the wrong foundation for serious AI systems.

Lár is a deterministic, define-by-run graph execution engine. Every node, every state change, every decision is logged to a forensic flight recorder. Built-in HMAC cryptographic audit trails. EU AI Act Article 12/13/14 compliant by architecture. Air-gap capable. FDA 21 CFR Part 11 ready.

Not magic. Not wrappers. Just pure, debuggable Python you actually own.

**The numbers:** 1% LLM + 99% code hybrid architecture → 0.08s vs 64s latency, $0.00 vs $3.60/run vs standard frameworks. LangGraph hits recursion limit at step 25. Lár ran 10,000+ steps without a single error.

### [Lár-JEPA](https://github.com/snath-ai/Lar-JEPA) — Post-LLM Orchestration
*The nervous system for world models.*

Every major agent framework assumes text in, text out. That assumption breaks when your model outputs a 768-dimensional tensor representing the abstract state of a physical environment.

Lár-JEPA is the deterministic execution spine for Predictive World Models — routing high-dimensional latent tensors without text prompting. Built for the post-LLM paradigm LeCun has been describing. The industry is building the brain. This is the nervous system.

### [DMN](https://github.com/snath-ai/DMN) — Bicameral Memory Architecture
*An organism, not a tool.*

Standard agents have amnesia. DMN implements a biologically-inspired Default Mode Network — a background daemon that watches execution logs, sleeps, dreams, and consolidates short-term memory into long-term semantic understanding via ChromaDB.

Solves catastrophic forgetting without retraining. Two processes: conscious mind (fast, responsive) and subconscious mind (slow, synthesising). Runs 24/7. Gets smarter while you're away.

### [Metacognition](https://docs.snath.ai/core-concepts/9-metacognition/) — Dynamic Self-Modifying Graphs
*Agents that rewrite their own execution topology at runtime. Safely.*

DynamicNode generates JSON graph specs — including BatchNodes for parallel execution — validated by a deterministic TopologyValidator before running. Self-modification as an auditable event, not a jailbreak risk. The AI proposes. The code decides.

---

## Other Work

**[BreakHis Classifier](https://github.com/axdithyaxo/BreakHis_Classifier)** — ResNet-50 breast cancer classifier on histopathology data. 0.96 F1-score, 0.98 AUC. Streamlit diagnostic interface.

**[MCP Forensic Toolkit](https://github.com/axdithyaxo/mcp-forensic-toolkit)** — AI-enabled digital forensics via Model Context Protocol.

**[MCP BioForensics](https://github.com/axdithyaxo/mcp-bioforensics)** — Clinical trial data exploration with hybrid retrieval and natural-language querying.

---

## The Philosophy

The industry is building the Brain.
I'm building the Nervous System.

Never use an LLM to police another LLM. Use code.
An approval is not a flag. It is a cryptographic signature of a specific state.
Self-modifying code is only dangerous in a black box. In a glass box it's just evolution with an audit trail.

Lár is to agents what Kubernetes is to containers and Git is to code — the infrastructure layer that makes everything else trustworthy, reproducible, and production-grade.

---

## The Stack

Lár → deterministic execution  
Lár-JEPA → world model orchestration  
DMN → persistent bicameral memory  
Metacognition → safe self-modification  

Execution spine → world modelling → persistent memory → self-awareness.

That's a complete cognitive architecture. Built from scratch. In public. Under Apache 2.0.

---

## Background

MSc Data Analytics, Dublin City University.  
Kerala → Dublin.  
Future: CTO, SnathAI.

---

## Find Me

[axdithya@gmail.com](mailto:axdithya@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aadithya-vishnu-sajeev-853a341a6/) · [snath.ai](https://snath.ai) · [docs.snath.ai](https://docs.snath.ai)

---


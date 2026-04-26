# Aadithya Vishnu Sajeev

I see patterns in the noise.

On November 11, 2024, I set out to build something like PyTorch—but for agents. Not a wrapper, not another "magic" framework, but a ground-up rethink of what agentic infrastructure should actually be.

109 days later, I had Lár, Lár-JEPA, DMN, and a compliance architecture mapped to the EU AI Act. I didn't plan most of it; the ideas emerged as I followed the internal logic of the problem wherever it led.

That's how I build everything.

---

## The Work

### [Lár](https://github.com/snath-ai/lar) — The Glass-Box Agent Engine (v1.7.1)
*The PyTorch for Agents.*

Most agent frameworks are black boxes. When they fail in production, you get a 100-line stack trace and no idea what happened, why, or how much it cost. I built Lár because trust is the only foundation for serious AI systems.

Lár is a **deterministic, define-by-run graph execution engine**. Every node, every state change, and every decision is logged to a forensic flight recorder.
- **Compliance by Architecture**: Built-in HMAC cryptographic audit trails. Native alignment with EU AI Act Art. 12 (Logging), Art. 13 (Transparency), and Art. 14 (Human Oversight).
- **The Validation Suite**: A robust "Kitchen Sink" suite proving deterministic DAG execution and safe "Fractal Agency" (recursive graph expansion).
- **The Numbers**: 1% LLM + 99% code hybrid architecture. 0.08s latency vs 60s+ in standard frameworks. Lár has run 10,000+ steps without a single error where others hit recursion limits at step 25.

### [Lár-JEPA](https://github.com/snath-ai/Lar-JEPA) — Post-LLM Orchestration
*The universal nervous system for world models.*

Lár-JEPA is the execution spine for **Predictive World Models**. It solves the "Autoregressive Bottleneck" by routing high-dimensional **latent tensors** directly—bypassing text prompting entirely.
- **Unified Model Routing**: Routes LLMs, JEPAs, and GNNs as first-class `AbstractCognitiveNode` instances in the same graph.
- **Mathematical Safety**: Uses a `TensorSafeEncoder` for native tensor logging and a **Spatial Kinematics Engine** to veto structurally entropic predictions (physics-based routing).
- **System 1 / System 2**: Formally orchestrates the difference between fast-reflex execution and deep-simulation planning in latent manifolds.

### [DMN](https://github.com/snath-ai/DMN) — Bicameral Memory Architecture
*Autopoietic AI: An organism, not a tool.*

Standard agents suffer from amnesia. DMN implements a biologically-inspired **Default Mode Network**—a 24/7 background cognitive system for memory consolidation.
- **3-Tier Memory Architecture**: Parallel management of **Hot** (Working), **Warm** (Semantic), and **Cold** (Episodic) memory tiers.
- **The Neuro-Architecture**: Implements a **Thalamus** gateway, a **Prefrontal Cortex** for context compression, and an **Amygdala** for persistent emotional state (Valence/Arousal).
- **Wake Up Protocol**: Consolidates raw interaction logs into narratives during "sleep" periods, injecting the "Last Dream" back into the prompt upon waking to solve catastrophic forgetting.

### [Metacognition](https://docs.snath.ai/core-concepts/9-metacognition/) — Dynamic Self-Modifying Graphs
*Agents that rewrite their own execution topology at runtime. Safely.*

Lár’s `DynamicNode` allows agents to propose new graph sub-topologies during execution. But unlike open loops, it is guarded by a deterministic `TopologyValidator` that scans for unauthorized nodes and infinite cycles. Self-modification is an auditable event, not a security risk.

---

## Other Work

**[BreakHis Classifier](https://github.com/axdithyaxo/BreakHis_Classifier)** — ResNet-50 breast cancer classifier on histopathology data. 0.96 F1-score, 0.98 AUC.

**[MCP Forensic Toolkit](https://github.com/axdithyaxo/mcp-forensic-toolkit)** — AI-enabled digital forensics via Model Context Protocol.

**[MCP BioForensics](https://github.com/axdithyaxo/mcp-bioforensics)** — Clinical trial data exploration with hybrid retrieval and natural-language querying.

---

## The Philosophy

The industry is building the Brain.
I'm building the Nervous System.

Never use an LLM (unreliable) to police another LLM. Use code (reliable).
An approval is not a flag. It is a cryptographic signature of a specific state.
Self-modifying code is only dangerous in a black box. In a glass box, it's just evolution with an audit trail.

---

## The Stack
```
Lár           → deterministic execution (Glass Box)
Lár-JEPA      → world model orchestration (Nervous System)
DMN           → persistent bicameral memory (Hippocampus/PFC)
Metacognition → safe self-modification (Evolution)
```

**Execution spine → World modelling → Persistent memory → Self-awareness.**

A complete cognitive architecture. Built from scratch. In public. Under Apache 2.0.

---

## Background

MSc Data Analytics, Dublin City University.
Kerala → Dublin.
Future: CTO, SnathAI.

---

[axdithya@gmail.com](mailto:axdithya@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aadithya-vishnu-sajeev-853a341a6/) · [snath.ai](https://snath.ai) · [docs.snath.ai](https://docs.snath.ai)

---

*"Apna time aayega."*

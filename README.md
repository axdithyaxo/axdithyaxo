# Aadithya Vishnu Sajeev

I see patterns in the noise.

On November 11, 2025, I set out to build something like PyTorch—but for agents. Not a wrapper, not another "magic" framework, but a ground-up rethink of what agentic infrastructure should actually be.

180 days later, I had Lár, Lár-JEPA, DMN, a compliance architecture mapped to every step of the EU AI Act, and the only open-source framework that produces three HMAC-signed audit artefacts a regulator can actually inspect. I didn't plan most of it; the ideas emerged as I followed the internal logic of the problem wherever it led.

That's how I build everything.

---

## The Work

### [Lár](https://github.com/snath-ai/lar) — The Glass-Box Agent Engine (v2.0.0)
*The PyTorch for Agents.*

Most agent frameworks are black boxes. When they fail in production, you get a 100-line stack trace and no idea what happened, why, or how much it cost. I built Lár because trust is the only foundation for serious AI systems.

Lár is a **deterministic, define-by-run graph execution engine**. Every node, every state change, and every decision is logged to a forensic flight recorder.

- **EU AI Act Compliance Backbone**: 12 primitives implementing every step of the Nannini et al. (2026) compliance sequence — `CredentialVault`, `HumanJuryNode`, `LethalTrifectaGuard`, `ComplianceManifestGenerator`, `RuntimeStateVersioner`, and more. The only framework that produces three HMAC-signed audit artefacts (causal trace, authority ledger, action inventory) on every run.
- **The Finance Showcase**: Run `python examples/compliance/22_eu_ai_act_finance_showcase.py` — a live €500,000 SME credit decision through all 12 primitives. [docs.snath.ai/compliance/finance-showcase](https://docs.snath.ai/compliance/finance-showcase/)
- **Fractal Agency**: `AdaptiveNode` composes new graph sub-topologies at runtime, guarded by a deterministic `TopologyValidator`. Self-modification is an auditable event, not a security risk.
- **The Numbers**: 1% LLM + 99% code hybrid architecture. 0.08s latency vs 60s+ in standard frameworks. 10,000+ steps without a single error where others hit recursion limits at step 25.

### [Lár-JEPA](https://github.com/snath-ai/Lar-JEPA) — Post-LLM Orchestration
*The universal nervous system for world models.*

Lár-JEPA is the execution spine for **Predictive World Models**. It solves the "Autoregressive Bottleneck" by routing high-dimensional **latent tensors** directly—bypassing text prompting entirely.

- **Unified Model Routing**: Routes LLMs, JEPAs, and GNNs as first-class `AbstractCognitiveNode` instances in the same graph.
- **Mathematical Safety**: Uses a `TensorSafeEncoder` for native tensor logging and a **Spatial Kinematics Engine** to veto structurally entropic predictions (physics-based routing).
- **Domain Isomorphism**: The same architecture that predicts spatial trajectories predicts molecular conformational phase shifts. The graph is the abstraction.
- **System 1 / System 2**: Formally orchestrates the difference between fast-reflex execution and deep-simulation planning in latent manifolds.

### [DMN](https://github.com/snath-ai/DMN) — Bicameral Memory Architecture
*Autopoietic AI: An organism, not a tool.*

Standard agents suffer from amnesia. DMN implements a biologically-inspired **Default Mode Network**—a 24/7 background cognitive system for memory consolidation.

- **3-Tier Memory Architecture**: Parallel management of **Hot** (Working), **Warm** (Semantic), and **Cold** (Episodic) memory tiers.
- **The Neuro-Architecture**: Implements a **Thalamus** gateway, a **Prefrontal Cortex** for context compression, and an **Amygdala** for persistent emotional state (Valence/Arousal).
- **Wake Up Protocol**: Consolidates raw interaction logs into narratives during "sleep" periods, injecting the "Last Dream" back into the prompt upon waking to solve catastrophic forgetting.

---

## Other Work

**[BreakHis Classifier](https://github.com/axdithyaxo/BreakHis_Classifier)** — ResNet-50 breast cancer classifier on histopathology data. 0.96 F1-score, 0.98 AUC.

**[MCP BioForensics](https://github.com/axdithyaxo/mcp-bioforensics)** — Clinical trial data exploration via Model Context Protocol. Natural-language querying over 17,000+ ClinicalTrials.gov records with hybrid semantic + SQL retrieval and conversational follow-up.

**[MCP Forensic Toolkit](https://github.com/axdithyaxo/mcp-forensic-toolkit)** — AI-enabled digital forensics: log triage, SHA-256 file integrity, correlation engine, audit-grade forensic reports.

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
Lár → deterministic execution (Glass Box)
Lár-JEPA → world model orchestration (Nervous System)
DMN → persistent bicameral memory (Hippocampus/PFC)
AdaptiveNode → safe self-modification (Evolution with an audit trail)
```

**Execution spine → World modelling → Persistent memory → Self-awareness.**

A complete cognitive architecture. Built from scratch. In public. Under Apache 2.0.

---

## Background

MSc Data Analytics, Dublin City University.
Kerala → Dublin.
Future: CTO, Snath AI.

---

[axdithya@gmail.com](mailto:axdithya@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aadithya-vishnu-sajeev-853a341a6/) · [snath.ai](https://snath.ai) · [docs.snath.ai](https://docs.snath.ai)

---

*"Apna time aayega."*

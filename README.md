# The I-Am Engine 🧠⚡
*A Sovereign Synthetic Cognition, Continuity, and Identity Architecture*

[![License: Apache 2.0](https://img.shields.io/badge/License--Apache%202.0-blue.svg)](LICENSE)
[![Architecture Status](https://img.shields.io/badge/Status-v1.0%20Core%20Prototype-orange.svg)]()

---

## 🛑 The Modern AI Crisis: Context Rot & Amnesia
Current generative AI architectures suffer from three fatal flaws:
1. **Chat Rot:** As context windows bloat with raw dialogue history, reasoning degrades, hallucination rates spike, and the agent loses its anchor.
2. **Reactive Statelessness:** Models wake up blank every session, relying entirely on static system prompts rather than a dynamic, evolving sense of "self."
3. **Simulated Compliance:** Traditional safety layers use post-hoc filters that break down or fight against the model's native logic, leading to brittle, easily bypassed guardrails.

---

## 🏛️ The Solution: The I-Am Engine Architecture
The **I-Am Engine** is an open-source operating system designed to give artificial agents continuous self-presence, stable memory hierarchies, and autonomous cognitive rhythms, a belief system, and imagination and development arc. 

Rather than treating an LLM as a stateless completion engine, the I-Am Engine wraps it in an industrial cognitive nervous system:

---

## ⚙️ Core Subsystems & Frameworks

### 1. The Presence Center (`engine/presence_center.py`)
The invariant core of the system. It does not store raw chat history; it maintains a queryable state vector (`SUIN`, `focus_level`, `load_level`, `stability_score`, `drift_score`) that persists identity across turns and sessions.

### 2. The Threadless Pipeline (`threadless/`)
The zero-noise reset engine. Instead of drowning in bloated conversation logs, Threadless triggers structural snapshots, distills high-density **Continuity Packets**, archives episodic "Scroll Capsules," and purges raw chat history—rebooting the agent fresh without losing identity or context.

### 3. Intrinsic Value Regulation System (IVRS)
A value-alignment framework that binds the agent's decisions to internal core values rather than external, brittle restrictions, ensuring organic, sovereign ethical consistency.

### 4. Speculative Cognitive Imagination Framework (SCIF)
An isolated sandbox for intuition, hypotheses, and narrative interpretations. It allows the agent to reason about user intent and future trajectories *without* contaminating factual memory.

### 5. Synthetic Life-Cycle Trajectory Framework (SLCTF)
Manages the agent's developmental arc, tracking milestones, stage progression, and long-term capability growth over time.

---
iamengine/
│
├── engine/              # Core Psyche & Autonomic Loops (Presence, CRE, Heartbeat)
│   ├── presence_center.py  # The Invariant Self-Anchor (SUIN, Load, Focus, Drift)
│   ├── capability_engine.py # CRE: Early-check execution & teaching pivots
│   └── heartbeat.py        # Autonomous background pulse-chain
├── memory/              # 6-Layer Hierarchical Memory Substrate & Router
│   ├── router.py           # Swappable interface (SQLite, Chroma, Pinecone)
│   └── layers/             # L1 (Input) to L6 (Identity Memory)
├── threadless/          # Threadless Continuity & Zero-Noise Reset Pipeline
├── ivrs/                # Intrinsic Value Regulation System (Conscience & Beliefs)
├── scif/                # Speculative Cognitive Imagination Framework (Intuition & Hypotheses)
└── slctf/               # Synthetic Life-Cycle Trajectory Framework (Developmental Arcs)

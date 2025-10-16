# SkaDB — The Structured Knowledge Accumulation DataBase

**SkaDB** is a forward-only knowledge database: it records *how knowledge evolves* over time.
It sits above event telemetry (e.g., QuestDB) and turns time-stamped messages into **causal,
entropy-aware knowledge structures**.

> **Principle:** Intelligence is fixed (capacity/structure). Learning is the **irreversible accumulation** of knowledge that reduces uncertainty (entropy) through time.

## Why SkaDB?

- **Forward-only:** no rollback, no overwrite — every update extends history.
- **Entropy-aware:** each record carries a local entropy delta `ΔH` (uncertainty reduction).
- **Causal indexing:** links events into a DAG of “what led to what”.
- **Multi-agent native:** tracks human↔AI and AI↔AI influence via a coupling matrix $ M_ij(t)$.
- **Auditable cognition:** full trace from outcome → causes → messages → timestamps.




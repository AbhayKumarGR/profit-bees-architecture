# Architecture Decision Records

This section records architecture decisions, including context, decision, rationale, alternatives, consequences, and follow-up actions.

## Current baseline decisions

- ADR-AI-001: AI is an on-demand advisory capability; it is never part of trade generation or execution.
- ADR-TIME-001: A centralized Time Service provides business timestamps in `Asia/Kolkata`.
- Broker-specific SDKs are isolated behind a Broker Adapter.
- Strategies are configuration-driven workflows.

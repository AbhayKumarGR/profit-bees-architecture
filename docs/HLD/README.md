# High Level Design

## Purpose

Defines the end-to-end architecture for Profit-Bees, including service boundaries, event-driven processing, Google Cloud deployment, strategy platform, broker abstraction, observability, security, and AI advisory boundaries.

## Core principles

- Event-driven market processing.
- Configuration-driven strategy execution.
- Rule Engine is the authoritative trade decision maker.
- AI is on-demand only and outside the trading execution path.
- Business timestamps are standardized to Asia/Kolkata through the centralized Time Service.
- Broker-specific SDKs are isolated behind a Broker Adapter.

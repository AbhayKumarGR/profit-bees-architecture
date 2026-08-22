# Observability Architecture

Profit-Bees treats observability as a first-class architecture capability.

## Coverage

- Structured application logs
- Correlation IDs
- Service health checks
- Metrics for market ingestion, strategy evaluation and trade generation
- Broker connection and WebSocket metrics
- Distributed tracing with OpenTelemetry
- Cloud Monitoring dashboards and alerts
- Cloud Logging centralization
- Cloud Trace integration
- Operations dashboard and manual diagnostics

Critical business events such as LTP ingestion, strategy evaluation, trade generation and execution shall be traceable with business timestamps normalized through ADR-TIME-001.

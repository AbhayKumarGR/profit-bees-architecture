# Deployment Architecture

Defines containerized deployment of Profit-Bees on Google Cloud.

Core runtime mapping:

- Cloud Run: application microservices
- Cloud SQL for PostgreSQL: durable relational data
- Memorystore for Redis: cache and event distribution
- Artifact Registry: container images
- Cloud Build / Cloud Deploy: CI/CD
- Secret Manager: broker and application secrets
- Cloud Scheduler: market-hour scheduling
- Cloud Storage: reports and artifacts

Market-hour services such as Broker Integration require an always-available runtime posture during the trading window; on-demand services such as AI Advisory may scale to zero.

# Security Architecture

## Principles

- Least-privilege IAM and service identities.
- TLS for external and internal service communication.
- Broker credentials and API keys stored in Google Secret Manager.
- JWT authentication and role-based authorization for application users.
- No credentials or tokens in application logs.
- Audit trail for strategy changes, approvals, trade generation and administrative actions.
- AI remains isolated from the trade execution path.

## Key controls

- Strategy activation requires approval.
- Strategy versions are immutable after activation.
- Trade records retain the strategy version that generated them.
- AI usage and billing events are auditable.

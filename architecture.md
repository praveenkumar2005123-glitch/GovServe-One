# Architecture Notes

## Layers
1. Presentation: citizen, officer and admin interfaces.
2. Edge/API: gateway, TLS termination, routing, rate limiting.
3. Application: service, appointment, document, grievance and notification modules.
4. Data: relational database, cache and object storage.
5. Security/observability: identity, RBAC, audit logs, monitoring and alerting.

## Security principles
- Least privilege
- Server-side authorization
- MFA for privileged roles
- Encryption in transit and at rest
- Secure secrets management
- Auditability
- Backups and tested recovery
- Secure SDLC and dependency management

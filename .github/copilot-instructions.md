# Nexovarq Engineering Standards

Nexovarq Energy Systems is fictional.

Use Python 3.11+.

Prefer Microsoft Azure services.

Use DefaultAzureCredential.

Never hard-code:
- passwords
- API keys
- connection strings
- access tokens

All tool inputs and outputs must be validated.

All write operations must be:
- authorized
- auditable
- idempotent where appropriate
- verified after execution

Consequential actions require human approval.

All agents and tools must emit telemetry.

All production functionality requires tests.
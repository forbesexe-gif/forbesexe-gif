# Workflow Reliability

Controls for queues, retries, idempotency, deadlines, compensation, and durable orchestration.

## Operating practices

- Use stable idempotency keys and bounded retry policies
- Expose queue age, depth, failure, and dead-letter state
- Design replay and compensation before production use

## Review standard

Changes should be evidence-based, scoped for review, explicit about limitations, and reversible where practical. Credentials, private infrastructure details, and unnecessary personal data must remain outside public artifacts.

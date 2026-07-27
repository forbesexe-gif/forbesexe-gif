# Database Design

Practices for durable schemas, migrations, constraints, transactions, retention, and recovery.

## Operating practices

- Model invariants with database constraints where practical
- Use reviewed, reversible migrations and tested backups
- Index from observed query patterns and measure write amplification

## Review standard

Changes should be evidence-based, scoped for review, explicit about limitations, and reversible where practical. Credentials, private infrastructure details, and unnecessary personal data must remain outside public artifacts.

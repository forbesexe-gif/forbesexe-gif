# Secrets Management

Controls for creating, storing, distributing, rotating, revoking, and auditing credentials and cryptographic material.

## Operating practices

- Keep secrets outside source control, prompts, logs, and build artifacts
- Use scoped identities and managed secret stores
- Test rotation and revocation before an incident

## Review standard

Changes should be evidence-based, scoped for review, explicit about limitations, and reversible where practical. Credentials, private infrastructure details, and unnecessary personal data must remain outside public artifacts.

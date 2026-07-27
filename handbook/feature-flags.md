# Feature Flags

Practices for bounded rollout, capability control, experimentation, and emergency disablement.

## Operating practices

- Define owners, defaults, audience, and expiration
- Evaluate authorization again at execution time
- Remove stale flags and test both enabled and disabled paths

## Review standard

Changes should be evidence-based, scoped for review, explicit about limitations, and reversible where practical. Credentials, private infrastructure details, and unnecessary personal data must remain outside public artifacts.

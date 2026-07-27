# Secure Coding

Implementation practices that reduce common input, authorization, dependency, concurrency, and data-handling failures.

## Operating practices

- Validate at trust boundaries and encode output for its context
- Centralize authorization and fail closed
- Use safe libraries, bounded resources, and explicit error handling

## Review standard

Changes should be evidence-based, scoped for review, explicit about limitations, and reversible where practical. Credentials, private infrastructure details, and unnecessary personal data must remain outside public artifacts.

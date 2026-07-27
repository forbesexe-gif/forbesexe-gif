# Prompt and Tool Safety

Boundaries for model inputs, retrieved content, tool calls, and externally visible side effects.

## Operating practices

- Treat prompts, retrieval, and model output as untrusted data
- Expose only minimal, typed, policy-checked tools
- Require deterministic authorization immediately before side effects

## Review standard

Changes should be evidence-based, scoped for review, explicit about limitations, and reversible where practical. Credentials, private infrastructure details, and unnecessary personal data must remain outside public artifacts.

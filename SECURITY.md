# Security Policy

## Reporting

Report suspected vulnerabilities privately through GitHub Security Advisories when enabled. Do not include API keys, private prompts, customer content or sensitive tool outputs in public issues.

Include affected version, configuration, reproduction steps and impact using sanitized fixtures.

## Data handling

Context pruning may process tool responses, prompts and other potentially sensitive context. Preserve source boundaries and do not silently transmit content to external services. Document any telemetry or remote processing, redact secrets in diagnostics, and keep credentials outside the repository.

Filtering must not remove safety-critical instructions, authorization context, provenance or information needed to interpret a tool result. Treat malformed or adversarial tool output as untrusted input.

# Security Policy

Most of CommonPractices is documentation. The exception is **`CommonTongue`**, which ships **code you
depend on** — the generated types and the hand-written protocol adapters that every product links.

## Reporting a vulnerability

Do not open a public issue. Report privately through
[GitHub Security Advisories](https://github.com/CommonPractices) on the affected repo, or by email to
**`<security contact — TBD>`**.

A flaw in a CommonTongue adapter — a parser bug, a framing error, a version-negotiation mistake — is
inherited by **every product that depends on it**, so it is treated as high-impact.

# Contributing to CommonPractices

CommonPractices holds the shared standards — `CommonMind` (principles), `CommonFraming` (shapes),
`CommonTongue` (contracts). A change here moves the ground other projects stand on, so the bar is
different from a product repo.

## Before you propose

- **Read the doctrine you're touching.** It states its own rules; a proposal that contradicts them
  must argue *why*, not ignore them.
- **Check the altitude.** A rule true of one project belongs in that project, not here. Only
  genuinely cross-project facts belong in `CommonMind` (Single-Source-of-Truth Doctrine).
- **`CommonTongue` is a contract.** Changes are **additive-only within a version** — never remove,
  rename, or retype a field. A real break forks a new version *alongside* the old (Interface
  Stability Doctrine).

## How

1. Open an issue describing the change **and the altitude it belongs at**.
2. Drafts land in `docs/_working/`; **nothing self-promotes** — the owner cuts and promotes.
3. Provenance and status are explicit: mark what is verified, documented, or assumed.

## Licensing

Docs and schema under the repository's license; `CommonTongue` code is **Apache-2.0** unless a repo
states otherwise.

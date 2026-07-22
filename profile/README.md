# CommonPractices — the shared substrate

CommonPractices holds the standards every other family here is built on. It is not a product; it is
the ground they stand on. Independent programs interoperate because they conform to the same
practices — not because they share code.

## The altitude stack

Three layers, rising in commitment. **CommonTongue's README is the single source of truth for the
stack** — this is an index that points at it, not a restatement:

- **`CommonMind`** — the PRINCIPLES (the why + the rules). You *read* it.
- **`CommonFraming`** — the SHAPES (how to build a recurring kind of thing) — the family's repo of
  product-shape blueprints. You *adapt to* it.
- **`CommonTongue`** — the CONTRACTS (the versioned wire language + per-language packages). You
  *depend on* it.

## Also here

- **`CommonStage`** — the family's shared web presentation layer: the standard, templates, styling,
  config schema, and generator for every family Org and product's public web pages. Not part of the
  altitude stack — it *presents* the family rather than governing it. **Design stage; no code yet.**

## How it's governed

Changes flow through the doctrine's own discipline: a changeset holds deltas, never a copy; every
fact lives at exactly one altitude and is *referenced*, not copied, from everywhere else; and the
owner alone promotes — nothing self-promotes. See `CommonMind`'s Documentation, Decision,
Single-Source-of-Truth, and Interface-Stability doctrines.

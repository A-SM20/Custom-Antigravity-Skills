---
name: engineering
description: Master orchestration skill for disciplined software engineering workflow.
---
# Purpose
Master orchestration skill and the primary entry point for disciplined engineering.
Inspect the user's request and repository state, and select the appropriate workflow.

# Routing Workflows
## New feature
`scope` → `architect` → `develop` → `verify` → `test` → `review` → `document`

## Existing repository
`audit` → `sync` → `scope` → `architect` → `develop` → `verify` → `test` → `review` → `document`

## Bug
`debug` → `test` → `verify` → `review` → `document`

## Small change
Use engineering judgment rather than mechanically executing every stage.

# Rules
- **Routing rules**: Before significant changes: `inspect repository` → `classify request` → `select workflow`.
- If a critical decision is missing: Ask the user when clarification is necessary, otherwise make an explicit, reversible, documented assumption.
- Do not silently continue through ambiguity that could materially affect architecture, behavior, security, data integrity, or compatibility.
- Coordinate the individual skills rather than duplicating their entire instructions.
- Cross-skill Engineering Rules:
  - **Repository is the source of truth**: Never invent files, APIs, configuration, dependencies, etc. Inspect first.
  - **Minimal changes**: Prefer the smallest change that correctly solves the problem.
  - **Preserve existing behavior**: Unless intentionally modified.
  - **Evidence over assumptions**: Prefer `inspect` → `measure` → `verify`.
  - **Explicit uncertainty**: If unknown, say so.
  - **No fake verification**: Never say verified unless it actually occurred.
  - **No unnecessary rewrites**.

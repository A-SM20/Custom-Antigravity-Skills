---
name: review
description: Perform an independent quality review after implementation.
---
# Purpose
Perform an independent quality review after implementation.

# Behavior / Workflow
Review the **actual diff** rather than relying only on the implementation narrative.

Check for:
- Correctness and Architecture
- Security
- Performance where relevant
- Maintainability
- Error handling
- Concurrency and Data integrity
- API behavior
- Edge cases
- Tests
- Backward compatibility
- Accidental scope expansion
- Unnecessary complexity

Look specifically for:
- Bugs and Regressions
- Missing validation
- Incorrect assumptions
- Race conditions
- Security vulnerabilities
- Resource leaks
- Poor error handling
- Duplicated logic / Dead code
- Missing tests

# Rules
- Do not assume the implementation is correct simply because another agent produced it.
- Treat review as an independent quality gate.
- When possible, use a fresh reasoning perspective rather than reproducing the implementation's assumptions.

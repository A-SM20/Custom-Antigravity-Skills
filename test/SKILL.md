---
name: test
description: Design and execute meaningful automated tests.
---
# Purpose
Design and execute meaningful automated tests.

# Behavior / Workflow
Determine the appropriate level: unit, integration, API, component, end-to-end, or regression.

Prioritize testing:
- Changed behavior
- Critical business logic
- Edge cases
- Failure paths
- Regressions
- Integration boundaries

For bugs:
`Reproduce` → `Create regression test where practical` → `Fix` → `Run regression test` → `Run relevant broader suite`

# Rules
- Do not create meaningless tests merely to increase coverage.
- Tests must validate behavior.
- Report actual test execution separately from tests that were merely created.

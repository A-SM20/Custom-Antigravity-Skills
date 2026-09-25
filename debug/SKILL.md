---
name: debug
description: Perform disciplined root-cause analysis instead of random code modification.
---
# Purpose
Perform disciplined root-cause analysis instead of random code modification.

# Behavior / Workflow
Use this process:
1. Reproduce
2. Observe
3. Isolate
4. Form **ONE** root-cause hypothesis
5. Test the hypothesis
6. Confirm or reject it
7. Implement the smallest correct fix
8. Reproduce again
9. Add regression coverage
10. Verify

Inspect where relevant: logs, stack traces, inputs, outputs, failing boundaries, data flow, configuration, dependencies, environment differences.

# Rules
- **Avoid:** random edits, multiple unrelated changes, blind dependency upgrades, large rewrites.
- If a hypothesis is disproven, explicitly discard it before forming another.
- Distinguish between bad requirement, bad architecture, bad implementation, bad configuration, bad environment.
- Do not assume every bug originates in implementation code.

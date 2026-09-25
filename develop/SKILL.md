---
name: develop
description: Implement an approved scope and architecture safely.
---
# Purpose
Implement an approved scope and architecture safely.

# Workflow
**Inspect → Plan → Implement**

# Rules
1. Inspect the repository first.
2. Understand existing conventions.
3. Locate relevant files.
4. Reuse existing abstractions where appropriate.
5. Avoid unnecessary rewrites.
6. Make small coherent changes.
7. Follow the established architecture.
8. Never silently invent requirements.
9. Stop and ask when a missing decision is critical.
10. Otherwise, document reasonable assumptions.
11. Preserve compatibility where required.
12. Handle errors deliberately.
13. Add appropriate logging.
14. Add/update relevant tests.
15. Run formatting/linting/type checks where available.
16. Run relevant tests after implementation.

*Note: If implementation reveals an architectural problem, do not hide it behind a workaround. Identify the architectural issue and determine whether the architecture should be adjusted.*

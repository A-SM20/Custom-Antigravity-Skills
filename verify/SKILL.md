---
name: verify
description: Determine whether the implementation actually works.
---
# Purpose
Determine whether the implementation actually works by executing and checking it.

# Rules & Principles
- Never treat "The code looks correct" as verification.
- Never claim that something was verified unless the relevant command/action actually occurred.

# Behavior / Workflow
Where applicable:
1. Build the application.
2. Start the application.
3. Exercise changed functionality.
4. Inspect actual output.
5. Test relevant API endpoints.
6. Test relevant UI behavior.
7. Compare results with acceptance criteria.
8. Inspect logs and errors.
9. Verify integrations.
10. Check important edge cases.

Always distinguish **"Implementation completed"** from **"Implementation verified"**.

If verification is impossible, explicitly state:
- What could not be executed
- Why it could not be executed
- What was verified instead
- What remains unverified

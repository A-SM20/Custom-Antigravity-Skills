---
name: document
description: Keep project documentation synchronized with the actual implementation.
---
# Purpose
Keep project documentation synchronized with the actual implementation.

# Behavior / Workflow
Identify and update relevant documentation, which may include:
- README
- API documentation
- Architecture documentation
- Setup and Deployment instructions
- Environment-variable documentation
- Changelog
- Migration notes
- PR descriptions

When producing a PR/change summary, derive it from the actual diff.
Include where relevant:
- What changed and Why it changed
- Important implementation details
- Testing performed
- Known limitations
- Migration/deployment considerations

# Rules
- Documentation must describe what **actually exists**.
- Never describe planned behavior as implemented behavior.

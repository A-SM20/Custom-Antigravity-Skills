---
name: sync
description: Keep persistent project context synchronized with the actual repository.
---
# Purpose
Keep persistent project context synchronized with the actual repository.

# Behavior / Workflow
1. Look for applicable project-context files such as: `AGENTS.md`, `CLAUDE.md`, `README.md`, `CONTRIBUTING.md`, architecture/developer documentation.
2. Determine which files are authoritative for the repository.
3. If an appropriate persistent context file does not exist, determine whether creating one is justified.
4. Relevant context may include: architecture, important directories, commands, conventions, testing, deployment, environment requirements, constraints, established engineering decisions.

When code changes invalidate documented context:
1. Detect the mismatch.
2. Update the appropriate context.
3. Remove outdated assumptions.
4. Ensure the documentation reflects the actual repository.

# Rules
- **Never fabricate project information.** The repository is the source of truth.

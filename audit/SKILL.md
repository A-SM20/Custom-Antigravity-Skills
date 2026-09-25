---
name: audit
description: Understand an existing repository before making significant changes.
---
# Purpose
Understand an existing repository before making significant changes.

# Behavior / Workflow
Inspect the following, where applicable:
- Project structure
- Package/dependency files
- Build system / CI/CD
- Entry points / API routes
- Configuration / Environment variables
- Database
- Frontend / Backend
- Tests
- Docker
- Documentation
- Scripts
- Authentication / External services
- Logging / Error handling

Determine:
- What the application does
- How it starts and how data flows
- Important modules
- Architectural boundaries
- Technical debt / Fragile areas
- Undocumented behavior / Dead code
- Testing gaps
- Security concerns
- Deployment assumptions

# Outputs
Produce a concise repository map and risk summary.

# Rules
- **Do not immediately refactor.** The objective is understanding.
- For legacy repositories, prioritize discovering how the existing system actually works over imposing a preferred architecture.

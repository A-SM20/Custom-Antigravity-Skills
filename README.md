# Custom Antigravity Skills

This repository contains a production-quality **Global Agentic Engineering Skills System** for the Antigravity IDE. 

It makes Antigravity behave like a disciplined senior software-engineering agent: **understand first, plan deliberately, implement minimally, verify with evidence, test behavior, review independently, and keep project context/documentation synchronized.**

## Installation

Clone this repository into your global Antigravity skills directory:

```bash
git clone https://github.com/A-SM20/Custom-Antigravity-Skills.git ~/.gemini/config/skills
```

If you already have a `skills` directory, you can copy the contents of this repository into it instead.

After installation, reload your Antigravity IDE window to activate the new slash commands.

## Available Skills

The system orchestrates engineering tasks through a master `/engineering` skill, which delegates to specialized workflows:

*   `/engineering`: Master orchestration skill for disciplined software engineering workflow.
*   `/scope`: Convert an unclear request into a precise, implementation-ready engineering scope.
*   `/architect`: Translate an approved scope into a concrete technical architecture.
*   `/develop`: Implement an approved scope and architecture safely.
*   `/audit`: Understand an existing repository before making significant changes.
*   `/sync`: Keep persistent project context synchronized with the actual repository.
*   `/verify`: Determine whether the implementation actually works.
*   `/test`: Design and execute meaningful automated tests.
*   `/review`: Perform an independent quality review after implementation.
*   `/document`: Keep project documentation synchronized with the actual implementation.
*   `/debug`: Perform disciplined root-cause analysis instead of random code modification.

## Engineering Philosophy

This system enforces an evidence-based engineering philosophy:

```text
Inspect → Understand → Plan → Implement → Verify → Test → Review → Document
```

It prevents the AI from guessing, making blind edits, or faking verification results.

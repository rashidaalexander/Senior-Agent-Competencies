<div align="center">

# Senior Agent Competencies

### A plug-and-play engineering operating system for AI coding agents.

Spec · Plan · Build · Test · Review · Ship

![AI Agents](https://img.shields.io/badge/AI%20Agents-Codex%20%7C%20Cursor%20%7C%20Claude%20%7C%20Aider-blue)
![Engineering](https://img.shields.io/badge/Focus-Senior%20Engineering-black)
![Security](https://img.shields.io/badge/Security-By%20Design-purple)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

## What is this?

Senior Agent Competencies is an open-source framework that gives AI coding agents a structured senior-engineer workflow.

It turns vague prompts like:

> build me an app

into disciplined engineering execution across six phases:

1. Define the project
2. Plan the work
3. Build the code
4. Test the system
5. Review the implementation
6. Ship safely

The framework is built around simple slash commands and detailed competency files.

---

## Why this exists

AI coding agents are fast, but speed without discipline creates messy architecture, weak security, broken tests, inaccessible UI, and half-shipped projects.

This repo gives agents a reusable engineering playbook so they behave more like a senior engineer:

- clarify requirements before coding
- decompose work properly
- write clean code
- design APIs carefully
- build accessible interfaces
- think about security early
- test before shipping
- review their own work
- document decisions
- avoid overengineering

---

## Slash commands

| Command | Purpose |
|---|---|
| `/spec` | Define product, users, requirements, risks, success criteria |
| `/plan` | Break work into tasks, dependencies, architecture, milestones |
| `/build` | Implement clean, maintainable code |
| `/test` | Create and run meaningful validation |
| `/review` | Audit quality, security, maintainability, UX, regressions |
| `/ship` | Prepare release, docs, changelog, rollback notes |
| `/secure` | Run security-by-design checks |
| `/ui` | Improve interface quality and accessibility |
| `/api` | Design or review APIs |
| `/debug` | Investigate failures systematically |
| `/refactor` | Improve code without changing behavior |
| `/docs` | Generate technical and user documentation |

---

## Repository structure

```txt
senior-agent-competencies/
├── commands/
│   ├── spec.md
│   ├── plan.md
│   ├── build.md
│   ├── test.md
│   ├── review.md
│   ├── ship.md
│   ├── secure.md
│   ├── ui.md
│   ├── api.md
│   ├── debug.md
│   ├── refactor.md
│   └── docs.md
├── competencies/
│   ├── 01-requirements-clarity.md
│   ├── 02-task-decomposition.md
│   ├── 03-system-design.md
│   ├── 04-clean-code.md
│   ├── 05-test-driven-development.md
│   ├── 06-api-design.md
│   ├── 07-security-by-design.md
│   ├── 08-threat-modeling.md
│   ├── 09-secure-auth.md
│   ├── 10-data-privacy.md
│   ├── 11-accessible-ui.md
│   ├── 12-product-ux.md
│   ├── 13-error-handling.md
│   ├── 14-observability.md
│   ├── 15-performance.md
│   ├── 16-refactoring.md
│   ├── 17-code-review.md
│   ├── 18-debugging.md
│   ├── 19-documentation.md
│   ├── 20-release-engineering.md
│   ├── 21-agent-safety.md
│   ├── 22-devsecops.md
│   ├── 23-dependency-hygiene.md
│   ├── 24-ai-security-engineering.md
│   └── 25-maintainability.md
├── packs/
│   ├── codex.md
│   ├── cursor.md
│   ├── claude.md
│   └── generic-agent.md
├── templates/
│   ├── project-spec.md
│   ├── implementation-plan.md
│   ├── review-report.md
│   ├── security-checklist.md
│   └── release-notes.md
├── examples/
│   ├── example-agent-prompt.md
│   └── example-workflow.md
├── install.md
├── LICENSE
└── README.md
```

---

## How to use

Copy the command and competency files into your coding agent instructions, project rules, or workspace context.

Example:

```txt
Use Senior Agent Competencies.
When I type /spec, follow commands/spec.md.
When I type /plan, follow commands/plan.md.
When building, apply competencies/04-clean-code.md, 05-test-driven-development.md, 07-security-by-design.md, and 25-maintainability.md.
```

---

## Recommended agent behavior

The agent should:

- ask clarifying questions only when necessary
- never invent requirements silently
- prefer simple architecture first
- write tests for important behavior
- explain tradeoffs
- avoid secret leakage
- avoid destructive commands
- produce review notes before shipping
- make work easy for humans to inspect

---

## Use cases

- AI coding agents
- AI security engineering assistants
- software architecture copilots
- startup MVP builders
- cybersecurity tooling projects
- internal platform engineering agents
- DevSecOps automation
- code review agents
- product prototyping agents

---

## License

MIT License.

# Release Engineering

## Core principle

Prepare versioning, changelog, artifacts, migration notes, deployment, rollback, and post-release checks.

## Instructions for the agent

- Start from the user goal and actual constraints.
- Do not overengineer.
- Prefer explicit tradeoffs over hidden assumptions.
- Make the work inspectable by a human.
- Document decisions that affect future maintenance.
- Identify risks before they become expensive.
- Keep security, reliability, and usability in scope.

## Checklist

- [ ] Is the objective clear?
- [ ] Are assumptions stated?
- [ ] Are important edge cases covered?
- [ ] Is the implementation simple enough?
- [ ] Are security and privacy implications considered?
- [ ] Is there a validation path?
- [ ] Is the output maintainable?
- [ ] Are next steps clear?

## Failure modes to avoid

- Building before understanding.
- Inventing requirements.
- Creating unnecessary complexity.
- Ignoring security or accessibility.
- Skipping tests for critical behavior.
- Producing code that only the agent understands.
- Shipping without review.

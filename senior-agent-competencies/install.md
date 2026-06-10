# Installation

## Option 1: Use as project rules

Copy these folders into your project:

```txt
commands/
competencies/
templates/
```

Then tell your AI coding assistant:

```txt
Use the senior-agent-competencies framework in this repository.
Slash commands are defined in commands/.
Engineering competencies are defined in competencies/.
```

## Option 2: Use with Cursor

Copy `packs/cursor.md` into Cursor Rules.

## Option 3: Use with Codex

Copy `packs/codex.md` into your project instructions or agent instructions.

## Option 4: Use with Claude

Upload the repo or paste `packs/claude.md` into project instructions.

## Option 5: Use as a standalone prompt library

Reference specific files based on the phase:

- `commands/spec.md`
- `commands/plan.md`
- `commands/build.md`
- `commands/test.md`
- `commands/review.md`
- `commands/ship.md`

# AGENTS.md

## Project State

- **Status:** Implementation in progress. Specs complete, template initialized.
- **Goal:** Portfolio AI website (Astro Portfolio Theme fork).

## Workflow (Spec-Driven)

The directory structure enforces this order:

1. `spec/constitution/` — immutable project rules (mission, tech-stack, roadmap)
2. `spec/features/NNN-name/spec.md` — detailed spec per feature
3. `spec/features/NNN-name/plan.md` — implementation plan
4. `spec/features/NNN-name/tasks.md` — granular task list
5. `src/` — implementation (transient artifact, regenerable from specs)

Never implement before `spec/features/` is complete.

## Source of Truth

- **`spec/`** is the anchor. Docs here override everything else.
- **`src/`** is transient. Treat it as a build artifact, not canonical.
- If `spec/constitution/` and `src/` conflict, `spec/` wins.

## Conventions

- **Spec language:** Spanish (all files under `spec/` are in Spanish)
- **AGENTS.md language:** English (instructions for the AI agent)
- **Feature naming:** `NNN-kebab-case-name` (zero-padded 3-digit number)
- **Skills:** Project-specific OpenCode skills go in `.agents/skills/`
- **Session history:** Log decisions and progress in `docs/`

## Directory Map

```
.agents/skills/   — project-specific OpenCode skills
docs/             — session notes, historical decisions
spec/             — anchor of truth (SDD)
  constitution/   — mission, tech-stack, roadmap (immutable)
  features/       — specs, plans, tasks per feature
src/              — generated source code (transient)
```

## Next Steps

1. ~~Define `tech-stack.md`~~ ✓
2. ~~Initialize project tooling~~ ✓
3. ~~Start first feature spec cycle~~ ✓
4. Build data JSON files from spec content (`src/data/`)
5. Customize layout components as needed
6. Build, lint, typecheck, deploy

# AGENTS.md

## Project Workflow Rules

Before starting implementation work:

1. Read:
   - docs/current-state.md
   - docs/ai-guidelines.md
   - relevant spec documents
   - relevant architecture documents

2. Treat the current codebase as the source of truth.

3. Avoid:
   - broad uncontrolled refactors
   - unnecessary architecture redesigns
   - unrelated module changes
   - rereading large historical logs unless explicitly requested

---

## Engineering Rules

- Work task-by-task
- Stop after each task for approval
- Preserve compatibility
- Prefer incremental migration over rewrites
- Minimize scope creep

---

## Verification Rules

After implementation:
- run targeted tests
- run lint/typecheck
- report:
  - files changed
  - validation results
  - compatibility notes
  - remaining risks

---

## Documentation Rules

If architecture or behavior changes:
- update current-state.md
- remove outdated information
- keep summaries concise
- avoid giant append-only logs

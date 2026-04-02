# Agent Guide (project-level)

This file is an operational index for agents working in this repository. **Update this index whenever the repository structure, entrypoints, or key documents change.**

## Repository purpose

- `selform-charter` is an **EN-first, bilingual (EN/中文)** charter repository for Selform.
- Scope: conceptual / philosophical / ethical framing around *agency*, *truth*, and *self-formation*.
- Non-scope: product scoping (MVP/features/growth) and engineering implementation / technical roadmap.

## Canonical language policy

- English under `en/` is canonical.
- Chinese under `zh/` mirrors English (may lag; mark translation status when needed).

## Index (entrypoints)

- Primary entry: `README.md`
- English navigation root: `en/INDEX.md`
- Chinese navigation root: `zh/INDEX.md`

## Index (structure)

- Charter (thin but hard): `en/charter/INDEX.md`, `zh/charter/INDEX.md`
- Concepts: `en/concepts/INDEX.md`, `zh/concepts/INDEX.md`
- Principles: `en/principles/INDEX.md`, `zh/principles/INDEX.md`
- Risks: `en/risks/INDEX.md`, `zh/risks/INDEX.md`
- Open questions: `en/questions/INDEX.md`, `zh/questions/INDEX.md`
- Dialogue syntheses (publishable): `en/dialogues/INDEX.md`, `zh/dialogues/INDEX.md`
- Decision records (meta): `en/decisions/INDEX.md`, `zh/decisions/INDEX.md`

## Index (key syntheses)

- 2026-04-01 synthesis: `en/dialogues/2026-04-01-selform-ideation-synthesis.md`, `zh/dialogues/2026-04-01-selform-ideation-synthesis.md`
- 2026-04-02 synthesis: `en/dialogues/2026-04-02-selform-ethics-and-subject-formation-synthesis.md`, `zh/dialogues/2026-04-02-selform-ethics-and-subject-formation-synthesis.md`

## Index (key constraints & decisions)

- Must not define product boundaries (default): `en/decisions/decision-must-not-define-product-boundaries.md`, `zh/decisions/decision-must-not-define-product-boundaries.md`
- Avoid “user” framing by default: `en/decisions/decision-terminology-no-user.md`, `zh/decisions/decision-terminology-no-user.md`
- Prefer auditable reasoning interface (vs raw CoT): `en/decisions/decision-auditable-interface-over-raw-cot.md`, `zh/decisions/decision-auditable-interface-over-raw-cot.md`

## Index (governance & license)

- License (CC BY 4.0): `LICENSE`, `LICENSE.zh.md`
- Attribution block: `ATTRIBUTION.md`
- Contribution guide: `GOVERNANCE/CONTRIBUTING.md`
- Code of conduct: `GOVERNANCE/CODE_OF_CONDUCT.md`
- Governance process: `GOVERNANCE/GOVERNANCE.md`

## Index (templates)

- English templates: `TEMPLATES/en/`
- Chinese templates: `TEMPLATES/zh/`

## Index (community discussion templates)

- Discussion category forms (GitHub): `.github/DISCUSSION_TEMPLATE/`
- Copyable discussion prompts: `TEMPLATES/en/discussion-*.md`, `TEMPLATES/zh/discussion-*.md`

## Index (repo memory system)

- Durable memory: `MEMORY.md`
- Task log: `WORKLOG.md`
- Repo-level decisions: `DECISIONS.md`
- Plans: `PLANS/`
- Specs: `SPECS/`

## Update protocol (must-do after changes)

After any repository update, do all applicable items:
- Update `AGENT.md` indexes if paths/entrypoints changed.
- Append a new entry to `WORKLOG.md`.
- Update `MEMORY.md` only for durable conventions/quirks.
- Update `DECISIONS.md` only for meaningful, lasting decisions.
- Add/update `PLANS/` and/or `SPECS/` if scope/behavior changes warrant it.

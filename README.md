# auf.so

Operating knowledge base for **Auf**, a Swiss association (Verein)
incubating founders and researchers connected to the ETH/Zurich ecosystem.

This repo is process and documentation only — there is no application code
here. The public-facing website lives in a separate repo.

Start with [`strategy/narrative.md`](strategy/narrative.md) if you're new —
it's the canonical "what is Auf and why" doc.

## Map

| Area | What's there |
|---|---|
| [`governance/`](governance/) | Legal setup: statutes, board, minutes, entity registry, tax status, data protection rules, templates |
| [`donors/`](donors/) | Fundraising strategy, donor pipeline (tracked via GitHub Issues), records, receipts, reporting, comms templates |
| [`participants/`](participants/) | Cohort model, application process (tracked via GitHub Issues), support offered, participant profiles, onboarding, mentors, alumni |
| [`operations/`](operations/) | Shared calendar, finance, communications |
| [`strategy/`](strategy/) | Canonical narrative — read first |
| [`planning/`](planning/) | Working notes and roadmaps |
| [`.github/`](.github/) | Issue templates and scheduled workflows that drive the donor and application pipelines |

## How this repo works

- **Markdown = policy and point-in-time records**, reviewed via pull request.
  Statutes, board composition, process docs, strategy, templates.
- **Live status = GitHub Issues + labels.** A donor's pipeline stage or an
  applicant's review stage changes often and cheaply — it lives on an Issue,
  not in a hand-edited file. See [`donors/pipeline.md`](donors/pipeline.md)
  and [`participants/application.md`](participants/application.md).
- **No real PII in git, ever.** Not payment details, not financial need, not
  immigration status — see
  [`governance/data-protection.md`](governance/data-protection.md).

Agents working in this repo should read
[`.agent/instructions.md`](.agent/instructions.md) (symlinked as
`CLAUDE.md` / `AGENTS.md`) first.

## Status

This repo was bootstrapped with a full directory structure and draft content
throughout. Many documents contain `[bracketed placeholders]` for facts the
founding team still needs to supply — legal names, board composition, tax
status, cadence details. Nothing with a placeholder should be treated as
final or filed with authorities until reviewed and completed by the
founding team.

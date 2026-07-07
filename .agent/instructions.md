# Agent instructions — auf.so

This file is the canonical set of instructions for any AI agent (Claude, or
otherwise) working in this repository. `CLAUDE.md` and `AGENTS.md` at the repo
root are symlinks to this file — edit here, not there.

## What this repo is

`auf.so` is the **operating knowledge base** for Auf, a Swiss association
(Verein) incubating founders and researchers connected to the ETH/Zurich
ecosystem. It holds governance documents, donor/fundraising process,
participant/cohort process, and internal operations docs.

## What this repo is not

- **Not the public website.** The public-facing site lives in a separate
  repo. Nothing here is assumed to be published; treat this as an internal
  operating repo unless told otherwise.
- **Not a database.** Anything that changes state often (a donor's pipeline
  stage, an applicant's review stage) does not belong in a hand-edited
  markdown file — see "Markdown vs. Issues" below.
- **Not a place for real personal data.** See "No real PII" below — this is
  a hard rule, not a style preference.

## Markdown vs. GitHub Issues

Two kinds of information live in this repo, and they go in different places:

1. **Policy and point-in-time records** (statutes, board composition, process
   descriptions, templates, strategy) → **markdown, reviewed via PR.** This is
   the source of truth for "how we operate" and "what was decided."
2. **Live, frequently-changing state** (where a specific donor is in the
   pipeline, where a specific applicant is in review) → **GitHub Issues +
   labels.** Issues are cheap to update, have a visible history/comment
   thread, and don't require a PR review cycle for a status change.

Per-donor and per-participant markdown files (see `donors/records/` and
`participants/profiles/`) exist only as a stable, de-identified index —
they **link to the tracking issue**, they do not duplicate or shadow its
live status. If you find yourself editing a stage/status field directly in
markdown, stop — that update belongs on the linked Issue instead.

See `donors/pipeline.md` and `participants/application.md` for the exact
label taxonomies.

## No real PII, ever

Git history is permanent and access control here is repo-wide, not
field-level — there is no way to redact a field later without rewriting
history. Never commit real:

- payment or bank details
- financial need / hardship information
- immigration or residency status
- any other sensitive personal data

...even though this repo may be private. Keep only de-identified/structural
fields (status, tier, track, dates). Full details are in
`governance/data-protection.md` — **where the real PII for donors and
participants should live is still an open decision for the founding team**,
not something to invent or improvise. If a task seems to require storing
real PII in this repo, stop and flag it instead of proceeding.

## Participant model

Auf supports founders, researchers, and people who don't fit neatly into
either bucket. Do not hard-code "founder" or "researcher" as the only two
tracks anywhere (docs, templates, issue forms) — the model in
`participants/model.md` is deliberately flexible per cohort. When adding or
editing participant-facing content, preserve that flexibility.

## Repo map

```
governance/    legal setup: statutes, board, minutes, entity registry, tax status, data protection
donors/        fundraising: strategy, pipeline (issues-based), records, receipts, reporting, comms
participants/  cohort process: model, application (issues-based), support offered, profiles, onboarding, mentors, alumni
operations/    calendar, finance, communications
strategy/      narrative.md — canonical "what is Auf and why", read this first
planning/      working notes / roadmaps
.github/       issue templates and scheduled workflows that drive the issues-based pipelines
```

`README.md` at the repo root is the navigation hub — start there.

## Working conventions

- Prefer editing existing docs over creating new ones; keep the structure
  above stable.
- Use `[bracketed placeholders]` for facts that aren't decided yet (legal
  names, dates, board members). Don't invent specifics to fill a gap.
- Changes to governance docs (especially `statutes.md`) should be flagged
  clearly as needing founding-team / board review before being treated as
  final — an agent editing these files is drafting, not deciding.
- See `.agent/skills/README.md` for any repo-specific skills.

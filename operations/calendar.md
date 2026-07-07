# Calendar

Single table of every recurring commitment across governance, donors, and
participants — the point of truth for "what happens when," so this
doesn't have to be reconstructed from five different files.

| Commitment | Frequency | Owner | Source doc |
|---|---|---|---|
| Board meeting | [TBD, e.g. monthly] | Board | `governance/board.md` |
| General Assembly (ordinary) | At least 1x/fiscal year | Board | `governance/statutes.md`, `governance/templates/ga-agenda-template.md` |
| Donor quarterly update | Quarterly | [TBD] | `donors/reporting.md` |
| Annual report | 1x/fiscal year, post-GA | [TBD] | `donors/reporting.md`, `donors/comms/annual-report-outline.md` |
| Donor pipeline review | [TBD, e.g. monthly] | Treasurer | `donors/pipeline.md` |
| Cohort application window | [TBD — see cohort cadence] | [TBD] | `participants/application.md`, `participants/model.md` |
| Stale-application check | Weekly (automated) | N/A (GitHub Action) | `.github/workflows/stale-application-check.yml` |
| Donor report reminder | Quarterly (automated) | N/A (GitHub Action) | `.github/workflows/donor-report-reminder.yml` |

Two of these rows are automated (scheduled GitHub Actions that open a
reminder issue or comment) — the rest need a human owner. Fill in
`[TBD]` owners as roles are confirmed in `governance/board.md`.

## Open questions for the founding team

- [ ] Confirm board meeting cadence.
- [ ] Confirm cohort application window(s) once cadence is decided
  (`participants/model.md`).
- [ ] Assign an owner to each manual row above.

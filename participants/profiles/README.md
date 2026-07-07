# Participant profiles

One file per participant **once accepted** (`applicant/accepted` or later
— see `participants/application.md`). Don't create a profile for every
applicant; that's what the Issue is for during review.

## Template

Create `participants/profiles/<participant-slug>.md` with:

```markdown
# [Participant or team name]

- **Track**: [founder / researcher / mixed / other — per cohort, see
  participants/model.md]
- **Cohort**: [cohort identifier]
- **Tracking issue**: #[issue number] — link, don't duplicate status
- **Status**: [active / alumni — kept loosely in sync with the issue
  label; the issue is still the source of truth]
- **Mentor(s)**: [link to participants/mentors.md entries]

## Notes

[Non-sensitive context: what they're building/researching, public-facing
description, support package summary. No financial need, no immigration
status, no other PII — see governance/data-protection.md.]
```

## What belongs here vs. what doesn't

| Belongs here (de-identified/structural) | Does NOT belong here |
|---|---|
| Track, cohort, tracking issue link | Financial need / hardship info |
| Public-facing project description | Immigration/residency status |
| Mentor assignment | Any data the participant hasn't consented to share, even internally, beyond what's needed to run the program |

If in doubt, leave it out and note "see [system TBD]" — per
`governance/data-protection.md`, the system of record for participant PII
isn't decided yet.

No participant profiles exist yet.

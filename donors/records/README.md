# Donor records

One file per donor **once they've reached `donor/committed` or later** in
the pipeline (see `donors/pipeline.md`) — don't create a record for every
lead, that's what the Issue is for.

## Template

Create `donors/records/<donor-slug>.md` with:

```markdown
# [Donor name or "Anonymous donor #N" if they prefer not to be named]

- **Tier**: [supporter / patron / founding partner — see donors/strategy.md]
- **Category**: [founder / family business / investor / political — see
  donors/strategy.md; matches the `donor/type-*` label on the issue]
- **Tracking issue**: #[issue number] — link, don't duplicate status
- **First committed**: [YYYY-MM-DD]
- **Introduced by**: [name or "cold outreach"]
- **Relationship owner**: [board member name]

## Notes

[Non-sensitive context: how the relationship started, what they care
about, any recognition preferences. No financial details, no payment
info — see governance/data-protection.md.]
```

## What belongs here vs. what doesn't

| Belongs here (de-identified/structural) | Does NOT belong here |
|---|---|
| Tier, donor type, tracking issue link | Bank details, payment references |
| Relationship owner, recognition preferences | Amounts, if the founding team decides amounts are sensitive — [confirm policy] |
| Non-sensitive relationship notes | Any data the donor asked to keep confidential |

If in doubt, leave it out and note "see [system TBD]" — per
`governance/data-protection.md`, the system of record for donor PII isn't
decided yet.

No donor records exist yet.

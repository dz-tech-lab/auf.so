# Application process

**The live application pipeline is tracked as GitHub Issues with labels —
not in this file.** This file documents the process; it does not itself
track individual applicants' status.

## Why Issues, not markdown

An applicant's stage changes as they move through review, needs a comment
history (interview notes, reviewer feedback), and shouldn't require a PR
review cycle to move forward. Issues give us that for free — see
`donors/pipeline.md` for the same reasoning applied to donors.

## How it works

1. An applicant is invited to submit via the
   `.github/ISSUE_TEMPLATE/participant-application.yml` form (or a
   reviewer opens the issue on their behalf if intake happens elsewhere).
   The form should ask track-appropriate questions per
   `participants/model.md` — not assume "founder" or "researcher" as the
   only options.
2. The issue is labeled with exactly one stage label at a time:

   | Label | Meaning |
   |---|---|
   | `applicant/received` | Application submitted, not yet reviewed |
   | `applicant/reviewing` | Under review by the team |
   | `applicant/interview` | Interview stage |
   | `applicant/accepted` | Accepted into a cohort |
   | `applicant/rejected` | Not accepted |
   | `applicant/active` | Currently an active participant |
   | `applicant/alumni` | Completed the program |

3. A scheduled check (`.github/workflows/stale-application-check.yml`)
   comments on applications that have been idle more than 14 days in a
   non-terminal stage, so nobody falls through the cracks.
4. On `applicant/accepted`, create a profile per
   `participants/profiles/README.md` and begin
   `participants/onboarding.md`.
5. On `applicant/alumni`, update `participants/alumni.md`.

## Review criteria

[TBD per cohort and track — see `participants/model.md`. Document the
actual criteria here once the founding team defines them, e.g. stage of
idea, connection to ETH/Zurich ecosystem, fit with available mentorship.]

## What never goes here or in an Issue

Financial need, immigration status, or any other sensitive personal data
— see `governance/data-protection.md`. If a reviewer needs to discuss
this, it happens outside git (e.g. a call), not in the Issue thread.

## Open questions for the founding team

- [ ] Confirm review criteria per track.
- [ ] Confirm who reviews (board, mentors, external reviewers?).
- [ ] Confirm interview format.

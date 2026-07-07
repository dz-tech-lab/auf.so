# Data protection (Swiss FADP)

This repo is subject to the Swiss Federal Act on Data Protection (FADP /
revDSG). This document sets the hard rule for what may and may not be
committed to git, for everyone — including agents.

## The rule

**No real personal data (PII) is ever committed to this repository, under
any circumstances — even though the repo may be private.**

This includes, non-exhaustively:

- payment details (IBANs, card numbers, bank account numbers)
- financial need / hardship information about a participant or applicant
- immigration or residency status
- health information
- government ID numbers
- home addresses of individuals (as opposed to the Association's
  registered seat)
- any other data that could identify a real person combined with
  sensitive context about them

## Why "private repo" doesn't fix this

- **Git history is permanent.** Deleting a file in a later commit does not
  remove it from history; purging history is disruptive and easy to get
  wrong, so the only reliable fix is to never commit it.
- **Access control here is repo-wide, not field-level.** Anyone with repo
  access — including future collaborators, contractors, or integrations —
  sees everything in every file. There's no way to grant "see the donor
  name but not their financial need."

## What's safe to keep in this repo

De-identified / structural fields only:

- status (pipeline stage, application stage)
- tier / track labels
- dates
- non-sensitive free text (e.g. "intro via [mentor]", "interested in
  climate")
- links to GitHub Issues that track live status

See `donors/records/README.md` and `participants/profiles/README.md` for
the exact per-record template that follows this rule.

## Open decision: where does real PII actually live?

**This is not yet decided and this file does not attempt to decide it.**
The founding team needs to choose a system of record for real donor and
participant PII (payment details, financial need, immigration status,
etc.) that is *not* this git repository — for example a dedicated CRM,
a spreadsheet with proper access controls, or a case-management tool.

Until that decision is made:

- Do not invent a workaround (e.g. "just encrypt it and commit it",
  "put it in a private gist") — raise it with the founding team instead.
- New donor/participant records should reference "PII stored in: [system
  TBD]" rather than a concrete answer, until this is resolved.

## Open questions for the founding team

- [ ] Choose the system of record for donor PII (payment info).
- [ ] Choose the system of record for participant PII (financial need,
  immigration status, etc.).
- [ ] Confirm data retention policy once a system is chosen.
- [ ] Confirm who has access to that system.

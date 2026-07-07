# Tax-exempt / gemeinnützig status

Tracker for the Association's application for tax-exempt status
(Steuerbefreiung wegen Gemeinnützigkeit) with the cantonal tax authority
(Kantonales Steueramt Zürich, or wherever the seat ends up being), and what
that status unlocks.

## Why this matters

Gemeinnützig status lets donors deduct their contributions from taxable
income (within statutory limits) and signals legitimacy to institutional
donors and foundations. It typically requires:

- a non-profit purpose serving the public good (not just members'
  private interest) — see `governance/statutes.md` Art. 2
- no distribution of profit or assets to members, including on dissolution
  — see `governance/statutes.md` Art. 18 (Auflösungsklausel)
- activity that actually matches the stated purpose in practice

## Draft application on file

A draft of the cantonal form (`Gesuch um Befreiung von der
Steuerpflicht — Gemeinnützige Zwecke`, Kanton Zürich) has been filled in
based on the draft statutes and is attached at
[`governance/tax-exemption-application-2026.pdf`](tax-exemption-application-2026.pdf).
**This is a draft, not a submission-ready document.** Before it goes to
the Steueramt:

- Resolve the legal name mismatch flagged at the top of
  `governance/statutes.md` (statutes say "Antimatter" in the operative
  Art. 1, everything else says "Auf").
- Have someone with tax expertise (board treasurer and/or external
  counsel) sanity-check questions **1.1, 1.6, 1.7, and 1.8** on the form
  against the purpose clause (Art. 2 of the statutes). Those four
  checkboxes were already marked "Trifft zu" (applies) in the source
  file I was given, but Art. 2 explicitly allows the association to
  **make investments in start-ups** and support fundraising for
  founders building for-profit companies — activities that Zurich's
  cantonal practice sometimes treats as commercial/competitive rather
  than classically gemeinnützig. I did not change those checkboxes, but
  flagging this now is cheaper than a rejected application later.
- Question 1.12's three "Bitte Artikel nennen" fields are now filled
  (Art. 16, 17, 18 — confirmed by the founding team), but that numbering
  still needs to be carried into the statutes' Word source, where
  numbering for that section is currently switched off — see
  `governance/statutes.md`.
- Fields 2.1–2.7 and the closing remarks were drafted from the statutes
  text and note several `[TBD]`s (e.g. estimated volunteer hours,
  whether the association will have paid staff, whether it will
  actually hold startup equity) that only make sense to answer once the
  association is operating.

## Application tracker

| Step | Status | Date | Notes |
|---|---|---|---|
| Statutes finalized (prerequisite) | in progress — draft exists, not adopted | [TBD] | See the open name-mismatch flag in `governance/statutes.md` |
| Application form drafted | done (draft) | 2026-07-07 | See `governance/tax-exemption-application-2026.pdf`; needs the review above before submission |
| Application submitted to cantonal tax authority | not started | [TBD] | |
| Follow-up / clarification requests | n/a | [TBD] | |
| Decision received | pending | [TBD] | |
| Status confirmed | pending | [TBD] | |

Update this table via PR as the application progresses — it's a
point-in-time record, not a live tracker, so a small number of updates
over the life of the application is expected and fine to do by hand.

## What gemeinnützig status unlocks for donors

- [Donation deductibility for individual donors, up to X% of taxable
  income — confirm current cantonal/federal limits]
- [Donation deductibility for corporate donors — confirm]
- Ability to be listed with donation-matching platforms or corporate
  giving programs that require proof of tax-exempt status
- Stronger positioning for grant applications from foundations that
  require non-profit status as a precondition

Reference this status (once confirmed) in
`donors/comms/outreach-template.md` and `donors/reporting.md`.

## Open questions for the founding team

- [ ] Confirm target canton/authority for the application.
- [ ] Confirm timeline — ideally aligned with statutes adoption.
- [ ] Confirm who owns the application (board treasurer, or external
  counsel?).
- [ ] Resolve the legal name mismatch in `governance/statutes.md` before
  finalizing the tax exemption form.
- [ ] Carry the confirmed Art. 16–20 numbering into the actual statutes
  Word source (not just this repo's transcription).
- [ ] Have tax counsel confirm the purpose clause's start-up investment
  language doesn't jeopardize questions 1.1/1.6/1.7/1.8 on the
  exemption form.

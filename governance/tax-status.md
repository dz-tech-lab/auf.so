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
Steuerpflicht — Gemeinnützige Zwecke`, Kanton Zürich) is attached at
[`governance/tax-exemption-application-2026.pdf`](tax-exemption-application-2026.pdf).
**As of 2026-07-17 this reflects external counsel's (Schellenberg
Wittmer) own edited wording for section 2** — their redlined version was
shared and applied directly (see below), not just their prose summary.
**Still a draft, not submission-ready:**

- Have someone with tax expertise (board treasurer and/or external
  counsel) sanity-check questions **1.1, 1.6, 1.7, and 1.8** on the form
  against the purpose clause (Art. 2 of the statutes). Those four
  checkboxes are marked "Trifft zu" (applies), but Art. 2 explicitly
  allows the association to **make investments in start-ups** and
  support fundraising for founders building for-profit companies —
  activities that Zurich's cantonal practice sometimes treats as
  commercial/competitive rather than classically gemeinnützig. Counsel's
  own edits didn't change these checkboxes either, which may mean
  they're comfortable with them — worth confirming explicitly rather
  than assuming.
- Question 1.12's three "Bitte Artikel nennen" fields are filled (Art.
  16, 17, 18), but that numbering still needs to be carried into the
  statutes' Word source, where numbering for that section is currently
  switched off — see `governance/statutes.md`.
- Section 2.2 references a **"Tätigkeitskonzept"** ("activity concept")
  as the document that will spell out admission criteria/process in
  detail — like the Statement of Purpose before it, **this document
  doesn't exist anywhere in this repo and hasn't been shared.** If it
  should exist, say where it should live and share its content.

## External counsel review (2026-07-16), with attachments received 2026-07-17

Schellenberg Wittmer (Lorenza Cavigelli, Marcel Jakob, Sahra Cade)
reviewed the tax exemption application, the Statement of Purpose, and
the budget. Their actual redlined attachments have now been shared and
applied:

- **Tax exemption application** — section 2 (2.1–2.7) and the closing
  remarks now use counsel's own wording verbatim, replacing my earlier
  draft language. Notably, their version:
  - Explicitly cites Art. 3/4/17/18 of the statutes throughout instead
    of vague references.
  - States plainly that the association has no employees and none are
    planned "gemäss provisorischem Budget 2026–2028."
  - Drops several `[TBD]` brackets I'd left in 2.5 and 2.7 and the
    closing remarks — worth noting as a pattern: counsel strips
    placeholder/meta notation before something is submission-ready,
    even where the underlying uncertainty (e.g. exact volunteer hours)
    still exists.
- **Statutes** — passive membership restricted to supporters, not
  currently-funded founders (Art. 4); see `participants/alumni.md` for
  the informal alumni-to-supporter path.
- **Participant model** — explicitly open to recent graduates, not just
  enrolled students (`participants/model.md`).
- **Budget** — added a real beneficiary-grants expense line sized off
  counsel's suggested ramp-up, reduced office equipment, added
  coworking/SaaS lines (`operations/budget-2026-2028.md`). This
  surfaced a real finding: the low-case CHF 100,000 fundraising target
  doesn't cover three years once grants are priced in — see that file.
- **Statement of Purpose** — now created in this repo at
  `governance/statement-of-purpose.md` (English, corrected per
  counsel's notes) with a German translation, per the founding team's
  request. Renamed "Member Profiles" → "Beneficiary Profiles" (and
  German equivalent), reframed "Cohort Composition" as an illustrative
  "Desired Profile" (Olympiad medalists moved to the end of the list,
  hard-science focus kept prominent), broadened eligibility language to
  graduates/alumni not just students, and dropped the "planning
  template" disclaimer footer per counsel's instruction to remove it
  before submission.

**Still outstanding**: the "Tätigkeitskonzept" referenced in the
application's own 2.2 answer (see above) — not yet a document anywhere
in this repo.

## Resolved: legal name

The founding team has confirmed the legal name is **"Auf"** — see
`governance/statutes.md`. Counsel's correspondence referred to the
entity as "Antimatter" because that reflected the not-yet-corrected
draft statutes at the time, not a separate legal name.

## Application tracker

| Step | Status | Date | Notes |
|---|---|---|---|
| Statutes finalized (prerequisite) | in progress — draft exists, not adopted | [TBD] | Legal name resolved (see above); Art. 16–20 numbering still needs to land in the Word source |
| Application form drafted | done — now reflects counsel's redlines | 2026-07-17 | See `governance/tax-exemption-application-2026.pdf` |
| External counsel review received | done | 2026-07-16 | Schellenberg Wittmer |
| Counsel's redlined attachments applied | done | 2026-07-17 | Tax exemption form, Statement of Purpose, budget — see "External counsel review" above |
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
- [ ] Carry the confirmed Art. 16–20 numbering into the actual statutes
  Word source (not just this repo's transcription).
- [ ] Have tax counsel confirm the purpose clause's start-up investment
  language doesn't jeopardize questions 1.1/1.6/1.7/1.8 on the
  exemption form.
- [ ] Confirm whether a "Tätigkeitskonzept" document should exist in
  this repo (referenced in the application's own 2.2 answer), and if
  so, share it or describe what it should contain.

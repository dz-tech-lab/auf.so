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

## External counsel review (2026-07-16)

Schellenberg Wittmer (Lorenza Cavigelli, Marcel Jakob, Sahra Cade)
reviewed the tax exemption application, a "Statement of Purpose"
document, and the budget, and sent back marked-up versions by email.
**Only their prose recommendations made it into this repo — the actual
edited attachments (`Tax Exemption Application 2026_bearbeitet.pdf`,
`Statement of Purpose_Auf.pdf`, `Auf-budget2026-2028.xlsx`) weren't
included when this was forwarded to me.** If those are shared, I can
cross-check this repo's copies against counsel's actual tracked
changes rather than my re-implementation of their prose notes.

What I applied from their feedback:

- **Passive membership**: counsel flagged that currently-supported
  founders were listed as eligible passive members in Art. 4 — which
  undermines the requirement that beneficiaries and members be
  distinct. Fixed in `governance/statutes.md` Art. 4; former
  beneficiaries can informally become supporters/passive members later
  (see `participants/alumni.md`).
- **Open beneficiary group / "hard science" framing**: reflected in
  `participants/model.md` (not limited to enrolled students; cohort
  profile write-ups should read as illustrative, not a closed list).
- **Budget**: added a grants-to-beneficiaries expense line and revised
  office costs — see `operations/budget-2026-2028.md`.

What I could **not** apply, for lack of the source document:

- A **"Statement of Purpose"** document is referenced repeatedly
  (sections like "Member Profiles" → rename to "Beneficiary Profiles",
  "Cohort Composition" → reframe as "Desired Profile", remove a
  planning-template disclaimer footer, submit in German too) — **this
  document doesn't exist anywhere in this repo and wasn't attached**.
  If it should live here, tell me where (a new file under `governance/`
  or `strategy/`?) and share its content so I can apply the specific
  renames/restructuring counsel asked for.
- The **tax exemption form's** own tracked-changes wording (counsel
  said they edited the PDF directly) — I don't have that file, so
  `governance/tax-exemption-application-2026.pdf` in this repo hasn't
  been updated to match their specific edits.
- Counsel's email refers to the client consistently as **"Antimatter"**
  and one attachment is titled "Statement of Purpose**_Auf**" —
  consistent with "Antimatter" being the legal name and "Auf" the
  public brand, reinforcing (but not resolving) the flag in
  `governance/statutes.md`.

## Application tracker

| Step | Status | Date | Notes |
|---|---|---|---|
| Statutes finalized (prerequisite) | in progress — draft exists, not adopted | [TBD] | See the open name-mismatch flag in `governance/statutes.md` |
| Application form drafted | done (draft) | 2026-07-07 | See `governance/tax-exemption-application-2026.pdf`; needs the review above before submission |
| External counsel review received | done | 2026-07-16 | Schellenberg Wittmer — see "External counsel review" above; some of their edits (the actual redlined attachments) are not yet reflected here |
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
- [ ] Share counsel's actual redlined attachments (tax exemption form,
  Statement of Purpose, budget) so this repo's copies can be
  cross-checked against their real tracked changes.
- [ ] Confirm whether a "Statement of Purpose" document should exist in
  this repo, and if so where — it's referenced in counsel's feedback
  but isn't part of this repo today.
- [ ] Confirm whether "Auf" is meant to be a registered operating
  name alongside the legal name "Antimatter" (see
  `governance/statutes.md`).

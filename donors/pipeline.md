# Donor pipeline

**The live donor pipeline is tracked as GitHub Issues with labels — not in
this file.** This file documents the process; it is not itself a status
tracker and should never accumulate a hand-edited list of donors and their
stages.

## Why Issues, not markdown

A donor's stage changes frequently, needs a comment history (who talked to
them, when, what was said), and shouldn't require a PR review cycle just to
move from "contacted" to "discussing." Issues give us that for free.

## How it works

1. A new prospect gets a GitHub Issue using the
   `.github/ISSUE_TEMPLATE/donor-prospect.yml` form.
2. The issue is labeled with exactly one stage label at a time:

   | Label | Meaning |
   |---|---|
   | `donor/lead` | Identified as a prospect, not yet contacted |
   | `donor/contacted` | Initial outreach sent |
   | `donor/discussing` | In active conversation |
   | `donor/committed` | Donor has committed, payment pending |
   | `donor/received` | Funds received |
   | `donor/declined` | Donor passed, or went quiet |

3. Two more label dimensions apply alongside the stage, matching the
   founding team's existing stakeholder CRM:

   | Dimension | Labels |
   |---|---|
   | Category | `donor/type-founder`, `donor/type-family-business`, `donor/type-investor`, `donor/type-political` — see `donors/strategy.md` for what each means |
   | Priority | `priority/high`, `priority/medium`, `priority/low` |

4. Moving a donor forward = swap the stage label and add a comment with
   context. Anyone with repo access can see the whole pipeline via the
   Issues list filtered by label.
5. Once a donor reaches `donor/received`, create or update their entry
   under `donors/records/` (see that folder's README for the template) —
   that markdown file is a stable pointer to the issue plus de-identified
   summary fields, not a duplicate of live status.
6. Closed issues (`donor/received` or `donor/declined`) stay closed but
   remain the historical record of that relationship.

## Board/finance visibility

The treasurer should review the pipeline board (Issues filtered by the
`donor/*` labels) at the cadence set in `operations/calendar.md`, and
reconcile `donor/received` issues against `donors/receipts.md`.

## What never goes here or in an Issue

Payment details, bank references, or any other PII — see
`governance/data-protection.md`. Issues should reference "payment received,
details in [system TBD]," not the details themselves.

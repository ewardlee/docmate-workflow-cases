# DocMate Workflow Cases

A public, reproducible library of fictional document scenarios that show how real document work gets completed with DocMate.

This repository is **not the DocMate source code**. It contains synthetic documents, expected changes, scripts, and media briefs that can be independently inspected and reused for demos, reviews, education, and product testing.

## The product idea

DocMate is built around a simple lifecycle:

> **Document → Context → Action → Record → Next Action**

The goal is not to show a list of PDF tools. The goal is to show a person solving a real problem from start to finish.

Examples:

- A tenant receives a renewal and needs to know what changed before signing.
- A job candidate receives a revised offer and needs to verify salary and start-date changes.
- A finance team receives an invoice that does not match the approved quote.
- A freelancer receives the seventh revision of a statement of work and needs to know which version was actually signed.
- A family member scans a warranty receipt and needs to find it again before the warranty expires.

## Rules for every case

1. **Synthetic documents only.** No real customer, employee, landlord, medical, financial, or legal records.
2. **Real product proof only.** AI-generated people, rooms, offices, and narrative shots are allowed; DocMate UI and product results must come from the real app.
3. **No fake claims.** If a workflow is not supported by the shipping build, label it as a future concept rather than presenting it as current behavior.
4. **Reproducible changes.** Every comparison case lists the exact expected changes.
5. **Preserve the story.** The important outcome is not merely "a diff appeared"; it is what the user decided and what record remains afterward.
6. **No legal advice.** Cases demonstrate document workflow, not legal interpretation or legal validity.

## Canonical story series

- **One Line Changed** — revisions that look harmless until one important clause changes.
- **Buried in the Document** — important dates, amounts, deadlines, or obligations hidden inside long files.
- **The Paper Trail** — version history, review records, signatures, fingerprints, and the question "what happened to this document?"
- **Restore It** — damaged, dark, skewed, or shadowed paper that becomes readable and searchable.
- **Life Admin** — receipts, warranties, insurance, school documents, renewals, and reminders.

See [STORY_BIBLE.md](STORY_BIBLE.md) for the full story library.

## First reproducible cases

| Case | Audience | Core pain | Hero workflow |
|---|---|---|---|
| [01 — Lease Renewal](cases/01-lease-renewal/) | Tenant / property manager | "Nothing major changed" but a clause did | Add as New Version → Compare → Review → Sign |
| [02 — Revised Job Offer](cases/02-revised-job-offer/) | Job candidate / HR | Salary, start date, or working terms changed | Compare → Evidence → Review → Sign |
| [03 — Quote vs Invoice](cases/03-quote-vs-invoice/) | Finance / procurement / SME | Invoice does not match approved commercial terms | OCR / Intelligence → evidence check → Review / Reminder |

## Media system

One canonical case can become:

- 20–35 second vertical short
- 45–90 second YouTube proof video
- Instagram carousel
- LinkedIn case post
- Reddit educational discussion
- GitHub reproducible case
- App Store Custom Product Page narrative
- Reviewer / journalist test fixture

See [MEDIA_PLAYBOOK.md](MEDIA_PLAYBOOK.md).

## The creative rule

> **AI = context and emotion. DocMate UI = proof.**

A cinematic scene can create tension. The moment the product makes a claim, the viewer should see the authentic app.

## Status

This repo starts with three canonical cases. More stories will be added only when they map cleanly to real DocMate workflows and can be demonstrated without inventing product behavior.

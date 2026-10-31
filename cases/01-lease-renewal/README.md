# Case 01 — Lease Renewal: "The Version You Didn't Read"

**Series:** One Line Changed  
**Audience:** tenant, property manager, landlord-side administrator  
**Status:** ACTIVE PRODUCTION — synthetic reproducible story  
**Product principle:** before signing a revision, know what changed and preserve what happened next.

## The human story

A couple is packing for a move. Their landlord sends a revised lease:

> "Everything's basically the same. Just the usual renewal."

They are about to sign.

The expected changes are rent and dates.

The unexpected change is the pet clause.

They have an older dog who has already been part of their life for years.

The workflow matters because one quiet revision can change a real decision.

## Synthetic fixtures

- `lease-2026.txt` / `lease-2026.pdf`
- `lease-renewal-2027.txt` / `lease-renewal-2027.pdf`
- `expected-changes.md`

All names, address, amounts, dates, and clauses are fictional.

## Hero change

Original:

> One small domestic pet is permitted with prior written approval.

Revised:

> Pets are not permitted without a separate written exception from the landlord.

Supporting changes include:
- Monthly rent: $1,500 → $1,550
- Late-fee grace period: 5 → 3 days
- Lease term: 12 → 18 months

The film should let the viewer first accept the rent/date changes as routine, then reveal the pet-policy change.

## DocMate workflow

1. Import/open the current lease.
2. Import/open the renewal and connect it as the new version where appropriate.
3. Run Compare:
   - Original = current lease
   - Revised = renewal
4. Let one or two routine findings pass first.
5. Select the pet-clause finding.
6. Jump to the exact source clause.
7. Open Review and add:
   - `Please confirm pet exception before signing.`
8. Save the Review result while retaining the original.
9. Do **not** sign in the story: the correct outcome is to pause and clarify.

This is important: DocMate does not always end in "Sign". The product value is helping the user make the right next decision.

## Film concept

See:
- [Creative Brief](../../episodes/01-the-version-you-didnt-read/CREATIVE_BRIEF.md)

## Product truth contract

The following must be authentic DocMate captures from a known build:
- document/version context
- Original/Revised Compare
- pet clause finding
- source-page jump
- Review note
- saved Review result

AI may create the couple, apartment, dog, packing environment, and phone-message context, but must not fabricate DocMate UI or product results.

## Platform angle

### Short film
A human story about a couple, a dog, and one quiet line in a lease.

### Proof cut
A separate, mostly real-product video showing the exact fixture and workflow.

### Reddit
Discuss why "what changed?" is different from "can I read this PDF?" Use the synthetic fixture and disclose that the author builds DocMate.

### LinkedIn
Frame the story around revision risk and decision history, not "AI PDF features."

## CTA

> **It was one line.**

> **Before you sign, know what changed.**

## Limitation

This case shows revision awareness and workflow. It does not assess whether a lease clause is lawful, enforceable, fair, or advisable.

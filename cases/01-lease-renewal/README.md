# Case 01 — Lease Renewal: "Just a Small Change"

**Series:** One Line Changed  
**Audience:** tenant, property manager, landlord-side administrator  
**Status:** synthetic reproducible story  
**Product principle:** before signing a revision, know what changed and preserve what happened next.

## The human story

A tenant receives a message:

> "Nothing major changed. Just the usual renewal. Sign when you can."

The rent increase is expected.

The notice-period change is not.

The value of the workflow is not merely detecting a diff. It is giving the user a path from **revised document → evidence → review decision → correct signed version → durable record**.

## Synthetic fixtures

- `lease-2026.txt` / `lease-2026.pdf`
- `lease-renewal-2027.txt` / `lease-renewal-2027.pdf`
- `expected-changes.md`

The names, address, amounts, dates, and clauses are fictional.

## Hero changes

| Field | Original | Revised |
|---|---|---|
| Monthly rent | $1,500 | $1,550 |
| Tenant notice period | 30 days | 90 days |
| Lease term | 12 months | 18 months |
| Late-fee grace period | 5 days | 3 days |
| Pet deposit | $0 | $300 |

The story should focus on **30 days → 90 days**. The other changes make the fixture realistic and reproducible.

## DocMate workflow

1. Import the current lease.
2. Import the renewal and use **Add as New Version of…** where appropriate.
3. Run Compare with:
   - Original = current lease
   - Revised = renewal
4. Select the notice-period finding and jump to the source page.
5. Open Review and add a comment such as:
   - "Confirm before signing."
6. Save the reviewed version while retaining the original.
7. Sign the version the user actually intends to accept.
8. Show the resulting version / Signed state / Activity or Fingerprint evidence available in the shipping build.

The final published demo must use authentic DocMate captures for steps 2–8.

## 30-second theatre script

### 0–3s — AI context
Night. A phone vibrates on a sofa.

Message:
> "Nothing major changed. Just the usual renewal."

PDF attachment:
`Lease_Renewal_2027.pdf`

### 3–6s — decision pressure
The tenant's thumb moves toward Sign.

On-screen line:
**Would you sign it?**

### 6–10s — transition to real product
Cut from cinematic scene to authentic DocMate UI.

Open the renewal beside the prior version.

### 10–16s — real Compare
First finding:
`Rent: $1,500 → $1,550`

Small caption:
**Expected.**

Next finding:
`Notice: 30 days → 90 days`

Music drops.

Caption:
**That wasn't mentioned.**

### 16–21s — source evidence
Tap the finding.
Show the actual revised clause in the real PDF.

### 21–25s — action
Open Review.
Highlight/comment:
`Confirm before signing.`

### 25–28s — record
Show the reviewed/current version state.
If using Sign in the demo, show the authentic saved signed result.

### 28–30s — brand
**One line can change everything.**

**Before you sign, know what changed.**

DocMate

## Shot contract

| Shot | Type | Can AI generate it? |
|---|---|---|
| phone notification / tenant on sofa | narrative | Yes |
| hand about to sign | narrative | Yes |
| DocMate document list | product | **No — real capture** |
| Compare findings | product | **No — real capture** |
| source-page jump | product | **No — real capture** |
| Review comment | product | **No — real capture** |
| saved/signed/fingerprint state | product | **No — real capture** |

## Reddit discussion version

**Suggested title:**  
I keep seeing people compare lease renewals manually. What should a "safe before-signing" workflow actually remember?

**Body angle:**  
Start with the generic problem: revised lease arrives, email says "nothing major changed", and people either reread 20 pages or copy both versions into another tool. Share these fictional fixtures and the five known changes. Ask what readers would want the software to preserve after the comparison: the exact pair, change list, review notes, signed version, or file fingerprint.

Disclosure:
> I build DocMate. These are synthetic files from the public workflow-case repo. I'm interested in the workflow problem as much as the product feedback.

Do not post in a subreddit that prohibits developer promotion.

## LinkedIn angle

> The dangerous part of a contract revision is not always the visible price increase. Sometimes it is the quiet operational term that changed beside it.

Use the 30→90 day finding, then explain why revision history + review record + correct signed version matters operationally.

## YouTube title candidates

- **The Lease Changed More Than the Rent**
- **Before You Sign a Lease Renewal, Compare This**
- **"Nothing Major Changed." We Checked.**

## CTA

> **Before you renew, know what changed.**

## Important limitation

This case demonstrates document workflow. It does not determine whether any clause is fair, enforceable, or legally advisable.

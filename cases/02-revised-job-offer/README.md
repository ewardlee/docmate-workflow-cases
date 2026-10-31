# Case 02 — Revised Job Offer: "We Cleaned Up the Wording"

**Series:** One Line Changed  
**Audience:** job candidate, recruiter, HR operations  
**Status:** synthetic reproducible story

## The human story

A candidate already reviewed an offer.

HR sends a revised copy:

> "We cleaned up the wording. Please sign the updated version."

The filename looks almost the same.
The changes are not all cosmetic.

## Synthetic fixtures

- `offer-original.txt` / `offer-original.pdf`
- `offer-revised.txt` / `offer-revised.pdf`
- `expected-changes.md`

All company, candidate, salary, dates, and terms are fictional.

## Hero changes

| Field | Original | Revised |
|---|---|---|
| Base salary | $92,000 | $88,000 |
| Start date | March 2, 2027 | March 16, 2027 |
| Target bonus | 10% | 8% |
| Probation | 3 months | 6 months |
| Remote days | 3 days/week | 2 days/week |

The film should make the **salary change** the immediate shock, then show one quieter work-arrangement change.

## DocMate workflow

1. Keep the first offer as the baseline.
2. Add/import the revised offer.
3. Compare Original vs Revised.
4. Open the salary finding and source text.
5. Review the revised copy and leave a note:
   - "Please confirm the agreed compensation before I sign."
6. Preserve both versions.
7. Only show Sign if the final real-product flow has an accepted version ready to sign.

## 30-second theatre script

### 0–4s — AI context
Morning. Candidate is getting ready for work.

Email preview:
> "Good news — just a cleaned-up version of the offer. Please sign today."

### 4–7s
Candidate smiles.
Opens `Offer_Revised.pdf`.

Caption:
**Same job. Same offer?**

### 7–13s — real DocMate
Authentic Compare.

`Base Salary: $92,000 → $88,000`

Hold for readability.

### 13–17s
Next finding:

`Remote work: 3 days/week → 2 days/week`

### 17–22s
Tap to source.
Show the revised paragraph.

### 22–26s
Review comment:
`Please confirm the agreed compensation before I sign.`

### 26–30s
Brand line:

**"Updated" doesn't always mean "unchanged."**

**Compare. Review. Then sign.**

DocMate

## Reddit discussion version

**Suggested title:**  
When someone sends "just an updated offer", what do you actually compare before signing?

Use the public fictional files and ask the community which fields matter most: salary, bonus, start date, probation, location, notice, or benefits.

Disclosure:
> I build DocMate, and I made these synthetic fixtures to test revision workflows. No real employer or candidate data is used.

## LinkedIn angle

> Version control is not just a software-engineering problem. People make career decisions from documents that arrive as "updated_offer_v2.pdf".

Discuss how the human problem is not reading PDFs; it is maintaining confidence that the version being signed is the version that was agreed.

## YouTube title candidates

- **The "Updated Offer" Changed the Salary**
- **Would You Notice This Before Signing?**
- **Compare the Offer You Accepted With the One You Were Sent**

## CTA

> **Before you accept, compare what changed.**

## Important limitation

DocMate can help surface document differences and evidence. It does not provide employment-law advice or determine whether terms are lawful or fair.

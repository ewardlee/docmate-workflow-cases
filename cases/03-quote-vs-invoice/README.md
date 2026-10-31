# Case 03 — Quote vs Invoice: "The Numbers Don't Match"

**Series:** Buried in the Document  
**Audience:** finance, procurement, small business owner, operations  
**Status:** synthetic reproducible story

## The human story

A business approved a supplier quote.
Two weeks later the invoice arrives.

Everyone remembers the approved total "roughly".
Nobody remembers the exact shipping charge or payment term.

The pain is not "I need a PDF reader."

The pain is:

> **Can I approve payment confidently without manually rebuilding the commercial history?**

## Synthetic fixtures

- `approved-quote.txt` / `approved-quote.pdf`
- `supplier-invoice.txt` / `supplier-invoice.pdf`
- `expected-checks.md`

All supplier, customer, bank, amount, and invoice details are fictional.

## Expected commercial checks

| Field | Approved quote | Invoice |
|---|---|---|
| Goods subtotal | $8,400 | $8,400 |
| Shipping | Included | $350 |
| Service fee | $0 | $1,000 |
| Total | $8,400 | $9,750 |
| Payment term | Net 30 | Net 15 |

This case is intentionally **not framed as a same-document revision**. It demonstrates a multi-document evidence workflow.

## DocMate workflow

A shipping V2 demonstration may use:

1. Import both documents.
2. OCR if required.
3. Use document Intelligence / **Ask Selected Documents** where supported by the final build to ask a bounded question such as:
   - "What totals and payment terms appear in these two documents?"
4. Open cited evidence rather than accepting an uncited answer.
5. Review the invoice or add a follow-up reminder before payment.
6. Keep the documents together in the relevant Workspace/folder.

If a final-build capture does not prove a specific multi-document behavior, the published video must fall back to individually opening the cited amounts rather than fabricating a cross-document result.

## 30-second theatre script

### 0–4s — AI context
Finance manager receives a message:
> "Invoice attached — please approve today."

### 4–7s
Screen shows:
Approved quote: `$8,400`
New invoice filename appears.

Caption:
**Looks routine.**

### 7–15s — real DocMate
Authentic product capture.

Show the invoice evidence:
`Total: $9,750`

Then the source line:
`Service fee: $1,000`

### 15–20s
Show:
`Payment Terms: Net 15`

Approved quote evidence:
`Net 30`

### 20–25s
Review/follow-up:
`Check added service fee before payment.`

Set reminder if appropriate.

### 25–30s
Brand line:

**The number you miss is the one that costs you.**

**Find the evidence before you approve.**

DocMate

## Reddit discussion version

**Suggested title:**  
How do small teams verify an invoice against the commercial document that was actually approved?

Share the synthetic quote and invoice. Ask whether a useful workflow should preserve only the mismatch or also the source evidence, approval note, and follow-up state.

Disclosure:
> I build DocMate. These are synthetic fixtures; I'm using them to test what a practical multi-document finance workflow should look like.

## LinkedIn angle

> In many small teams, invoice approval still depends on someone remembering what the supplier originally quoted.

Show the $8,400 → $9,750 story and make the lesson about evidence-backed document workflow rather than "AI accounting".

## YouTube title candidates

- **The Invoice Was $1,350 Higher Than the Approved Quote**
- **Before You Approve That PDF, Check These Two Lines**
- **A Finance Workflow for the Number Everyone Thought They Remembered**

## CTA

> **Find the evidence before you approve.**

## Important limitation

This fixture is designed to demonstrate document understanding and evidence retrieval. DocMate is not an accounting system and does not independently authorize or reject payments.

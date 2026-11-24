---
name: etsy-listing-auditor-lite
description: Free lite version — run a compliance-only checklist on a draft Etsy listing before publication. Checks tags, title, pricing, AI disclosure, and digital-delivery rules against Etsy's published Seller Handbook. Use when a seller says "check my listing," "is this listing compliant," or asks for a quick pre-publish check of an Etsy listing.
---

# Etsy Listing Auditor — Lite (Free)

Version: November 2026. One job: check a draft Etsy listing against the compliance rules below and list what fails.

## Inputs

Ask for whatever is missing: title, all tags, full description, category, attributes, price and any sale dates, and the list of delivery files with sizes. If the seller can't provide an item, mark its checks "NOT CHECKED — not provided" instead of guessing.

## How to run the check

Go through the checklist in order. Count characters yourself — never estimate title or tag length. Report one line per check: PASS, or FAIL with the offending text quoted and one sentence on what to change.

## Compliance checklist

Rules checked against Etsy's published Seller Handbook (August 2025) and Etsy's policy updates through October 2026.

**Title**

- Length is 140 characters or fewer.
- Reads like a person wrote it and leads with what the item is — not a keyword-stuffed list of phrases separated by commas or pipes.

**Tags**

- Exactly 13 tags.
- Every tag is 20 characters or fewer, spaces included.
- Tags are unique, multi-word, spelled correctly, in one language; long-tail phrases over single generic words.
- No tag simply repeats the category name or an attribute phrase.

**Category and attributes**

- Category is the most specific subcategory available.
- Every accurate attribute is filled in; no inaccurate attribute is selected.

**Claims and trust**

- No seller-made badges: no "Star Seller" or "Bestseller" graphics or claims added by the seller, in images or text — prohibited even if earned. Only trust signals Etsy itself displays are allowed.
- No invented proof: no undocumented sales counts, review quotes, testimonials, "#1"-style ranking claims, or response-time promises the seller doesn't always keep.
- Compatibility claims are true and stated near the top of the description; no platform or program the delivered file doesn't actually work in.

**Pricing and sales**

- The base price is a genuine selling price, not an inflated anchor for a permanent discount.
- Any sale has real start and end dates. No perpetual or rolling sales, and no fake urgency ("sale ending soon!") on an undated sale.

**AI use**

- If AI helped create the product or the listing content, the description contains a plain disclosure sentence (Etsy policy update, October 22, 2026).
- The listing is the seller's own reviewed work — not bot-generated and posted unchecked.
- Instruction text inside the product is written or personally rewritten by the seller; Etsy does not allow AI-generated functional instructions.

**Digital delivery**

- Spreadsheets are delivered inside a .zip file — .xlsx is not on Etsy's documented accepted-format list.
- Delivery totals at most 5 files and 20 MB per listing.
- A digital listing has no variations.
- No QR codes in delivered files or listing images (Etsy Off-Platform Policy, October 5, 2026). An email signup, if offered, is a printed URL and opt-in only.

## Output format

```
CHECKLIST RESULT: ALL PASS  (or)  <n> ITEMS TO FIX
✗ Tags — "printable planner spreadsheet" is 29 characters; the limit is 20.
✓ Title
✓ Pricing and sales
...
```

## Verify before relying

Etsy changes its rules. These checks were verified against the Seller Handbook (https://www.etsy.com/seller-handbook) and policy updates through October 2026. Where this checklist and the current Handbook disagree, the Handbook wins. This checklist does not guarantee sales, search ranking, or traffic, and cannot predict Etsy's enforcement decisions.

---

**Want the full audit?** The full version of this skill adds an SEO pass (title structure, tag coverage, description opening, attributes and materials), exact character counts on every check, and a fix-by-fix report that quotes each problem and gives the exact replacement text, in the order to fix them.

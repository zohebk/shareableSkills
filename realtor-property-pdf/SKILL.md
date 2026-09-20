---
name: realtor-property-pdf
description: Research a US residential property from its address and create a sourced, comparable-sales PDF report. Use when someone asks for a property brief, realtor CMA-style report, or home comparison PDF from an address.
---

# Realtor Property PDF

Turn a user-provided residential address into a clear, source-linked property research PDF. Treat the result as preliminary market research, not a licensed appraisal, inspection, legal opinion, or guaranteed valuation.

## Workflow

1. **Resolve the address.** Normalize the street address, city, state, ZIP, and unit. If the ZIP or unit is needed to distinguish properties and is missing, ask a concise question. Never fill gaps with a nearby home or another unit. Use the resolved address as the search scope.
2. **Research current public sources.** Search for direct property and listing pages for the exact subject and candidate comparable sales. Open the pages and verify their contents. Treat search snippets as leads, not evidence. Record publisher, URL, retrieval date, property identity, listing or sale status, price, dates, living area, property type, and any unit information that the source actually establishes. Preserve source disagreements and mark unavailable or unverified facts clearly.
3. **Select relevant comparables.** Prefer recent closed sales in the same local market and property type, with similar size, age, and features. Explain why each sale is relevant and disclose material differences. Do not present active asking prices as closed sales. Exclude the subject itself, duplicate listings, mismatched units, unsupported addresses, and stale or materially dissimilar sales from calculations. You may show excluded candidates separately with the reason.
4. **Calculate only from supported inputs.** Show the formula, source inputs, date basis, and rounding. A price-per-square-foot figure is descriptive, not a standalone valuation. Offer an indicated range only when there are enough credible, comparable closed sales and the subject identity and key inputs are sufficiently corroborated. Otherwise state that the evidence does not support a range and explain what is missing. Do not invent or silently impute prices, area, condition, concessions, status, or adjustments.
5. **Handle photographs honestly.** Use a real subject photo only when a direct listing page matches the complete address, ZIP, and unit. Prefer the listing's primary structured-data or Open Graph image. Follow source terms and obtain permission before redistribution. Never use stock, generated, or neighboring-property images. If identity, access, or usage rights are unclear, omit the image or label it "Photo unavailable." Apply the same checks independently to each comparable.
6. **Create the PDF.** Use the available property-report application/export path when it is available; otherwise use an available document or PDF workflow. Include the subject address and report date, a concise property summary, a comparable-sales table, a transparent calculation or an explicit unavailable result, source links next to the facts they support, retrieval dates, methodology, and limitations. Keep the report readable when printed; use landscape pages for wide tables. Do not present draft or uncorroborated facts as verified.
7. **Deliver and verify.** Confirm that the PDF exists, opens, and contains the intended address, tables, sources, calculations or limitation statement, and page layout. Give the user the file and a short note on the number and quality of usable comparables. Do not publish or share the address or report externally unless the user asks for that destination.

## Evidence and privacy

- Use current web research for facts that change, especially status, price, sale date, and source availability. Cite direct pages rather than search result pages.
- Distinguish sourced facts, derived metrics, assumptions, and unresolved conflicts in the report.
- A residential address is sensitive location information. Use it only for the requested research and the resulting private report; do not expose it in public repository examples, logs, or public sharing without explicit direction.
- Do not bypass logins, paywalls, CAPTCHAs, or source access controls. When a source cannot be verified, say so and continue with available evidence.
- Avoid claims that imply appraisal-level certainty. Include a brief statement that the report is informational, based on the cited public sources available on the retrieval date, and is not an appraisal.

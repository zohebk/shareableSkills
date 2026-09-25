# Shareable Codex Skills

This repository is a growing collection of reusable Codex skills. It starts with skills for realtor property research and PDF reports; more skills will be added over time.

## Current skill

### [Realtor Property PDF](realtor-property-pdf/SKILL.md)

Research a US residential property from its address and create a sourced, comparable-sales PDF. The skill emphasizes exact property and unit matching, direct source verification, transparent comparable selection, and clear limits when evidence is incomplete.

Invoke it in Codex with `$realtor-property-pdf` and the property address. See the [skill instructions](realtor-property-pdf/SKILL.md) for its full workflow.

## Try the report workflow

Open the live [Property Folio app](https://property-folio.zohebkerawalla.workers.dev/) to research an address and export the resulting report as a PDF. The app searches current public sources, checks the exact address and unit, links the evidence, and says when a fact or photo is unavailable.

You can use prompts like these with the skill:

```text
$realtor-property-pdf 2 Sweet Briar Ct, Belle Mead, NJ 08502-4631
```

```text
Create a sourced comparable-sales PDF for 123 Main Street, Princeton, NJ 08540. Verify the exact property and unit, use direct listing pages, include source links and retrieval dates, and clearly label any unavailable facts.
```

```text
Generate a preliminary CMA-style PDF for 45 Oak Avenue, Austin, TX 78701. Find recent comparable closed sales, explain why each comp was selected, show the calculation inputs, and do not invent a value if the evidence is insufficient.
```

## Sharing and privacy

Keep API keys, private property research, and personal reports out of this public repository. Use current direct sources, cite evidence, and label uncertainty clearly. Additional skills can be added in their own folders and listed here as the collection grows.

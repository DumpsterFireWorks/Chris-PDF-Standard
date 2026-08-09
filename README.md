# Chris PDF Standard

Canonical PDF/document design standard - Version 1.

This repository is the reusable source of truth for Chris's PDF and document visual system. Future PDFs should start here instead of being redesigned from scratch.

## Default rule

Change the content, not the visual language, unless the document genuinely needs a different format or Chris explicitly requests a different design.

## Included layout families

- Multi-page analysis / management report
- One-page portrait priority / legend / quick-reference sheet
- General procedure / instruction / technical-reference page

## Canonical source

- `template/Chris_PDF_Standard_v1.html` - self-contained editable master template
- `PDF_STANDARD_RULES.md` - visual and usage rules
- `brand_tokens.json` - reusable design tokens
- `template/Chris_PDF_Standard_v1.pdf` - rendered master/reference

The master HTML carries the current ReFab-style header directly, so the template has no external brand-image dependency.

## Golden references

- `references/ReFab_Flow_Analysis_Improvement_Template.pdf`
- `references/ReFab_Flow_Improvement_Priority_Legend_Portrait.pdf`

The golden references preserve approved layout patterns. They are reference examples, not blank forms to overwrite.

## Versioning

Do not silently change V1. Material changes to the design system should be explicitly approved and recorded as a new version when appropriate.

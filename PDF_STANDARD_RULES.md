# Chris PDF Standard v1

## Purpose
This is the default visual and structural standard for future PDFs unless Chris explicitly asks for a different design. The goal is consistency: future reports should look like they came from the same system, not from a different template every time.

## Visual DNA
- US Letter portrait by default.
- Strong centered brand header.
- Large uppercase red document title.
- Small gray subtitle directly below the title.
- Thin red divider under the title block.
- Red uppercase section labels.
- White page with generous whitespace.
- Light gray cards for neutral notes and summaries.
- Very light red cards for primary takeaways or important new signals.
- Dark charcoal body text; muted gray helper text.
- Consistent page numbering in the upper-right corner.
- Tables use thin gray rules, not heavy borders.
- Charts use restrained gridlines and the same red accent.

## Default page types
1. Executive Summary / Fast Read
2. Ranking or Frequency Chart
3. Themes / What Stands Out
4. Priority / Action Table
5. General Procedure / Instruction / Technical Reference

Use only the pages needed. Do not force every PDF to contain all five page types.

## One-page quick-reference pattern
For signs, legends, priority sheets, and quick-reference documents, use the approved portrait pattern:
- bold centered title;
- one-line subtitle;
- prominent rule/callout near the top;
- clearly numbered priority tiers or steps;
- short severity/status labels;
- concise Why / rationale text;
- short rollout/process footer when useful.

## Content rules
- Front-load the most important conclusion.
- Keep the main takeaway readable in about 20 seconds.
- Prefer short evidence-driven statements over long prose.
- Use callouts for constraints, scope notes, exceptions, or proof requirements.
- Keep charts and tables readable on an iPad and when printed.
- Avoid decorative clutter.
- Preserve the same spacing, typography hierarchy, accent use, and page structure across documents.

## Generation rule
When a future PDF is requested, start from `template/Chris_PDF_Standard_v1.html` or the appropriate golden reference and replace the content. Do not redesign the document unless Chris explicitly asks for a different style or the content truly requires a different page format.

## Brand swapping
The master HTML uses a self-contained ReFab-style text header so it has no external image dependency. For another company/project, replace the brand text/header and, if needed, the accent token. Keep the rest of the visual system intact unless the new brand genuinely requires a controlled variation.

## Versioning rule
Do not silently replace V1. Material visual changes require explicit approval and should create a new version when appropriate.

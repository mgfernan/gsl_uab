# GitHub Copilot Instructions for `gsl_uab`

These instructions apply project-wide when generating or editing content in this repository.

## Primary Objective

Maintain technical clarity and **consistent notation** across the book and teaching materials.

## Notation Consistency (Required)

When writing or editing any chapter, notebook narrative, slide, or asset text:

1. Treat `book/notation.qmd` as the source of truth for symbols and conventions.
2. Reuse existing symbols before introducing new ones.
3. If a new symbol is unavoidable, make it consistent with current style and add/update its definition in `book/notation.qmd`.
4. Keep symbol meaning stable across files (do not reuse one symbol for different concepts).
5. Keep indexing and vector/matrix style consistent (for example: scalar vs vector notation, transpose style, time indices, coordinate frames).
6. Keep naming aligned with chapter context and avoid silent renaming of variables between sections.

## Acronyms and Terminology

1. Use `book/acronyms.md` as the source of truth for abbreviations.
2. Expand acronym on first use in a chapter/section unless the local style already establishes it.
3. Use one term per concept consistently (avoid alternating synonyms unless pedagogically needed).

## Editing Behavior

1. Prefer minimal, localized edits.
2. Preserve existing structure and tone of each document.
3. Avoid introducing broad formatting churn unrelated to the requested change.
4. For math-heavy edits, quickly scan nearby sections to ensure variable continuity.

## Pre-Completion Checklist

Before finishing a content edit, verify:

- Symbols used are already defined in `book/notation.qmd` or were added there.
- Acronyms used match `book/acronyms.md`.
- No conflicting notation was introduced in the touched files.
- Equations, captions, and surrounding prose use the same variable names.

## Style

1. Use allways impersonal style (avoid "we", "you", "I").
2. Use active voice when possible.
3. Use clear and concise language.
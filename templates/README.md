# MediaWiki template collection

Reusable MediaWiki templates for documenting Tower District content. The collection is organized by purpose so individual templates can be copied into the existing wiki as needed.

## Structure

- `decorations/` — reusable visual sections and page decorations.
- `infoboxes/` — compact, structured summaries for area, tower, and difficulty pages.
- `documentation/` — usage notes and import guidance.

## Conventions

- Template source files use the `.wikitext` extension in this repository for easy review. When importing a template into MediaWiki, copy the source into a page named `Template:TemplateName`.
- Parameter names should be descriptive and consistent. Optional values should not leave broken labels or empty rows.
- Use plain wiki markup where possible; avoid dependencies on extensions unless the documentation explicitly says otherwise.
- Preview templates in a sandbox before using them on live pages.
- Replace example values with verified information. Do not invent game details to fill empty fields.

See [documentation](documentation/README.md) for usage and import notes.

# Template documentation

This directory documents how to use and maintain the Tower District MediaWiki templates.

## Importing a template

1. Open the relevant `.wikitext` file in this repository.
2. Copy its contents.
3. On the target wiki, create the corresponding page under the `Template:` namespace. For example, import `infoboxes/Tower.wikitext` as `Template:Tower infobox`.
4. Preview it in a sandbox with sample parameters before using it on real pages.
5. Check the rendered page on both desktop and mobile layouts.

The source files are examples for adaptation, not a guarantee that every wiki's installed extensions, CSS, or configuration will match. If your wiki uses a different naming convention, update the template page names and examples consistently.

## General usage

- Keep factual content on the article page; templates should organize and display it.
- Use the same parameter names across pages of the same type.
- Leave unknown information blank rather than guessing.
- Prefer accessible headings and readable contrast. Do not rely on colour alone to communicate difficulty or status.
- If a template uses CSS classes, confirm that the target wiki's stylesheet supports them. The starter templates here mainly use standard MediaWiki table markup.

## Suggested page names

| Repository file | Suggested MediaWiki page |
| --- | --- |
| `decorations/AreaInfo.wikitext` | `Template:Area info section` |
| `decorations/TowerInfo.wikitext` | `Template:Tower info section` |
| `decorations/DifficultyInfo.wikitext` | `Template:Difficulty info section` |
| `infoboxes/Area.wikitext` | `Template:Area infobox` |
| `infoboxes/Tower.wikitext` | `Template:Tower infobox` |
| `infoboxes/Difficulty.wikitext` | `Template:Difficulty infobox` |

## Contributing

Before adding or changing a template, explain its intended use, document its parameters, and include a small example. Keep changes focused so templates can be reviewed and imported independently.

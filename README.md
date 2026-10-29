# Tower District Wiki Templates

A community-maintained collection of reusable [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) templates for documenting Tower District areas, towers, and difficulty classifications.

## Repository layout

```text
templates/
├── README.md
├── decorations/
│   ├── AreaInfo.wikitext
│   ├── TowerInfo.wikitext
│   └── DifficultyInfo.wikitext
├── infoboxes/
│   ├── Area.wikitext
│   ├── Tower.wikitext
│   └── Difficulty.wikitext
└── documentation/
    └── README.md
```

### Decorations
Reusable highlighted sections for area, tower, and difficulty articles.

### Infoboxes
Structured summary boxes for areas, towers, and difficulty classifications.

### Documentation
Instructions for importing, testing, and maintaining templates on a MediaWiki installation.

## Using the templates

The `.wikitext` files contain source code for individual MediaWiki templates. Copy a file's contents into the corresponding `Template:` page on your wiki, then test it in a sandbox before using it on live articles. The suggested page names and usage examples are documented in [templates/documentation/README.md](templates/documentation/README.md).

These templates are starter components and may need adjustments to match the target wiki's styling and conventions. Verify all game information before publishing it.

## License

This repository is distributed under the MIT License. See [LICENSE](LICENSE) for the full text.

# MECCG Arda Master Database

A navigable GitHub Pages site and auditable master database for Hero Arda in the Middle-earth Collectible Card Game (MECCG).

## Website

- Published website: https://jamspot.github.io/meccg-arda-master-database/
- Card inventory page: https://jamspot.github.io/meccg-arda-master-database/docs/card-inventory.html
- Download the current card inventory: https://jamspot.github.io/meccg-arda-master-database/data/gandalf-gene-arda-card-inventory.csv

## Project principles

- Canonical Gandalf Gene Arda is the primary comparison point.
- Other Arda lists and rulesets are labelled comparisons or variants, not silently merged.
- No proxies: acquisition work is for genuine physical MECCG cards.
- Source discrepancies are recorded rather than silently corrected.
- Minion Arda is outside scope unless explicitly requested.

## Current working quantity baseline

The extracted Gandalf Gene spreadsheet contains 699 explicit physical copies across METW (552), METD (105), MEDM (41) and MEBA (1). Two named rows, Army of the Dead and The White Tree, have blank quantities. The published summary of 695 copies remains inconsistent with the explicit row quantities.

## Main site sections

- [Arda overview](docs/arda-overview.md)
- [Gandalf Gene — canonical deck](docs/gandalf-gene.md)
- [Card inventory page](docs/card-inventory.md)
- [Card inventory CSV](data/gandalf-gene-arda-card-inventory.csv)
- [Source reconciliation](docs/source-reconciliation.md)
- [Comparison lists](docs/comparison-lists.md)
- [Rules and variants](docs/rules-and-variants.md)
- [Sources and downloads](docs/sources.md)
- [Research progress](docs/research-progress.md)
- [Inventory method](docs/card-inventory-method.md)
- [Reconciliation log](docs/reconciliation-log.md)
- [Expansion checksum CSV](data/expansion-checksums.csv)

GitHub Pages uses Jekyll and the shared layout in `_layouts/default.html`. All site links should use Jekyll-compatible page URLs and the configured `baseurl`.

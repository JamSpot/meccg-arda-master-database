# MECCG Arda Master Database

A navigable learning site and auditable master database for Hero Arda in the Middle-earth Collectible Card Game (MECCG).

## Website

- Main site: https://jamspot.github.io/meccg-arda-master-database/
- Multiplayer Arda guide: https://jamspot.github.io/meccg-arda-master-database/docs/arda-multiplayer-play.html
- Arda-specific solo guide: https://jamspot.github.io/meccg-arda-master-database/docs/arda-solo-play.html
- Card inventory: https://jamspot.github.io/meccg-arda-master-database/docs/card-inventory.html
- Inventory CSV: https://jamspot.github.io/meccg-arda-master-database/data/gandalf-gene-arda-card-inventory.csv

## Project boundaries

- This repository teaches the Arda Basic Game multiplayer format and documents Arda-specific solo adaptations.
- Multiplayer instructions follow the published Arda Rules 4.0 unless a page explicitly labels another rules version.
- Solo variants are labelled by source/version; their procedures are not silently combined.
- Conventional Hero-vs-Hazard solo lessons and their fixed teaching decks belong only in the separate [MECCG Hero Solo Academy](https://jamspot.github.io/meccg-hero-solo-academy/).
- Canonical Gandalf Gene Arda is the primary card-pool comparison point.
- Other Arda lists and rulesets are labelled comparisons or variants, not silently merged.
- No proxies: acquisition work is for genuine physical MECCG cards.
- Source discrepancies are recorded rather than silently corrected.
- Minion Arda is outside scope unless explicitly requested.

## Main learning routes

1. [Arda overview](docs/arda-overview.md)
2. Choose [multiplayer Arda](docs/arda-multiplayer-play.md) or [solo Arda](docs/arda-solo-play.md)
3. [Rules and variants](docs/rules-and-variants.md)
4. [Gandalf Gene canonical deck](docs/gandalf-gene.md)
5. [Card inventory](docs/card-inventory.md) and [comparison lists](docs/comparison-lists.md)

## Current working quantity baseline

The working Gandalf Gene inventory contains 699 explicit physical copies across METW (552), METD (108), MEDM (32), MELE (6) and MEBA (1). Independent catalogue checks corrected the expansion assignments for Peril Returned, Uruk-Lieutenant and Wild Trolls; quantities were retained. Army of the Dead and The White Tree are METW but have blank quantities. The published summary of 695 copies remains inconsistent with the explicit row quantities.

GitHub Pages uses Jekyll and the shared layout in `_layouts/default.html`. All site links should use Jekyll-compatible page URLs and the configured `baseurl`.

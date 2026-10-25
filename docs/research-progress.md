# Research Progress

## Current stage
The source spreadsheet has been extracted into a card-by-card working CSV. The current priority is row-level reconciliation and independent card-metadata checks, not collecting more general Arda references.

## Confirmed from the extracted Gandalf Gene workbook
- 377 named card rows after excluding title/header structure.
- 375 rows have numeric quantities.
- 374 distinct names among numeric rows because Nenseldë the Wingild appears twice.
- Numeric quantity sum: 699.
- The workbook Desglose summary states 695.
- Army of the Dead and The White Tree have blank quantity fields.
- Uruk-Lieutenant and Wild Trolls have quantity 3 but blank rarity in the extraction.
- Published expansion distinct counts 300 + 59 + 14 + 2 + 1 sum to 376, not 377.

## Completed
- Added a [reconciliation log](reconciliation-log.html) with the count bridge and named anomalies.
- Added a machine-readable [expansion checksum CSV](../data/expansion-checksums.csv).
- Added the [inventory data method](card-inventory-method.html).
- Published the [card-by-card working inventory](card-inventory.html) and [downloadable CSV](../data/gandalf-gene-arda-card-inventory.csv).
- Added the [24 October 2026 source watch](research-watch-2026-10-24.html), including the Samwise deckbuilding tool and BGG file-format clarification.
- Added the [25 October 2026 source watch](research-watch-2026-10-25.html), documenting direct MeCCG catalogue downloads for independent card identity, expansion and rarity checks.

## Latest source-watch result — 25 October 2026
- MeCCG's downloads page links a separate [MeCCG List of Cards XLS](https://meccg.es/meta/cards/list/MeCCG%20List%20of%20Cards.xls), a [Full Spoiler List PDF](https://meccg.es/meta/cards/MeCCG%20Full%20Spoiler%20List.pdf) and a [Fixed Sets PDF](https://meccg.es/meta/cards/list/Fixed%20Sets.pdf).
- The XLS is a candidate cross-check for card identity, expansion and rarity; its version/date and actual coverage have not yet been verified. The spoiler PDF states it was updated in February 2007.
- These are reference/catalogue resources, not Arda quantity lists. No newly found downloadable Arda spreadsheet or alternate canonical pool changes the inventory baseline.
- The 699 explicit-copy total versus the published 695 summary remains unresolved.

## Next concrete work
1. Recompute the workbook's Desglose totals by category from raw rows.
2. Match all source rows to the independent transcription.
3. Verify expansion, rarity and card identity against the reference catalogue and Council card database.
4. Resolve or document the four-copy discrepancy.
5. Produce an audited physical-card acquisition table with provenance for every quantity.

## Status labels
- Verified — identity and source fields checked.
- Source discrepancy — source summaries disagree.
- Needs reconciliation — row-level investigation remains.
- Variant — belongs to another Arda list/ruleset.
- Excluded — outside canonical project scope.

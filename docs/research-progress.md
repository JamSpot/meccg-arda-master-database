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
- Added the [26 October 2026 source watch](research-watch-2026-10-26.html), documenting the separate 888-card Dream Cards Arda list and distinguishing its role from the canonical pool.
- Added the [27 October 2026 source watch](research-watch-2026-10-27.html), verifying the current official card database download artifacts and tracking recent BGG Arda discussion leads.

## Latest source-watch result — 27 October 2026
- Verified the Council of Elrond official card database repository was last updated 19 September 2026 and its tree contains a 4,163,611-byte `cards.json` plus a 22,147-byte `changes-guide.xlsx`. These are useful for metadata and errata checks, not Arda quantities; the JSON was too large for the connector's content-fetch limit, so no row matching is claimed yet.
- Flagged three BGG community leads: a modular solo/Arda/variants thread (shown as 23 days old), a request for ARDA card lists (21 days old), and the Gen Con 2026 Arda thread (four months old, 24 replies). BGG thread access was blocked, so no new attachment or quantity source was verified.
- No new standard Hero Arda quantity list was confirmed. The explicit 699-copy total versus the published 695 remains unresolved.

## Previous source-watch result — 26 October 2026
- Documented the 888-card “The Houses of the North” Arda list on Council of Elrond. It is an itemized forum post last edited 30 July 2025, but includes Dream Cards, optional UEPs and unreleased-set experiments; it remains a separately labelled variant, not part of the canonical standard Hero pool.
- Reconfirmed the available downloads: BGG's MECCG Card List v1.13 XLS and Starter Set Decks Lists XLS, BGG's Arda example PDF, plus MeCCG's direct card catalogue XLS, Full Spoiler PDF and Fixed Sets PDF.
- No new standard Hero Arda quantity source resolves the discrepancy. Explicit quantities remain 699 versus the published 695.

## Previous source-watch result — 25 October 2026
- MeCCG's downloads page links a separate [MeCCG List of Cards XLS](https://meccg.es/meta/cards/list/MeCCG%20List%20of%20Cards.xls), a [Full Spoiler List PDF](https://meccg.es/meta/cards/MeCCG%20Full%20Spoiler%20List.pdf) and a [Fixed Sets PDF](https://meccg.es/meta/cards/list/Fixed%20Sets.pdf).
- The XLS is a candidate cross-check for card identity, expansion and rarity; its version/date and actual coverage have not yet been verified. The spoiler PDF states it was updated in February 2007.
- These are reference/catalogue resources, not Arda quantity lists. No newly found downloadable Arda spreadsheet or alternate canonical pool changes the inventory baseline.
- The 699 explicit-copy total versus the published 695 summary remains unresolved.

## Next concrete work
1. Obtain a parseable copy of the Council of Elrond `cards.json` or catalogue XLS, then match every source row by identity and expansion.
2. Recompute the workbook's Desglose totals by category from raw rows.
3. Match all source rows to the independent transcription.
4. Verify expansion, rarity and card identity against the reference catalogue and Council card database.
5. Resolve or document the four-copy discrepancy.
6. Produce an audited physical-card acquisition table with provenance for every quantity.

## Status labels
- Verified — identity and source fields checked.
- Source discrepancy — source summaries disagree.
- Needs reconciliation — row-level investigation remains.
- Variant — belongs to another Arda list/ruleset.
- Excluded — outside canonical project scope.

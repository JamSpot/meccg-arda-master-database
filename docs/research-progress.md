# Research Progress

## Current stage
The source spreadsheet has been extracted into a card-by-card working CSV. Independent catalogue and Council of Elrond checks have corrected three numeric expansion assignments, identified the two blank-quantity cards' expansions, and verified five card identities/set codes. The remaining priority is the four-copy row-level reconciliation and complete automated metadata match.

## Confirmed from the extracted Gandalf Gene workbook
- 377 named card rows after excluding title/header structure.
- 375 rows have numeric quantities.
- 374 distinct names among numeric rows because Nenseldë the Wingild appears twice; the two blank-quantity rows bring the unique named identity count to 376.
- Numeric quantity sum: 699; the workbook Desglose summary states 695, leaving +4 unresolved.
- Army of the Dead and The White Tree have blank quantity fields; independent catalogue identifies both as METW.
- Peril Returned (3 copies) is corrected from MEDM to METD; Uruk-Lieutenant and Wild Trolls (3 copies each) are corrected from MEDM to MELE. Rarity remains blank for the latter two.
- Verified expansion copies are METW 552, METD 108, MEDM 32, MELE 6 and MEBA 1; total remains 699.
- Published expansion distinct counts 300 + 59 + 14 + 2 + 1 sum to 376, matching unique named identities. The headline 377 likely counts duplicate Nenseldë twice.

## Completed
- Added a [reconciliation log](reconciliation-log.html) with the count bridge and named anomalies.
- Added a machine-readable [expansion checksum CSV](../data/expansion-checksums.csv).
- Added the [inventory data method](card-inventory-method.html).
- Published the [card-by-card working inventory](card-inventory.html) and [downloadable CSV](../data/gandalf-gene-arda-card-inventory.csv).
- Added the [24 October 2026 source watch](research-watch-2026-10-24.html), including the Samwise deckbuilding tool and BGG file-format clarification.
- Added the [25 October 2026 source watch](research-watch-2026-10-25.html), documenting direct MeCCG catalogue downloads for independent card identity, expansion and rarity checks.
- Added the [26 October 2026 source watch](research-watch-2026-10-26.html), documenting the separate 888-card Dream Cards Arda list and distinguishing its role from the canonical pool.
- Added the [27 October 2026 source watch](research-watch-2026-10-27.html), verifying current official card database download artifacts, tracking recent BGG Arda discussion leads, and recording three independent expansion corrections.
- Added the [28 October 2026 source watch](research-watch-2026-10-28.html), documenting a previously untracked 2013 solo-Arda build with a session report and comparing its pile structure with the canonical format.\n- Added the [29 October 2026 source watch](research-watch-2026-10-29.html), documenting Arda Rules 4.0's general pile-sizing guidance, contrasting it with the 423-card Gandalf Gene Play Deck, and adding five targeted CoE card-metadata checks to the inventory.
- Added the [30 October 2026 source watch](research-watch-2026-10-30.html), cataloguing the 2014 Arda Revised rules, the 2023–24 Hero compiled ruleset, Thorin's Wizards/Dragons treasure-travel aid, the 2022 Spanish solo-Arda variant, and the BGG Arda deck example XLS lead. Corrected the source register's earlier PDF label for that XLS.

## Latest source-watch result — 30 October 2026
- Found additional BGG Arda resources: Arda Revised (2014 PDF); Compiled Arda Ruleset — Hero (2023, revisions through 13 March 2024); Thorin's Travel Guide to Treasure (2023 PDF, explicitly The Wizards and The Dragons only); and a Spanish Arda summary with a solitaire version added in November 2022.
- Corrected the BGG archive format for **Arda deck example** by Jose-san: the archive lists it as **XLS**, not PDF. The workbook attachment was not retrievable for extraction in this pass, so it has not yet been compared card-by-card or used to change any quantities.
- The Hero compiled ruleset is a community compilation with optional variants, not an official Council of Elrond ruling. The travel guide is a site/item aid, not an inventory. The Spanish file is a separate language-specific solo variant.
- No newly found file establishes a replacement canonical quantity list. Explicit quantities remain METW 552, METD 108, MEDM 32, MELE 6 and MEBA 1 (699 total), versus the workbook's published 695 summary. Army of the Dead and The White Tree remain blank-quantity rows.
- No user decision is required for this pass.

## Previous source-watch result — 29 October 2026
- Added the published [Arda Rules 4.0 PDF](https://lureofmiddleearth.com/wp-content/uploads/2016/03/arda_4.0_en.pdf). It describes shared-deck multiplayer Arda (2–7 players) and recommends a 250+ Play Deck with equal resources/hazards, about 15 MP cards per player, a character pool of about 70 for larger games, and a 30–35 card Minor Item Offering Deck.
- The 1:1 resource/hazard recommendation differs from the current Gandalf Gene transcription (171 resources and 252 creatures/hazards). This is a rules/build comparison; do not alter the source quantities without evidence.
- Targeted Council of Elrond database checks verified TW-193 Army of the Dead, TW-348 The White Tree, TD-54 Peril Returned, LE-96 Uruk-lieutenant and LE-100 Wild Trolls. The inventory now records card IDs and metadata; source quantities for Army of the Dead and The White Tree remain blank.
- Identified direct downloads for MeCCG's character XLSX, Challenge Decks ZIP and Challenge Decks player-aid PDF. These are catalogue/Challenge Deck references, not new Arda quantity sources.
- No new standard Hero Arda spreadsheet or exact deck file was found. The 699 explicit copies versus the workbook's 695 summary remains unresolved.
- The full 4.16 MB CoE JSON could not be loaded as one parseable file through the current GitHub connector, so the full automated match remains outstanding.

## Previous source-watch result — 28 October 2026
- Found [My Solo Arda Build with Session Report](https://boardgamegeek.com/thread/1058232/my-solo-arda-build-with-session-report), published 22 October 2013 and edited with additional turns in November 2013. It describes separate MP, Ring, Resource, Minor Item, two Character, Hazard and Site decks, generally using one of each owned card plus selected multiples. It excludes Lidless Eye, White Hand and Balrog.
- This is a meaningful solo-method comparison but not an exact decklist: no card-by-card quantities, spreadsheet or downloadable deck file were verified. It must not be used to change canonical card counts.
- The original Gandalf Gene workbook remains the canonical quantity source. Its 699 explicit copies still conflict with its published 695 summary.
- Compared the locally archived MECCG_Card_List.xlsx: 144 catalogue rows, 45 normalized name overlaps, and no rarity values. It is too partial to establish the full pool or override set assignments; it does not resolve quantities.
- No user decision is required for this research step.

## Previous source-watch result — 27 October 2026
- Cross-checked five expansion assignments against an independent catalogue: Army of the Dead and The White Tree are METW; Peril Returned is METD; Uruk-Lieutenant and Wild Trolls are MELE. This corrects working metadata while preserving all quantities.
- Verified the Council of Elrond official card database repository was last updated 19 September 2026 and contains a 4,163,611-byte `cards.json` plus a 22,147-byte `changes-guide.xlsx`. The JSON was too large for the connector's content-fetch limit, so full machine matching remains outstanding.
- Flagged three BGG community leads: a modular solo/Arda/variants thread (shown as 23 days old), a request for ARDA card lists (21 days old), and the Gen Con 2026 Arda thread (four months old, 24 replies). BGG thread access was blocked, so no new attachment or quantity source was verified.
- Corrected distinct-card counts now align with the published expansion subtotals at 376 unique identities. The headline 377 likely counts duplicate Nenseldë twice. The physical-copy total remains 699 versus the published 695.

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
1. Recompute the workbook's Desglose totals by category from raw rows and locate the four-copy difference.
2. Obtain a parseable copy of the Council of Elrond `cards.json` or catalogue XLS, then match every source row by identity, expansion and rarity.
3. Match all source rows to the independent transcription.
4. Resolve or document remaining identity and rarity anomalies.
5. Produce an audited physical-card acquisition table with provenance for every quantity.

## Status labels
- Verified — identity and source fields checked.
- Source discrepancy — source summaries disagree.
- Needs reconciliation — row-level investigation remains.
- Variant — belongs to another Arda list/ruleset.
- Excluded — outside canonical project scope.

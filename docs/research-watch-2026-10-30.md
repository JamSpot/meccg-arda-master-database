---
layout: default
title: Source watch — 30 October 2026
---

# Source watch — 30 October 2026

## Summary

This pass uncovered a useful cluster of published Arda references in the BoardGameGeek MECCG file archive:

- a revised all-in-one Arda rulebook (2014);
- a later Hero-only compiled Arda ruleset, with revisions through 13 March 2024;
- a treasure/site-travel player aid (2023), limited to The Wizards and The Dragons;
- a Spanish Arda summary whose later version adds a solitaire variant (2022);
- and an **Arda deck example listed as an XLS spreadsheet**, not a PDF.

The XLS is the most relevant new lead for card-pool comparison. Its listing confirms the file format, but the attachment contents were not available for extraction in this pass. None of these sources is a verified replacement for the Gandalf Gene workbook as the canonical quantity source.

## New Arda rules and player-aid references

| Source | Date / format | What it contributes | How to use it |
|---|---|---|---|
| [Arda Revised](https://boardgamegeek.com/filepage/98645/arda-revised) by SpiralDawn | 4 January 2014; PDF, 3 MB | An all-in-one revised rulebook intended to replace the original rulebook when playing Arda. | Historical rules comparison; not a card inventory or official rules authority. |
| Compiled Arda Ruleset — Hero by Gamer_2k4 | Original 20 September 2023; revisions 27 November 2023 and 13 March 2024; PDF (latest listed 160 KB) | Compiles and streamlines Hero Arda rules, drawing on the original Arda rules and selected adjustments from other players; includes optional variants and modifications. | Particularly relevant to the Hero-only scope. Keep it labelled as a community compilation, not as the canonical pool definition. |
| Thorin's Travel Guide to Treasure by CDavis7M | 26 May 2023; PDF, 2.32 MB | Arda player aid listing item playability, site attacks, site paths and card draw. The author explicitly limits it to The Wizards and The Dragons cards. | Useful for route planning and treasure-site checks in a METW/METD-focused build; it does not cover the full later-expansion pool. |
| Arda and summary by HANJEL | 31 October 2022; PDF, 1.28 MB; revised 2 November | Simplified Arda mode and game-rule summary in Spanish. | Separate language-specific variant/reference. |
| Arda and summary — solitaire addition | 23 November 2022; PDF, 1.29 MB | Later file description explicitly says a solitaire version was added. | A lead for solo-Arda comparison; Spanish text must be translated/checked before adopting rules. |

The BGG archive describes the compiled Hero ruleset as a personal compilation that includes optional variants. It should not be treated as an official Council of Elrond ruling. The 2023 travel guide is a navigation aid rather than a decklist: it may be useful to the practical Arda guide, but its stated Wizards/Dragons scope must be preserved.

## New downloadable deck-list lead: Arda deck example XLS

The [BoardGameGeek MECCG files archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files) lists **“Arda deck example” by Jose-san** as an **XLS spreadsheet** (listed as approximately 13 years old).

This corrects the previous source-register description, which called this file a PDF. The same archive separately lists several Arda rulebooks and solo/player aids as PDFs; these are distinct files.

**Extraction status:** the archive listing confirms that the Arda deck example is an XLS, but the BGG attachment itself was not exposed as a retrievable workbook during this pass. I have therefore not claimed to have parsed its card names or quantities. Once its workbook contents can be obtained, it should be compared against:
1. the original Gandalf Gene spreadsheet;
2. the 178-entry CardGameGeek transcription, which explicitly says two hazards are missing;
3. the working card inventory and expansion codes.

Until that comparison is complete, the XLS is an independent Arda example, not an authority for the canonical card pool.

## Comparison with existing sources

| Source | Primary purpose | Card quantities? | Relationship to Gandalf Gene |
|---|---|---|---|
| Gandalf Gene's original workbook (2016) | Specific published Hero Arda build | Yes; main quantity authority | Canonical comparison baseline for this project |
| Arda Rules 4.0 | General shared-pool Arda rules and pile-size guidance | No fixed card-by-card list | General format guidance; its recommended 1:1 resource/hazard Play Deck differs from the extracted Gene list |
| Arda Revised (2014) | Revised all-in-one Arda rules | No verified inventory | Rules variant, not a pool replacement |
| Compiled Arda Ruleset — Hero (2023–24) | Hero-focused rules compilation and optional variants | No verified inventory | Most directly relevant new rules reference for Hero Arda, but still a community variant |
| Thorin's Travel Guide (2023) | Item/site route and playability aid | No | Useful for METW/METD site planning only |
| Spanish Arda/solitaire summary (2022) | Simplified rules and solo adaptation | No verified card-by-card quantities | Separate solo variant lead |
| Arda deck example XLS | Example card pool/deck listing | Potentially; contents not yet extracted | Promising independent pool comparison, but not yet reconciled |
| CardGameGeek Gandalf Gene transcription | Online transcription | Yes, but incomplete | Reports 178 main entries and says two hazards are missing; use as a checksum, not as authority |

## Downloadable files and where to find them

All BGG files below are discoverable from the [MECCG files archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files):

- **Arda deck example — XLS**, Jose-san — the new spreadsheet lead for card-pool comparison.
- **Arda Revised — PDF**, SpiralDawn — [individual file page](https://boardgamegeek.com/filepage/98645/arda-revised).
- **Compiled Arda Ruleset — Hero — PDF**, Gamer_2k4 — latest listed revision 13 March 2024.
- **Thorin's Travel Guide to Treasure — PDF**, CDavis7M — 2.32 MB; The Wizards and The Dragons only.
- **TierraMediaF2.pdf — PDF**, HANJEL — Spanish Arda summary with solitaire version added.
- **MECCG Card List v1.13 — XLS** — card information, rarity and distribution; dated 6 March 2010.
- **Starter Set Decks Lists — XLS** — Gandalf and Saruman starter-set deck lists.

The [MeCCG.com lists and downloads page](https://meccg.com/cards/lists-and-downloads/) and the [Council of Elrond card database](https://github.com/council-of-elrond-meccg/meccg-cards-database) remain separate metadata cross-checks. Their catalogues and errata data do not establish Arda copy quantities.

## Canonical quantities — unchanged

No newly discovered rules or aid file supplies evidence to alter the working quantities.

| Expansion | Explicit copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

The original workbook's published summary still states **695**, leaving a four-copy discrepancy. Army of the Dead and The White Tree still have blank source quantities. Their expansion identities are verified as METW, but their counts remain unknown.

The working distinct-card bridge remains 377 named rows, 375 numeric-quantity rows, 374 distinct names among numeric rows, and 376 unique named identities overall after deduplicating the repeated Nenseldë the Wingild row and retaining the two blank-quantity cards.

## Next concrete work

1. Obtain the BGG **Arda deck example XLS** attachment and extract its complete list without changing the canonical inventory.
2. Compare that XLS with the original Gandalf Gene workbook and the incomplete CardGameGeek transcription; record exact overlap, additions, omissions and quantity differences.
3. Extract and compare the latest Hero compiled rules and the Spanish solitaire variant where the files are accessible, keeping variant rules separate from canonical card counts.
4. Continue the row-level investigation of the 699-versus-695 discrepancy.
5. Complete the full Council of Elrond metadata match when a parseable copy of its full card database is available.

**Input needed:** none for this pass. The next meaningful milestone is obtaining and reconciling the Arda deck example workbook.

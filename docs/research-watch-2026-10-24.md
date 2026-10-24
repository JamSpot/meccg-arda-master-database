---
layout: default
title: Source watch — 24 October 2026
---

# Source watch — 24 October 2026

## Summary

This pass found **one new card-gallery/deckbuilding tool** and reconfirmed a current official rulings reference. No newly discovered public Arda list provides a better canonical quantity source than Gandalf Gene's original spreadsheet.

## New tool: Samwise MECCG Card Gallery & Deckbuilder

Repository: [SylvanSign/Samwise](https://github.com/SylvanSign/samwise)

The project describes an offline card gallery and deckbuilder for standard MECCG cards, with filtering, local save/load, human-readable deck files, and import/export using the Cardnum decklist format. Its README says its card metadata is sourced from Cardnum and that Dream Cards are not currently included.

**Database use:** a potential format and card-identity cross-check, and a possible route for testing future deck exports. It is not an Arda quantity list and must not be treated as evidence for the canonical pool's copy counts.

## Current official card/rulings references

- [Council of Elrond official card database](https://github.com/council-of-elrond-meccg/meccg-cards-database) — maintained card identity, card text, errata and clarifications; the repository also offers `cards.json` and a changes-guide spreadsheet.
- [Collected Rulings File 22](https://meccg.com/rules/collected-rulings-and-errata/crf-22/) — published 21 January 2026. Use it when checking current rulings and clarifications, not for Arda copy counts.
- [MeCCG deck database](https://meccg.com/decks/) — useful published constructed-deck examples and strategy context; not a canonical Arda inventory.
- [MeCCG lists and downloads](https://meccg.com/cards/lists-and-downloads/) — official-community card lists and fixed lists.

## Downloadable files: format clarification

The current BoardGameGeek [Middle-earth files archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files) lists:

- **MECCG Card List v1.13 — XLS**: card information, rarity and distribution; dated 6 March 2010.
- **Starter Set Decks Lists — XLS**: Gandalf and Saruman starter decks.
- **Arda deck example — PDF**: the currently listed archive entry is described as an example Arda deck. Treat it as a PDF deck reference, not as a spreadsheet unless a separate spreadsheet attachment is found.

This format clarification matters because the card catalogue is a spreadsheet, but the currently indexed Arda example is a PDF.

## Canonical quantity status — unchanged

The extracted Gandalf Gene workbook still has these explicit quantities:

| Expansion | Copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 105 |
| Dark Minions (MEDM) | 41 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

The published summary remains 695. Army of the Dead and The White Tree have blank quantity fields. No new source found in this pass resolves the four-copy difference or justifies changing any canonical quantity.

## Next useful work

Prioritize row-level reconciliation over more broad source searching:
1. Audit the workbook's category subtotals and identify the exact four-copy difference.
2. Compare card names and expansion assignments against the CoE card data and the v1.13 catalogue.
3. Keep alternative Arda lists and variants as separately labelled comparisons.
4. Once source quantities are reconciled, build the physical-card acquisition checklist.

No user decision is required for this research step.

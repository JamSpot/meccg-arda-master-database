---
layout: default
title: Source watch — 27 October 2026
---

# Source watch — 27 October 2026

## Summary

This pass made a **meaningful row-level correction** to the working inventory. An independent set-coded card catalogue identifies three cards whose extracted expansion assignments were wrong. The corrections make the working inventory's expansion distinct-card counts align with the published expansion subtotals. **No source quantities were changed**, and the four-copy difference between 699 explicit copies and the published 695 remains open.

## Row-level expansion corrections

The independent [MECCG cards list](https://elvenforest.narod.ru/meccg/cards/meccg_list.html) gives these set codes:

| Card | Copies in source | Original extraction assignment | Verified expansion | Catalogue evidence |
|---|---:|---|---|---|
| Peril Returned | 3 | MEDM | METD — The Dragons | Listed under TD |
| Uruk-Lieutenant | 3 | MEDM | MELE — The Lidless Eye | Listed under LE |
| Wild Trolls | 3 | MEDM | MELE — The Lidless Eye | Listed under LE |

The same catalogue places **Army of the Dead** and **The White Tree** under METW — The Wizards. Their quantity cells are blank, so they are counted as named identities but not as physical copies. The working CSV now uses the verified set codes and retains the original extracted assignment in each affected row's notes. The quantities are unchanged.

### Corrected expansion totals

| Expansion | Distinct cards with numeric quantities | Explicit physical copies |
|---|---:|---:|
| The Wizards (METW) | 298 | 552 |
| The Dragons (METD) | 59 | 108 |
| Dark Minions (MEDM) | 14 | 32 |
| The Lidless Eye (MELE) | 2 | 6 |
| The Balrog (MEBA) | 1 | 1 |
| **Total** | **374** | **699** |

The two additional blank-quantity identities, Army of the Dead and The White Tree, are both METW. Including them yields **300 METW and 376 unique named identities overall**. The published expansion subtotals (300 + 59 + 14 + 2 + 1) also sum to 376. The headline count of 377 likely counts the duplicate Nenseldë the Wingild row as another card; this interpretation is supported by the row arithmetic, though the original author's counting method is not confirmed.

## Verified downloadable metadata files

The [Council of Elrond official card database repository](https://github.com/council-of-elrond-meccg/meccg-cards-database) reports a last-updated date of **19 September 2026**. Its current `master` tree contains:

| File | Verified repository size | Direct access | Intended use |
|---|---:|---|---|
| `cards.json` | 4,163,611 bytes | [View JSON](https://github.com/council-of-elrond-meccg/meccg-cards-database/blob/master/cards.json) · [Raw JSON download](https://raw.githubusercontent.com/council-of-elrond-meccg/meccg-cards-database/master/cards.json) | Card identity and official-community metadata cross-check |
| `changes-guide.xlsx` | 22,147 bytes | [View spreadsheet](https://github.com/council-of-elrond-meccg/meccg-cards-database/blob/master/changes-guide.xlsx) · [Download XLSX](https://raw.githubusercontent.com/council-of-elrond-meccg/meccg-cards-database/master/changes-guide.xlsx) | Audit trail for changes from original printed card text |

The database README says the Council of Elrond Rules Committee maintains the database, applies rulings and errata, and has updated the text of approximately 300 cards. It is a current text/rulings reference, not an Arda quantity list. The connector confirmed the JSON file in the repository tree but could not retrieve its full contents because it exceeds the content-fetch limit; full machine matching is still outstanding.

## Recent community leads — no new list confirmed

The [BoardGameGeek Middle-earth page](https://boardgamegeek.com/boardgame/1915/middle-earth) currently surfaces these relevant forum threads:

- **“Turning MECCG into a Modular Solo Board Game – ARDA, Variants & Card Lists. Is it possible?”** — shown as 23 days old when checked on 27 October 2026.
- **“Looking for card lists to build ARDA decks”** — shown as 21 days old.
- **“MECCG ‘Arda’ at Gen Con 2026”** — shown as four months old, with 24 replies.

These are useful leads for community list discovery, but automated access to the individual BGG forum content was blocked (HTTP 403), so I could not inspect replies or verify any attachments. No new downloadable standard Hero Arda spreadsheet was confirmed.

The [BGG files archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files) still lists the MECCG Card List v1.13 XLS (6 March 2010), Starter Set Decks Lists XLS, and an Arda deck example PDF. The [MeCCG downloads page](https://meccg.com/cards/lists-and-downloads/) remains useful for catalogue and fixed-set references.

## Remaining quantity discrepancy

The source workbook's numeric rows still total **699 copies**, while its own Desglose summary says **695**. The expansion corrections merely reassign the same nine copies between sets; they do not explain the four-copy difference. Army of the Dead and The White Tree still have blank quantities, and the rarity fields for Uruk-Lieutenant and Wild Trolls remain blank.

## Next concrete work

1. Recalculate the workbook's Desglose totals by category from raw rows and identify the exact four-copy difference.
2. Obtain a parseable copy of the Council of Elrond `cards.json` or catalogue XLS for systematic identity/expansion/rarity matching.
3. Continue checking the recent BGG threads if accessible to see whether any new Arda list or downloadable file was shared.

**Input needed:** none at present. The next milestone is tracing the four-copy difference, not collecting more general sources.

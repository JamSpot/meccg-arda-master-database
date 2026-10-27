---
layout: default
title: Source watch — 27 October 2026
---

# Source watch — 27 October 2026

## Summary

This pass verified a current downloadable metadata source and identified three recent BoardGameGeek discussion leads. **No new standard Hero Arda quantity list was verified, and the canonical inventory totals remain unchanged.**

The most useful addition is a precise, version-tracked reference to the Council of Elrond's official card database repository and its two downloadable data files. These can support card identity, expansion and errata checks, but they do not establish the quantities in Gandalf Gene's Arda pool.

## Verified downloadable metadata files

The [Council of Elrond official card database repository](https://github.com/council-of-elrond-meccg/meccg-cards-database) reports a last-updated date of **19 September 2026**. Its current `master` tree contains:

| File | Verified repository size | Direct access | Intended use |
|---|---:|---|---|
| `cards.json` | 4,163,611 bytes | [View JSON](https://github.com/council-of-elrond-meccg/meccg-cards-database/blob/master/cards.json) · [Raw JSON download](https://raw.githubusercontent.com/council-of-elrond-meccg/meccg-cards-database/master/cards.json) | Card identity and official-community metadata cross-check |
| `changes-guide.xlsx` | 22,147 bytes | [View spreadsheet](https://github.com/council-of-elrond-meccg/meccg-cards-database/blob/master/changes-guide.xlsx) · [Download XLSX](https://raw.githubusercontent.com/council-of-elrond-meccg/meccg-cards-database/master/changes-guide.xlsx) | Audit trail for changes from original printed card text |

The database README says that the Council of Elrond Rules Committee maintains this database, applies rulings and errata, and has updated the text of approximately 300 cards. Treat this as the current rules/text reference, not as an Arda deck list. The repository's large JSON file was confirmed in the Git tree, but the connector could not retrieve its full contents because the file exceeds its content-fetch limit; no card-by-card comparison is claimed in this report.

## Recent community leads — no new list confirmed

The [BoardGameGeek Middle-earth page](https://boardgamegeek.com/boardgame/1915/middle-earth) currently surfaces these relevant forum threads:

- **“Turning MECCG into a Modular Solo Board Game – ARDA, Variants & Card Lists. Is it possible?”** — shown as 23 days old when checked on 27 October 2026.
- **“Looking for card lists to build ARDA decks”** — shown as 21 days old.
- **“MECCG ‘Arda’ at Gen Con 2026”** — shown as four months old, with 24 replies.

These are useful leads for finding community lists and recent Arda practices. However, automated access to the individual BGG forum content was blocked (HTTP 403), so I could not inspect replies or verify any attachment. They are therefore recorded as **follow-up leads only**, not as evidence for new card quantities or downloadable files.

The [BGG files archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files) still lists the MECCG Card List v1.13 XLS (6 March 2010), Starter Set Decks Lists XLS, and an Arda deck example PDF. The [MeCCG downloads page](https://meccg.com/cards/lists-and-downloads/) remains another source for catalogue and fixed-set references. No newly confirmed Arda spreadsheet was found in this pass.

## Canonical quantities — unchanged

The working Gandalf Gene extraction still has **699 explicit copies**, not the 695 stated in its published summary:

| Expansion | Explicit copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 105 |
| Dark Minions (MEDM) | 41 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

Army of the Dead and The White Tree still have blank quantity cells. The source's published distinct-card figures also remain inconsistent with the extracted rows. No quantity or expansion assignment was changed based on this source watch.

## Next concrete work

1. Obtain a parseable copy of the official metadata JSON or catalogue XLS and match every inventory row by card identity and expansion.
2. Recalculate the original workbook's category subtotals against the 699 explicit copies and the published 695 total.
3. Revisit the recent BGG threads if accessible to determine whether participants have posted a new Arda pool or downloadable list.
4. Keep alternate Dream Cards, Minion and other variant pools separately labelled; do not merge them into the canonical Hero Arda quantities.

**Input needed:** none at present. The next useful milestone is a row-level reconciliation backed by the source workbook and an independently parsed card catalogue.

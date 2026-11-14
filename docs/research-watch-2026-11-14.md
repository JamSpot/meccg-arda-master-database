---
layout: default
title: Research watch — 14 November 2026
---

# Research watch — 14 November 2026

## Result

**No new eligible ICE-only Hero Arda card pool or downloadable deck file was verified.** This pass did uncover a published Dream Card Arda decklist and a material audit issue in the separate 2022 Leon workbook. Both are excluded from the canonical physical-card database.

## 1. Published Dream Card Arda list — The Houses of the North

[Council of Elrond: ARDA with Dream Cards — The Houses of the North](https://councilofelrond.org/forum/viewtopic.php?p=38931)

- First posted **3 November 2021**; last edited **30 July 2025**.
- A Dwarves-themed Arda build described by its author as a Dream Card format.
- The author says it uses Dream Card rules/UEPs and tests some cards from unreleased sets.
- The author describes the list as **888 cards**. Its card-by-card contents are posted across the forum thread; no separate XLS/XLSX or standalone deck file is attached in the thread.
- It includes both original ICE cards and non-ICE Dream Card material. Examples of non-standard set-coded entries include A More or Less Decent Giant (DF), Asfaloth (RS), Carc (DF), Bolg, Son of Azog (DF), Gorfaur the Lame (NE), His Beard Long and Forked (DF) and Aglarond (TI).

This is a useful published Arda decklist for documenting the wider community, but it is **not** an ICE-only Hero pool. No names or quantities from it are imported into the master database.

## 2. 2022 Leon workbook — row-level audit and exclusion

The Library copy of `cards for Arda Leon 20220901.xlsx` was originally supplied from a Facebook/Lookaside URL that is no longer retrievable. Workbook metadata identifies the creator as **Leon en Claudia**, with creation date **1 September 2022** and last-modified date **21 February 2024**. Its public-source provenance cannot be independently verified, so it is treated as a user-supplied comparison workbook, not a verified published list.

| Category | Workbook summary | Direct row sum |
|---|---:|---:|
| Hazard creatures | 143 | **144** |
| Hazard events | 190 | 190 |
| Resource events | 265 | 265 |
| Resources | 199 | 199 |
| Characters | 100 | 100 |
| Minor items | 54 | 54 |
| Rings | 23 | 23 |
| **Total** | **974** | **975** |

The one-copy error is in the hazard-creature summary formula: the first category sum starts at row 7, but row 6 contains Carrion Birds, quantity 1. The formula excludes that copy. The row-level total is therefore 975, not the displayed 974.

A normalized English-name screen against the **1,674 card-ID rows** in the original MECCG Card List v1.13 found:

- **803 of 898 distinct names** have an exact name match in the original ICE catalogue.
- **95 names** do not match exactly.
- The exact-match names account for **863 copies**; the unmatched names account for **112 copies** across 85 non-zero names (10 unmatched names have zero copies).

This is a name-level screen only, not a definitive ICE filter. The unmatched group includes spelling/abbreviation/translation variants, but also names confirmed in the published Dream Card Arda list above. The workbook has no per-card set or printing IDs, so it cannot support safe expansion totals. It is not an ICE-only list and is not merged into any canonical quantity.

## 3. Current Arda forum lead — The Nine are Abroad

[Council of Elrond post, 23 September 2026](https://councilofelrond.org/forum/viewtopic.php?t=5369) announces a nine-player **Dream Card Minion Arda** box and points to the [Mellon deckbuilder](https://meccg.herokuapp.com/#/decks). The author says the list can be played and downloaded through that deckbuilder. It is current, but explicitly Dream Card and Minion material, so it is outside this Hero ICE-only project.

## 4. BoardGameGeek file archive check

The current [BoardGameGeek MECCG files index](https://boardgamegeek.com/boardgame/1915/middle-earth/files) surfaces the *Compiled Arda Ruleset — Hero* (15 March 2024) and older Arda resources, but no newer ICE-only Hero Arda card pool. The compiled ruleset is a rules reference, not a card-quantity source.

## 5. Canonical quantities — unchanged

| Expansion | Gandalf Gene explicit copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

CCG Collector's independent published summary remains **695 copies**, leaving the four-copy difference unresolved. The two blank-quantity rows in Gandalf Gene remain Army of the Dead and The White Tree. The Leon workbook and Dream Card decklist do not change this baseline.

## Next work

1. Recover and parse Thorondor's 83.5 KiB no-rares XLS as a separate pool.
2. Obtain a row-level export of BanalityBob's Google Sheet.
3. Continue the card-by-card reconciliation of Gandalf Gene's 699 explicit copies against CCG Collector's 695 report.
4. Keep every variant pool separate until its original ICE-only eligibility and card printing are verified.

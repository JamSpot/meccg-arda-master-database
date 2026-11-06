---
layout: default
title: Card inventory
---

# Gandalf Gene Arda card inventory

**Download the card-by-card inventory:** [gandalf-gene-arda-card-inventory.csv](../data/gandalf-gene-arda-card-inventory.csv)

The CSV is a spreadsheet-ready working inventory with source-row references. Expansion and rarity metadata have been checked against the full MECCG Card List v1.13 catalogue. Army of the Dead and The White Tree are METW; Peril Returned is METD; Uruk-Lieutenant and Wild Trolls are MELE. The audit also corrected Peath, Ambusher, Uruk-Lieutenant and Wild Trolls rarity metadata. These are metadata corrections only; no source quantities changed. The original extracted assignments are preserved in each affected row's notes. This improves the expansion breakdown without changing any quantity.

The v1.13 reference workbook contains 1,674 catalogue rows with card IDs across the seven official expansion codes. Its 48 additional N/A-ID entries belong to sourcebook scenario/site material from Hands of the Healer, A Long-Expected Party and The Northern Waste; they are excluded from this physical-card inventory. The presence of a seven-set code does not by itself prove a base-expansion printing: promotional printings and duplicate promo versions must be classified separately before expansion counts are finalized. See the [v1.13 set-code audit](../data/catalogue-v1-13-set-audit.csv). Dream Cards and all fan-made/custom or unreleased cards are outside the project's scope.

Official physical promotional cards are tracked separately from the seven standard expansion totals. A promo printing can share a name with a base-set card, so card name alone is not enough to assign a printing or expansion quantity. The 2024 Arda Intro Game all-rarities sample includes at least Black Arrow, Fatty Bolger, Fury of the Iron Crown and The Iron Crown as English promo entries; the printing of The Arkenstone is unspecified. The Lure of MECCG special card is not an original ICE expansion card and is excluded. See the [3 November 2026 promo-scope research](research-watch-2026-11-03.html).

## Current working totals

| Expansion | Distinct cards with numeric quantities | Explicit physical copies |
|---|---:|---:|
| The Wizards (METW) | 298 | 552 |
| The Dragons (METD) | 59 | 108 |
| Dark Minions (MEDM) | 14 | 32 |
| The Lidless Eye (MELE) | 2 | 6 |
| The Balrog (MEBA) | 1 | 1 |
| **Total with numeric quantities** | **374** | **699** |

The two named rows with blank quantities, Army of the Dead and The White Tree, are also METW. Including them gives **300 METW identities and 376 unique named card identities overall**. The source has 377 named rows because Nenseldë the Wingild appears twice; the inventory keeps both source-row references but counts Nenseldë as one distinct identity.

The published expansion subtotals (300 METW + 59 METD + 14 MEDM + 2 MELE + 1 MEBA) now align with the 376 unique named identities after the independent expansion checks. The published headline of 377 likely counts the duplicated Nenseldë row as a separate card, but the source author's intended counting method has not been confirmed.

## Remaining discrepancies and limitations

- CCG Collector's 3 June 2020 Council of Elrond post reports **695 physical copies**, while the explicit Gene rows still sum to **699**. The four-copy difference remains unresolved. The Gene workbook's static Desglose tab totals **691**, but its categories match the separate Jose-san pool (including Minion categories absent from the Gene rows), so it is treated as stale rather than as the Gene summary.
- Army of the Dead and The White Tree have blank quantity cells. Their expansions are known; their quantities are not.
- The v1.13 catalogue audit also corrected rarity metadata without changing quantities: Peath is Fixed (not Uncommon), Ambusher is Common (not Uncommon), Uruk-Lieutenant is Rare, and Wild Trolls is Common. See the [catalogue audit CSV](../data/catalogue-v1-13-audit.csv) for the source-versus-catalogue trail.
- Owned quantity and quantity-to-acquire fields are blank. They must not be treated as zero or as a statement about the user's collection.
- The independent catalogue is a card-identity/set cross-check, not an Arda quantity source. The Council of Elrond card database remains the preferred current reference for card text and errata.

## How to use the CSV

Open it in Excel, LibreOffice Calc, or another spreadsheet tool. Filter by expansion, card type, alignment, rarity, or quantity status. Keep the source quantity separate from your own owned count. Do not calculate a final shopping list until the four-copy discrepancy versus CCG Collector's 695-copy report has been resolved.

See the [reconciliation log](reconciliation-log.html) for the count audit and [sources and downloads](sources.html) for published comparison material.


## Jose-san source: Hero-compatible quantity baseline

The row-level extraction of the Jose-san ARDA.xls copy produces 322 Avatar/Hero/Neutral identities and 623 copies. Of those, 320 identities / 620 copies are non-promo expansion cards; the remaining three copies are official promotional cards (Black Arrow x2, Fatty Bolger x1). Do not count those three promo copies as base METW quantities.

See [the per-expansion CSV](../data/jose-san-hero-expansion-summary.csv) and [the promo detail CSV](../data/jose-san-promo-quantities.csv). The source's Minion and Stage rows were excluded from this Hero-only baseline.


## Seven-expansion catalogue count resolved

The metw.net base cardlists and v1.13 workbook now reconcile exactly: v1.13 contains 1,674 rows with IDs, including 17 rows marked Promotion; removing those promo rows leaves **1,657 base expansion cards**. The base counts by expansion are METW 484, METD 180, MEDM 180, MELE 417, MEBA 104, MEAS 170 and MEWH 122. See [the reconciliation CSV](../data/catalogue-expansion-reconciliation.csv).

Do not use card IDs as cross-source join keys. The v1.13 and Council of Elrond databases assign different TW numbers to some of the same cards; use normalized name, set, type, alignment and printing status.


## 6 November 2026 — current catalogue and promo reconciliation

The earlier 1,674 figure is the historical v1.13 workbook count, not the complete current printing catalogue. A current Council of Elrond database cross-check and Card Hunters HQ's seven-set checklists report 1,683 records. One of these, TW-500 Lure of MECCG, is a separate Lure event promo and is not an original ICE card, so it remains excluded.

The working original-ICE catalogue is now **1,682 card/printing records**: **1,657 base expansion cards plus 25 promo-coded printings**. This is eight more than v1.13. Eight additional ICE promo cards were identified: TW-493 Neeker-breekers, TW-494 Black Arrow, TW-495 Fatty Bolger, TW-496 The Iron Crown, TW-497 A Pack at the Door, TW-498 Swordmaster, TW-499 Dwarven Axe and TD-185 Belegennon. The 2007 Full Spoiler List separately documents standard English promos and nine special German promos.

| Expansion | Base cards | Working ICE printings |
|---|---:|---:|
| The Wizards (METW) | 484 | 499 |
| The Dragons (METD) | 180 | 185 |
| Dark Minions (MEDM) | 180 | 183 |
| The Lidless Eye (MELE) | 417 | 419 |
| The Balrog (MEBA) | 104 | 104 |
| Against the Shadow (MEAS) | 170 | 170 |
| The White Hand (MEWH) | 122 | 122 |
| **Total** | **1,657** | **1,682** |

The 1,682 working total includes eight promo-variant rows already present in v1.13 whose original printing provenance still needs scan-level checking. The audit keeps those rows provisional. TW-500 is excluded as a non-ICE event promo; it is not a Dream Card.

- [Current expansion reconciliation CSV](../data/catalogue-expansion-reconciliation.csv)
- [Full promo-printing audit CSV](../data/promo-card-inventory-2026-11-06.csv)
- [6 November research watch](research-watch-2026-11-06.html)

This does **not** alter the quantities in Gandalf Gene, Jose-san or the Arda Intro Game. It only improves the master card/printing catalogue.

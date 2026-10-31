---
layout: default
title: Card inventory
---

# Gandalf Gene Arda card inventory

**Download the card-by-card inventory:** [gandalf-gene-arda-card-inventory.csv](../data/gandalf-gene-arda-card-inventory.csv)

The CSV is a spreadsheet-ready working inventory with source-row references. Five expansion assignments have been cross-checked against an independent card catalogue: Army of the Dead and The White Tree are METW; Peril Returned is METD; Uruk-Lieutenant and Wild Trolls are MELE. The original extracted assignments are preserved in each affected row's notes. This improves the expansion breakdown without changing any quantity.

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
- Rarity remains blank in the extraction for Uruk-Lieutenant and Wild Trolls; this pass verified their expansion only.
- Owned quantity and quantity-to-acquire fields are blank. They must not be treated as zero or as a statement about the user's collection.
- The independent catalogue is a card-identity/set cross-check, not an Arda quantity source. The Council of Elrond card database remains the preferred current reference for card text and errata.

## How to use the CSV

Open it in Excel, LibreOffice Calc, or another spreadsheet tool. Filter by expansion, card type, alignment, rarity, or quantity status. Keep the source quantity separate from your own owned count. Do not calculate a final shopping list until the four-copy discrepancy versus CCG Collector's 695-copy report has been resolved.

See the [reconciliation log](reconciliation-log.html) for the count audit and [sources and downloads](sources.html) for published comparison material.

---
layout: default
title: Card inventory
---

# Gandalf Gene Arda card inventory

**Download the card-by-card inventory:** [gandalf-gene-arda-card-inventory.csv](../data/gandalf-gene-arda-card-inventory.csv)

The CSV is built from the extracted Gandalf Gene Arda spreadsheet and preserves source-row references. It is a practical, spreadsheet-ready working inventory—not yet a fully reconciled final master.

## Current extracted totals

| Expansion | Distinct cards with numeric quantities | Physical copies |
|---|---:|---:|
| The Wizards (METW) | 298 | 552 |
| The Dragons (METD) | 58 | 105 |
| Dark Minions (MEDM) | 17 | 41 |
| The Balrog (MEBA) | 1 | 1 |
| **Total with numeric quantities** | **374** | **699** |

The source contains 377 named rows. One card, Nenseldë the Wingild, appears on two rows; the inventory represents it as one identity with quantity 2 and retains both source-row references. Army of the Dead and The White Tree are also named in the source but have blank quantities. They are included in the CSV with blank quantity fields and are not counted above.

## Important limitations

- The source workbook's own Desglose summary says 695 copies, while the explicit numeric rows sum to 699. The four-copy difference is still unresolved.
- The published expansion distinct-card figures sum to 376, not the published total of 377.
- Rarity is blank in the source extraction for Uruk-Lieutenant and Wild Trolls.
- Owned quantity and quantity-to-acquire fields are left blank. They must not be treated as zero or as a statement about the user's collection.
- Expansion and rarity fields will be checked against the general MECCG card catalogue and Council of Elrond card database; those catalogues are not themselves Arda quantity lists.

## How to use the CSV

Open it in Excel, LibreOffice Calc, or another spreadsheet tool. Filter by expansion, card type, alignment, rarity, or quantity status. Keep the source quantity separate from your own owned count. Do not calculate a final shopping list until the source discrepancies have been resolved.

See the [reconciliation log](reconciliation-log.html) for the count audit and [sources and downloads](sources.html) for published comparison material.

# Source Reconciliation

## The central discrepancy

The independent [CCG Collector post of 3 June 2020](https://councilofelrond.org/forum/viewtopic.php?t=2494) reports:
- 377 distinct cards
- 695 physical cards
- expansion identities: 300 METW, 59 METD, 14 MEDM, 2 MELE and 1 MEBA (subtotal 376)

The extracted original Gandalf Gene workbook has:
- 377 named rows after excluding the title row
- 375 rows with numeric quantities
- 374 distinct names among numeric rows
- two additional named rows with blank quantities (Army of the Dead and The White Tree)
- 376 unique named identities overall
- **699 explicit physical copies**

The four-copy difference between the 699 numeric-row sum and CCG Collector's 695 report remains unresolved. The 377-versus-376 identity difference is also retained; the duplicated Nenseldë row may explain the headline, but that has not been confirmed by the author.

## Do not use the Gene Desglose tab as the 695 source

The static Desglose sheet in the supplied Gene workbook sums to **691**, not 695. Its category values exactly match the separate Jose-san ARDA.xls category table and include 34 Minion characters and 30 Minion resources that are not present in the Gene card rows. It is therefore treated as a stale copied summary, not as a valid checksum for the Gene list. An intermediate collecting-list workbook in the Library labels 695 as “Source Desglose total”; that label is incorrect. The 695 figure is CCG Collector's separate community summary, while the original workbook's Desglose tab totals 691.

## Published expansion figures

| Expansion | Published distinct cards |
|---|---:|
| METW | 300 |
| METD | 59 |
| MEDM | 14 |
| MELE | 2 |
| MEBA | 1 |
| **Expansion subtotal sum** | **376** |

The subtotals match the 376 unique named identities after the independent expansion checks. The CCG Collector headline says 377; the one-card difference is not confirmed.

## Verified working inventory

| Expansion | Distinct cards with numeric quantities | Explicit copies |
|---|---:|---:|
| METW | 298 | 552 |
| METD | 59 | 108 |
| MEDM | 14 | 32 |
| MELE | 2 | 6 |
| MEBA | 1 | 1 |
| **Working total** | **374** | **699** |

The two additional blank-quantity identities, Army of the Dead and The White Tree, are both METW. The verified working inventory corrects Peril Returned to METD and Uruk-Lieutenant/Wild Trolls to MELE, based on the independent [MECCG card catalogue](https://elvenforest.narod.ru/meccg/cards/meccg_list.html). These are metadata corrections only; all source quantities are retained.

## Separate Jose-san pool comparison

The local ARDA.xls is a high-confidence candidate for BGG's Jose-san Arda example XLS. Its full all-alignment pool has 370 names / 691 copies. Filtering out Minion alignment leaves 322 Hero/Neutral/Avatar names / 623 copies. The [comparison CSV](../data/jose-san-hero-arda-pool-comparison.csv) records those rows and Gandalf Gene quantities where names match. It is a separate pool and must not be merged into the canonical Gene inventory.

## Still unresolved

- 699 explicit Gene row copies versus CCG Collector's 695 community total: **+4**.
- 377 published headline identities versus 376 unique names in the working inventory.
- The exact four source rows responsible for the copy difference.
- Remaining card metadata and rarity fields.

## Reconciliation plan

1. Compare every quantity-bearing Gene row against the original workbook and independent transcription to locate the four-copy difference.
2. Confirm the local Jose-san workbook against the BGG attachment if the original binary can be retrieved.
3. Verify remaining expansion and rarity fields against the Council of Elrond card database and catalogue.
4. Produce an audited acquisition table with provenance for every quantity.

Until the copy-count audit is complete, the inventory is improved but still not a final shopping list.


## Promotional-printing scope discovered 3 November 2026

The current Card Hunters HQ The Wizards checklist reports 500 entries, but it is a mirror of the Council of Elrond restoration archive and includes promo rows marked P. It is not an independent count of the 484-card base The Wizards checklist. The MeCCG collecting archive separately lists English, German and other promo/misprint material. The v1.13 total of 492 may include some promotional entries; the exact eight-row difference from the 484 base checklist is still unresolved.

The 2024 Arda Intro Game all-rarities pool includes at least four English promotional cards: Black Arrow, Fatty Bolger, Fury of the Iron Crown and The Iron Crown. The Arkenstone printing is not specified. These are not additional base METW copies; retain them in a separate promo-printing category until the exact physical printing is established. The special Lure of MECCG card is excluded from the original ICE expansion inventory.

This does not change the Gandalf Gene quantity baseline of 699 or the 695 community report. It changes the catalogue method: card identity, expansion code, physical printing and promo status must be separate fields.

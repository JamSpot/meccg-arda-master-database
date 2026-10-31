# Gandalf Gene reconciliation log

**Status: partially reconciled — expansion identities improved; physical-copy total still open.** This log separates primary workbook rows, independent community summaries and stale copied workbook metadata.

## Evidence set

1. Original source: Council of Elrond, “Gandalf Gene's Arda Deck” (26 December 2016), including GandalfGeneArda.xls.
2. Workbook extraction: Gandalf_Gene_Arda_Collecting_List_v2.xlsx, based on the original workbook's MECCG Cards sheet.
3. Independent published summary: CCG Collector's Council of Elrond post dated 3 June 2020, reporting 377 distinct cards / 695 physical copies.
4. Independent transcription: CardGameGeek transcription, which warns that two hazards are missing.
5. Independent card catalogue: [MECCG cards list](https://elvenforest.narod.ru/meccg/cards/meccg_list.html), used to verify printed-set codes.
6. Separate Jose-san pool: local ARDA.xls, a high-confidence candidate for BGG's Jose-san Arda deck example XLS.

## Count bridge — Gandalf Gene

| Measure | Result | Interpretation |
|---|---:|---|
| Named rows after excluding title row | 377 | Includes duplicate Nenseldë and two blank-quantity rows |
| Rows with numeric quantity | 375 | Source-row count, not distinct identities |
| Distinct names among numeric rows | 374 | Nenseldë the Wingild appears twice |
| Additional named rows with blank quantities | 2 | Army of the Dead and The White Tree |
| Unique named identities overall | 376 | 374 numeric identities plus two blank-quantity identities |
| Explicit quantity sum | 699 | Sum of numeric rows |
| CCG Collector community summary | 695 | Independent 3 June 2020 report |
| Difference: explicit sum minus community summary | +4 | Still unresolved |
| Static workbook Desglose total | 691 | Stale copied table; not a Gene checksum |
| Published expansion subtotal sum | 376 | 300 + 59 + 14 + 2 + 1 |

The static Desglose table's category values match the separate Jose-san workbook and include Minion categories not present in the Gene rows. The 695 figure comes from CCG Collector's forum post, not from the Gene workbook's Desglose tab.

## Expansion corrections from the independent catalogue

| Card | Quantity | Original extraction assignment | Cross-checked set | Evidence |
|---|---:|---|---|---|
| Army of the Dead | blank | blank | METW / TW | Catalogue lists it under The Wizards |
| The White Tree | blank | blank | METW / TW | Catalogue lists it under The Wizards |
| Peril Returned | 3 | MEDM | METD / TD | Catalogue lists it under The Dragons |
| Uruk-Lieutenant | 3 | MEDM | MELE / LE | Catalogue lists it under The Lidless Eye |
| Wild Trolls | 3 | MEDM | MELE / LE | Catalogue lists it under The Lidless Eye |

The quantity fields were not changed. The three numeric corrections move 3 copies of Peril Returned from MEDM to METD and 3 copies each of Uruk-Lieutenant and Wild Trolls from MEDM to MELE. This yields the current expansion copy totals: METW 552, METD 108, MEDM 32, MELE 6 and MEBA 1 — still 699 overall.

## Current working expansion counts

| Expansion | Distinct identities with numeric quantities | Explicit copies |
|---|---:|---:|
| METW | 298 | 552 |
| METD | 59 | 108 |
| MEDM | 14 | 32 |
| MELE | 2 | 6 |
| MEBA | 1 | 1 |
| **Total numeric-quantity inventory** | **374** | **699** |

The two blank-quantity METW rows bring the unique named identity count to 376. The published expansion subtotals match these 376 identities. The +4 copy discrepancy versus CCG Collector's 695 remains separate and unresolved.

## Jose-san pool cross-check

The local Jose-san candidate workbook has 370 unique names / 691 copies across all alignments. Excluding 48 Minion-alignment rows / 68 copies leaves 322 Hero/Neutral/Avatar names / 623 copies. Name comparison with Gene yields 242 shared names, 80 Jose-only names and 134 Gene-only names; 29 shared names have different quantities. The [comparison CSV](../data/jose-san-hero-arda-pool-comparison.csv) records the 322 non-Minion rows. Do not merge the lists.

## Next forensic steps

1. Compare each Gene quantity-bearing row against the original sheet and the CCG Collector summary to identify the exact four-copy difference.
2. Confirm the local Jose-san workbook against the BGG attachment if possible.
3. Verify all remaining expansion and rarity assignments against the Council of Elrond database and catalogue.
4. Only after this audit, publish a final acquisition requirement.

**Do not use the 699-copy inventory as a definitive shopping list until the four-copy difference versus the independent 695 report is resolved.**

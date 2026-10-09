# Gandalf Gene reconciliation log

**Status: open — source arithmetic is now itemised.** This log records what the available spreadsheet extraction supports and separates facts from hypotheses.

## Evidence set

1. Original source: Council of Elrond, “Gandalf Gene's Arda Deck” (26 December 2016), including GandalfGeneArda.xls.
2. Workbook extraction: `Gandalf_Gene_Arda_Collecting_List_v2.xlsx`, based on the original workbook's `MECCG Cards` and `Desglose` sheets.
3. Independent published summary: 377 distinct cards / 695 physical cards.
4. Independent transcription: CardGameGeek transcription, which itself warns that two hazards are missing.

## Count bridge

| Measure | Result | Interpretation |
|---|---:|---|
| Named card rows in extracted source sheet | 377 | Includes rows without a numeric quantity |
| Rows with numeric quantity | 375 | Current provisional acquisition rows |
| Distinct names among numeric rows | 374 | Nenseldë the Wingild appears twice |
| Sum of numeric quantities | 699 | Current extracted physical-copy count |
| Workbook Desglose total | 695 | Source's own summary |
| Difference: extracted sum minus Desglose | +4 | Unresolved |
| Published distinct-card count | 377 | Does not match the 374 distinct numeric rows |
| Published expansion subtotal sum | 376 | 300 + 59 + 14 + 2 + 1; one short of published 377 |

## Specific rows requiring treatment

| Card / issue | Source observation | Current handling |
|---|---|---|
| Army of the Dead | Named row; quantity blank | Not counted in the 699 total; do not assume quantity |
| The White Tree | Named row; quantity blank | Not counted in the 699 total; do not assume quantity |
| Nenseldë the Wingild | Two separate source rows, each quantity 1 | Both source rows retained for audit; distinct-name count deduplicates the name |
| Uruk-Lieutenant | Quantity 3; rarity blank in extracted source | Quantity retained; rarity requires verification |
| Wild Trolls | Quantity 3; rarity blank in extracted source | Quantity retained; rarity requires verification |

## What the arithmetic does and does not tell us

The two blank-quantity rows explain why the sheet has 377 named rows but only 375 quantity-bearing rows. They do **not** by themselves explain the +4 copy difference, because they contribute no numeric quantities to the current sum.

The duplicate Nenseldë row explains why 375 quantity-bearing rows yield 374 distinct names. It does **not** explain the copy-count difference: both rows are quantity 1 and the current sum includes both.

Therefore, the +4 difference must be investigated in the quantity-bearing rows or in how the `Desglose` summary was produced. There is not yet enough evidence to name the four excess copies.

## Next forensic steps

1. Recalculate `Desglose` by category from the raw rows and compare each category, not just the grand total.
2. Check every quantity-bearing row against the original sheet and the independent transcription.
3. Verify expansion and rarity using the MECCG Card List v1.13 and Council of Elrond card database.
4. Mark each mismatch as a transcription issue, identity/printing issue, source-summary issue or unresolved.
5. Only after this audit, publish the final canonical quantity and acquisition requirement.

**Do not use the provisional 699-copy list as a definitive shopping list yet.**

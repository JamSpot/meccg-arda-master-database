# Research Progress

## Current stage
Source extraction exists; card-level reconciliation is underway. The next task is auditing raw rows and category subtotals, not collecting more general Arda references.

## Confirmed from the extracted Gandalf Gene workbook
- 377 named card rows after excluding title/header structure.
- 375 rows have numeric quantities.
- 374 distinct names among numeric rows because Nenseldë the Wingild appears twice.
- Numeric quantity sum: 699.
- The workbook Desglose summary states 695.
- Army of the Dead and The White Tree have blank quantity fields.
- Uruk-Lieutenant and Wild Trolls have quantity 3 but blank rarity in the extraction.
- Published expansion distinct counts 300 + 59 + 14 + 2 + 1 sum to 376, not 377.

## Completed in this iteration
- Added [a reconciliation log](reconciliation-log.html) with the count bridge and named anomalies.
- Added a machine-readable [expansion checksum CSV](/data/expansion-checksums.csv).
- Added [the inventory data method](card-inventory-method.html) for an auditable collection tracker.

## Next concrete work
1. Recompute the workbook's Desglose totals by category from raw rows.
2. Match all source rows to the independent transcription.
3. Verify expansion, rarity and card identity against reference databases.
4. Resolve the four-copy discrepancy.
5. Publish the full audited card inventory and then the acquisition list.

## Status labels
- Verified — identity and source fields checked.
- Source discrepancy — source summaries disagree.
- Needs reconciliation — row-level investigation remains.
- Variant — belongs to another Arda list/ruleset.
- Excluded — outside canonical project scope.

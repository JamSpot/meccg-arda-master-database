# Card Inventory: Data Method

## Purpose

Create an auditable card-level inventory for the canonical Gandalf Gene Hero Arda list. The inventory must support both source reconciliation and a later physical collection/acquisition tracker.

## Required fields

| Field | Meaning |
|---|---|
| Card | Card name as printed / named in source |
| Expansion code | Source expansion code, e.g. METW |
| Card type | Type recorded in the source |
| Alignment | Alignment recorded in the source |
| Rarity | Rarity recorded in the source; blanks stay blank until checked |
| Source quantity | Quantity from the Gandalf Gene workbook |
| Have | User's owned physical copies; starts at 0 until supplied |
| Need to buy | Calculated as max(source quantity − have, 0), but only after quantity is approved |
| Source row(s) | Original workbook row reference(s) |
| Identity status | Verified / ambiguous / needs check |
| Quantity status | Matches source / discrepancy / blank |
| Provenance | Exact source or independent verification |
| Notes | Duplicate, alternate printing, errata or reconciliation note |

## Rules

- Do not fill missing quantities by inference.
- Do not replace the source's rarity or expansion silently with a modern database value.
- Preserve raw source fields separately from normalized/verified fields.
- Keep canonical Gene membership separate from later Arda variants.
- The physical-card master is limited to the seven original ICE card expansions: METW, METD, MEDM, MELE, MEAS, MEWH and MEBA. Exclude Dream Cards, fan-made/custom cards, unreleased material, sourcebook map/site entries without official card IDs, and proxies.
- The v1.13 workbook has 48 additional N/A-ID entries from Hands of the Healer, A Long-Expected Party and The Northern Waste sourcebooks. They are scenario/map references, not standard printed MECCG card records; see the [v1.13 set-code audit](../data/catalogue-v1-13-set-audit.csv).
- A card can have verified identity but unresolved deck quantity.
- Do not treat the provisional acquisition list as final until the 699 explicit Gene copies versus CCG Collector's 695-copy community summary is reconciled. The Gene Desglose tab's 691 total is stale and is not the source of 695.
- Never mark a card as owned without user confirmation.

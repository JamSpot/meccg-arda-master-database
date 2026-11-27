---
layout: default
title: Research Watch — 27 November 2026
---

# Research Watch — 27 November 2026

## No new complete Hero Arda pool; an older draft quantity needs to be quarantined

This pass did not verify a new published original-ICE Hero Arda decklist, spreadsheet or complete card-pool file. It did uncover a provenance issue in an older project workbook that could otherwise be mistaken for evidence for one of the two blank Gandalf Gene quantities.

### 1. Earlier 17-row workbook is not a quantity authority

The Library contains an early file, **Middle-earth_CCG_Arda_Master_Database_v1.xlsx**, created 24 July 2026. Its populated `Master Database` sheet contains only 17 card rows; the other seven named sheets are empty. It lists:

- **Army of the Dead — The Wizards — Resource — Qty 1**
- Source field: “Gandalf Gene reconstruction”
- Verified field: “Yes”

However, it contains no original source-row reference, quotation or other evidence for that quantity, and it does not include The White Tree. The later, row-level **Gandalf_Gene_Arda_Collecting_List_v2.xlsx** explicitly records Army of the Dead and The White Tree as blank in the original Gandalf Gene quantity column.

**Decision for the master inventory:** quarantine the old workbook's Army of the Dead quantity of 1 as an unsupported draft value. It is not independent evidence and must not replace the blank source quantity, be added to the 699-copy total, or be used in an acquisition list. The official card catalogue confirms both Army of the Dead (TW-193) and The White Tree (TW-348) are Hero Resources from The Wizards; it does not provide Arda quantities.

### 2. Current card-catalogue cross-check

The Council of Elrond Rules Committee's downloadable `cards.json` was successfully parsed in this pass after an earlier retrieval attempt had failed. It contains 1,683 set-coded records across the seven official expansion codes. Excluding TW-500, **Lure of MECCG** (a separate event promo, not an original ICE card), leaves the already documented 1,682-record working ICE catalogue:

| Expansion | Working ICE card/printing records |
|---|---:|
| The Wizards (TW) | 499 |
| The Dragons (TD) | 185 |
| Dark Minions (DM) | 183 |
| The Lidless Eye (LE) | 419 |
| The Balrog (BA) | 104 |
| Against the Shadow (AS) | 170 |
| The White Hand (WH) | 122 |
| **Total** | **1,682** |

This confirms the existing 6 November catalogue audit; it is not a new Arda pool and these counts are catalogue records, not deck quantities. The database includes updated errata/text and some promo-printing distinctions, so it remains a metadata and current-text cross-check rather than a literal original-print transcription or Arda quantity authority.

Source: [Council of Elrond official cards database](https://github.com/council-of-elrond-meccg/meccg-cards-database). Its README requests acknowledgement and notification for third-party projects that incorporate its data. No card text or bulk dataset was copied into this project in this pass.

### 3. Decklist and download sweep

The current [MeCCG Decks library](https://meccg.com/decks/) exposes many conventional constructed Hero, Minion, Fallen-wizard and Balrog decklists, with card-by-card starting pools, characters, resources, hazards and sideboards on individual entries. These are useful secondary strategy references, but they are not Arda's shared-pile card pools. No new Arda XLS/XLSX/CSV or complete `.meccg` deck file was verified.

The highest-value outstanding published-list leads remain Thorondor's 2015 83.5 KiB no-rares XLS (attachment retrieval still blocked), the original BGG Jose-san XLS (local candidate parsed; binary hash match outstanding), and a complete BanalityBob sheet export.

### 4. Gandalf Gene quantities remain unchanged

The canonical working list remains **699 explicit copies**:

| Expansion | Copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

The independent CCG Collector report says 695, leaving four copies unresolved. Army of the Dead and The White Tree remain blank in the source extraction. The 17-row draft's unsupported Army of the Dead quantity does not resolve either blank.

### Next steps

1. Keep the 17-row workbook out of the canonical quantity calculations.
2. Continue pursuing Thorondor's XLS and a verifiable Jose-san attachment.
3. Continue the row-by-row four-copy reconciliation against the original Gene workbook and CCG Collector's 695-copy report.
4. Do not publish a final shopping list until the discrepancy and blank quantities are resolved.

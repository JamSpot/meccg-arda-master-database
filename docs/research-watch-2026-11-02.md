---
layout: default
title: Source watch — 2 November 2026
---

# Source watch — 2 November 2026

## Summary

This pass found a stronger current card-reference layer, several direct catalogue downloads, and an independent set-by-set card-list collection. **No new standard Arda deck spreadsheet was verified, and no card quantities have been changed.**

The project scope is now explicit: only original, officially published ICE Middle-earth CCG cards are eligible. No Dream Cards, fan-made/custom cards, unreleased cards, proxies or Minion Arda build recommendations are included.

## 1. Council of Elrond Rules Committee — current card database

The [Council of Elrond official cards database repository](https://github.com/council-of-elrond-meccg/meccg-cards-database) contains:

- [cards.json](https://raw.githubusercontent.com/council-of-elrond-meccg/meccg-cards-database/master/cards.json) — 4,163,611 bytes.
- [changes-guide.xlsx](https://github.com/council-of-elrond-meccg/meccg-cards-database/raw/master/changes-guide.xlsx) — 22,147 bytes.

The repository's latest commit is dated **19 May 2026** and says **“CRF 22 applied.”** Its README says approximately 300 card texts have been updated, including standardized typography, CRF errata and clarifications, current Rules Book card-specific rules, Challenge Deck text, and unified text for cards with multiple versions across The Wizards/The Dragons and The Lidless Eye.

**Use:** preferred current reference for rules text, errata and current card identity checks.

**Limit:** this is not an Arda decklist or quantity source. It is not a literal transcription of every original physical printing: updated text and unified multi-version entries mean it must not silently overwrite original printed wording or expansion assignments. The database's README also asks third-party community projects to acknowledge it and notify the Council of Elrond when using it.

The 4.16 MB JSON could not be fully extracted through the current GitHub connector in this pass. Its repository metadata and README were verified; full automated row matching remains outstanding.

## 2. MeCCG.com — direct catalogue and deck downloads

The current [Lists and downloads page](https://meccg.com/cards/lists-and-downloads/) links several directly downloadable references:

| File | Format | Appropriate use |
|---|---|---|
| [MeCCG List of Cards](https://meccg.es/meta/cards/list/MeCCG%20List%20of%20Cards.xls) | XLS | Candidate full card catalogue; version/date not stated on the landing page; contents still need parsing. |
| [Characters list with filters](https://meccg.es/meta/cards/list/meccg-characters.xlsx) | XLSX | Character identity and metadata cross-check. |
| [Challenge Decks list](https://meccg.es/meta/cards/list/Challenge%20Decks.zip) | ZIP | Official Challenge Deck card lists; not an Arda deck. |
| [Full Spoiler List](https://meccg.es/meta/cards/MeCCG%20Full%20Spoiler%20List.pdf) | PDF | Historical expansion-organized reference; front matter says updated February 2007. |
| [Fixed Sets](https://meccg.es/meta/cards/list/Fixed%20Sets.pdf) | PDF | Fixed product contents, useful for sealed-product collation, not Arda quantities. |
| [Challenge Decks player aid](https://meccg.es/meta/cards/list/MECCG-CD-playeraid_v1.0.pdf) | PDF | Card-by-card reference for the ten Challenge Decks. |

The downloads page is an index of catalogue and Challenge Deck resources, not a newly published Arda quantity list. The current [MeCCG Decks page](https://meccg.com/decks/) did not expose deck records in this pass. The older [MeCCG deck archive](https://meccg.es/mazos/) does expose many conventional tournament/constructed decklists, but no Arda entry was found on its index; it is not a new Arda pool source.

## 3. metw.net — independent expansion card-list PDFs

[metw.net's cardlists section](https://metw.net/) links expansion PDFs with card names, types/categories and rarity/distribution codes. The PDFs state these set totals:

| Expansion | Listed card count |
|---|---:|
| The Wizards (METW) | 484 |
| The Dragons (METD) | 180 |
| Dark Minions (MEDM) | 180 |
| The Lidless Eye (MELE) | 417 |
| The Balrog (MEBA) | 104 |
| The White Hand (MEWH) | 122 |
| Against the Shadow (MEAS) | 170 |

The Wizards and The Dragons PDFs include booster/starter distribution explanations; the other PDFs also describe product collation. The Wizards PDF includes an errata list dated 28 July 2000.

**Use:** independent historical cross-check for set membership, card categories and printed rarity/distribution. The explicit set totals are useful for checking catalogue coverage.

**Limit:** these are not Arda decklists and do not give Gandalf Gene card quantities. They are historical lists, so current card text/rulings should be checked against the Council of Elrond database. Do not use their old rules summaries as a replacement for current rules.

Direct PDFs:
- [The Wizards — 484 cards](https://metw.net/documents/Middle-Earth-The-Wizards-Cardlist.pdf)
- [The Dragons — 180 cards](https://metw.net/documents/Middle-Earth-The-Dragons-Cardlist.pdf)
- [Dark Minions — 180 cards](https://metw.net/documents/Middle-Earth-Dark-Minions-Cardlist.pdf)
- [The Lidless Eye — 417 cards](https://metw.net/documents/Middle-Earth-The-Lidless-Eye-Cardlist.pdf)
- [The Balrog — 104 cards](https://metw.net/documents/Middle-Earth-The-Balrog-Cardlist.pdf)
- [The White Hand — 122 cards](https://metw.net/documents/Middle-Earth-The-White-Hand-Cardlist.pdf)
- [Against the Shadow — 170 cards](https://metw.net/documents/Middle-Earth-Against-The-Shadow-Cardlist.pdf)

## 4. Corrected v1.13 physical-card scope audit

I re-opened the local 1.58 MB MECCG Card List v1.13 workbook and grouped its rows by set code, checking whether each entry has a real card ID.

| Set code | Set/source | Entries with card IDs | Physical-card master |
|---|---|---:|---|
| METW | The Wizards | 492 | Include |
| METD | The Dragons | 184 | Include |
| MEDM | Dark Minions | 183 | Include |
| MELE | The Lidless Eye | 419 | Include |
| MEAS | Against the Shadow | 170 | Include |
| MEWH | The White Hand | 122 | Include |
| MEBA | The Balrog | 104 | Include |
| MEHH | Hands of the Healer sourcebook | 0 of 16 entries | Exclude |
| MELP | A Long-Expected Party sourcebook | 0 of 16 entries | Exclude |
| MENW | The Northern Waste sourcebook | 0 of 16 entries | Exclude |
| **Total** | **All v1.13 named entries** | **1,674 eligible card IDs** | **48 sourcebook entries excluded** |

The workbook has 1,722 named entries across these codes, but the 48 additional sourcebook entries all have N/A rather than a card ID. They are 14 site entries plus one item and one event from Hands of the Healer, 16 A Long-Expected Party site-map entries, and 16 Northern Waste site entries. The sourcebooks confirm the distinction: [The Northern Waste](https://files.spawningpool.net/docs/Vault2.0.-.TTRPG-Gamebooks/Middle-Earth%E2%84%A2%20%28MERP%29%20%5Bmulti%5D/Middle-Earth%20Role%20Playing%20%28MERP%29%20%5Bmulti%5D/2nd%20Edition/Realms/ICE2025%20The%20Northern%20Wastes%20%5BOCR%5D.pdf) explicitly says its new location entries are not official MECCG cards as published; [A Long-Expected Party](https://tolkiengateway.net/wiki/A_Long-Expected_Party:_MECCG_Sites_and_Scenarios) provides 16 new site panels on a map; and [Hands of the Healer](https://www.dragonstrove.com/products/hands-of-the-healer) includes scenario sites for casual play. These are sourcebook scenario/map aids, not standard printed card records, so they are now excluded from the physical-card master.

The eligible original ICE expansion catalogue counts therefore total **1,674**: METW 492 + METD 184 + MEDM 183 + MELE 419 + MEAS 170 + MEWH 122 + MEBA 104. This is a catalogue count, not the number of cards in the Gandalf Gene Arda deck.

I added a machine-readable [v1.13 set-code audit CSV](../data/catalogue-v1-13-set-audit.csv) so this exclusion is explicit and repeatable.

### Independent catalogue discrepancy

The seven metw.net PDFs state lower counts for four expansions: METW 484 (v1.13 has 492), METD 180 (184), MEDM 180 (183), and MELE 417 (419). They match v1.13 for MEAS 170, MEWH 122 and MEBA 104. The difference is **17 entries** across the first four sets. The exact missing/different card names have not yet been reconciled, so the PDF totals are retained as a historical secondary check and do not override the card-ID workbook.

CollecCards' separate set-summary estimates are METW 493, METD 184, MEDM 184, MELE 420, MEAS 172, MEWH 122 and MEBA 175. Its Balrog total includes grey-bordered reprints from earlier expansions, so that number is not comparable to the 104 unique Balrog expansion card IDs. These estimates are useful as another warning that catalogue counts depend on whether promos, reprints and product contents are included.

## 5. CollecCards — searchable card catalogue

[CollecCards' English Middle Earth list](https://www.colleccards.com/ListeMEccgAng.en.htm) exposes a large searchable table with set name, set code, card name, rarity, rarity detail, type and a note field. It distinguishes some Hero/Minion versions and includes Challenge Deck entries.

**Use:** an additional independent card-name, set-code, rarity and type cross-check.

**Limit:** it is a collector/trading-site catalogue, not an Arda source. Repeated rows can represent alignment-specific versions or Challenge Deck printings; they must not be interpreted as Arda copy quantities or blindly summed.

## 6. Quantity baseline — unchanged

The canonical comparison remains the original Gandalf Gene Hero Arda workbook:

| Expansion | Explicit copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

The source has two named METW rows with blank quantities (Army of the Dead and The White Tree). CCG Collector's independent 3 June 2020 community summary says 695, leaving a four-copy difference unresolved. The Gene workbook's static Desglose tab totals 691 and remains classified as stale. No new catalogue or cardlist changes these quantities.

Jose-san's separate workbook remains a comparison build: its Hero/Neutral/Avatar subset has 322 names and 623 copies after excluding Minion-alignment rows. It is not merged into Gandalf Gene.

### Side-by-side Arda list quantities

| Expansion | Gandalf Gene Hero Arda | Jose-san Hero-compatible subset |
|---|---:|---:|
| The Wizards (METW) | 552 | 410 |
| The Dragons (METD) | 108 | 126 |
| Dark Minions (MEDM) | 32 | 48 |
| The Lidless Eye (MELE) | 6 | 12 |
| The Balrog (MEBA) | 1 | 3 |
| Against the Shadow (MEAS) | — | 18 |
| The White Hand (MEWH) | — | 6 |
| **Total** | **699** | **623** |

These are separate lists, not a combined pool. Jose-san's full workbook has 370 identities and 691 copies; 48 Minion-alignment identities (68 copies) are excluded from the Hero-compatible comparison above. The remaining 322 Hero/Neutral/Avatar identities total 623 copies.

The identity comparison has 242 names in common, 80 found only in Jose-san, and 134 found only in Gandalf Gene. Twenty-nine shared names have different quantities. These differences need card-by-card reconciliation before any merge.

## Next work

1. Obtain and parse the MeCCG List of Cards XLS and compare its names, set codes, types and rarities with v1.13.
2. Retrieve and parse Thorondor's 83.5 KiB Arda Sample Deck_no rares XLS.
3. Obtain a row-level export of BanalityBob's Arda spreadsheet, then verify every entry against the official ICE card catalogue.
4. Reconcile the four-copy difference between Gandalf Gene's 699 explicit rows and CCG Collector's 695-copy summary.

No user decision is needed in this pass. The canonical Arda quantities remain unchanged, and the project excludes Dream Cards and all non-physical/custom material.

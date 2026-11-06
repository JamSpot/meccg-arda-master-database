---
layout: default
title: Research watch — 6 November 2026
---

# Research watch — 6 November 2026

## Summary

A new cross-check against the current Council of Elrond card database and Card Hunters HQ has found **nine card IDs beyond the 2010 v1.13 workbook's seven-set totals**. They are not nine new Arda deck entries: they are promotional-printing catalogue records.

The new records separate into:

- **Eight official ICE promo cards** omitted from the v1.13 count: four English promos and four German promos.
- **One non-ICE Lure of MECCG event promo** (TW-500), which is a real printed event card but is excluded from the official ICE master.

This gives a working current catalogue of **1,682 eligible ICE card/printing records**: 1,657 base expansion cards plus 25 promo-coded printings. Eight pre-existing promo variants still need scan/provenance review before this can be called a fully definitive printing audit.

**No quantities in Gandalf Gene, Jose-san or the Arda Intro Game have been changed.** This is a card-catalogue correction, not an Arda deck-quantity change.

## 1. New cross-check sources

### Council of Elrond card database

The current `cards.json` is the card-text and card-ID reference used by the Council of Elrond database. It includes the additional IDs TW-493 through TW-500 and TD-185.

- [Raw cards.json](https://raw.githubusercontent.com/council-of-elrond-meccg/meccg-cards-database/master/cards.json)
- [Council of Elrond database repository](https://github.com/council-of-elrond-meccg/meccg-cards-database)

The database is authoritative for current community-standard card text and errata, but its promo records still need to be classified by original ICE versus later event provenance.

### Card Hunters HQ — current seven-set checklist

Card Hunters HQ reports 1,683 entries across seven MECCG sets, updated October 2026. Its source register credits the Council of Elrond card database. It is an independent collector checklist, not an Arda decklist or a quantity source.

- [Middle-earth CCG set overview](https://cardhuntershq.com/browse/meccg)
- [The Wizards checklist](https://cardhuntershq.com/browse/meccg/TW/checklist)
- [The Dragons checklist](https://cardhuntershq.com/browse/meccg/TD/checklist)
- [Dark Minions checklist](https://cardhuntershq.com/browse/meccg/DM/checklist)
- [The Lidless Eye checklist](https://cardhuntershq.com/browse/meccg/LE/checklist)
- [Against the Shadow checklist](https://cardhuntershq.com/browse/meccg/AS/checklist)
- [The White Hand checklist](https://cardhuntershq.com/browse/meccg/WH/checklist)
- [The Balrog checklist](https://cardhuntershq.com/browse/meccg/BA/checklist)

### Full Spoiler List — February 2007 update

The 186-page downloadable PDF contains all seven expansion lists, a Standard Promo Cards section (pages 184–185), and a Special German Promo Cards section (page 186). It explicitly lists the nine German promo cards and is a valuable independent provenance check.

[Download the 186-page MECCG Full Spoiler List PDF](https://meccg.es/meta/cards/MeCCG%20Full%20Spoiler%20List.pdf)

### MeCCG collecting archive and Lure event rules

The [MeCCG collecting archive](https://meccg.com/collecting/) separately lists English, German, Dutch, French and Japanese promos/misprints. The [Lure of Middle-earth event rules](https://lureofmiddleearth.com/general-rules-middle-earth-ccg/) distinguish the nine German promo cards from the separate Lure of MECCG event promo.

## 2. Expansion reconciliation

| Expansion | Base cards | v1.13 IDs | Current checklist IDs | Current P rows | Excluded non-ICE promo | Working ICE printings |
|---|---:|---:|---:|---:|---:|---:|
| The Wizards (METW) | 484 | 492 | 500 | 16 | 1 | **499** |
| The Dragons (METD) | 180 | 184 | 185 | 5 | 0 | **185** |
| Dark Minions (MEDM) | 180 | 183 | 183 | 3 | 0 | **183** |
| The Lidless Eye (MELE) | 417 | 419 | 419 | 2 | 0 | **419** |
| The Balrog (MEBA) | 104 | 104 | 104 | 0 | 0 | **104** |
| Against the Shadow (MEAS) | 170 | 170 | 170 | 0 | 0 | **170** |
| The White Hand (MEWH) | 122 | 122 | 122 | 0 | 0 | **122** |
| **Total** | **1,657** | **1,674** | **1,683** | **26** | **1** | **1,682** |

The v1.13 workbook's 1,674 count remains a valid historical count of its own rows. It is no longer a complete current printing catalogue. The current CoE/Card Hunters checklist has 26 P-coded rows; one is the non-ICE Lure event card, leaving 25 working ICE promo printings. The working total is eight above v1.13.

## 3. Eight additional official promo cards

The IDs not present in the v1.13 set totals are:

| Card ID | Card | Promo provenance |
|---|---|---|
| TW-493 | Neeker-breekers | Standard English promo |
| TW-494 | Black Arrow | Standard English promo |
| TW-495 | Fatty Bolger | Standard English promo |
| TW-496 | The Iron Crown | Standard English promo |
| TW-497 | A Pack at the Door | Special German promo |
| TW-498 | Swordmaster | Special German promo |
| TW-499 | Dwarven Axe | Special German promo |
| TD-185 | Belegennon | Special German promo |

The 2007 Full Spoiler List explicitly records the standard and German promo sections. These are physical promo cards, not Dream Cards.

### Excluded event promo

TW-500, **Lure of MECCG**, is listed in the current CoE/Card Hunters catalogue and is a real event promo. The Lure event rules call it the official Lure promo, but it is not an original ICE card. It remains excluded from the official ICE master. It is not a Dream Card; it is excluded because it is outside the original ICE publication scope.

## 4. Printing audit and remaining caution

The full P-row inventory is in [promo-card-inventory-2026-11-06.csv](../data/promo-card-inventory-2026-11-06.csv). It separates:

- the eight newly identified ICE promo records;
- the nine German promo cards;
- the standard promo records already present in v1.13;
- promo-variant rows already present in v1.13 whose exact physical printing/provenance still needs scan-level checking;
- TW-500, the non-ICE event promo, excluded from the master.

The working count of 1,682 assumes the eight promo-variant rows already counted in v1.13 remain eligible physical ICE printings. They are retained provisionally, not silently treated as newly verified.

## 5. Arda deck quantities and downloadable decklists

No new Arda decklist or spreadsheet with card quantities was verified in this pass. The Full Spoiler List is a card catalogue PDF, not a decklist. Card Hunters HQ is a web checklist, not an exportable Arda quantity spreadsheet.

The established Arda quantity sources remain separate:

- Gandalf Gene: 699 explicit copies, with the 695 external-report discrepancy unresolved.
- Jose-san: 623 Hero-compatible copies including promos; 620 base-expansion copies.
- Arda Intro Game: 554 no-rares physical components and 694 all-rarities physical components, with unresolved printing assignments retained separately.

No Dream Cards, proxies, or Minion Arda recommendations have been introduced.

## 6. Next work

1. Compare the eight pre-existing promo-variant rows against original card scans and the language-specific collecting archive.
2. Recheck the four-copy Gandalf Gene discrepancy against the original workbook rows.
3. Continue extracting Thorondor's no-rares XLS and any complete BanalityBob export.
4. Keep promo printings separate from base expansion card counts and from Arda deck quantities.


## 7. New community leads checked on 6 November 2026

### BoardGameGeek discussion leads

The current Middle-earth BGG page surfaces two recent Variant discussions by proxegentyc:

- **Turning MECCG into a Modular Solo Board Game – ARDA, Variants & Card Lists. Is it possible?** — shown as 23 days old.
- **Looking for card lists to build ARDA decks** — shown as 21 days old.

These are potential leads to further lists, but the individual BGG thread pages were not accessible to the research browser (403). No attachment, spreadsheet, card names or quantities could be verified from the indexed page. They are therefore recorded as leads only and have not been added to the master pool.

[Open the Middle-earth BGG page and its current hot threads](https://boardgamegeek.com/boardgame/1915)

### Gen Con 2026 Arda event

The Gen Con listing for **Middle-Earth CCG: “Arda” Format** describes a four-hour shared-deck event for 4–18 players. It says that almost all cards for 2026 would be official versions rather than Virtuals. The listing does not publish the shared-pile inventory, card quantities or a downloadable deck file.

[Gen Con 2026 event listing](https://www.gencon.com/events/303679)

This is a useful contact lead for a real-world physical Arda pool, not a new quantity source. The listed game masters are Joe Bisz and Kenneth Hardcastle.

### Current deck archive check

The current MeCCG deck database contains many constructed tournament decks, but this pass did not verify a new Arda-labelled deck or shared-pool export. The database is still useful for conventional constructed-deck research; those lists must not be merged into the Arda shared pool.

[MeCCG deck database](https://meccg.com/decks/)

**Result:** no new Arda card quantities, XLS/XLSX decklist or `.dek` file was verified in this pass. The catalogue/promo reconciliation above remains unchanged.

---
layout: default
title: Research watch — 8 November 2026
---

# Research watch — 8 November 2026

## Summary

This pass found a useful new group of downloadable reference files for card identity, fixed-pack composition and the ten official Challenge Decks. It did **not** find a new independently verified Arda shared-pool list or a new Arda quantity spreadsheet.

The new files are valuable for checking card names, set codes and deck-list extraction, but they are ordinary MECCG product/deck references. They must not be merged into Gandalf Gene, Jose-san or any other Arda pool.

## 1. MeCCG.com — current lists and downloads page

The current [MeCCG Lists and Downloads page](https://meccg.com/cards/lists-and-downloads/) exposes several distinct downloadable resources:

| Resource | Format | What it contains | Arda quantity status |
|---|---|---|---|
| [MeCCG List of Cards](https://meccg.es/meta/cards/list/MeCCG%20List%20of%20Cards.xls) | XLS | A downloadable card-list workbook; the landing page does not state its version/date | Not parsed; no quantities adopted |
| [Fixed Sets](https://meccg.es/meta/cards/list/Fixed%20Sets.pdf) | 1-page PDF | The contents of five Hero fixed packs for The Wizards and five Minion fixed packs for The Lidless Eye | Product contents, not an Arda pool |
| [Challenge Decks](https://meccg.es/meta/cards/list/Challenge%20Decks.zip) | ZIP | Download bundle of the ten Challenge Deck lists | Challenge Decks, not Arda |
| [Challenge Decks player aid v1.0](https://meccg.es/meta/cards/list/MECCG-CD-playeraid_v1.0.pdf) | 3-page PDF | Strategies and card-by-card quantities for the ten Challenge Decks | Useful card-name/quantity cross-check only |

The Fixed Sets PDF specifies five different 24-card Hero fixed packs and five different 24-card Minion fixed packs. It is a useful reference for the original starter-product composition, but it is not evidence of how many copies belong in an Arda pool.

The Challenge Decks player aid is more useful for card-list verification. For example, its A — Stewards of Gondor list specifies 8 characters, 30 resources, 30 hazards, 15 sites and a 20-card sideboard. It separately identifies Alatar as the backup Wizard. These are conventional preconstructed-deck quantities, not Arda quantities.

**Retrieval limitation:** the browser identified the XLS as an Excel file and the ZIP as an archive, but this session could not retrieve either binary for parsing. Their direct download links are recorded above; no totals have been inferred from their filenames or landing-page labels.

## 2. Samwise — plaintext Challenge Deck files

The [Samwise repository](https://github.com/SylvanSign/samwise) is an offline MECCG card gallery and deckbuilder. Its README says it supports standard cards (no Dream Cards), saves decks as human-readable plaintext files, and was preloaded with the ten Challenge Deck lists. It also says its card metadata is sourced from Cardnum.

The repository's [decks folder](https://github.com/SylvanSign/samwise/tree/main/decks) contains ten individual `.deck` files:

- A — Stewards of Gondor
- B — Release of Prisoners
- C — Dwarven Quest
- D — Bargain Between Friends
- E — Return of the King
- F — Spies and Traitors
- G — Marauding Brood of Uglies
- H — Stealthy Tribe
- I — Morgul Rallying Cry
- J — Seducing Nations of Men

The plaintext format separates Pool, Characters, Resources, Hazards, Sideboard and Sites, and includes expansion abbreviations beside card names. This makes it a useful technical example for parsing deck files and checking set-code labels. It is not an Arda list, and its card quantities must not be imported into an Arda pool.

### Cross-check against the Challenge Deck player aid

All ten `.deck` files were inspected for section totals. Their main decks consistently list 30 resources and 30 hazards. The five Hero Challenge Deck files A–E list 15 sites; the five Ringwraith Challenge Deck files F–J list 13 sites.

One important completeness warning emerged: the A–E Samwise files each show 19 sideboard cards, while the player aid labels each sideboard as 20 and explicitly includes a backup Wizard. In the A file, the player aid names Alatar as the backup Wizard, but that entry is not present in the Samwise sideboard section. The player aid should therefore take precedence when reconstructing the complete Challenge Deck sideboard.

The Samwise A file's main card quantities agree with the player aid's A — Stewards of Gondor list: 8 characters, 30 resources, 30 hazards and 15 sites. The sideboard omission is why the `.deck` files should be treated as convenient transcriptions, not definitive source records.

The GitHub releases page lists v0.8.0-alpha, published 28 February 2022. This is a useful archived tool and file-format reference, not a current rules authority.

## 3. Council of Elrond card database — role unchanged

The [Council of Elrond card database repository](https://github.com/council-of-elrond-meccg/meccg-cards-database) remains a high-value source for current card identity, text and errata. Its repository contains:

- `cards.json` — 4,163,611 bytes
- `changes-guide.xlsx` — 22,147 bytes

The README explains that card text has been standardized and updated with CRF errata, Rules Book clarifications and Challenge Deck text. This makes it a current rules-text reference, not a literal transcription of every original printing and not an Arda quantity source.

The README also says third-party projects using the database must acknowledge it and notify the Council of Elrond. **No card data from this repository was copied into the Arda database during this pass.** Any future import must first follow that attribution/notification requirement.

## 4. Downloadable source register — new findings

| File | Direct link | Recommended use |
|---|---|---|
| MeCCG List of Cards XLS | [Download XLS](https://meccg.es/meta/cards/list/MeCCG%20List%20of%20Cards.xls) | Parse later as an independent card-list candidate; compare against v1.13 and the seven-set catalogue |
| Fixed Sets PDF | [Open PDF](https://meccg.es/meta/cards/list/Fixed%20Sets.pdf) | Check fixed starter-pack contents and product composition |
| Challenge Decks ZIP | [Download ZIP](https://meccg.es/meta/cards/list/Challenge%20Decks.zip) | Obtain the ten Challenge Deck list files |
| Challenge Decks player aid | [Open PDF](https://meccg.es/meta/cards/list/MECCG-CD-playeraid_v1.0.pdf) | Cross-check names and quantities in the ten preconstructed decks |
| Samwise plaintext deck files | [Browse .deck files](https://github.com/SylvanSign/samwise/tree/main/decks) | Test deck-file parsing and expansion-code normalization |

These are additional reference assets, not additional Arda pools.

## 5. Arda quantity baseline — unchanged

The working Gandalf Gene extraction remains **699 explicit copies**:

| Expansion | Explicit copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

The two named METW cards with blank source quantities remain *Army of the Dead* and *The White Tree*. CCG Collector's independent 2020 report remains 695 copies, four fewer than the explicit workbook rows. The discrepancy is unresolved.

No quantities have been added, removed or adjusted. The new Challenge Deck references do not change the Arda card-pool totals.

## 6. Next research priorities

1. Retrieve and parse the MeCCG List of Cards XLS and Challenge Decks ZIP, then compare their card names, set codes and quantities with the current catalogue.
2. Continue trying to recover the primary Arda quantity workbooks: Gandalf Gene, Thorondor's no-rares sample and other independently published Arda pools.
3. Keep the four-copy Gandalf Gene discrepancy and the two blank quantity rows open until a primary source or independent transcription resolves them.

## Scope

Only genuine, originally published ICE MECCG cards are eligible. Dream Cards, fan-made/custom cards, unreleased material, proxies and Minion Arda quantities are excluded. Conventional Challenge Decks are comparison references only and are not Arda pools.

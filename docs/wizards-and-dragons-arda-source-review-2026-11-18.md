---
layout: default
title: Wizards and Dragons Arda Deck Review
---

# Wizards and Dragons — Arda deck file review

**Reviewed 18 November 2026**

## Source and provenance

A new platform-hosted Arda deck file was found in the public [MECCG Online repository](https://github.com/Heinrich-Barth/meccg-online):

- [View the original `.meccg` file](https://github.com/Heinrich-Barth/meccg-online/blob/main/public/decks/Arda/Wizards%20and%20Dragons.meccg)
- [Download the original `.meccg` file](https://raw.githubusercontent.com/Heinrich-Barth/meccg-online/main/public/decks/Arda/Wizards%20and%20Dragons.meccg)
- Added to the repository on **31 January 2024**, in commit [`ba6ea3f`](https://github.com/Heinrich-Barth/meccg-online/commit/ba6ea3fdbd560099cd1b12d001a7879acbae86a9)
- File size: 9,285 bytes
- Format header: GCCG v0.9.4 Middle-earth deck

The file is in the repository's `public/decks/Arda` folder and is explicitly named **Wizards and Dragons**. The repository supports Arda-format play and importing deck files. Its README also cautions that the included sample data is intended for test play and is not suitable as a complete deckbuilding data source. Treat this as a useful, published digital-play comparison list—not as a canonical or official Arda inventory.

## Source-quality clarification — 19 November 2026

A follow-up audit of the repository changes the confidence classification of this file. The MECCG Online README explicitly describes the repository's included data as generic sample data and says its two supplied decks are for test play; it warns that the data files are not suitable for deckbuilding. The repository's `public/decks/Arda` directory currently contains **only this one file**. Its commit message is simply “arda deck added”; no separate author notes or Arda rules explanation accompany it.

Therefore, retain this as a **countable digital Arda test fixture / sample deck**, not as an independently validated or author-confirmed community Arda pool. Its exact transcription remains useful for comparison, but its selection, completeness and physical-printing provenance are not established.

A small but relevant cross-pool observation: the main Resource section contains **1 copy of The White Tree (TW / The Wizards)**. It contains no Army of the Dead entry. This does not fill either blank in Gandalf Gene's workbook: a quantity in a different sample deck cannot be transferred to another list.

## Main deck contents

The file's `Deck` section declares three categories. The listed quantities add up exactly to the declared subtotals.

| Category | Distinct entries | Copies |
|---|---:|---:|
| Hazards | 126 | 293 |
| Characters | 72 | 72 |
| Resources | 223 | 469 |
| **Main deck total** | **421** | **834** |

### Main deck by expansion

| Expansion | Hazard copies | Character copies | Resource copies | Total copies |
|---|---:|---:|---:|---:|
| The Wizards (METW) | 222 | 67 | 288 | **577** |
| The Dragons (METD) | 71 | 5 | 130 | **206** |
| Against the Shadow (MEAS) | — | — | 51 | **51** |
| **Total** | **293** | **72** | **469** | **834** |

This is a different pool from Gandalf Gene. It has a larger The Dragons allocation and includes 51 Against the Shadow resource copies. It contains no MEDM, MELE or MEWH copies in the main deck. It also does not have a main-deck MEBA card.

### Separate Pool and Sideboard sections

Do not add these to the 834-card main-deck total without preserving their separate roles.

| Section | Entries | Copies | Contents |
|---|---:|---:|---|
| Pool | 6 | 6 | Five Wizard avatars from METW and one *Rumours of Rings* from MEBA |
| Sideboard | 7 | 19 | Six ring entries (three copies each) plus one *Lost in the Wilderness* |

The platform card metadata identifies *Rumours of Rings* as a Hero resource. The main deck's 72 characters are Hero characters, all 469 resources are Hero resources, and its 293 hazards are Neutral. The file therefore supplies a Hero-aligned resource/character pool with neutral hazards; it is not a Minion Arda list. Cards with “Minions” in their names are hazard cards, not Minion-alignment player resources.

## Comparison with Gandalf Gene

I compared the 421 main-deck rows with the current Gandalf Gene inventory using normalized English card names and expansion assignments. The comparison removes accents, punctuation and the file's `[H]` version marker before matching; it does not use fuzzy matching.

| Result | Entries | Copies in Wizards and Dragons |
|---|---:|---:|
| Matched to a Gandalf Gene name in the same expansion | 300 | 514 |
| Not found in Gandalf Gene by that exact normalized comparison | 121 | 320 |
| **Total** | **421** | **834** |

The unmatched rows are not automatically errors or newly discovered cards. They may be deliberate additions/omissions between two different builds; any spelling or printing aliases still need individual review.

| Expansion | Main-deck copies | Matched rows / copies | Unmatched rows / copies |
|---|---:|---:|---:|
| METW | 577 | 257 / 443 | 50 / 134 |
| METD | 206 | 43 / 71 | 48 / 135 |
| MEAS | 51 | 0 / 0 | 23 / 51 |
| **Total** | **834** | **300 / 514** | **121 / 320** |

All 23 Against the Shadow entries (51 copies) are absent from the Gandalf Gene inventory. This is the most significant expansion-level difference. The new list also uses a different selection of The Wizards and The Dragons cards.

## Download the normalized comparison data

- [Original Wizards and Dragons `.meccg` file](https://raw.githubusercontent.com/Heinrich-Barth/meccg-online/main/public/decks/Arda/Wizards%20and%20Dragons.meccg)
- [434-row normalized CSV, including main deck, Pool and Sideboard](../data/wizards-and-dragons-arda-pool-2024.csv)
- [Expansion/category summary CSV](../data/wizards-and-dragons-arda-expansion-summary.csv)

The normalized CSV preserves the original section and category labels and includes a Gandalf Gene match-status column for the main-deck entries. The source's Pool and Sideboard sections remain separate.

## How this source should be used

1. Keep it as a **separate Hero Arda comparison pool**.
2. Use its exact expansion totals and card quantities as a source transcription, not as an addition to Gandalf Gene.
3. Do not treat the 834 main-deck cards as the standard four-pile Arda Basic Game setup. The file groups its cards as Hazard, Character and Resource, with separate Pool and Sideboard sections; it does not document a complete rules procedure or a separate MP/Minor Item pile structure.
4. Do not use the repository's sample-data warning as evidence that the list is invalid; it is a reason to treat it as a digital-play/test list pending author confirmation.
5. Keep physical ICE card eligibility, alignment and printing identity checked independently before using any row in an acquisition list.

**Conclusion:** this is a meaningful new downloadable Hero-aligned Arda deck file with a fully countable 834-copy main deck. It expands the comparison set, particularly through 51 Against the Shadow resource copies, but it does not replace or modify Gandalf Gene's canonical quantities.

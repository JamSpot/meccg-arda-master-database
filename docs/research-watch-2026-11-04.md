---
layout: default
title: Research watch — 4 November 2026
---

# Research watch — 4 November 2026

## Summary

The 2024 *Arda Intro Game* PDF has now been normalized card-by-card against the current Council of Elrond card database. This is the first completed expansion-level audit of that published sample pool.

Two important corrections emerged:

1. The PDF's printed totals omit the site cards paired with each MP resource. Those are additional physical cards, so the physical build is larger than the author's headline total.
2. In the all-rarities pool, 69 hazard-card copies cannot yet be assigned to one expansion because the PDF gives card names but not the exact printing. They remain explicitly unresolved rather than being guessed.

The source remains a separate teaching variant. **No quantities have been merged into or changed in the canonical Gandalf Gene inventory.**

## 1. Source and method

Source: Jared Brayshaw, *The Arda Intro Game*, 14 pages, last updated May 2024. It is a 2–5 player community teaching variant based on the Compiled Arda Ruleset — Hero, Arda Revised and Gandalf Gene's Arda Deck.

- [Download the Arda Intro Game PDF (127.6 KiB)](https://www.councilofelrond.org/forum/download/file.php?id=4315)
- Card identities, alignments, types, set codes and promo rarities were checked against the [Council of Elrond MECCG card database](https://github.com/council-of-elrond-meccg/meccg-cards-database).
- The current database repository's latest commit is [CRF 22 applied](https://github.com/council-of-elrond-meccg/meccg-cards-database/commit/d734847c1ba396ea3a702b3dc588823bc6519249).

The extraction contains 727 source rows across the two variants, including the MP resources and their paired site cards. Every source row now has an official-card match; source spellings and abbreviations are retained alongside the normalized card identity.

## 2. The key physical-card count correction

The PDF says every MP resource is paired with a site card in the same clear sleeve. The printed MP total counts the resource side, not the additional site card.

| Variant | PDF's listed total | MP paired site cards omitted from that total | Physical card components |
|---|---:|---:|---:|
| METW + METD, no rares | 505 | 49 | **554** |
| All rarities and sets | 606 | 88 | **694** |

The Haven Deck's 20 site cards are already included in the PDF's 505/606 totals. The additional 49/88 cards are the sites paired with MP resources.

## 3. Expansion quantities

These figures include the MP paired sites and the Haven Deck sites, because they are physical cards needed for the pool.

| Expansion | METW + METD, no rares | All rarities and sets |
|---|---:|---:|
| The Wizards (METW) | **461** | **514** |
| The Dragons (METD) | **93** | **89** |
| Dark Minions (MEDM) | — | **15** |
| The Lidless Eye (MELE) | — | **6** |
| Against the Shadow (MEAS) | — | **1** |
| The Balrog (MEBA) | — | — |
| The White Hand (MEWH) | — | — |
| Cross-set printing unresolved | 0 | **69** |
| **Physical total** | **554** | **694** |

### What is included in the site totals

- No-rares variant: 49 MP paired sites = METW 44, METD 5; plus 20 Haven sites from METW.
- All-rarities variant: 88 MP paired sites = METW 77, METD 9, MEDM 1, MEAS 1; plus 20 Haven sites from METW.

The no-rares list is fully assigned to METW/METD at expansion level. The all-rarities list has 69 unresolved copies because 23 hazard names have more than one eligible official printing:
- 57 copies could be METW or MELE.
- 12 copies could be METD or MELE.

Those quantities are not missing cards; they are present in the list but their exact expansion printing is unspecified. The card-by-card CSV records the candidate card IDs and expansions.

## 4. Promo-printing audit

The all-rarities pool contains four confirmed official promotional cards, all from the METW promo catalogue:

| Card | Quantity | Official card ID |
|---|---:|---|
| Fury of the Iron Crown | 1 | TW-492 |
| Black Arrow | 1 | TW-494 |
| Fatty Bolger | 1 | TW-495 |
| The Iron Crown | 1 | TW-496 |
| **Confirmed promo copies** | **4** | |

There are also **14 copies across six names** where the PDF does not distinguish the base printing from a promo printing: Dark Quarrels ×3, Escape ×3, Test of Form ×3, Pick-pocket ×3, Quickbeam ×1 and Boromir II ×1. The no-rares variant has 13 such copies across Dark Quarrels, Escape, Test of Form, Barrow-wight and Boromir II.

The expansion assignment for these rows is still METW; only the exact base-versus-promo printing is unresolved.

**Correction to the 3 November note:** The Hero Arda list's *The Arkenstone* is the Hero card TW-341 (The Wizards, rare). The separate Minion-alignment promo LE-418 is not the card used in this Hero pool.

## 5. Card-name normalization and scope

The following source spellings were matched to official printed names:

- Beregrond → **Beregond**, TW-127.
- Edehellond → **Edhellond**, TW-393.
- Dwarven Ring – Durin → **Dwarven Ring of Durin's Tribe**, TW-216.
- Bert, Tom and William → the corresponding original ICE hazard cards.

The PDF includes **Dreams of Lore**, TW-210. This is an original printed ICE Hero resource card, not a Dream Card. No Dream Cards, custom cards or proxies have been admitted.

The PDF is a Hero Arda teaching pool, not a Minion Arda deck. Separate Minion Arda variants remain excluded from this project.

## 6. Downloadable data

- [Normalized card-by-card inventory CSV](../data/arda-intro-game-card-inventory.csv) — 727 rows across both variants, including source spelling, official card identity, card ID, expansion, printing status and unresolved candidates.
- [Expansion summary CSV](../data/arda-intro-game-expansion-summary.csv) — counts by variant, deck section, expansion and reconciliation status.

## 7. Other source checks

- The current Council of Elrond Arda forum index has 46 topics. Its newest 2026 topic is *The Nine are Abroad (The Nine DC version)*; the 2025 Northern Exposure and other Dream Card/Minion variants are also outside this project's scope. They were not imported.
- BanalityBob's 2020 Google Sheet is view-only. The browser-exposed sheet currently shows only seven populated rows (the five Wizards, Fram Frampson and Saw Further and Deeper); it does not expose a complete card pool in this pass. No quantities were adopted.
- Thorondor's [83.5 KiB no-rares XLS](https://www.councilofelrond.org/forum/download/file.php?id=4091) remains a real downloadable source, but its binary still could not be extracted.
- The BGG archive continues to list Jose-san's Arda example as an XLS. No new eligible Hero Arda `.dek` file or independent XLS/XLSX pool was verified in this pass.

## 8. Canonical inventory status and next work

The Gandalf Gene working inventory remains unchanged at 699 explicit copies: METW 552, METD 108, MEDM 32, MELE 6 and MEBA 1. The independent 695-copy community summary still differs by four; the stale 691 Desglose tab is not used.

Next:
1. Extract Thorondor's no-rares XLS.
2. Obtain a complete export of BanalityBob's sheet, if one exists beyond the currently visible rows.
3. Resolve the 69 cross-set hazard printings in the Arda Intro Game list if a source or author clarification becomes available.
4. Continue the 699-versus-695 Gandalf Gene quantity reconciliation.
5. Compare the normalized Intro Game rows against Gandalf Gene and Jose-san as separate variants; do not merge quantities.

No user decision is needed at this stage.

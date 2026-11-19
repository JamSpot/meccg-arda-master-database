---
layout: default
title: Research Watch — 19 November 2026
---

# Arda research watch — 19 November 2026

## Result

No new independently validated ICE-only Hero Arda card pool, spreadsheet or complete deck file was verified today. This pass instead tightened the provenance and quality rating of the **Wizards and Dragons** file recorded yesterday.

## Reclassification: countable test fixture, not a confirmed pool

The [MECCG Online repository](https://github.com/Heinrich-Barth/meccg-online) has an [Arda deck directory](https://github.com/Heinrich-Barth/meccg-online/tree/main/public/decks/Arda). The directory currently contains just one file:

- [Wizards and Dragons.meccg — original download](https://raw.githubusercontent.com/Heinrich-Barth/meccg-online/main/public/decks/Arda/Wizards%20and%20Dragons.meccg)
- [Original commit, 31 January 2024](https://github.com/Heinrich-Barth/meccg-online/commit/ba6ea3fdbd560099cd1b12d001a7879acbae86a9), message: “arda deck added”

The repository README explicitly describes the included data as generic sample data and says its two supplied decks are for test play; the data files are not suitable for deckbuilding. See the [README](https://github.com/Heinrich-Barth/meccg-online#introduction) and the [repository's Arda gameplay notes](https://github.com/Heinrich-Barth/meccg-online#arda-gameplay).

**Disposition:** retain the file as a countable digital Arda test fixture. Do not call it a verified author-curated pool, assume completeness, or use it as an acquisition target. Its file structure is useful, but its list provenance and intended balance are not established.

## Recomputed quantities

I parsed the original text file again and independently summed each row.

### Main Deck

| Category | Entries | Copies |
|---|---:|---:|
| Hazards | 126 | 293 |
| Characters | 72 | 72 |
| Resources | 223 | 469 |
| **Main Deck total** | **421** | **834** |

| Expansion | Main-deck copies |
|---|---:|
| The Wizards (TW / METW) | 577 |
| The Dragons (TD / METD) | 206 |
| Against the Shadow (AS / MEAS) | 51 |
| **Total** | **834** |

The file's remaining sections are separate:

| Section | Entries | Copies | Treatment |
|---|---:|---:|---|
| Pool | 6 | 6 | Five Wizards from TW and one Rumours of Rings from BA / The Balrog |
| Sideboard | 7 | 19 | Keep outside the main-deck subtotal |
| **All sections** | **434** | **859** | Not a single 859-card main deck |

The original deck file and the normalized data are available from the [18 November source review](wizards-and-dragons-arda-source-review-2026-11-18.html), with [card-by-card CSV](../data/wizards-and-dragons-arda-pool-2024.csv) and [expansion/category summary CSV](../data/wizards-and-dragons-arda-expansion-summary.csv).

## Card-level observation: The White Tree

The sample's main Resource section contains **1 The White Tree (TW / The Wizards)**. There is no Army of the Dead row anywhere in the file.

This is useful cross-pool evidence that the sample deck includes The White Tree once. It does **not** establish the missing quantity in Gandalf Gene's different workbook. No quantity is copied across lists, and the canonical Gandalf Gene inventory is unchanged.

## Other source checks

- The current [BoardGameGeek MECCG files archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files) still exposes the known **Arda deck example — XLS** by Jose-san and the **Arda Revised** rules PDF among its listed files. The Jose-san workbook candidate remains separately parsed in the project; the original BGG attachment still has not been hash-matched.
- The known [Thorondor no-rares XLS](https://councilofelrond.org/forum/download/file.php?id=4091) remains the highest-priority inaccessible Arda workbook. The direct Council attachment endpoint could not be opened or downloaded in this pass, so it remains unparsed.
- [BanalityBob's Google Sheet](https://docs.google.com/spreadsheets/d/1a_32IVLD7SkX6A8fqVsAz95i67HtcxAb4VZYuvxg8ns/edit?usp=sharing) still has no verified complete export in this environment. No quantities were inferred from the visible partial rows.
- The [Gandalf Gene original forum post](https://councilofelrond.org/forum/viewtopic.php?f=37&t=2870) remains the primary fixed Hero Arda quantity source. No canonical quantities were changed.

## Project record

- [Arda research website](https://jamspot.github.io/meccg-arda-master-database/)
- [Sources & Downloads](sources.html)
- [Comparison Lists](comparison-lists.html)
- [Research Progress](research-progress.html)

**No user decision is required.** The next material step is still obtaining the original Thorondor XLS or a complete export of BanalityBob's sheet; either could add an independent row-level pool for comparison.

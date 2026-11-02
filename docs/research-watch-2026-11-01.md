---
layout: default
title: Source watch — 1 November 2026
---

# Source watch — 1 November 2026

## Summary

This pass identified BanalityBob's public Arda spreadsheet and the 2024 Arda Variants discussion with two downloadable rules PDFs. On 2 November, the project scope was tightened to original, officially published ICE cards only; previously noted Dream Card and custom-card material has been removed from active comparison. No quantities were changed.

## 1. BanalityBob's Arda — public spreadsheet lead

The [Council of Elrond post](https://www.councilofelrond.org/forum/viewtopic.php?f=37&t=4324) (16 September 2020) links a public [MECCG Arda Deck Google Sheet](https://docs.google.com/spreadsheets/d/1a_32IVLD7SkX6A8fqVsAz95i67HtcxAb4VZYuvxg8ns/edit?usp=sharing) and a separate rules document.

The author says the variant uses non-standard character and minor-item choices, separates resources and hazards into different decks, gives each player a themed hazard deck, changes ring handling and does not use Underdeep sites. This is a meaningful community deck-list lead because it is a spreadsheet rather than just a rules discussion.

The sheet opened in view-only mode, but the current browser extraction exposed only a small part of its rows. I did not invent a total or adopt any quantities. The next step is to obtain an XLSX/CSV export and compare its card names and quantities against the v1.13 catalogue and the canonical Gene inventory.

## 2. ARDA VARIANTS — rule comparison and downloadable PDFs

The [Council of Elrond ARDA VARIANTS thread](https://www.councilofelrond.org/forum/viewtopic.php?f=37&t=4992), started 1 March 2024, records differences among:

- Arda Basic Game (four shared decks; up to seven players; 20 MP to call the Council in the described version).
- Gandalf Gene's Arda rules (four shared decks; up to five players; two high-mind characters plus Gimli in the major-character draft; 25 MP to call the Council).
- A Wizards-of-Middle-Earth house variant (Strider/Aragorn are kept out of the opening draft and placed in the Roving Character Deck; 20 MP).
- A Winter/Lure 2024 variant (five shared piles including a tested-ring deck; random Wizard; deal four minor items and choose two; 18/20/25 MP depending on the game).

The thread links two rules files:

- [arda_intro_game.pdf](https://www.councilofelrond.org/forum/download/file.php?id=4315) — 127.6 KiB, an introductory variant in which MP cards are paired with sites.
- [Arda_eng.pdf](https://www.councilofelrond.org/forum/download/file.php?id=4286) — 67.33 KiB, the rules used by one play group.

These are rules references, not card lists. They should be stored as separate variants and not treated as a change to the canonical card pool.

## 3. Existing quantity baselines — unchanged

### Gandalf Gene canonical comparison point

| Expansion | Explicit physical copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

The inventory has 374 distinct identities with numeric quantities, plus two named METW rows with blank quantities (Army of the Dead and The White Tree). The independent CCG Collector report remains 695 copies, leaving a four-copy difference unresolved. The static Gene workbook Desglose table totals 691 and is treated as stale because its categories match the separate Jose-san workbook.

### Jose-san — BGG Arda deck example candidate

The parsed local workbook has 370 unique names / 691 copies across all alignments. Excluding 48 Minion-alignment entries / 68 copies leaves 322 Hero/Neutral/Avatar names / 623 copies:

| Expansion | Card names | Copies |
|---|---:|---:|
| METW | 228 | 410 |
| METD | 61 | 126 |
| MEDM | 18 | 48 |
| MELE | 4 | 12 |
| MEAS | 8 | 18 |
| MEWH | 2 | 6 |
| MEBA | 1 | 3 |
| **Total** | **322** | **623** |

The 322-row comparison has 242 names shared with Gandalf Gene, 80 Jose-san-only names, 134 Gene-only names and 29 shared names with different quantities. These lists remain separate builds.

## 4. Downloadable-source status

| Source | Format | What it provides | Current status |
|---|---|---|---|
| Gandalf Gene's Arda Deck | XLS | Primary card quantities | Local copy parsed; binary hash against forum attachment outstanding |
| Jose-san Arda deck example | XLS | Alternative Arda pool | Local candidate parsed; BGG attachment hash outstanding |
| Thorondor Arda Sample Deck without Rares | XLS | Beginner/lower-rarity Arda quantities | Attachment located (83.5 KiB); binary still not parsed |
| BanalityBob's Arda | Google Sheets | Separate resource/hazard and themed-hazard pool | Public sheet located; export/row extraction still needed |
| Arda Intro Game | PDF | Introductory rules variant | Attachment located (127.6 KiB) |
| Arda_eng | PDF | Play-group Arda rules | Attachment located (67.33 KiB) |
| Arda Revised | PDF | Revised rules | BGG download |
| Compiled Arda Ruleset — Hero | PDF | Hero rules compilation | BGG download |
| MECCG Card List v1.13 | XLS | Full card identity/set/rarity catalogue | Local catalogue parsed; not an Arda quantity source |

## Scope correction — 2 November 2026

Only original, officially published ICE cards are eligible for this project. Dream Cards, fan-made/custom cards, unreleased cards and proxies are excluded. This page no longer treats those materials as comparison sources.

## Next concrete work

1. Obtain and parse Thorondor's 83.5 KiB **Arda Sample Deck_no rares.xls**.
2. Obtain an XLSX/CSV export of BanalityBob's Google Sheet.
3. Confirm the Jose-san local workbook against the BGG attachment binary.
4. Trace the four-copy discrepancy between Gandalf Gene's 699 explicit copies and CCG Collector's 695 report.
5. Only after those checks, produce a final physical-card acquisition table.

**No user decision is needed in this pass. No canonical quantities have been changed.**

---
layout: default
title: Source watch — 31 October 2026
---

# Source watch — 31 October 2026

## Summary

This pass produced two useful card-pool comparisons and corrected an important source-attribution error in the quantity audit:

1. The project Library's ARDA.xls is a high-confidence match for the BoardGameGeek Arda deck example XLS by Jose-san. I parsed its card-level ARDA quantities.
2. A separate Spanish community thread links a solo-Arda card list and Callasmar's solo-Arda rules.
3. The 695-copy figure is not the Desglose total in the Gandalf Gene workbook. It comes from CCG Collector's 3 June 2020 Council of Elrond post. The Gene workbook's static Desglose tab actually totals 691 and appears to be a stale summary copied from the Jose-san pool.

The canonical Gandalf Gene card quantities remain unchanged at **699 explicit copies**. The independent 695-copy report leaves a four-copy discrepancy open.

## 1. Parsed Arda deck example — Jose-san

The BoardGameGeek [MECCG files archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files) lists **Arda deck example** as an XLS by Jose-san. The project Library contains ARDA.xls (311,808 bytes); its Excel metadata says it was last saved by Jose San Miguel on 2 May 2010. The author/format and the workbook's recorded category totals make this a high-confidence match to the BGG entry, although I have not verified the BGG attachment's binary hash.

### Full source workbook

The MECCG Cards sheet contains 370 unique card names with nonblank ARDA quantities, totalling **691 copies**. Its category breakdown is:

| Category | Copies |
|---|---:|
| Characters | 112 |
| Hazard creatures | 120 |
| Hazard events | 121 |
| Resource allies | 20 |
| Resource events | 197 |
| Resource factions | 31 |
| Resource items | 90 |
| **Total** | **691** |

The full workbook contains all alignments, including 48 Minion-alignment entries / 68 copies. Those Minion entries are excluded from this project's Hero comparison.

### Hero-compatible subset

Filtering to Hero, Neutral and Avatar alignments gives **322 card names / 623 copies**. Neutral cards are retained because neutral hazards are part of a Hero Arda pool; Minion-alignment rows are not.

| Expansion | Card names | Copies |
|---|---:|---:|
| The Wizards (METW) | 228 | 410 |
| The Dragons (METD) | 61 | 126 |
| Dark Minions (MEDM) | 18 | 48 |
| The Lidless Eye (MELE) | 4 | 12 |
| Against the Shadow (MEAS) | 8 | 18 |
| The White Hand (MEWH) | 2 | 6 |
| The Balrog (MEBA) | 1 | 3 |
| **Total** | **322** | **623** |

This is a distinct, broader community pool—not a replacement for Gandalf Gene's published list. The downloadable [Hero-pool comparison CSV](../data/jose-san-hero-arda-pool-comparison.csv) contains the 322 non-Minion rows and the corresponding Gandalf Gene quantities where card names match. It deliberately omits the Minion-alignment rows.

### Card-by-card comparison with Gandalf Gene

Using normalized English card names:

- **242** names appear in both Hero-compatible Jose-san rows and the Gandalf Gene inventory.
- **80** names are in the Jose-san Hero/Neutral/Avatar subset but not in Gandalf Gene.
- **134** names are in Gandalf Gene but not in the Jose-san subset.
- **29** of the 242 shared names have different quantities between the two lists.
- After the independently verified expansion corrections, all 242 shared names have matching expansion assignments. The original Gene workbook had Peril Returned and Wild Trolls assigned to the wrong sets; the master inventory now corrects them.

The comparison is a discovery/checksum aid only. Do not merge either list's quantities into the other.

## 2. Correcting the 695 / 699 / 691 reconciliation

The Council post exposes the original `GandalfGeneArda.xls` attachment (attachment ID 945) and lists it as 79 KiB. The Library copy is 80,896 bytes (exactly 79 KiB), matching the published size. A binary hash comparison against the server attachment has not been possible, but this is a strong file-provenance check.

The original [Gandalf Gene Council post](https://councilofelrond.org/forum/viewtopic.php?f=37&t=2870) says the Play Deck contains 171 resources and 252 creatures/hazards (423 cards). The attached GandalfGeneArda.xls has:

- 377 named card rows after excluding the title row;
- 375 rows with numeric ARDA quantities;
- 374 distinct names among numeric rows because Nenseldë the Wingild appears twice;
- two named rows with blank quantities (Army of the Dead and The White Tree);
- 376 unique named identities overall;
- **699** explicit copies across numeric rows.

The **695** figure comes from CCG Collector's post on 3 June 2020 in the Council of Elrond thread [Which sets are best for ARDA?](https://councilofelrond.org/forum/viewtopic.php?t=2494). That post reports 377 distinct cards / 695 physical cards and expansion identity counts of 300 METW, 59 METD, 14 MEDM, 2 MELE and 1 MEBA. Those expansion subtotals sum to 376, matching the working unique-name count, while the headline says 377.

The Gene workbook's static Desglose sheet totals **691**, not 695. Its category table exactly matches the Jose-san workbook's 691-card category summary, including 34 Minion characters and 30 Minion resources that are not present in the Gene card rows. This is strong evidence that the Gene Desglose tab is stale and should not be used as the Gene list's checksum. An intermediate collecting-list workbook in the Library labels 695 as “Source Desglose total”. That label is incorrect: the original GandalfGeneArda.xls Desglose tab totals 691, while 695 is CCG Collector's independent community summary. Treat the derived workbook's 695 field as the published checksum, not as the source tab's total.

**Correct reconciliation status:** 699 explicit Gene row copies versus the independently reported 695 community total = **+4 unresolved**. The stale 691 Desglose table is a separate source artifact, not the explanation for the four-copy difference.

## 3. Published sample Arda pool without rares — Thorondor (2015)

The Council of Elrond thread [ARDA Sample Deck without Rares](https://www.councilofelrond.org/forum/viewtopic.php?f=37&t=2630) contains a downloadable **Arda Sample Deck_no rares.xls** attachment (83.5 KiB), posted on 20 July 2015 by Thorsten the Traveller (forum name thorondor).

The author describes it as a beginner-friendly pool that avoids rares, is mostly The Wizards and The Dragons with a few Dark Minions cards, and generally uses one copy of each unique card and three of each non-unique card. Exceptions include extra Gold Rings and testing cards, plus additional Doors of Night, Gates of Morning and Twilight. The workbook is bilingual (English/German).

This is a meaningful independent Arda quantity source and a useful lower-rarity/entry-level comparison against Gandalf Gene and Jose-san. The forum page exposes the 83.5 KiB XLS attachment, but the current browser download path rejects the binary, so its rows and expansion totals have not yet been extracted. No quantities have been adopted. Retrieval and parsing of this workbook is now a high-priority next step.

## 4. Dedicated Arda Solitaire rules — Kober (2015)

The Council of Elrond thread [Arda Solitaire](https://councilofelrond.org/forum/viewtopic.php?t=2578) contains a separate published solo-Arda rules PDF: **Arda Solitaire v0.2.pdf**, posted by Kober on 4 April 2015 (44.23 KiB).

A May 2016 comment compares it with Callasmar's BGG solo-Arda variant. The commenter says Callasmar pairs a site with a playable card, while Kober's approach keeps the normal site requirements: the company must travel to the appropriate sites to play a Greater or Major Item, Information, or a Gold Ring. The commenter considers Kober's approach closer to the standard game's movement/site logic. Kober later says themed Arda solo pools—such as Trolls threatening Rohan and Gondor or Orcs of Angmar—are actively encouraged.

This is a distinct Arda-specific solo ruleset, not the normal constructed-deck solo variant and not a card-quantity list. The forum exposes the PDF attachment, but the current browser download path rejects its binary content, so I have not transcribed or adopted its rules text. It is a strong candidate for a later side-by-side solo-rules comparison with Callasmar and the 2013 solo-Arda session report.

## 5. Historical Arda-design discussion clarifies pool boundaries and hazard omissions

The Council of Elrond thread [Which sets are best for ARDA?](https://councilofelrond.org/forum/viewtopic.php?t=2494) adds useful context around the Gandalf Gene list:

- In January 2015, a contributor explicitly distinguishes Hero Arda from Minion Arda and recommends keeping their Arda decks separate. For Hero Arda, the suggested foundation is The Wizards, with selected non-MP resources and hazards from The Dragons and Dark Minions added as desired. The post cautions against agents and their associated cards as too complicated for this format.
- In June 2020, CCG Collector independently reports the 377 / 695 Gene-list summary. In the follow-up discussion, players suggest that Dragon Ahunt manifestations and Drakes were left out because they can be disproportionately punishing in Arda: hazards can persist across several player turns, the shared hazard environment can stack up, and random resource/site choices make the Drakes more broadly playable than in ordinary constructed games.
- The same discussion describes the hazard pool as having been tuned over time toward more familiar Orc, Troll and Man threats with events that support those creature types.

This is community recollection and analysis, not a formal statement from Gandalf Gene or an official ruling. It is nevertheless a useful warning for the audit: a card's absence from a published Arda list is not automatically a transcription error. Some omissions may be intentional balance choices. It also supports keeping Hero and Minion pools separate rather than importing the whole MELE card set into the Hero baseline.

## 6. Additional solo-Arda pool lead — La BSK

The Spanish [SATM partida en solitario thread](https://labsk.net/index.php?topic=126528.30) (thread started 28 January 2014) contains two useful posts:

- A 2014 description says the author's Arda pool uses cards from The Wizards, The Dragons and Dark Minions, generally one copy of each card except commons and uncommons, which are included as three copies. It excludes promos, the drinking game and the Spanish beginners set. The author says he played solo using Callasmar's solo-Arda rules.
- On 4 June 2017, Borja shares a [Google Docs card list](https://docs.google.com/document/d/1XSkyc_lnn0av7pbvqs814zlwN4kZSs4hKaNm00nm5Rw/edit?usp=sharing), explicitly saying he had only played this build solo, and links the [Callasmar solo-Arda rules file](https://boardgamegeek.com/filepage/87333/variante-a-las-reglas-arda-para-jugar-en-solitario).

The forum evidence is accessible, but automated retrieval of the Google Doc returned HTTP 410. I have therefore recorded the pool-building method and links without extracting card names or adopting quantities. This is a separate solo-Arda variant, not a canonical Gene list.

## 7. Canonical Gene expansion quantities — unchanged

| Expansion | Explicit copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

Army of the Dead and The White Tree remain named rows with blank source quantities. The four-copy difference versus CCG Collector's 695 report remains unresolved. No quantities have been changed in this pass.

## Next concrete work

1. Retrieve and parse Thorondor's 83.5 KiB **Arda Sample Deck_no rares.xls**; this is now the highest-priority independent card-quantity comparison.
2. Confirm the local Jose-san ARDA.xls against the BGG attachment, ideally by binary hash or a direct file comparison.
3. Retrieve the La BSK Google Docs pool and Kober's Arda Solitaire v0.2 PDF; both are currently blocked at the attachment/document binary stage.
4. Trace the four-copy difference between the Gene workbook's 699 explicit rows and CCG Collector's 695 report.
5. Complete the full Council of Elrond metadata match and audit remaining rarity/identity fields.
6. Produce an audited physical-card acquisition table with source provenance for every quantity.

**Input needed:** none for this pass. No canonical quantity or deck-membership decision is being requested.

# Comparison Lists

These lists are useful for comparison but must not be merged into the canonical Gandalf Gene deck without explicit evidence.

## 4 November 2026 — Arda Intro Game row-level normalization

The May 2024 *Arda Intro Game* PDF has now been mapped against the current official card database. Its two pools remain separate variants, not additions to Gandalf Gene.

| Variant | PDF listed total | Additional MP-paired sites | Physical components |
|---|---:|---:|---:|
| METW + METD, no rares | 505 | 49 | **554** |
| All rarities and sets | 606 | 88 | **694** |

Physical expansion totals, including the MP-paired sites and Haven Deck:

| Expansion | No rares | All rarities and sets |
|---|---:|---:|
| METW | 461 | 514 |
| METD | 93 | 89 |
| MEDM | — | 15 |
| MELE | — | 6 |
| MEAS | — | 1 |
| Unresolved cross-set printings | 0 | 69 |
| **Total physical components** | **554** | **694** |

The all-rarities list has 69 hazard copies whose names match both an original METW/METD printing and a MELE printing; the PDF does not specify which printing it uses. Four further copies are confirmed METW promos (Black Arrow, Fatty Bolger, Fury of the Iron Crown and The Iron Crown). Fourteen more copies have a base-versus-promo printing ambiguity within METW. The no-rares list has 13 such copies.

The author’s 505/606 totals count the MP resource cards but not the site cards paired with them. The additional 49/88 sites are physical cards and are included in the expansion totals above.

Download the [727-row normalized card inventory](../data/arda-intro-game-card-inventory.csv) and [expansion summary](../data/arda-intro-game-expansion-summary.csv). The card-name aliases Beregrond → Beregond, Edehellond → Edhellond and Dwarven Ring – Durin → Dwarven Ring of Durin’s Tribe are documented in the inventory.

The Hero Arda *Arkenstone* is TW-341 (Hero, The Wizards); the separate Minion promo LE-418 is not used. *Dreams of Lore* is the original ICE Hero card TW-210, not a Dream Card. No Dream Cards, custom cards or Minion Arda decklists were added.

## Scope clarification — Jose-san comparison

The 322-name / 623-copy Jose-san subset is a strict Avatar/Hero/Neutral alignment filter, retained for comparison only. It is not a replacement canonical Hero Arda list or a physical acquisition list. Keep the separate Minion Arda variant excluded; do not merge its quantities into the Hero pool.



## Jose-san — ARDA.xls (likely BGG Arda deck example)

The BGG [MECCG files archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files) lists an **Arda deck example — XLS** by Jose-san. The project Library contains a local ARDA.xls whose workbook metadata says it was last saved by Jose San Miguel on 2 May 2010. Its categories and totals match the previously recorded Jose-san summary, making it a high-confidence candidate for that BGG file; the BGG attachment has not yet been hash-compared.

The parsed workbook has **370 unique names / 691 copies** across all alignments. It includes 48 Minion-alignment entries / 68 copies. Those Minion entries are excluded from this Hero project.

### Hero / Neutral / Avatar subset

Filtering out Minion alignment leaves **322 names / 623 copies**:

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

This subset retains neutral hazards and the five Wizards. It is not a replacement for Gandalf Gene.

### Comparison with Gandalf Gene

Exact normalized English-name matching gives:
- 242 shared names;
- 80 names unique to the Jose-san Hero/Neutral/Avatar subset;
- 134 names unique to Gandalf Gene;
- 29 shared names with different quantities.

After the independent expansion corrections already recorded in the master inventory, all 242 shared names have matching expansion assignments. The [downloadable comparison CSV](../data/jose-san-hero-arda-pool-comparison.csv) contains the 322 non-Minion rows, Jose-san quantities and Gandalf Gene quantities where matched. Blank Gene quantities mean the card is not in the Gene list.

Do not merge the two sources' quantities. They are different Arda builds.

## Leon — 2022 Arda pool (user-supplied; mixed/uncertain, not ICE-only) {#leon-2022-arda-pool}

The workbook `cards for Arda Leon 20220901.xlsx` was supplied from a Facebook/Lookaside link; that original link is no longer retrievable. Its file properties identify the creator as **Leon en Claudia**, with a creation date of 1 September 2022 and last-modified date of 21 February 2024. Treat it as an independent comparison workbook, not a verified public/published decklist.

The workbook's displayed category totals are:

| Category | Workbook summary | Direct row sum |
|---|---:|---:|
| Hazard creatures | 143 | **144** |
| Hazard events | 190 | 190 |
| Resource events | 265 | 265 |
| Resources | 199 | 199 |
| Characters | 100 | 100 |
| Minor items | 54 | 54 |
| Rings | 23 | 23 |
| **Total** | **974** | **975** |

The one-copy error is inside the workbook: the first hazard-creature category formula starts at row 7, while row 6 contains **Carrion Birds — 1 copy**. The formula therefore omits that copy. The 974 headline is not a reliable checksum; the direct sum of the listed quantity cells is 975.

A name-level screen against the 1,674 card-ID rows in the original MECCG Card List v1.13 catalogue found **803 of 898 distinct names** with an exact normalized English-name match. The other **95 names account for 112 copies** (85 names have non-zero quantities; 10 have zero). The exact matches account for 863 copies. This is only a screening result: several unmatched entries are abbreviations, misspellings or translations, and a name match cannot identify a specific printing or expansion.

Importantly, several names in the workbook also appear in the published Dream Card Arda list *The Houses of the North* under non-standard set codes, including **A More or Less Decent Giant (DF), Asfaloth (RS), Carc (DF), Bolg, Son of Azog (DF), Gorfaur the Lame (NE), His Beard Long and Forked (DF)** and **Aglarond (TI)**. This confirms that the workbook is not a clean ICE-only pool. It has no per-card expansion/printing identifiers, so safe expansion totals cannot be derived from it.

**Disposition:** retain only as an excluded comparison lead. Do not merge its quantities or names into the physical ICE-only master database, and do not use its 974/975 total as an Arda acquisition target.

## Published Dream Card Arda — The Houses of the North (2021–2025; excluded)

[Council of Elrond thread and full text list](https://councilofelrond.org/forum/viewtopic.php?p=38931). The Dwarves-themed Arda list was first posted on 3 November 2021 and last edited on 30 July 2025. Its author describes it as a Dream Card Arda, says it uses Dream Card rules/UEPs and includes cards from unreleased sets, and gives the pool as **888 cards**. The card-by-card list is spread across forum posts; there is no separate XLS/XLSX or standalone deck file attached in the thread.

The list mixes original ICE cards with non-ICE entries. Examples identified with non-standard set codes include A More or Less Decent Giant (DF), Asfaloth (RS), Carc (DF), Bolg, Son of Azog (DF), Gorfaur the Lame (NE), His Beard Long and Forked (DF) and Aglarond (TI). This is a published Arda decklist, but it is **not** an ICE-only Hero pool. It is retained as an excluded community reference only; no card identities or quantities are imported into the master database.

## Published Dream Card Hero Arda — Northern Exposure (2025; excluded)

[Council of Elrond thread and full text list](https://councilofelrond.org/forum/viewtopic.php?t=5233). This is a **three-player, avatarless Hero-alignment** Arda variant focused on the Northern Wastes factions (Umli, Elves of Evermist and Berninga), posted 30 July 2025 and last edited 6 August 2025. The thread contains a detailed pool/deck list and a **95-card sideboard**, but no separate XLS/XLSX or standalone deck file.

Although it is Hero-alignment, the list explicitly uses Dream Cards and numerous non-ICE set codes (for example NW, DF, RS, GW and FB), alongside original ICE cards. It is therefore not an eligible physical ICE-only Hero pool. It shares names such as Great Seagull, Bain and Gorfaur the Lame with the Leon workbook, reinforcing the need to keep that workbook out of the canonical inventory.

Retain as a published community variant reference only. Do not import its card names or quantities into the master database.


## 2014–2017 — Spanish community solo-Arda pool

[La BSK: SATM partida en solitario](https://labsk.net/index.php?topic=126528.30) includes a 2014 pool-building description and a 4 June 2017 follow-up. The described pool uses The Wizards, The Dragons and Dark Minions; one copy of each card except commons/uncommons at three copies; and Callasmar's solo-Arda rules. Borja's 2017 post links a [Google Docs card list](https://docs.google.com/document/d/1XSkyc_lnn0av7pbvqs814zlwN4kZSs4hKaNm00nm5Rw/edit?usp=sharing) and the [solo-Arda rules file](https://boardgamegeek.com/filepage/87333/variante-a-las-reglas-arda-para-jugar-en-solitario). He says he had only played the pool solo. The Google Doc could not be extracted automatically, so this remains a separate source lead, not a quantity authority.

## Scope boundary
Only original, officially published ICE Middle-earth CCG cards are eligible for comparison or quantity totals. Dream Cards, fan-made/custom cards, unreleased cards and proxies are excluded from this project entirely.


## 2013 — My Solo Arda Build with Session Report
[BoardGameGeek thread](https://boardgamegeek.com/thread/1058232/my-solo-arda-build-with-session-report), published 22 October 2013 and edited with additional turns on 14 November 2013.

This is a useful **solo-method variant**, not a complete quantity list. It describes separate MP, Ring, Resource, Minor Item, two Character, Hazard and Site decks. It generally uses one of each owned card, with selected multiples of useful resources and common hazards. The author says the build excludes The Lidless Eye, The White Hand and The Balrog. The tested scenario lasts eight turns and targets 25 Marshaling Points. The solo hazard player draws four times the site's printed number when travelling and twice that number when staying, then chooses the most damaging legal hazards from that hand. The setup also uses a randomly selected Wizard, a starting character line, two random minor items and a 5-resource/3-MP hand. These are explicitly experimental rules, not a final official solo ruleset. No downloadable spreadsheet or exact deck file was verified, and the exact card counts are not given.

Keep this source separate from both Gandalf Gene's canonical 423-card Arda Play Deck and normal constructed-deck solo play, which uses a built Hero deck and a defined Hazard deck rather than this large-pool Arda arrangement.


## Arda Rules 4.0 — general pool-sizing baseline (29 October 2026)

[Published Arda Rules 4.0 PDF](https://lureofmiddleearth.com/wp-content/uploads/2016/03/arda_4.0_en.pdf) describes shared-deck Arda for 2–7 players. Its general construction guidance is a 250+ Play Deck with equal numbers of resources and hazards, an MP deck of at least 15 cards per player (often around 100), around 70 characters in the Roving Character Deck for larger games, and a 30–35 card Minor Item Offering Deck.

This is a rules baseline, not an exact list. The current Gandalf Gene transcription has 423 Play Deck cards split into 171 resources and 252 creatures/hazards, so it does not follow the generic 1:1 recommendation. Keep that difference visible; do not normalize the canonical list without primary-source evidence. This multiplayer Arda ruleset is also distinct from the experimental 2013 solo-Arda adaptation and from constructed-deck solo play.


## BanalityBob — community Arda spreadsheet (2020)

[Council of Elrond post](https://www.councilofelrond.org/forum/viewtopic.php?f=37&t=4324) links the [MECCG Arda Deck spreadsheet](https://docs.google.com/spreadsheets/d/1a_32IVLD7SkX6A8fqVsAz95i67HtcxAb4VZYuvxg8ns/edit?usp=sharing). The author describes separate resource and hazard decks, individual themed hazard decks, different ring handling and no Underdeep sites. This is a genuine list lead, but the sheet's card rows could not be extracted in this pass. Keep it unquantified until a workbook export is available; do not infer counts from the author's rules description.

## 2024 Arda variants — rules, not quantities

The [ARDA VARIANTS thread](https://www.councilofelrond.org/forum/viewtopic.php?f=37&t=4992) records differences between the Basic Game, Gandalf Gene's house rules, a Wizards-of-Middle-Earth variant and a Winter/Lure 2024 variant. It links two PDFs: [Intro Game](https://www.councilofelrond.org/forum/download/file.php?id=4315) and [Arda_eng](https://www.councilofelrond.org/forum/download/file.php?id=4286). These should be compared as rules variants, not used as evidence for card quantities.


## 2024 — The Arda Intro Game sample pools (Jared Brayshaw)

A 14-page community PDF, last updated May 2024, contains two sample Arda Intro Game card pools. [Download the public PDF](https://www.councilofelrond.org/forum/download/file.php?id=4315). The row-level inventory and expansion reconciliation were completed on 4 November 2026.

### METW + METD only, no rares

- Play Deck: 141 Resource Events + 93 Hazard Events + 96 Hazard Creatures = **330**
- MP Deck: **49**
- Character Deck: **57**
- Minor Item Deck: **34**
- Ring Deck: **10**
- Avatar Deck: **5**
- Haven Deck: **20**
- **Total: 505 cards across all listed piles**

### All rarities and sets

- Play Deck: 156 Resource Events + 107 Hazard Events + 97 Hazard Creatures = **360**
- MP Deck: **88**
- Character Deck: **71**
- Minor Item Deck: **41**
- Ring Deck: **21**
- Avatar Deck: **5**
- Haven Deck: **20**
- **Total: 606 cards across all listed piles**

The PDF uses an Arda Intro Game structure with sites paired to MP resources and separate Character, Minor Item, Ring, Haven and Avatar piles. It is a community teaching variant, not the canonical Gandalf Gene list and not a conventional constructed-deck solo format.

Spot-checks against the Council of Elrond card database confirm that several distinctive entries are official ICE Hero cards, including Lindion the Oronín (DM-177), Emerald of Doriath (TD-112), Habergeon of Silver (TD-120), Valiant Sword (TD-161), Wormsbane (TD-172), Adamant Helmet (TD-96), Scabbard of Chalcedony (TD-150), The Arkenstone (TW-341), The Mithril-coat (TW-345), The One Ring (TW-347) and The Iron Crown (TW-496). Some similarly named Minion printings exist in The Lidless Eye; use the Hero card IDs only.

The list's **Dreams of Lore** entry is the official ICE Hero card TW-210, not a Dream Card. Custom Dream Cards remain excluded.

The author's printed section totals have now been independently reconciled row-by-row. The additional MP-paired site cards are counted separately, and unresolved cross-set printings are explicitly flagged. Keep both sample pools separate from Gandalf Gene and Jose-san.


### Promo-printing note for the 2024 Arda Intro Game all-rarities pool

The all-rarities sample includes at least four English promotional cards: Black Arrow, Fatty Bolger, Fury of the Iron Crown and The Iron Crown. The Arkenstone is also listed in the promo archive, but the PDF does not identify which printing it uses. Keep those entries in a separate promo-printing audit until the physical version is known; do not add them to the seven standard expansion totals by card name alone.

The 500-entry Card Hunters HQ The Wizards checklist is a mirror of the Council of Elrond restoration archive and includes promo printings (rarity P), so it is not an independent count of the 484-card base The Wizards checklist. The exact v1.13-versus-base-set difference remains unresolved.


## Jose-san Arda source — row-level expansion reconciliation (3 November 2026)

The Library copy of ARDA.xls has an Arda quantity column and file properties identifying José San Miguel as last editor. Its Hero-compatible rows reproduce the previously reported 322 identities / 623 copies, but the extraction now separates promotional printings from base expansion copies.

| Expansion | Base identities | Base copies | Promo identities | Promo copies | Total identities | Total copies |
|---|---:|---:|---:|---:|---:|---:|
| METW | 226 | 407 | 2 | 3 | 228 | 410 |
| METD | 61 | 126 | 0 | 0 | 61 | 126 |
| MEDM | 18 | 48 | 0 | 0 | 18 | 48 |
| MELE | 4 | 12 | 0 | 0 | 4 | 12 |
| MEBA | 1 | 3 | 0 | 0 | 1 | 3 |
| MEAS | 8 | 18 | 0 | 0 | 8 | 18 |
| MEWH | 2 | 6 | 0 | 0 | 2 | 6 |
| **Total** | **320** | **620** | **2** | **3** | **322** | **623** |

The two promotional identities are Black Arrow (2 copies) and Fatty Bolger (1 copy). Therefore the previous 623-copy Hero-compatible figure remains correct, but **only 620 copies belong in the seven base-expansion totals**. Keep the three promo copies separate.

The source workbook includes other alignments; only Avatar, Hero and Neutral rows were used. Minion and Stage rows were excluded from this Hero comparison. The detailed output is available in [the expansion summary CSV](../data/jose-san-hero-expansion-summary.csv) and [promo quantities CSV](../data/jose-san-promo-quantities.csv). The BGG file archive lists Jose-san's Arda deck example XLS; a binary hash match between the Library copy and the BGG attachment remains outstanding.


## Base expansion catalogue reconciliation

The metw.net expansion PDFs count base cards; the v1.13 workbook adds 17 promo rows. Removing those rows produces an exact match in every set:

| Expansion | Base cards | v1.13 rows | Promo rows |
|---|---:|---:|---:|
| METW | 484 | 492 | 8 |
| METD | 180 | 184 | 4 |
| MEDM | 180 | 183 | 3 |
| MELE | 417 | 419 | 2 |
| MEBA | 104 | 104 | 0 |
| MEAS | 170 | 170 | 0 |
| MEWH | 122 | 122 | 0 |
| **Total** | **1,657** | **1,674** | **17** |

This resolves the earlier 484/492/500 catalogue-count confusion: 1,657 is the base expansion total, 17 v1.13 rows are promotional printings, and the 500-entry Card Hunters HQ list is a broader Council of Elrond database mirror. TW IDs differ between v1.13 and the CoE database; join by normalized card name and printing metadata, never by numeric TW ID alone. See [the reconciliation CSV](../data/catalogue-expansion-reconciliation.csv).


## 6 November 2026 — official promo catalogue reconciliation

The current Council of Elrond data and Card Hunters HQ set checklists report 1,683 records across the seven expansions. This is nine above the v1.13 workbook's 1,674 card-ID rows.

The difference is eight official ICE promo entries plus TW-500, the separate Lure of MECCG event promo. TW-500 is not an original ICE card and is excluded. The working official ICE catalogue therefore rises to 1,682 physical card/printing records, subject to scan-level verification of eight older promo-variant printings.

| Expansion | Base cards | v1.13 IDs | Current catalogue IDs | ICE promo printings in working count |
|---|---:|---:|---:|---:|
| METW | 484 | 492 | 500 (499 after excluding TW-500) | 15 |
| METD | 180 | 184 | 185 | 5 |
| MEDM | 180 | 183 | 183 | 3 |
| MELE | 417 | 419 | 419 | 2 |
| MEBA | 104 | 104 | 104 | 0 |
| MEAS | 170 | 170 | 170 | 0 |
| MEWH | 122 | 122 | 122 | 0 |
| **Total** | **1,657** | **1,674** | **1,682 eligible** | **25** |

The eight additional ICE promo IDs are TW-493 Neeker-breekers, TW-494 Black Arrow, TW-495 Fatty Bolger, TW-496 The Iron Crown, TW-497 A Pack at the Door, TW-498 Swordmaster, TW-499 Dwarven Axe and TD-185 Belegennon. The 2007 Full Spoiler List identifies the standard English promos and nine special German promos.

The complete P-row audit, including the excluded TW-500 Lure event promo and the older promo-variant rows, is in [promo-card-inventory-2026-11-06.csv](../data/promo-card-inventory-2026-11-06.csv). Expansion-level counts are in [catalogue-expansion-reconciliation.csv](../data/catalogue-expansion-reconciliation.csv).

This is a catalogue/printing update only. It does not change Gandalf Gene, Jose-san or Arda Intro Game deck quantities.

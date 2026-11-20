---
layout: default
title: Research Watch — 20 November 2026
---

# Arda research watch — 20 November 2026

## Result

No new independently validated ICE-only Hero Arda card-pool spreadsheet or complete deck file was found in this pass. The useful progress is a completed expansion-level reconciliation of the already normalized 2024 **Arda Intro Game** pools, plus a practical clarification about how site cards should be stored in different Arda variants.

## 1. Completed expansion reconciliation: Arda Intro Game (2024)

The source is Jared Brayshaw's [Arda Intro Game PDF](https://www.councilofelrond.org/forum/download/file.php?id=4315), already normalized in the project as 727 row-level records across two variants. I re-summed the row-level CSV independently by variant, expansion, section and printing status.

### METW + METD — no-rares variant

This is a teaching Arda pool with its own piles, not a conventional constructed Hero deck.

| Expansion | Physical copies |
|---|---:|
| The Wizards (METW) | 461 |
| The Dragons (METD) | 93 |
| **Total** | **554** |

The author's printed total is 505. The difference is 49 MP-paired site cards that the PDF says accompany MP resources but does not include in the printed subtotal. The 554 total is the physical card-component count.

### All-rarities-and-sets variant

| Expansion | Assigned physical copies |
|---|---:|
| The Wizards (METW) | 514 |
| The Dragons (METD) | 89 |
| Dark Minions (MEDM) | 15 |
| The Lidless Eye (MELE) | 6 |
| Against the Shadow (MEAS) | 1 |
| **Assigned subtotal** | **625** |
| Cross-set expansion unresolved | **69** |
| **Physical total** | **694** |

The 69 unresolved copies are not missing cards. They are 23 hazard rows at three copies each where the source list gives a card name that exists in more than one candidate expansion:

- 57 copies have METW / MELE as candidate printings.
- 12 copies have METD / MELE as candidate printings.

These rows must remain unassigned to a single expansion until the source printing is established. The 625 assigned copies include four confirmed official promo copies and 14 METW copies whose base-versus-promo printing is unspecified. The 14 ambiguous METW printing copies are Dark Quarrels ×3, Escape ×3, Test of Form ×3, Pick-pocket ×3, Quickbeam ×1 and Boromir II ×1.

The author's printed total is 606. The additional 88 MP-paired site cards bring the physical component count to 694.

### What this changes — and what it does not

- We can now give expansion totals for both Intro Game variants without treating the unresolved 69 as if they belonged to one expansion.
- The no-rares variant is fully assigned to METW and METD at 461 / 93 copies.
- The all-rarities variant has 625 copies assigned by expansion and 69 that remain cross-set ambiguous.
- These totals include the separate site cards paired with MP resources. They are not comparable as if they were just a Play Deck.
- Neither variant is a replacement for Gandalf Gene's canonical Hero Arda list. Do not merge their quantities into Gene or Jose-san.

Source files:
- [Row-level 727-record inventory CSV](../data/arda-intro-game-card-inventory.csv)
- [Expansion and pile summary CSV](../data/arda-intro-game-expansion-summary.csv)
- [Sources & Downloads](sources.html)
- [Comparison Lists](comparison-lists.html)

## 2. Physical site-card handling differs by variant

Arda Rules 4.0 Basic Game describes a separate Site Deck: each player ideally brings their own, or the group uses one shared site deck and tracks visited/tapped/discarded sites. See the [published Arda Rules 4.0 PDF](https://lureofmiddleearth.com/wp-content/uploads/2016/03/arda_4.0_en.pdf).

The 2024 Arda Intro Game is different: it pairs each MP resource with a site card. The paired sites are additional physical cards, which explains the 49- and 88-card differences between the author's printed totals and the physical totals above. Keep each pair together if using that variant.

A related practical discussion appears in the BGG [Arda Revised file page](https://boardgamegeek.com/filepage/98645/arda-revised). In August 2022, a player asked how to handle a site card sleeved with an MP card. In a follow-up, the player reread the rule and concluded that the site is considered tapped for that company, but the site card itself is not physically tapped. This is a community interpretation attached to Arda Revised, not a universal Basic Game rule. It supports keeping the site-pair method explicitly tied to the ruleset being used.

## 3. Cross-check against Gandalf Gene

I compared the all-rarities Intro Game inventory against the explicit-quantity rows in Gandalf Gene using normalized card name plus expansion. This is a screening comparison; it preserves unresolved printings and does not merge quantities.

| Comparison result | Identities | Copies |
|---|---:|---:|
| Shared name + expansion | 298 | 514 Intro Game / 525 Gene |
| Intro Game-only, expansion resolved | 77 | 111 |
| Gene-only, absent from resolved Intro rows | 76 | 174 |
| Intro Game hazard names with expansion unresolved | 23 | 69 |

Fourteen of the 298 shared identities have different quantities between the two sources. The total difference across those 14 is 11 fewer copies in Intro Game than Gene. The row-level comparison CSV records both quantities and each identity's status.

All 23 expansion-ambiguous Intro Game hazard names also occur in Gene. Gene assigns each to METW or METD, which is one of the Intro Game candidate expansions. This makes the Gene list a useful clue, but not proof of the Intro Game's actual printing. The 69 copies remain unresolved rather than being assigned by assumption.

[Download the 474-row comparison CSV](../data/arda-intro-game-vs-gandalf-gene-comparison.csv) · [Open the comparison-lists page](comparison-lists.html#4-november-2026--arda-intro-game-row-level-normalization).

## 4. User-supplied BGG thread remains inaccessible

The [BGG discussion titled “Arda”](https://boardgamegeek.com/thread/1426276/arda) supplied by the user remains a useful research lead, but direct retrieval returns HTTP 403. The current [BGG XML API documentation](https://boardgamegeek.com/using_the_xml_api) describes an endpoint for retrieving an individual thread, but BGG's current API policy requires an approved application and bearer-token authorization. No authenticated BGG token is available in this research environment, so the thread's posts and attachments cannot yet be inspected. No claims or quantities are attributed to it.

## 5. Downloadable source checks

The current [MeCCG Lists and Downloads page](https://meccg.com/cards/lists-and-downloads/) still exposes these useful downloads:

- [MeCCG List of Cards — XLS](https://meccg.es/meta/cards/list/MeCCG%20List%20of%20Cards.xls) — direct link verified; binary not parseable by the current browser retrieval.
- [Full Spoiler List — PDF](https://meccg.es/meta/cards/MeCCG%20Full%20Spoiler%20List.pdf) — expansion-organized card reference; compiled by Black Council of Mordor and updated February 2007. Useful for historical card identity/type/rarity cross-checks, not Arda quantities or current errata.
- [Fixed Sets — PDF](https://meccg.es/meta/cards/list/Fixed%20Sets.pdf) — product composition reference, not an Arda pool.
- [Challenge Decks — ZIP](https://meccg.es/meta/cards/list/Challenge%20Decks.zip) and [Challenge Deck player aid PDF](https://meccg.es/meta/cards/list/MECCG-CD-playeraid_v1.0.pdf) — conventional preconstructed deck references, not Arda shared pools.

No newly verified Arda-specific XLS/XLSX or standalone deck file was found today.

## 6. Canonical Gene baseline unchanged

The original Gandalf Gene workbook remains the primary fixed Hero Arda quantity source:

| Expansion | Explicit copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

CCG Collector's 3 June 2020 community summary remains 695 copies, leaving a four-copy discrepancy. Army of the Dead and The White Tree still have blank quantity fields in the original Gene workbook. The static 691-copy Desglose tab remains stale. No Gene quantities were changed.

## Next research steps

1. Obtain Thorondor's 2015 [Arda Sample Deck — no rares XLS](https://www.councilofelrond.org/forum/download/file.php?id=4091) or a complete export of BanalityBob's 2020 Google Sheet for a genuinely independent row-level comparison.
2. Resolve the 69 Intro Game hazard copies to specific printings only if source evidence identifies the chosen expansion; do not guess from name alone.
3. Continue tracing the 699-versus-695 Gene discrepancy and the two blank Gene quantities.
4. If the BGG “Arda” thread's contents or attachments become available, add only verified material to the source comparison.

**No user decision is required for this pass.**

## Project links

- [Arda research website](../)
- [Build and sort physical Arda decks](building-arda-decks.html)
- [Card inventory](card-inventory.html)
- [Source reconciliation](source-reconciliation.html)

---
layout: default
title: Source watch — 29 October 2026
---

# Source watch — 29 October 2026

## Summary

This pass added a clearly identified **Arda Rules 4.0** reference and compared its recommended shared-pool structure with the existing Gandalf Gene Arda list. It also used the Council of Elrond card database to verify five card identities and expansion assignments already under reconciliation.

**No new standard Hero Arda spreadsheet with card quantities by expansion was found. The canonical physical-copy totals therefore remain unchanged.**

## New rules reference: Arda Rules 4.0

- **Source:** [Middle Earth: The Arda Game — Concept, Rules and Tips, version 4.0 (PDF)](https://lureofmiddleearth.com/wp-content/uploads/2016/03/arda_4.0_en.pdf)
- **Credits shown in the PDF:** concept by Joe Bisz; design by Joe Bisz and Eric Dané.
- **Format:** 25-page PDF. This is a published rules reference, not a card-by-card inventory spreadsheet.
- **Scope:** shared-deck Arda for 2–7 players, with Basic Arda rules and optional Expanded World / scenario variants.

The Basic Arda rules describe these shared piles:

1. Play Deck — hazards and non-Marshaling-Point resources.
2. Marshaling Points Deck — resources that yield MPs.
3. Roving Character Deck.
4. Minor Item Offering Deck.
5. Site cards / Site Deck.

The document offers approximate sizing guidance rather than a fixed canonical list:

- Play Deck: about 50 cards per player; a standard deck is 250+ cards, with equal numbers of resources and hazards.
- MP Deck: at least 15 cards per player; often around 100.
- Roving Character Deck: around 70 characters for larger games.
- Minor Item Offering Deck: around 30–35 cards, with a suggested two copies of each minor item.

These are general Arda construction guidelines, not a new authoritative quantity list.

## Comparison with Gandalf Gene and other pools

| Feature | Arda Rules 4.0 guidance | Gandalf Gene list in this project |
|---|---|---|
| Main design | Shared-pool multiplayer format | A specific published Arda build |
| Play Deck size | 250+ cards as a general guide | 423 listed cards |
| Play Deck composition | Equal numbers of resources and hazards recommended | 171 resources and 252 creatures/hazards in the current transcription |
| Quantity authority | General sizing guidance only | Card-by-card quantities in the original workbook, with an unresolved summary mismatch |
| What it contributes | A baseline for judging whether a pool follows the general format | The concrete list whose quantities are being audited |

The unequal 171/252 split in the Gandalf Gene transcription does not match the general 1:1 recommendation in Rules 4.0. That is a real comparison point to preserve, not a reason to alter the original quantities. The Gene list should remain identified as its own published build until its original workbook and rules context show otherwise.

The rules PDF is multiplayer-oriented. It should not be treated as the solo ruleset: the 2013 solo-Arda experiment documented in the [28 October source watch](research-watch-2026-10-28.html) is a separate adaptation, and normal constructed-deck solo play is a third approach.

## Official card-metadata cross-check

The [Council of Elrond card database](https://github.com/council-of-elrond-meccg/meccg-cards-database) contains card IDs, set codes, types, alignment, rules text and rarity/distribution metadata. Targeted checks in its downloadable [cards.json](https://raw.githubusercontent.com/council-of-elrond-meccg/meccg-cards-database/master/cards.json) confirm these assignments:

| Card | CoE database ID | Set code | Metadata check |
|---|---|---|---|
| Army of the Dead | TW-193 | TW | Hero Resource; rarity R |
| The White Tree | TW-348 | TW | Hero Resource; rarity R |
| Peril Returned | TD-54 | TD | Hazard; raw rarity code C2 |
| Uruk-lieutenant | LE-96 | LE | Hazard Creature; rarity R |
| Wild Trolls | LE-100 | LE | Hazard Creature; raw rarity/distribution code CB+CS1 |

The inventory CSV now records the CoE IDs and verified metadata for these five rows. The two cards with blank source quantities remain quantity-unknown; metadata verification does not justify inventing a count. The raw code CB+CS1 is retained without forcing it into the inventory's simpler Common/Uncommon/Rare vocabulary.

**Limitation:** the full 4.16 MB JSON file could not be loaded as a single parseable file through the current GitHub connector. The five targeted records were checked through the web-rendered raw file, but a complete automated match of every inventory row against all CoE records remains outstanding.

## Downloadable spreadsheets and deck files checked

| Resource | Format | Appropriate use | Limitation |
|---|---|---|---|
| [Arda Rules 4.0](https://lureofmiddleearth.com/wp-content/uploads/2016/03/arda_4.0_en.pdf) | PDF | Rules and general pile-sizing baseline | Not an exact card list |
| [Council of Elrond cards.json](https://raw.githubusercontent.com/council-of-elrond-meccg/meccg-cards-database/master/cards.json) | JSON | Card IDs, set codes, text and metadata | No Arda copy quantities |
| [Council of Elrond changes-guide.xlsx](https://github.com/council-of-elrond-meccg/meccg-cards-database/blob/master/changes-guide.xlsx) | XLSX | Errata / text-change reference | Not an Arda pool |
| [MeCCG List of Cards](https://meccg.es/meta/cards/list/MeCCG%20List%20of%20Cards.xls) | XLS | Independent catalogue cross-check | Version and coverage still need validation |
| [MeCCG character list](https://meccg.es/meta/cards/list/meccg-characters.xlsx) | XLSX | Character metadata cross-check | Not a complete Arda pool |
| [Challenge Decks list](https://meccg.es/meta/cards/list/Challenge%20Decks.zip) | ZIP | Challenge Deck card-list files | Reference decks, not Arda quantities |
| [Challenge Decks player aid](https://meccg.es/meta/cards/list/MECCG-CD-playeraid_v1.0.pdf) | PDF | Card-by-card cross-check for the ten Challenge Decks | Not an Arda deck |
| [BoardGameGeek MECCG file archive](https://boardgamegeek.com/boardgame/1915/middle-earth/files) | Mixed files | Includes the 2010 v1.13 card-list XLS, starter-deck list XLS and a known Arda example PDF | The Arda example is not a verified quantity-by-expansion spreadsheet |
| [MeCCG published deck database](https://meccg.com/decks/) | Web deck records | Constructed-deck examples and card-name cross-checks | The published decks found here are not automatically Arda lists |

The MeCCG download page and the Council of Elrond repository provide useful independent metadata and deck references. None supplies a replacement quantity authority for the Gandalf Gene workbook.

## Canonical quantity status — unchanged

| Expansion | Explicit copies |
|---|---:|
| The Wizards (METW) | 552 |
| The Dragons (METD) | 108 |
| Dark Minions (MEDM) | 32 |
| The Lidless Eye (MELE) | 6 |
| The Balrog (MEBA) | 1 |
| **Total** | **699** |

The source workbook's published summary still states **695**, so the four-copy discrepancy remains unresolved. Army of the Dead and The White Tree still have blank quantity fields. The five metadata checks above do not change any copy counts.

## Next concrete work

1. Recompute the original workbook's category subtotals and locate the four-copy difference.
2. Obtain a locally parseable copy of the full Council of Elrond JSON or catalogue XLS and match the complete inventory by card identity, set and rarity.
3. Continue matching all rows against the independent Gandalf Gene transcription.
4. Keep the standard Arda, solo-Arda and constructed-deck solo variants separately labelled.

**Input needed:** none for this research step.

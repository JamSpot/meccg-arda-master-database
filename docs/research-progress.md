# Research Progress

## Current stage
The original Gandalf Gene workbook and a separate Jose-san Arda workbook are parsed and compared. The full local MECCG Card List v1.13 catalogue has 1,674 original ICE card-ID rows across the seven official expansions: 1,657 base expansion cards plus 17 promo rows; 48 N/A-ID sourcebook scenario/site entries are excluded. The 2024 Arda Intro Game PDF is now normalized against the current Council of Elrond card database: 727 row-level records across two variants, with no unmatched card identities after spelling/abbreviation aliases. Its physical totals are 554 (METW+METD no-rares) and 694 (all rarities); 69 all-rarities hazard copies remain cross-set ambiguous. The canonical Gene inventory remains 699 explicit copies versus CCG Collector's independent 695-copy community summary; the static 691 Desglose tab remains stale. No Intro Game quantities have been merged into Gene. The Council of Elrond Rules Committee cards.json and changes-guide.xlsx are now recorded as the current errata/text reference, while the MeCCG downloads page and independent metw.net/CollecCards catalogues provide additional metadata cross-checks.

## Confirmed from the extracted Gandalf Gene workbook
- 377 named card rows after excluding title/header structure.
- 375 rows have numeric quantities.
- 374 distinct names among numeric rows because Nenseldë the Wingild appears twice; the two blank-quantity rows bring the unique named identity count to 376.
- Numeric quantity sum: 699. CCG Collector's 3 June 2020 Council post independently reports 695, leaving +4 unresolved. The Gene workbook's static Desglose table actually sums to 691 and is stale; its categories match the separate Jose-san pool, not the current Gene card rows.
- Army of the Dead and The White Tree have blank quantity fields; independent catalogue identifies both as METW.
- Peril Returned (3 copies) is corrected from MEDM to METD; Uruk-Lieutenant and Wild Trolls (3 copies each) are corrected from MEDM to MELE. v1.13 confirms their rarities as Common, Rare and Common respectively for Peril Returned, Uruk-Lieutenant and Wild Trolls.
- Verified expansion copies are METW 552, METD 108, MEDM 32, MELE 6 and MEBA 1; total remains 699.
- Published expansion distinct counts 300 + 59 + 14 + 2 + 1 sum to 376, matching the working unique named identities. CCG Collector's headline says 377; the duplicate Nenseldë row may explain the headline difference, but that counting convention is not confirmed.

## Completed
- Added a [reconciliation log](reconciliation-log.html) with the count bridge and named anomalies.
- Added a machine-readable [expansion checksum CSV](../data/expansion-checksums.csv).
- Added the [inventory data method](card-inventory-method.html).
- Published the [card-by-card working inventory](card-inventory.html) and [downloadable CSV](../data/gandalf-gene-arda-card-inventory.csv).
- Added the [24 October 2026 source watch](research-watch-2026-10-24.html), including the Samwise deckbuilding tool and BGG file-format clarification.
- Added the [25 October 2026 source watch](research-watch-2026-10-25.html), documenting direct MeCCG catalogue downloads for independent card identity, expansion and rarity checks.
- Added the [26 October 2026 source watch](research-watch-2026-10-26.html); its earlier non-standard variant material was removed from active research on 2 November under the official-ICE-only scope.
- Added the [27 October 2026 source watch](research-watch-2026-10-27.html), verifying current official card database download artifacts, tracking recent BGG Arda discussion leads, and recording three independent expansion corrections.
- Added the [28 October 2026 source watch](research-watch-2026-10-28.html), documenting a previously untracked 2013 solo-Arda build with a session report and comparing its pile structure with the canonical format.
- Added the [29 October 2026 source watch](research-watch-2026-10-29.html), documenting Arda Rules 4.0's general pile-sizing guidance, contrasting it with the 423-card Gandalf Gene Play Deck, and adding five targeted CoE card-metadata checks to the inventory.
- Added the [30 October 2026 source watch](research-watch-2026-10-30.html), cataloguing the 2014 Arda Revised rules, the 2023–24 Hero compiled ruleset, Thorin's Wizards/Dragons treasure-travel aid, the 2022 Spanish solo-Arda variant, and the BGG Arda deck example XLS lead. Corrected the source register's earlier PDF label for that XLS.
- Added the [31 October 2026 source watch](research-watch-2026-10-31.html), parsed the local Jose-san ARDA.xls candidate, created a 322-row strict Hero/Neutral/Avatar alignment-filtered comparison CSV, identified the source of the 695-copy figure, and corrected the stale Gene Desglose attribution.
- Added the [4 November 2026 source watch](research-watch-2026-11-04.html), normalized both Arda Intro Game sample pools against official card IDs, added a 727-row card inventory CSV and an expansion summary CSV, counted the additional MP-paired site cards, and isolated 69 cross-set ambiguous hazard copies plus promo-printing uncertainties.

- Added the 31 October Council of Elrond discussion context: Hero and Minion Arda are separate pool designs, and community commentary suggests Dragon Ahunt/Drake omissions in the Gene hazard mix may be intentional balance curation rather than extraction gaps.

- Added Kober's separate Arda Solitaire v0.2 rules PDF (2015) and a 2016 comparison with Callasmar's site/card pairing approach; it is a solo-rules source, not a quantity list, and its PDF binary remains unavailable for extraction.

- Identified a downloadable 83.5 KiB bilingual Arda Sample Deck_no rares.xls by Thorondor (20 July 2015), a low-rarity METW/METD/MEDM comparison pool. The attachment is listed but not yet retrievable for row-level extraction.

- Parsed the full local MECCG Card List v1.13 workbook (1,674 official card-ID rows across seven ICE expansions; 48 N/A-ID sourcebook entries excluded) and matched all 377 Gandalf Gene rows and all 370 Jose-san rows; corrected six Gene metadata exceptions, added `data/catalogue-v1-13-audit.csv`, and marked every inventory row's catalogue match status without changing quantities.

## Latest source-watch result — 4 November 2026

- Normalized Jared Brayshaw's 2024 Arda Intro Game PDF against the current Council of Elrond cards.json (latest repository commit message: CRF 22 applied). Created a 727-row inventory covering both variants, MP resources, MP-paired sites, characters, minor items, rings, avatars and Haven sites.
- Reproduced the author's 505/606 listed totals, then counted the additional 49/88 MP-paired site cards. The resulting physical totals are 554 and 694.
- Expansion totals including paired sites: no-rares METW 461 / METD 93; all-rarities METW 514 / METD 89 / MEDM 15 / MELE 6 / MEAS 1, plus 69 cross-set ambiguous hazard copies.
- Identified four confirmed METW promo copies in the all-rarities pool and 14 further copies where base-versus-promo printing is unspecified. The no-rares pool has 13 such copies. The Arkenstone row is resolved to Hero TW-341; the Minion promo LE-418 is not used.
- Confirmed that Dreams of Lore (TW-210) is an original ICE Hero card, not a Dream Card. No Dream Cards, custom cards or Minion Arda decklists were imported.
- Rechecked current Arda forum topics: the newest 2026 topic is a Dream Card/Minion variant and is excluded. BanalityBob's public sheet currently exposes only seven populated rows in the browser view; it is not a complete quantity source in this pass.
- The 699 explicit Gandalf Gene copies versus CCG Collector's 695 remain unresolved. No canonical Gene quantities changed.

## Latest source-watch result — 2 November 2026

- Added the Council of Elrond Rules Committee's current cards database: 4,163,611-byte cards.json and 22,147-byte changes-guide.xlsx. The latest repository commit is 19 May 2026 (“CRF 22 applied”); its README says approximately 300 card texts have been updated. This is the current errata/text reference, not an Arda quantity source or literal original-print transcription.
- Added direct MeCCG.com downloads: the MeCCG List of Cards XLS, character-list XLSX, Challenge Decks ZIP, full spoiler PDF, fixed-set PDF and Challenge Deck player aid PDF. These are catalogue or product references, not new Arda quantity lists.
- Added metw.net's seven expansion cardlist PDFs. Their stated totals are METW 484, METD 180, MEDM 180, MELE 417, MEBA 104, MEWH 122 and MEAS 170. They provide historical card-category and rarity/distribution checks, not Arda quantities. Reparsed v1.13 by set code: 1,674 original ICE card-ID rows across the seven official expansions, plus 48 N/A-ID sourcebook scenario/site entries that are excluded. The metw.net PDFs are 17 lower across METW/METD/MEDM/MELE because v1.13 includes 17 promo rows; removing those rows produces an exact match to the 1,657-card base expansion counts.
- Added CollecCards' searchable English catalogue with set code, name, rarity, type and notes. Repeated entries include alignment-specific versions and Challenge Deck entries; they are not quantities to sum.
- Rechecked current searches for new standard Arda decklists. No new standard Hero Arda XLS/deck file was verified. BanalityBob's spreadsheet and Thorondor's no-rares XLS remain the highest-priority unparsed list leads.
- Enforced the user's scope: original, officially published ICE cards only. Dream Cards, fan-made/custom cards, unreleased cards and proxies are excluded. No quantities have been changed.
- Canonical Gandalf Gene quantities remain METW 552, METD 108, MEDM 32, MELE 6 and MEBA 1 = 699. The four-copy difference versus CCG Collector's 695 remains unresolved.

## Previous source-watch result — 31 October 2026
- Parsed the local ARDA.xls workbook, a high-confidence candidate for BGG's Jose-san Arda deck example XLS. It has 370 unique names / 691 copies across all alignments.
- Excluded 48 Minion-alignment rows / 68 copies from the project's Hero comparison. The Hero/Neutral/Avatar subset has 322 names / 623 copies, with expansion totals METW 410, METD 126, MEDM 48, MELE 12, MEAS 18, MEWH 6 and MEBA 3.
- Compared the subset with Gandalf Gene: 242 shared names, 80 Jose-only, 134 Gene-only and 29 shared-name quantity differences. Added a downloadable card-by-card comparison CSV.
- Identified CCG Collector's 3 June 2020 Council of Elrond post as the source of the 377 / 695 community summary. The 695 figure is not in the Gene workbook's Desglose tab.
- The Gene workbook's static Desglose table totals 691 and matches the Jose-san category table, including Minion categories absent from the Gene card rows. Treat it as stale, not as a Gene checksum.
- Found a La BSK 2014–2017 solo-Arda pool lead and a linked Google Docs list; automated extraction returned HTTP 410, so no quantities were adopted.
- Canonical Gene quantities remain METW 552, METD 108, MEDM 32, MELE 6 and MEBA 1 = 699. The +4 difference versus CCG Collector's 695 remains open. No user input is needed.

## Previous source-watch result — 30 October 2026
- Found additional BGG Arda resources: Arda Revised (2014 PDF); Compiled Arda Ruleset — Hero (2023, revisions through 13 March 2024); Thorin's Travel Guide to Treasure (2023 PDF, explicitly The Wizards and The Dragons only); and a Spanish Arda summary with a solitaire version added in November 2022.
- Corrected the BGG archive format for **Arda deck example** by Jose-san: the archive lists it as **XLS**, not PDF. The workbook attachment was not retrievable for extraction in this pass, so it has not yet been compared card-by-card or used to change any quantities.
- The Hero compiled ruleset is a community compilation with optional variants, not an official Council of Elrond ruling. The travel guide is a site/item aid, not an inventory. The Spanish file is a separate language-specific solo variant.
- No newly found file establishes a replacement canonical quantity list. Explicit quantities remain METW 552, METD 108, MEDM 32, MELE 6 and MEBA 1 (699 total), versus CCG Collector's published 695 community summary. Army of the Dead and The White Tree remain blank-quantity rows.
- No user decision is required for this pass.

## Previous source-watch result — 29 October 2026
- Added the published [Arda Rules 4.0 PDF](https://lureofmiddleearth.com/wp-content/uploads/2016/03/arda_4.0_en.pdf). It describes shared-deck multiplayer Arda (2–7 players) and recommends a 250+ Play Deck with equal resources/hazards, about 15 MP cards per player, a character pool of about 70 for larger games, and a 30–35 card Minor Item Offering Deck.
- The 1:1 resource/hazard recommendation differs from the current Gandalf Gene transcription (171 resources and 252 creatures/hazards). This is a rules/build comparison; do not alter the source quantities without evidence.
- Targeted Council of Elrond database checks verified TW-193 Army of the Dead, TW-348 The White Tree, TD-54 Peril Returned, LE-96 Uruk-lieutenant and LE-100 Wild Trolls. The inventory now records card IDs and metadata; source quantities for Army of the Dead and The White Tree remain blank.
- Identified direct downloads for MeCCG's character XLSX, Challenge Decks ZIP and Challenge Decks player-aid PDF. These are catalogue/Challenge Deck references, not new Arda quantity sources.
- No new standard Hero Arda spreadsheet or exact deck file was found. The 699 explicit copies versus CCG Collector's 695 community summary remains unresolved.
- The full 4.16 MB CoE JSON could not be loaded as one parseable file through the current GitHub connector, so the full automated match remains outstanding.

## Previous source-watch result — 28 October 2026
- Found [My Solo Arda Build with Session Report](https://boardgamegeek.com/thread/1058232/my-solo-arda-build-with-session-report), published 22 October 2013 and edited with additional turns in November 2013. It describes separate MP, Ring, Resource, Minor Item, two Character, Hazard and Site decks, generally using one of each owned card plus selected multiples. It excludes Lidless Eye, White Hand and Balrog.
- This is a meaningful solo-method comparison but not an exact decklist: no card-by-card quantities, spreadsheet or downloadable deck file were verified. It must not be used to change canonical card counts.
- The original Gandalf Gene workbook remains the canonical quantity source. Its 699 explicit copies still conflict with CCG Collector's published 695 community summary.
- Compared the locally archived MECCG_Card_List.xlsx: 144 catalogue rows, 45 normalized name overlaps, and no rarity values. It is too partial to establish the full pool or override set assignments; it does not resolve quantities.
- No user decision is required for this research step.

## Previous source-watch result — 27 October 2026
- Cross-checked five expansion assignments against an independent catalogue: Army of the Dead and The White Tree are METW; Peril Returned is METD; Uruk-Lieutenant and Wild Trolls are MELE. This corrects working metadata while preserving all quantities.
- Verified the Council of Elrond official card database repository has a latest commit dated 19 May 2026 (CRF 22 applied) and contains a 4,163,611-byte `cards.json` plus a 22,147-byte `changes-guide.xlsx`. The JSON was too large for the connector's content-fetch limit, so full machine matching remains outstanding.
- Flagged three BGG community leads: a modular solo/Arda/variants thread (shown as 23 days old), a request for ARDA card lists (21 days old), and the Gen Con 2026 Arda thread (four months old, 24 replies). BGG thread access was blocked, so no new attachment or quantity source was verified.
- Corrected distinct-card counts now align with the published expansion subtotals at 376 unique identities. The headline 377 likely counts duplicate Nenseldë twice. The physical-copy total remains 699 versus the published 695.

## Previous source-watch result — 26 October 2026
- The earlier 26 October source-watch entry for non-physical/custom Arda material has been superseded by a scope correction. Such material is no longer catalogued or compared in this project.
- Reconfirmed the available downloads: BGG's MECCG Card List v1.13 XLS and Starter Set Decks Lists XLS, BGG's Arda example PDF, plus MeCCG's direct card catalogue XLS, Full Spoiler PDF and Fixed Sets PDF.
- No new standard Hero Arda quantity source resolves the discrepancy. Explicit quantities remain 699 versus the published 695.

## Previous source-watch result — 25 October 2026
- MeCCG's downloads page links a separate [MeCCG List of Cards XLS](https://meccg.es/meta/cards/list/MeCCG%20List%20of%20Cards.xls), a [Full Spoiler List PDF](https://meccg.es/meta/cards/MeCCG%20Full%20Spoiler%20List.pdf) and a [Fixed Sets PDF](https://meccg.es/meta/cards/list/Fixed%20Sets.pdf).
- The XLS is a candidate cross-check for card identity, expansion and rarity; its version/date and actual coverage have not yet been verified. The spoiler PDF states it was updated in February 2007.
- These are reference/catalogue resources, not Arda quantity lists. No newly found downloadable Arda spreadsheet or alternate canonical pool changes the inventory baseline.
- The 699 explicit-copy total versus the published 695 summary remains unresolved.

## Next concrete work
1. Retrieve and parse Thorondor's 83.5 KiB Arda Sample Deck_no rares.xls as an independent low-rarity pool comparison.
2. Confirm the local Jose-san ARDA.xls against the BGG attachment, ideally by binary hash or direct file comparison.
3. Retrieve the La BSK Google Docs pool and Kober's Arda Solitaire v0.2 PDF; both remain blocked at the binary/document extraction stage.
4. Trace the four-copy difference between the 699 explicit Gene rows and CCG Collector's 695 community summary; treat the static 691 Desglose tab as stale.
5. Obtain a parseable copy of the Council of Elrond `cards.json` or catalogue XLS, then match every source row by identity, expansion and rarity.
6. Match all source rows to the independent transcription, resolve remaining identity/rarity anomalies, and produce an audited physical-card acquisition table with provenance for every quantity.

## Status labels
- Verified — identity and source fields checked.
- Source discrepancy — source summaries disagree.
- Needs reconciliation — row-level investigation remains.
- Variant — belongs to another Arda list/ruleset.
- Excluded — outside canonical project scope.


## 8 November 2026 — Challenge Deck reference-source audit

- Added a dated research watch and updated the homepage and Sources & Downloads register.
- Checked the current MeCCG card-list XLS, Fixed Sets PDF, Challenge Decks ZIP and Challenge Deck player aid. The PDF references are readable; the XLS and ZIP binaries remain unavailable for extraction in this environment.
- Inspected all ten plaintext Challenge Deck `.deck` files in Samwise. The main A-deck quantities match the player aid, but A–E sideboards are one card short in the `.deck` files because the separately listed backup Wizard is absent. Prefer the player aid for complete Challenge Deck lists.
- These are conventional Challenge Deck/product references, not Arda shared pools. No Dream Cards or custom cards were imported.
- **Arda quantity result: no change.** Gandalf Gene remains at 699 explicit copies; the 695 comparison and two blank quantities remain unresolved.


## Latest source-watch result — 9 November 2026

- Identified two recent BoardGameGeek hot-thread leads: “Turning MECCG into a Modular Solo Board Game – ARDA, Variants & Card Lists. Is it possible?” and “Looking for card lists to build ARDA decks,” both by proxegentyc and listed as roughly three weeks old. Direct BGG thread access returned HTTP 403; thread contents and attachments are unverified, so neither is treated as a card list.
- Verified the official Gen Con 2026 listing for a 4–18 player shared-deck Hero Arda event. The organizer said almost all cards would be official versions rather than Virtuals. This is evidence of active physical-card play, not a card-pool source.
- Rechecked Arda Rules 4.0 as the published general format reference; its 250+ Play Deck and balanced resource/hazard guidance are sizing recommendations, not a fixed list.
- No new downloadable Arda card pool or deck file was verified. Gandalf Gene remains 699 explicit copies versus CCG Collector's 695; the two blank quantity rows remain unresolved. No quantities changed.


## Latest source-watch result — 12 November 2026

- Reviewed the 46-topic Council of Elrond Arda forum index and rechecked the available original-card Hero Arda leads. Recent 2025–26 topics are Dream Card / Minion variants and remain excluded.
- Identified the 2010 “Cards for Arda Expanded World” printable archive, including a 1.77 MiB character ZIP and associated MSE/PDF card files. The thread describes community-created custom cards, not ICE releases; recorded as an explicit exclusion and did not import any card identities or quantities.
- Reviewed the 2023 Arda Co-op proposal. It describes an eight-pile cooperative variant based on Gandalf Gene, but supplies no complete decklist or expansion counts.
- Rechecked BanalityBob's public Google Sheet; the accessible preview remains incomplete, so no quantities were adopted.
- The canonical Gandalf Gene inventory remains 699 explicit copies (METW 552, METD 108, MEDM 32, MELE 6, MEBA 1) against CCG Collector's 695-copy report. The four-copy discrepancy and blank quantities for Army of the Dead / The White Tree remain unresolved.


- Reviewed the user-supplied Council of Elrond attachment **Arda Rules 5.1.pdf** (attachment 466; 32 pages; posted 28 May 2012). Confirmed provenance and version history from the original forum thread. Recorded Basic Game pile structure, flexible size guidance, setup, hazard-passing threshold and separate 20-MP Basic / 25-MP Expanded World Council thresholds. The Ring Special Item Deck is the standout Expanded World addition. The PDF is rules-only, not a card-quantity source; its Virtual Card Set 1, custom Arda designs and altered-card text are explicitly excluded from the ICE-only master inventory. No card quantities changed. See [Arda Rules 5.1 source review](arda-rules-5-1-source-review.html).


## Latest source-watch result — 14 November 2026

- Rechecked the Council of Elrond Arda forum index and the current BoardGameGeek files index. The newest Arda forum lead is a 23 September 2026 nine-player Dream Card Minion Arda; the BGG Arda-specific file surfaced is the March 2024 *Compiled Arda Ruleset - Hero*, which is rules material rather than a card pool. No new eligible ICE-only Hero Arda XLS/XLSX or deck file was verified.
- Found and reviewed the published *ARDA with Dream Cards — The Houses of the North* list (first posted 3 November 2021; last edited 30 July 2025). It is a Dwarves-themed 888-card Dream Card Arda and includes unreleased-set material. The complete list is text across forum posts, not a separate spreadsheet. It is explicitly excluded.
- Re-audited the user-supplied 2022 Leon workbook. Its category formulas total 974, but the listed quantities sum to 975 because the hazard-creature formula omits one Carrion Birds copy. Exact-name screening against v1.13 matched 803 of 898 names; 95 unresolved names carry 112 copies. Several of those names are confirmed Dream Card entries, so the workbook is not ICE-only and cannot supply reliable expansion totals. No quantities were imported.
- The canonical Gandalf Gene baseline remains 699 explicit copies (METW 552, METD 108, MEDM 32, MELE 6, MEBA 1) against CCG Collector's independent 695-copy report. The four-copy discrepancy and the two blank quantity rows remain unresolved.

See [14 November source watch](research-watch-2026-11-14.html) and [comparison-list audit](comparison-lists.html#leon--2022-arda-pool-user-supplied-mixeduncertain-not-ice-only).
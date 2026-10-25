# saved-inbox.md — reels Marcus saved on Instagram, waiting for the scan (BANK.md step 1b)

Filled by `ig-routine-core/read-saved.sh` (headless render of the private Saved collection
"Viral stuff" with Marcus's own Chrome session — his allowance 2026-09-24; BANK.md guard 4
carve-out), by Marcus pasting links, or by an interactive session on his request. The scan
runs read-saved.sh at the top of step 1b and never reads the collection any other way.
Line shape under `## inbox`: `<shortcode> @<handle> <url>`.
The scan moves each line to `## processed` with the date and the verdict.
Filler rule: skip any shortcode already under `## processed` or already a catalog.md header.
`## re-measure`: catalog entries banked by Marcus's ruling without frames; the scan fetches,
measures tests 5/6, rewrites the entry, and moves the line here as `re-measured`.

## inbox
<!-- empty 2026-10-25: read-saved.sh read 24 on the grid and appended 2 new lines (exit 0); both other creators' reels (not the profile-grid redirect). Gated and moved to ## processed: 0 BANKED, 2 tombstoned. -->
<!-- ⚠⚠ 2026-10-24 — READ-SAVED.SH RETURNED THE WRONG GRID AGAIN (third time: 10-07, 10-14, 10-24). NOT A REAL INBOX; 23 LINES REMOVED.
     read-saved.sh exited 0, "24 on grid, 23 new appended", and all 23 appended lines were @imabgold's OWN reels
     (handle @imabgold on every line, Dd-Ss2PI0PB and Dext2XzpLKs among them). Not gated (test 1 by construction).
     Shortcodes recorded in logs/2026-10-24.log. Not re-run. TODAY'S SAVED READ IS A MISS, not an empty inbox.
     ⚠ FOR MARCUS: make the exit-5 check assert the FINAL URL contains /saved/. -->
<!-- empty 2026-10-22: read-saved.sh read 24 on the grid and appended 3 new lines (exit 0); all three other creators' reels. Gated and moved to ## processed: 0 BANKED, 3 tombstoned. -->
<!-- empty 2026-10-21: read-saved.sh read 24 on the grid and appended 2 new lines (exit 0); both other creators' reels. All 9 lines (7 carried from 10-20's early stop) gated and moved to ## processed: 2 BANKED, 5 tombstoned, 1 ad-skip, 1 burned-skip. -->
<!-- empty 2026-10-18: read-saved.sh read 24 on the grid and appended 1 new line (exit 0). One line cannot be a profile-grid redirect (that appends ~23 of @imabgold's own reels), and the line is another creator's reel. Gated and moved to ## processed: tombstone (tests 2/3/4). ⚠ The exit-5 check still does not assert /saved/ in the final URL. -->
<!-- empty 2026-10-17: read-saved.sh read 24 on the grid and appended 11 new lines (exit 0). Verified by hand: all 11 are other creators (not one is @imabgold's own reel), so the profile-grid redirect did NOT reproduce. All 11 gated and moved to ## processed: 2 BANKED, 8 tombstoned, 1 ad-skip. ⚠ The exit-5 check still does not assert /saved/ in the final URL. -->
<!-- ⚠⚠ 2026-10-14 — READ-SAVED.SH RETURNED THE WRONG GRID AGAIN. NOT A REAL INBOX; 23 LINES REMOVED.
     Exact reproduction of the 2026-10-07 failure. read-saved.sh exited 0 and reported "24 on grid,
     23 new appended", and all 23 appended lines were @imabgold's OWN last-25 reels in exact
     reverse-chronological feed order, including DedNsnBNWSh which was posted this morning. Verified
     by hand against step 0's imabgold media list: 23/23 of the appended shortcodes are his own.
     Instagram served (or redirected to) his PROFILE grid instead of
     instagram.com/imabgold/saved/viral-stuff/901996575663900/. The script's exit-5 check only asks
     whether the rendered page identified his session, and a redirect to his own profile still does,
     so the bad read reports exit 0.
     The 23 lines were NOT gated: @imabgold is Marcus's own account, every line fails test 1 by
     construction, and gating them would have burned the morning. Removed; shortcodes recorded in
     logs/2026-10-14.log. The script was NOT re-run (step 1b: never twice a day, never improvise
     another read). TODAY'S SAVED READ IS A MISS, not an empty inbox.
     ⚠ FOR MARCUS, EIGHTH DAY ASKED AND NOW THE SECOND TIME IT HAS COST A DAY: make the exit-5
     check assert the FINAL URL contains /saved/. The 10-09..10-13 reads were only verifiable
     because they appended 0-1 lines; this one appended 23 and the script still said exit 0. -->
<!-- empty 2026-10-10: read-saved.sh read 24 on the grid and appended 0 NEW lines (exit 0). All 24 are
     already under ## processed, so the backlog is clear and there was nothing to gate from Saved today.
     ⚠ VERIFICATION, since the exit-5 check is still unfixed: a profile-grid redirect (the 10-07 failure)
     would have appended ~24 of @imabgold's OWN shortcodes, NONE of which has ever been processed here or
     catalogued — so a redirect today could not have produced "0 new appended". Zero appends is itself the
     proof the read hit the real collection. ⚠ FOURTH DAY RUNNING, FOR MARCUS: make read-saved.sh's exit-5
     check assert that /saved/ is in the FINAL URL, not just that the page identified Marcus's session.
     Today's negative check happened to be conclusive; on a day with new saves it would not be. -->
<!-- empty 2026-10-09: read-saved.sh read 24 on the grid and appended 1 new line (exit 0). All three live
     lines — today's @salama_win line plus the two @xl_roi / @archetype_origins lines that 10-08's
     "Application request limit reached" 403 left ungated — were resolved and gated this morning and moved
     to ## processed. The backlog is clear. The carryover pair was probed FIRST, before the tag pages, as
     promised. ⚠ THIRD DAY RUNNING, FOR MARCUS: read-saved.sh's exit-5 check still only asks whether the
     rendered page identified Marcus's session, so a redirect to his own profile grid would still report
     exit 0. Today's read was again verified BY HAND against step 0's imabgold last-25 shortcode list
     (DeO37s0AUWk is not one of his own reels). Make the exit-5 check assert /saved/ is in the final URL. -->
<!-- 2026-10-08 — READ-SAVED.SH WORKED CORRECTLY TODAY. Exit 0, "24 on grid, 2 new appended", and the
     two appended lines are genuine saved reels from real creators (@xl_roi, @archetype_origins) — NEITHER
     shortcode is in @imabgold's own last-25, which is the check yesterday's bad read failed. Yesterday's
     profile-grid redirect did NOT reproduce. ⚠ THE SCRIPT IS STILL UNFIXED: its exit-5 check only asks
     whether the rendered page identified Marcus's session, so a redirect to his own profile would still
     report success. Today's read was verified by hand against the step-0 imabgold shortcode list. FOR
     MARCUS, second day running: make the exit-5 check also assert the final URL contains /saved/.
     BOTH LINES BELOW ARE UNGATED and deliberately left under ## inbox: business_discovery returned
     HTTP 403 code 4 "Application request limit reached" for both (the scan burned app quota on a
     duplicate probe pass this morning), and the guard-5 throwaway fallback was unavailable because
     ig-search had already spent 10/10 on the tag pages. They have FIRST call on tomorrow's budget. -->
<!-- ⚠⚠ 2026-10-07 — READ-SAVED.SH RETURNED THE WRONG GRID. NOT A REAL INBOX; 23 LINES REMOVED.
     read-saved.sh exited 0 and reported "24 on grid, 23 new appended", and all 23 appended lines were
     @imabgold's OWN last-25 reels in exact reverse-chronological feed order, including DeLUR4Jui1J which
     was posted 02:49 the same morning. The collection_url in ~/.config/ig-fetch/saved.json is
     instagram.com/imabgold/saved/viral-stuff/901996575663900/ — Instagram served (or redirected to) his
     PROFILE grid instead of the saved collection. The script's exit-5 check only asks whether the page
     identified his session, and a redirect to his own profile still does, so the bad read reported exit 0.
     The 23 lines were NOT gated: @imabgold is Marcus's own account, every line fails test 1 by
     construction (a man to camera, and his own output is not a donor), and gating them would have burned
     the morning. Removed, shortcodes recorded in logs/2026-10-07.log. The script was NOT re-run (step 1b:
     never twice a day, never improvise another read). TODAY'S SAVED READ IS A MISS, not an empty inbox.
     FOR MARCUS: the exit-5 check needs to also assert the rendered page IS the collection (its title /
     the /saved/ path in the final URL), otherwise a redirect silently kills step 1b and reports success. -->
<!-- empty 2026-10-02: read-saved.sh read 24 on the grid and appended 0 new lines (exit 0). The one
     backlog line, @adley's DdVB4DQM86E, was fetched FIRST THING this morning — before the tag pages,
     deliberately, because yesterday ig-search exited 4 and killed the fetch budget before the inbox
     was reached — gated, and moved to ## processed. The backlog is clear. -->
<!-- SUPERSEDED 2026-10-02, kept for the sequencing lesson. 2026-10-01: READ, NOT GATED, and deliberately LEFT HERE (an ungated line belongs under ## inbox).
     @adley resolved on one business_discovery call: Adley Kinsman, 1,457,447 followers, ceo @viralish,
     readable, 0/23 serving media_url. This reel is OLDER than the 25 media the probe returns, so there is
     no caption, no cover frame and no media_url for it — the only route to the gate is ig-fetch.sh, and
     ig-search exited 4 this morning (two read timeouts), which under guard 4 ends ALL ig-fetch use for the
     day. Logged download-miss: DdVB4DQM86E saved inbox (fetch cap). It has FIRST call on tomorrow's fetch
     budget. Handle was still added to watchlist.md under [saved] per Marcus's add-first rule, with guard 7
     flagged on the whole account (she sells a viral-growth service and the feed is the funnel). -->
<!-- empty 2026-09-30: read-saved.sh read 24 on the grid and appended 3 new lines; all three were
     gated and moved to ## processed the same morning at a cost of ZERO download slots and ZERO
     cookie budget — every one settled on its cover, read free via thumbnail_url on the
     business_discovery probe. The backlog is clear. -->
<!-- RESOLVED 2026-09-29: DbTQfj3hVF0 was fetched, gated and BANKED on the first slot of the day;
     its line now sits under ## processed with the verdict. The note below is kept because the
     filing lesson in it is the reason the reel survived to be banked at all. -->
<!-- MOVED HERE FROM ## processed on 2026-09-28. The 09-27 scan wrote it under ## processed as
     "DEFERRED, still a live candidate", which is exactly the filing mistake the note below
     warns about: step 1b's dedup rule skips anything under ## processed, so a deferred line
     parked there is a save that never gets read again. An unprocessed candidate lives HERE
     until it is gated. Attempted 2026-09-28, first call on the budget as promised: ig-fetch
     failed on a yt-dlp Instagram extractor error (KeyError(' ')), not a cap and not an IG
     signal. Still 0/25 serving media_url, still ig-fetch-only, still first call tomorrow. -->
<!-- empty 2026-09-27: all 4 lines from this morning's read-saved.sh were gated and moved to
     ## processed, together with the 5 lines the 09-26 interactive session had written into
     ## processed with the verdict "inbox" (i.e. unprocessed). The backlog is clear. -->
<!-- NOTE for whoever appends next: an unprocessed line belongs under ## inbox. A line under
     ## processed is skipped by the dedup rule in BANK.md step 1b, so "— inbox" written there
     nearly cost 5 of Marcus's saves. -->

## re-measure

## processed
2026-10-25 De5mlQGC8HZ @ahsan.deve https://www.instagram.com/reel/De5mlQGC8HZ/ — tombstone (test 1). Man to camera, B&W, card "The daily urge to bet on yourself and go all in on that one idea". ig-fetch 1/8. Handle → [saved].
2026-10-25 DXmFSpMDGYn @bylaurendudley https://www.instagram.com/reel/DXmFSpMDGYn/ — tombstone (tests 2/3/4). Real woman, "What if I told you you could build a personal brand in three and a half months…", brand how-to aimed at women, masterclass funnel. ig-fetch 2/8. Handle → [saved].
2026-10-22 Ddm08FwTdVt @robertmckeaveney https://www.instagram.com/reel/Ddm08FwTdVt/ — tombstone (test 1). Man to camera, "This creator copied me. Just watch." then a split screen vs @bryanjohnson_. ig-fetch 1/8. Handle → [saved].
2026-10-22 DexlgSSN3t8 @lexisummits https://www.instagram.com/reel/DexlgSSN3t8/ — tombstone (tests 2/3/4). Real woman, "I graduated college a year ago… it only gets better", about her engineering degree. Free Graph copy. Handle → [saved].
2026-10-22 DcOdPVJRg8l @meli.shares https://www.instagram.com/reel/DcOdPVJRg8l/ — tombstone (test 2). Real woman, card "PROOF YOUR MAN IS THAT N***A", aimed at women ("your man… girl"), answers her own blank (haters), carries a slur. ig-fetch 2/8. Handle → [saved].
2026-10-21 DeLrYBazaLe @jordiegarner_ https://www.instagram.com/reel/DeLrYBazaLe/ — **BANKED as COPY**. His reel opens 0.00-4.95s on a borrowed woman in a car: "These are seven non-sexual things that I think are attractive that guys do." 3.72s (4.68s with "Number one."), tagged list-opener: 7, creator unknown. ig-fetch 2/8. Handle → [saved] (donor source).
2026-10-21 DQvT1RngKx6 @datingwithgracie https://www.instagram.com/reel/DQvT1RngKx6/ — **BANKED**. Real woman to camera in her car: "These are signs that you are a walking green flag to women." 3.56s, word-timed, tagged list-opener (unnumbered "signs"). ig-fetch 1/8. Handle → [premise] (readable, 9/25 serving).
2026-10-21 DdejYH2irKY @chelskocoaching https://www.instagram.com/reel/DdejYH2irKY/ — tombstone (test 4). "Ladies, he's not single because girls don't want him. He's single because he hasn't found a girl he wants yet." She answers her own blank; same frame as the FRESH DYH7OUkMOUw. ig-fetch 3/8.
2026-10-21 DbJNmIBo_33 @herlastsightband https://www.instagram.com/reel/DbJNmIBo_33/ — burned-skip (not gated). @herlastsightband sits on a `dead` watchlist line (Marcus 09-27: "just a donor I was testing… don't include it in the viral scan"), so BANK.md's burned-creator rule skips it unread. If you saved it on purpose to revive the account, move its line back yourself.
2026-10-21 Desr8I2CJBv @chelskocoaching https://www.instagram.com/reel/Desr8I2CJBv/ — tombstone (tests 2/4). Transcribed: "The most powerful thing a woman can do for her man is choosing [him] every single day without him having to ask" (0.0-5.4s). Aimed at women, the man is the passive beneficiary, and she fills her own blank. Free Graph copy.
2026-10-21 DesE4k1sKHM @viralclubhouse_ https://www.instagram.com/reel/DesE4k1sKHM/ — **ad-skip** (guard 7) + tombstone. Caption is a "Comment MASTERCLASS… free live 100k followers in 100 days masterclass" funnel. Handle → [saved].
2026-10-21 Derw8hliw-b @chelskocoaching https://www.instagram.com/reel/Derw8hliw-b/ — tombstone (tests 2/3/4). "HE'S JUST A FRIEND" 🚩, Men, …: a red-flag premise about HER hiding messages; the man is the victim, no blank. Free Graph copy, framed.
2026-10-21 DeivNZRzkb3 @jordiegarner_ https://www.instagram.com/reel/DeivNZRzkb3/ — tombstone (tests 2/4/6). Opens on a borrowed woman in a car: "Okay, harder does not mean…" (0.0-2.0s, an innuendo tease), then his golf drill. No premise about men, no blank, 2.0s. Free Graph copy, transcribed. Handle → [saved] (donor-source shape).
2026-10-21 DeqlxRDzu8X @jwchock https://www.instagram.com/reel/DeqlxRDzu8X/ — tombstone (test 1). Man swimming laps under a card "No one cares about your Ironman content bro". Free Graph copy, framed. Handle → [saved].
2026-10-19 DdpLmYnyshN @pwrupcoaching https://www.instagram.com/reel/DdpLmYnyshN/ — tombstone (tests 2/3/4). Woman to camera in a car, coaching bit "how bad do you want it?", no man, no blank. ig-fetch 1/8 (older than the 25 Graph returns). Handle → [saved].
2026-10-19 DepN6mytpfv @sallie.gracee https://www.instagram.com/reel/DepN6mytpfv/ — tombstone (tests 1/2/4). "Finding Nana a boyfriend" car vlog, Ferrari driver, card only. Free Graph download. Handle → [saved].
2026-10-18 DekdCCVJDtx @nothmkaaron https://www.instagram.com/reel/DekdCCVJDtx/ — tombstone (tests 2/3/4). His reel opens on a borrowed woman in a car: "I think you're a loser if you have to ask everyone else… their opinion". Negative frame, no blank. Free Graph download, zero fetch cost. Handle → [saved] as a donor source.
2026-10-17 DehtTimC4yH @too.cute.labs https://www.instagram.com/reel/DehtTimC4yH/ — tombstone (test 1). Dog account. Settled free on the cover.
2026-10-17 DeinJjvgbDC @martinwang.mp4 https://www.instagram.com/reel/DeinJjvgbDC/ — tombstone (tests 1/2/4). Man to camera, growth tactic card. Settled free on the cover.
2026-10-17 DakdLX_SKOW @thesheemamahek https://www.instagram.com/reel/DakdLX_SKOW/ — tombstone (tests 2/3/4). "Being hated by the losers… is the price you pay". No man, no blank. File reused from preview-1015.
2026-10-17 DZEhefevFsy @stellacarvenne https://www.instagram.com/reel/DZEhefevFsy/ — tombstone (test 1: AI avatar, feed shape). Same woman in six podcast studios across a week, identical B&W grade, up to 4 quote-clips a day. Handle to Dropped. File reused from preview-1016, zero fetch cost.
2026-10-17 DbqLa2UTlUI @brennaberg https://www.instagram.com/reel/DbqLa2UTlUI/ — **BANKED**. "Call me crazy, but I think the sexiest thing that a man can do is…" cut 4.35s, card flips at 4.40s. File reused from Marcus's 10-15 donor hunt, zero fetch cost. She is already on [premise].
2026-10-17 DYH7OUkMOUw @chelskocoaching https://www.instagram.com/reel/DYH7OUkMOUw/ — **BANKED**. Woman to camera, solo desk mic, "He's not single because he can't get a woman. He's single…" cut 3.55s before her card gives the answer at 3.90s. Claim + elimination + blank, man the hero, on-audience by construction (her account coaches men). ig-fetch slot 1. Creator readable (333,942 followers, 17/25 serving) → [premise].
2026-10-17 DbQZF2PvlQn @weirdy_beardysfunkos https://www.instagram.com/reel/DbQZF2PvlQn/ — tombstone (test 1). Funko toys doing "men only want one thing, not money, not power" verbatim. File reused from preview-1015.
2026-10-17 DdyYsXFIZ8G @sofia.zianii https://www.instagram.com/reel/DdyYsXFIZ8G/ — tombstone (tests 2/3/4). Walking vlog, "you guys got to just be funny with it". ig-fetch slot 2.
2026-10-17 DbG9ZdHJO7p @hyundaisandy https://www.instagram.com/reel/DbG9ZdHJO7p/ — **ad-skip** (guard 7) + tombstone. Hyundai dealership sales account. Not fetched.
2026-10-17 DdTriwWB4H1 @launchwhasmik https://www.instagram.com/reel/DdTriwWB4H1/ — tombstone (test 8, also 2). She says "Claude or Codex" and addresses girls. File reused from preview-1015.
2026-10-17 Ddjkp9INMGO @only.onam https://www.instagram.com/reel/Ddjkp9INMGO/ — tombstone (test 1). Text-card POV over a man at a code wall. Settled free on the cover.
2026-10-12 DeXUUBNPSKe @programmergrind — tombstone (test 1, also 2). Borrowed woman-reaction opener 0.00-5.33s under a card; she never speaks. Settled on FRAMES, not the cover: IG's cover for this reel is his terminal, which is the evidence that made 10-11 write the account off. Donor-source structure CONFIRMED and his watchlist line corrected.
2026-10-09 DeO37s0AUWk @salama_win https://www.instagram.com/reel/DeO37s0AUWk/ — **BANKED as COPY**. @salama_win is Ahmed Salama | AI & Analytics, a man to camera (7,268 followers, 23/24 serving), so he fails test 1 himself — but this reel OPENS 0.00-3.80s on a borrowed real-woman-to-camera clip, full-bleed, her own word captions: "if you've got a girlfriend / and you are stressing out / about what to get her / I'm gonna put you on something…" Hard cut at 3.85s, blank never closed. Second-person sub-case, HERO reading, premise whole, Graph-served so ZERO cookie cost and one free download slot. ⚠ **AND HIS PAYOFF IS A CLAUDE 20X MAX PLAN CHECKOUT SCREEN** — the first outside account the scan has seen run the whole donor-opener template with Marcus's own object. Original creator NOT nameable (no watermark, no handle in any frame), so attach HIS sound in-app and credit him. FIFTH donor-source account after @programmergrind, @jeffery_zang, @tradonatev1 and @herlastsightband. Handle to [saved] (a donor SOURCE stays on [saved]; only a named creator goes to [premise], and she cannot be named).
2026-10-09 DeChJh4SGtb @xl_roi https://www.instagram.com/reel/DeChJh4SGtb/ — tombstone (test 1), settled FREE on the cover, no slot and no cookie spent. Carried over from 10-08's app-limit 403 and taken first this morning. A bearded man scrolling his phone in a dark wood-panelled room under a serif card: "If I have to work 12+ hours, 7 days a week so my wife gets to hear this everyday… so be it, I'll make it happen." FAIL 1 (no girl to camera; a text card over b-roll, nobody says it aloud), FAIL 2 (husband/provider frame — the exact age anchor the audience-fit rule rejects), FAIL 4 (the sentence closes itself, no blank). All 4 of his covers screened are this shape. Handle stays on [saved].
2026-10-09 DeHNtrqD_pp @archetype_origins https://www.instagram.com/reel/DeHNtrqD_pp/ — tombstone (test 1), settled FREE on the cover, no slot and no cookie spent. Carried over from 10-08's app-limit 403 and taken first this morning. 190,518 likes / 1,233 comments and not one frame of it is a setup: a man in glasses holding up a phone showing an ASUS ROG post, red rim-light, "How Many Times Do I Have to Press?! #asus #rog #pc". FAIL 1 (man to camera, no spoken premise), FAIL 4 (self-contained joke, which is what exclusive mode rejects by design). Ben & Jenny are custom PC builders; footage-led, so no 5b entry either. Handle stays on [saved].
2026-10-06 Dd0JrDsIXWj @datingwjessie https://www.instagram.com/reel/Dd0JrDsIXWj/ — tombstone (tests 2/3/4), catalogued DO-NOT-SPLICE. Her #1 reel by 3.4x (72,701 likes). FORM IS PERFECT — real woman, straight to lens, bedroom, full-bleed, own word captions, premise complete at 4.00s inside the winning band — and the SUBJECT is wrong: "I think my favourite form of intimacy is always been asking questions." No man in the sentence (tests 2/3), and she closes her own blank at 2.50s with a BEHAVIOUR (test 4). Cost ONE Graph slot and ZERO cookie budget: she serves 25/25. Handle added to [saved] and flagged as the cheapest line on either lane — a free-to-fetch real woman to camera who tags #datingadviceformen.
2026-10-06 DdtqNUwRSs1 @venecraftllc https://www.instagram.com/reel/DdtqNUwRSs1/ — **ad-skip** (guard 7) + tombstone (tests 1/2/4), no catalog entry, no slot spent. Screened FREE on the cover. 28,825 followers, 0/22 serving. A Venezuelan/US custom-manufacturing shop ("Personalizacion Premium en Madera & Acrilico e Impresion 3D... Ordena por DM o Web") — an account promoting its own product, which guard 7 names exactly. The cover is a 3D-printed branded microphone prop held over grass: no person, no speech, no premise, no slot. 100,807 likes on craft-satisfaction reach, Spanish-language. Cannot produce a donor by construction. Handle added to [saved] and flagged to Marcus as a line to cut.
2026-10-06 DeFfWXKvQ6F @greatsportingmoments https://www.instagram.com/reel/DeFfWXKvQ6F/ — tombstone (test 1, by construction), no slot spent. Screened FREE on the cover. 17,027 followers, 25/25 serving. A sports-meme aggregator: a letterboxed borrowed clip under the card "Texans defense this season" with @Greatsportingmoments burned over the frame — an aggregator's quote card, which test 1 names, over someone else's footage. Caption is an NFL recap. OLD LANE (sports): format-capture only since 2026-09-17, so no download slot and no catalog entry may be spent on it either way. Handle added to [saved].
2026-10-06 DeHsmAzDiAV @programmergrind https://www.instagram.com/reel/DeHsmAzDiAV/ — tombstone (test 1). His one allowed read this scan, settled FREE on the cover: no borrowed woman opener. The frame is his OWN webcam (headphones, mic, bedroom) over a split Claude Code terminal wall, caption "sry for screaming that much was in a bad mood :(". **EIGHTH consecutive read with no girl-to-camera borrowed opener**, against one hit (Dd1kEvAgli2, 09-29). The cover screen has now settled him in seconds for five scans running at zero cost; keep it, and note the hit rate for Marcus.
2026-10-02 DdVB4DQM86E @adley https://www.instagram.com/reel/DdVB4DQM86E/ — **ad-skip** (guard 7) + tombstone (tests 2/3/4), catalogued AD-REJECTED. Fetched on slot 1 of 8, the third attempt at this line and the first that got a budget: it was taken FIRST, before the tag pages, so an ig-search failure could not kill it a second time. 72.2s, 1080x1920. Static burned card "The ONLY AI you need to grow on Instagram?" over a real woman to camera in a cap and glasses — **test 1 passes on form** — and the body is a product pitch for an AI growth tool ("...scans its entire... for trending data, pulls... breakdown that you can..."). @adley is Adley Kinsman, ceo @viralish; an account promoting its own service is exactly what guard 7 names. No man in the sentence (test 3), no positive premise about men (test 2), blank answered by a tool name she supplies herself (test 4). Her handle was already on [saved] from 10-01 with guard 7 flagged; nothing changes. **The cost of the three-day wait was one cookie slot and the finding is that her line is dead weight for donors** — she remains a first-class FORMAT source (step 5b), never a donor. Marcus's call whether to cut the line.
2026-09-30 Dd2lcKeRVVd @janeddove https://www.instagram.com/reel/Dd2lcKeRVVd/ — tombstone (tests 2/3/4). 107,825 followers, 38,264 likes, **0/23 serving media_url** (ig-fetch only). Screened FREE on the cover, no slot spent. ⭐ THE FORM IS EXACTLY RIGHT — real woman straight to camera, full-bleed, native English, one burned sentence card, near-perfect framing — but the card is `"Ur so pretty, how are you single?"`, a premise about HER. There is no man in the sentence to be the hero (test 3), no positive superlative about men (test 2), and the blank it opens is an explanation of her own singleness, not an object a viewer owns (test 4). Same shape as @sofia.zianii: right camera, wrong subject. Handle added to [saved] — worth a free cover screen every scan for the day she points the premise at men.
2026-09-30 Dd4KqX6AMFZ @programmergrind https://www.instagram.com/reel/Dd4KqX6AMFZ/ — tombstone (tests 1/4). His one allowed read this scan, and the cover settled it FREE: no borrowed woman opener. The first frame is his OWN laptop screen full of TypeScript with a pink script card over it, "Do you think he'll say yes?? 🥺" (caption "my app is terminal based"). No woman to camera, and the blank is a yes/no rather than an object. **Fourth read of his pattern, fourth non-woman opener after a dashcam clip (09-26), a couple clip (09-28) and this** — against one hit, `Dd1kEvAgli2` on 09-29. Keep the cover screen; it costs nothing and it has now settled him in seconds three scans running.
2026-09-30 DdAP-GyvRY_ @skinbyash_mbco https://www.instagram.com/reel/DdAP-GyvRY_/ — **ad-skip** (guard 7) + tombstone (tests 1/2). 4,790 followers, 8,472 likes. Screened FREE on the cover, no slot spent. The cover is a styled product shot of five Face Reality skincare bottles with the creator behind them in an "Acne Slayer" tee, and the caption closes "Come get pampered girl you deserve it 🫶🏻 Midtown Beauty Co 📍Ventura, CA" — an account promoting its own service, which guard 7 names exactly. No person stating a premise, no man, no slot. Handle added to [saved] and flagged: an esthetician's business account cannot produce a donor, so this is a candidate line for Marcus to cut.
2026-09-29 DbTQfj3hVF0 @hannahkopen.co https://www.instagram.com/reel/DbTQfj3hVF0/ — **BANKED**. Third attempt, first call on the budget as promised, and this time ig-fetch worked (slot 1 of 8). Woman to camera in a sunlit backyard, full-bleed, serif card "The GREEN FLAGS that instantly make me like someone" + word captions: "People be always talking about red flags, but I'm here to talk about green flags." Setup 0.00-5.15s, card drops at 4.50s, her next line ("What are the green flags?") at 5.20s, so the blank is open at the cut. Green flags is the proven theme behind DdxZCCmR8i0 (52,837 views / 990 shares). She moves from [saved] to [premise]. ⚠ Two disclosures written into the catalog entry, not hidden: her card says "someone", never "men"; and the host reel's last 13s are a "comment REGULATE" lead-magnet CTA, which guard 7 names — banked anyway because the donor beat carries nothing promotional, and reversible to AD-REJECTED on Marcus's word.
2026-09-29 DHECXD0Ra-_ @paoloplaysgames https://www.instagram.com/reel/DHECXD0Ra-_/ — tombstone (test 1, by construction). 62,838 followers, 24/25 serving. Philippines tech/gaming commentary, man to camera; all 25 recent reels are his own takes and NOT ONE opens on a borrowed clip, so he is not a donor source. Screened free on the business_discovery read, no slot spent. Handle added to [saved].
2026-09-29 DZK5SnhtGag @samoilovart https://www.instagram.com/reel/DZK5SnhtGag/ — tombstone (test 1, by construction). 209,997 followers, 0/22 serving. A Star Wars helmet-replica studio: prop builds and paint reveals, no person to camera anywhere. Screened free, no slot spent. Handle added to [saved] and flagged to Marcus as the cheapest line to cut.
2026-09-29 DbVTnfEI_cn @ari.gutman https://www.instagram.com/reel/DbVTnfEI_cn/ — tombstone (tests 1/4, by construction). 3,671 followers, 5/25 serving, median engagement 0. Daily finance/motivation talking head, man to camera, same template every day. Screened free, no slot spent. Handle added to [saved].
2026-09-28 DdzE1pVTdE- @jeffery_zang https://www.instagram.com/reel/DdzE1pVTdE-/ — **BANKED as COPY**. @jeffery_zang is a man to camera (anime/cosplay/fitness, 584,891 followers) so he fails test 1 himself, but this reel OPENS 0.00-5.55s on a borrowed woman-to-camera clip, full-bleed, burned card "non sxual things men do that are attractive to me". Transcribed: she SAYS "non-sexual things men do that are really attractive", 0.00-2.72s, premise complete, then "Okay, the first thing…" at 3.16s. Donor beat cut at 3.10s with the blank still open. 156,664 likes, Graph-served so zero cookie cost. FOURTH donor-source account after @programmergrind, @tradonatev1 and @herlastsightband — and the second one that serves media_url.
2026-09-26 DZsw9oGtP0I @tradonatev1 https://www.instagram.com/reel/DZsw9oGtP0I/ — tombstone (test 5 only; 7 of 8 pass). Borrowed woman-to-camera opener 0.00-6.90s, "the hottest f***ing thing a guy can do is… make a little noise", cut measured at 4.30s with the blank still open. NO captions and no card anywhere, so a muted viewer cannot read it. Also a spent theme. Catalogued DO-NOT-SPLICE with the full measurement so a Marcus ruling on test 5 flips it to FRESH with no re-fetch.
2026-09-26 DAGvNIvibiv @cycasmotivation https://www.instagram.com/reel/DAGvNIvibiv/ — tombstone (test 2, audience fit; "it don't matter how old a man gets, he's got options" — older men, and the slot is filled with women). Right form, wrong premise. Aggregator watermark on every frame.
2026-09-26 C5lmW0Mij_7 @successskill https://www.instagram.com/reel/C5lmW0Mij_7/ — tombstone (tests 1/2; Shia LaBeouf podcast repost, "when do you become a man")
2026-09-26 Da8BS72t7mv @itsmrbugatti https://www.instagram.com/reel/Da8BS72t7mv/ — tombstone (test 1; Andrew Tate podcast edit, man to camera behind a boom mic)
2026-09-25 DdXYkKyv6hT @lifewithjorgeg https://www.instagram.com/reel/DdXYkKyv6hT/ — tombstone (tests 1/2/4; man to camera, life-insurance coach, "who cares, just keep posting your cringe content")
2026-09-25 DdNbCWyRjdd @siixuc https://www.instagram.com/reel/DdNbCWyRjdd/ — tombstone (tests 2/3; woman to camera but the premise is "men gaslight", negative frame)
2026-09-25 C4bhhVTtG-v @niktekofficial https://www.instagram.com/reel/C4bhhVTtG-v/ — tombstone (tests 1/2/4; PC-meme channel, no woman, no premise)
2026-09-25 DVe3khJjOU4 @_officer.ahmed https://www.instagram.com/reel/DVe3khJjOU4/ — tombstone (tests 1/2; man to camera, red-flag coaching aimed at women)
2026-09-24 DaWr4F9OH9q @programmergrind https://www.instagram.com/reel/DaWr4F9OH9q/ — BANKED as COPY (the 0-4.03s woman opener; creator unknown; source: Marcus pointed at it, not the collection)
2026-09-24 DYLF0zvTx80 @lilybrooksmind https://www.instagram.com/reel/DYLF0zvTx80/ — BANKED (all 8 pass; setup 3.26s/3.74s; one_thing shape)
2026-09-24 DIwXzqnxjUM @casiahwest https://www.instagram.com/reel/DIwXzqnxjUM/ — tombstone (tests 2/3, negative)
2026-09-24 DdRj8VNRO3D @brennaberg https://www.instagram.com/reel/DdRj8VNRO3D/ — BANKED (all 8 pass; setup 3.54s; half-filled slot; theme cooldown)
2026-09-24 DZd-6CEAWPc @hey_berg https://www.instagram.com/reel/DZd-6CEAWPc/ — tombstone (test 8, says Claude)
2026-09-24 Ddqwhx2xmW7 @prettylushangel https://www.instagram.com/reel/Ddqwhx2xmW7/ — re-measured (tests 5/6 pass; setup 3.84s; weak slot; FRESH)
2026-09-24 DZGH-MeorB6 @annabellegesson https://www.instagram.com/reel/DZGH-MeorB6/ — BANKED (all 8 pass; setup 3.52s/3.70s; theme cooldown vs fire_dev_v2)
2026-09-24 DVHDA5OiEgq @thegroundedmen https://www.instagram.com/reel/DVHDA5OiEgq/ — tombstone (aired as credits_reset; test 1)
2026-09-24 Ddb0oCCkgXr @nvidia https://www.instagram.com/reel/Ddb0oCCkgXr/ — tombstone (aired as astra_nvidia, floored; test 1)
2026-09-24 Dde-go9xl7f @programmergrind https://www.instagram.com/reel/Dde-go9xl7f/ — tombstone, format record (test 1)
2026-09-24 DcExxS_SvR_ @saynasheikhh https://www.instagram.com/reel/DcExxS_SvR_/ — tombstone (tests 2/4)
2026-09-24 DcEiX69BMBo @itspikaaa https://www.instagram.com/reel/DcEiX69BMBo/ — tombstone (tests 1/2/4)
2026-09-24 Ddb6cZGPJFN @pb_ema https://www.instagram.com/reel/Ddb6cZGPJFN/ — tombstone (tests 2/4)
2026-09-24 DceQiMLAgC6 @here.isivy https://www.instagram.com/reel/DceQiMLAgC6/ — tombstone (tests 2/4)
2026-09-24 DYrxpOopcSR @pulsetoria https://www.instagram.com/reel/DYrxpOopcSR/ — tombstone (test 1)
2026-09-24 DdMAalGznCy @thequietsociety_ https://www.instagram.com/reel/DdMAalGznCy/ — tombstone (tests 1/4)
2026-09-24 DalwVftpd5A @jacobb.lifestyle https://www.instagram.com/reel/DalwVftpd5A/ — tombstone (tests 1/2/3)
2026-09-24 Dao0ESOudKj @xel.official https://www.instagram.com/reel/Dao0ESOudKj/ — BANKED (reversed by Marcus 09-24 evening; the tombstone was caption-only)
2026-09-27 DbTQfj3hVF0 @hannahkopen.co — SUPERSEDED: this line was written here as "DEFERRED, still a live candidate", which the dedup rule would have buried. The live line now sits under `## inbox` above. Do not re-file it here until it is actually gated.
2026-09-27 DdZQxLtMA2S @thepocketpodcast https://www.instagram.com/reel/DdZQxLtMA2S/ — tombstone (tests 1/4; a podcast, which test 1 excludes by name, and "act like the version of you who already has it" carries no blank)
2026-09-27 DdZ1cvAN0gW @sofia.zianii https://www.instagram.com/reel/DdZ1cvAN0gW/ — tombstone (tests 2/3/4; FETCHED AND FRAMED via Graph, zero cookie cost). Right form exactly (girl to camera, full-bleed, word captions, native English, 55,400 likes) but a 79s manifestation monologue: "one month ignoring the entirety of external reality". No man, no slot.
2026-09-27 DcXgOUHoxvl @hothighpriestess https://www.instagram.com/reel/DcXgOUHoxvl/ — tombstone (tests 2/4; motivation with no premise about men and no blank; 1.42M followers but the account is a manifestation-app funnel, guard-7 risk on anything of hers)
2026-09-27 Da1kL96umUn @xel.official https://www.instagram.com/reel/Da1kL96umUn/ — tombstone (test 4; FETCHED AND FRAMED via Graph, zero cookie cost, deliberately NOT judged on caption after the Dao0ESOudKj reversal). The burned card is a static "let them hate" held unchanged 0-10s — the exact example THE GATE test 2 names as a fail. No blank, no slot.
2026-09-27 DdwliSKI4-J @herlastsightband https://www.instagram.com/reel/DdwliSKI4-J/ — tombstone (tests 2/3) ⚠ RULING QUESTION. FETCHED AND FRAMED via Graph, zero cookie cost. The account is a metal band and the reel is a BORROWED woman-to-camera opener (third donor-source account after @programmergrind and @tradonatev1). Tests 1/4/5/6/8 pass: real woman, full-bleed, burned captions, setup 0.00-5.2s COMPLETE, elimination + open blank, hard cut at 5.5s, 18,954 likes. Fails 2/3 on one noun: "Harder does not mean X. Harder means ___" has no man in it.
2026-09-27 DdE-6nQzR5F @hellobethanyreyes https://www.instagram.com/reel/DdE-6nQzR5F/ — tombstone (tests 1/2) + format capture. An IG-growth coach demoing a trend template, not a premise to camera. Screened free on the cover. The FORMAT (a fill-in-the-blank hook popping on the beat over 7s of b-roll) went to playbook.md.
2026-09-27 DdIcAYItexA @emmakarolyna https://www.instagram.com/reel/DdIcAYItexA/ — tombstone (tests 2/4). 241,270 likes, 389,917 followers, right form, manifestation content. Screened free on the cover, 0/25 serving so no slot spent.
2026-09-27 Dckk8b1RWZI @rossoreserve https://www.instagram.com/reel/Dckk8b1RWZI/ — ad-skip + tombstone (guard 7, test 1). Bio is "DMV / Delivery anywhere / DM for inquiries" — a sales account. No slot spent.

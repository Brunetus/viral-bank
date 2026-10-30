# Customer pickups: what the daily scan collects for client reels

Input file for BANK.md step 6e (added 2026-10-30, Marcus via Asana cards
1220037125948049 and 1220037126947603). Marcus edits this file. The scan
reads it, appends to each lane's `manifest.md`, and its only edit here is
rewriting the replogle `url:` line to `done` or `failed` after one try. These lanes are NOT the donor
bank: nothing here goes into catalog.md, and nothing here relaxes THE GATE.

Files land in `~/Claude Code/footage/donors/<lane>/` with a `manifest.md` beside
them (one line per clip: date, account, link, likes, file, one-line note).

Shared rules for every lane:
- Originals only, as BANK.md step 6e defines it: an outlet's own interview
  counts (tagging the speaker is fine); a "via/credit/repost" caption or
  another account's watermark does not.
- Like floor, per account (Grok relay, 2026-10-30, replaces the flat 100,000):
  look only at the VIDEO posts among the account's last 25 (photos and carousels
  never count). A reel passes if it has at least 2x that account's median
  like_count. From an outlet, that median is still the whole account's, not just
  its Rick Ross posts. The lane's 3 downloads go to the highest like counts. In
  the manifest note, record the exact like count and that median.
- Dedup: skip any permalink already in that lane's manifest.md.
- Sources are ACCOUNTS only (read with business_discovery), plus Evora's YouTube
  channels, which are read for links and view counts only. No hashtags, no
  ig-fetch (Bubba's withheld leads excepted), no throwaway tag pages: those
  budgets belong to the donor bank.
- Budget: at most 3 downloads per lane per scan, Graph `media_url` unless noted. A
  reel whose media is withheld is logged as a lead in the manifest
  (`lead, media withheld`) with its link and likes. Only Bubba's leads are then
  fetched, through ig-fetch; Evora stays links-only until Marcus picks one.

## replogle: Xi and President Trump clip (one-off)

- url: done 2026-10-29 cspan-685735-trump-xi-white-house-greeting-2026-09.mp4 (saved by hand on Grok's relay; was https://www.c-span.org/program/white-house-event/pres-trump-first-lady-greet-chinese-pres-first-lady-at-white-house/685735)
  (yt-dlp's generic extractor found the c-span.org /program/ page's HLS
  stream and saved it in 5 seconds; the page's paywall redirect only hits
  page readers. Verified 2:08, both leaders on screen.)
- what: the US / C-SPAN clip of Xi and President Trump that Marcus wants for
  @replogleglobescanada. Xi's state visit to the White House was 2026-09-24/25.
- source exception (Marcus, 2026-10-29): this ONE pickup may be downloaded from
  c-span.org with yt-dlp, no cookies. Apart from Evora's YouTube read (metadata
  only, it downloads nothing), nothing else in the scan may use yt-dlp.
- when the url line is filled: download it once, log it, mark this lane `done`.
- while it is empty: search c-span.org for the clip and list up to 3 candidate
  URLs with titles and durations in the manifest as `candidate`; download none.

## evora: Rick Ross donors

- for: Evora (@evora.canada) reels.
- wants: Rick Ross talking in his OWN voice, interview audio kept (podcast,
  radio, press, the Drake / Toronto beef, US interviews). North American
  context. Music-only clips, songs,
  music videos, album or track promos and lip-sync edits fail, however many
  likes they have.
- accounts: @breakfastclubam, @drinkchamps, @richforever
  (picked by Claude on 2026-10-29; Marcus may replace them. @richforever is Rick
  Ross's own account, swapped in 2026-10-30 because @rickross is not a readable
  handle on the Graph API). From the outlets, only posts whose caption names
  Rick Ross.
- youtube: @BreakfastClubPower1051FM, @DrinkChamps
  (Grok relay, 2026-10-30; links and view counts only, per BANK.md step 6e. The
  scan never downloads from YouTube: Marcus says yes to a clip in chat first,
  as he did for the 10-25 and 10-28 Ross donors.)
- check (Instagram clips only, YouTube is judged on the title and never
  fetched): the caption or the opening frames show it is Rick Ross speaking,
  and the clip is speech, not a song bed. If unsure, transcribe the first
  15 seconds; a clip with no speech from him fails.

## bubba: authentic people donors

- for: bubba-ig reels (a donor OPENER, per ROUTINE-REELS guard 8).
- wants: real people being genuinely themselves on camera: unscripted,
  candid, unpolished, a person talking or reacting as they are. Not ads, not
  brand content, not skits with a script, not other water-bottle brands.
- audience: active women 30-50 (Grok, 2026-10-29).
- fetch: withheld leads are downloaded with ig-fetch, top 3 per scan, after the
  donor bank has fetched its picks (Marcus via Grok relay, 2026-10-30).
- accounts: @thebirdspapaya, @mynameisjessamyn
  (picked by Claude on 2026-10-29 on Grok's relay, not yet read by the scan;
  Marcus's own picks replace them). @thebirdspapaya: Sarah Nicole Landry,
  Canadian mom, unfiltered real-body and real-life videos to camera, very high
  likes. @mynameisjessamyn: Jessamyn Stanley, candid yoga and movement, no
  polish. A handle that business_discovery cannot read is logged
  `pickup-skip: bubba @handle unreadable`, never guessed around.

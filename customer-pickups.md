# Customer pickups: what the daily scan collects for client reels

Input file for BANK.md step 6e (added 2026-10-30, Marcus via Asana cards
1220037125948049 and 1220037126947603). Marcus edits this file; the scan only
reads it and appends to each lane's `manifest.md`. These lanes are NOT the donor
bank: nothing here goes into catalog.md, and nothing here relaxes THE GATE.

Files land in `~/Claude Code/footage/donors/<lane>/` with a `manifest.md` beside
them (one line per clip: date, account, link, likes, file, one-line note).

Shared rules for every lane:
- Originals only: skip reposts, compilations and fan edits (caption credits
  another account, a watermark from another account, or a "via @x" line).
- Like floor: **100,000 likes** (Marcus, 2026-10-29). Record the exact like count.
- Dedup: skip any permalink already in that lane's manifest.md.
- Budget: at most 3 downloads per lane per scan, Graph `media_url` only. No
  ig-fetch slots: a reel whose media is withheld is logged as a lead in the
  manifest (`lead, media withheld`) with its link and likes, never fetched.

## replogle: Xi and President Trump clip (one-off)

- url: (none yet: Marcus to supply the exact link)
- what: the US / C-SPAN clip of Xi and President Trump that Marcus wants for
  @replogleglobescanada. Xi's state visit to the White House was 2026-09-24/25.
- source exception (Marcus, 2026-10-29): this ONE pickup may be downloaded from
  c-span.org with yt-dlp, no cookies. Nothing else in the scan may use yt-dlp.
- when the url line is filled: download it once, log it, mark this lane `done`.
- while it is empty: search c-span.org for the clip and list up to 3 candidate
  URLs with titles and durations in the manifest as `candidate`; download none.

## evora: Rick Ross donors

- for: Evora (@evora.canada) reels.
- wants: Rick Ross talking in his OWN voice, interview audio kept (podcast,
  radio, press, the Drake / Toronto beef, US interviews). North American
  context. Music-only clips, songs, music videos and lip-sync edits fail.
- sources: hashtag `#rickross` (top_media), plus these accounts via
  business_discovery: @breakfastclubam, @drinkchamps, @rickross.
  (Seed accounts picked by Claude on 2026-10-29; Marcus may replace them.)
- check: the caption or the opening frames show it is Rick Ross speaking,
  and the clip is speech, not a song bed. If unsure, transcribe the first
  15 seconds; a clip with no speech from him fails.

## bubba: authentic people donors

- for: bubba-ig reels (a donor OPENER, per ROUTINE-REELS guard 8).
- wants: real people being genuinely themselves on camera: unscripted,
  candid, unpolished, a person talking or reacting as they are. Not ads, not
  brand content, not skits with a script, not other water-bottle brands.
- sources: hashtag `#beyourself` (top_media) until Marcus names seed
  accounts or better tags.

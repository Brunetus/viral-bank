# Viral bank watchlist — accounts the scan watches for spiking clips

**EXCLUSIVE MODE (Marcus, 2026-09-17): only the `[premise]` lane below produces
donors.** Every other lane on this list is format-capture only — the scan may still
read those accounts for a playbook entry, but never spends a download slot or writes
a catalog entry on them. See `ig-routine-core/BANK.md` → EXCLUSIVE MODE and THE GATE.

## [premise] lane — anything that sets up a man in a positive way, with a slot

The lane that feeds the donor-opener template (performance.md rules 90-93). It starts
EMPTY on purpose: no account on the old list makes this shape, and the four donors
behind the account's hits (@uldouz, @abb.davv, the originals @thexcelguy reposted)
were all hand-picked. The scan fills this lane from the hashtag sweep (BANK.md step
2b): a gate-passing hashtag find is a HANDLE LEAD, resolved through ig-fetch.sh and
probed with ONE business_discovery call first (a personal account returns HTTP 400 and
is logged `premise-unreadable`, never appended), then appended here with the date, the
shortcode that led to it, and its serve rate. From the next scan on, the creator is read
directly.

Line shape, same as the rest of the file (the scan reads any line starting with @):
`@handle [premise] — added <date> via #<tag> <shortcode>; <N>/<25> serving media_url; <one line on what she does>`

A creator is dropped from this lane only by Marcus. A creator whose last 25 reels
produce zero gate passes across 14 days is reported in the log as
`premise-quiet: @handle`, never removed by the scan.

Known but NOT added: @thexcelguy — repost aggregator; its 2.0-2.4s cuts produced both
floor reels (`kiss_you`, `texting`). Gate test 7 rejects everything it posts.

## Old lanes (tech / general / sports / family) — format-capture only since 2026-09-17

One account per line: `@handle [lane] — why it's watched`. The lane tag
(tech / general / sports / family) is carried into each catalog entry so an
architect can filter for relevance — tech feeds @imabgold (building with
Claude), family feeds @bambi.map, general/sports feed the joke-splice canon
for everyone. Handles must be business/creator accounts or
`business_discovery` can't read them (the scan logs misses, never crashes).

Curated 2026-07-18: every handle below was verified live via
business_discovery (posts REELS, recent activity). Dropped futurism and
dadsaysjokes (0 reels, image/text accounts) plus averageparentproblems
(newest reel 2022-12), all dead surfaces for a reel bank. (Handles written
without @ here on purpose: the scan treats any line starting with @ as a
live watchlist handle, so a dropped account must never lead a prose line.)

@mkbhd [tech] — biggest tech creator; viral tech-moment clips
@techcrunch [tech] — startup/AI news moments, launch-day clips
@verge [tech] — tech culture clips (very active, near-daily reels)
@mrwhosetheboss [tech] — tech reviews/gadget moments, active reels
@openai [tech] — AI product/demo moments, active reels
@techburner [tech] — tech creator, humor + gadget reels, very active (added 2026-07-18 for tech-humor splice surface)
@morningbrew [tech] — startup/business humor skits, founder-POV (imabgold-adjacent, added 2026-07-18)
@pubity [general] — general meme/viral clips, huge reach
@daquan [general] — meme edits with caption-joke structure
@9gag [general] — general meme clips
@ladbible [general] — viral human-moment clips
@browncardigan [general] — absurdist/general meme clips, active
@houseofhighlights [sports] — splice-meme canon (Mbappé-tier moments)
@sportscenter [sports] — viral sports moments
@mom.uncharted [family] — parenting reels, very active (bambi-adjacent)
@parents [family] — family/parenting moments, near-daily reels
@corporate.bro [tech] — corporate/sales/office humour, 1.5M, 13/25 serving media_url (added 2026-08-28, Marcus). The closest surface the bank has to imabgold's own working life; sponsored posts appear (#RampPartner etc) so lean on the guard-7 ad filter
@rghoss1 [general] — relatable/observational joke reels, 6.9k, 7/25 serving (added 2026-08-28, Marcus). Thin on volume but strategically load-bearing: this is the SOURCE of the held-line format that ARCHITECT-CORE carries as UNPROVEN claim #2 and that performance.md rule 76 calls the account's comment engine
@julianomass [general] — sales/hustle motivation, 927k, 24/24 serving (added 2026-08-28, Marcus). Best serve rate on the whole watchlist. Content is heavily self-promotional (YouTube plugs), so most posts will fail guard 7 or have no joke to lend; its value is the confident-talking-head archetype and format capture
@kofibelizaire [tech] — corporate / job-interview skit comedy, 50.7k followers, 24/24 serving media_url (added 2026-08-28, Marcus). ⭐ THE HIGHEST-LEVERAGE HANDLE ON THIS LIST: its reels run 298k / 296k / 180k / 152k likes against a 50.7k follower base — roughly 6x its own following, which is the breakout signature step 3 ranks for, and every single video serves a media_url. Same corporate/office lane as @corporate.bro but with an order of magnitude more engagement per follower. Tagged tech because office-and-interview humour is the surface closest to imabgold's own working life, not because it is about technology.
@noah.rolette [general] — fashion/lifestyle, 657k, 17/23 serving (added 2026-08-28, Marcus). ⚠ HEAVILY SPONSORED (#KEENpartner, #uopartner) — expect guard 7 to reject most of it; watched for aesthetic b-roll rather than jokes
@adanxai [tech] — AI/coding humour (AWS, GitHub, SWE, Claude), 12.4k, 23/25 serving media_url (added 2026-08-29, Marcus). The ONLY handle on this list whose subject matter is literally @imabgold's own — building with Claude — so it is a lane fill, not a reach play. Bimodal and worth knowing before reading its numbers: median engagement is 47 but the top two posts run 8.7k and 6.3k likes, which is 185x and 135x its own median. 185x would be the highest ratio the bank has ever recorded (the standing record is 172.47x, DcjzjFthFLS/@rghoss1), so step 3 will surface this account loudly on the days it hits and not at all on the days it doesn't — that is the account, not a bug. Two structural caveats: (a) it posts ~8x/day, so the 25-media window covers only about THREE DAYS — a spike older than that is invisible to the scan and a missed day is a permanently missed clip, which no other watchlist account is true of; (b) it is an AGGREGATOR (captions carry `cred:` lines), so a banked clip may be someone else's footage at second hand — treat its donor provenance the way pubity/daquan/9gag are already treated.

Tested 2026-08-28 and NOT added, all measured via business_discovery:
cormacbuilds — HTTP 400, not a business/creator account, so business_discovery cannot read it at
all. Marcus asked for this handle; it can only be watched if the account converts to a
business/creator profile. failarmy, unilad, newsflare — each returned 25 media and ZERO media_url
(licensed audio on every reel), so they cannot feed the donor bank and would burn ig-fetch slots.
viralhog, caters_news — HTTP 400, same reason as cormacbuilds.

Donor-serving audit 2026-08-28 (VIDEO posts carrying a media_url, out of the last 25 media).
Recorded because a zero-serving account can still be a first-class FORMAT source under BANK.md
step 5b, but must never be given a download slot:
  healthy — techcrunch 25/25, mkbhd 20/20, houseofhighlights 21/21, sportscenter 23/24,
            techburner 23/24, mrwhosetheboss 18/19, pubity 16/16, morningbrew 12/12
  thin    — ladbible 2/8, parents 2/6, 9gag 1/11
  ZERO, format-capture only — verge 0/20, openai 0/11, daquan 0/23, browncardigan 0/18,
            mom.uncharted 0/25
The family lane (mom.uncharted, parents) STAYS: Marcus confirmed 2026-08-28 that the bambi daily
routine is still live and still cutting reels off this bank (it cut `best-seat` on playbook #37
that same day), so the lane is not removed despite serving almost nothing.

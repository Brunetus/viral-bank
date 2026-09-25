# Viral bank watchlist — accounts the scan watches for spiking clips

**EXCLUSIVE MODE (Marcus, 2026-09-17): only the `[premise]` lane below produces
donors.** Every other lane on this list is format-capture only — the scan may still
read those accounts for a playbook entry, but never spends a download slot or writes
a catalog entry on them. See `ig-routine-core/BANK.md` → EXCLUSIVE MODE and THE GATE.
**Exception (Marcus, 2026-09-24): `[saved]` handles are read like `[premise]` — a gate-passing reel from a `[saved]` creator may be banked (entry `lane: premise`) and the creator moves to `[premise]`. See BANK.md step 1b.**

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

@uldouz [premise] — added 2026-09-18 via Marcus's own `texting` donor DZsOX8fxFtc (proven creator, not a hashtag lead); 4.5M followers, 6/24 serving media_url; one format: "Keep two / Pick one / Choose two / Pick 3" named-choice premises to camera (top: DW-Ik-2EfFR 48.6k likes / 15.9k comments, 93x her median). Most spikes are media-withheld — ig-fetch, highest-ranked first. ⚠ premise-quiet: SILENT SINCE 2026-08-19 (37 days on 09-25); the strongest creator on this lane is producing nothing to read. Her "Is this a red flag" posts fail gate test 2 by caption.
@makayla.tonn [premise] — added 2026-09-18 via Marcus's own `other_woman` donor DdKyR60pldh (the ordinary-band reel, NOT a hit; attribution corrected same day); 34.8k followers, 22/25 serving. Woman to camera, on-audience, but she talks about Claude herself ("Claude is the other woman"), so most of her posts fail gate test 8, and her 09-18 spikes (kids rant, girls skit) fail test 1. Low hit rate expected; kept because she is readable, served, and inside the tribe.
@the_prosperityplan [premise] — added 2026-09-18 via Marcus's own `one_thing` donor DcRZppCMir8 (THE 532k reel; attribution corrected same day); 23.9k followers, 24/24 serving. ⚠ Feed is mostly finance-advice reposts ("send this to a friend", cashflow), so most posts fail gate test 4; watched for the occasional woman-to-camera desire premise it reposts. Repost account: test 7 as amended 2026-09-24 — a repost that carries the premise WHOLE may be banked with the chain recorded; a truncated one is skipped and the original creator becomes a handle lead.
@shrestha_mohanty20 [premise] — added 2026-09-19 via throwaway tag page #whatwomenwant DQorZuoEYDI (browsed; banked the same day); 89.9k followers, 0/25 serving media_url (every reel withheld, ig-fetch only); her whole feed is the format: woman to camera, English title card, Hinglish speech, "Boys…/Ladies…" premises ("3 things girls secretly love", "signs that make you look attractive", "MARRY THIS PERSON"). India-heavy, on-audience. Top spikes DcGFSWqxy2Y 132k and Dcc7my4xZdr 123k likes against a ~2.1k median.
@un_filtered98 [premise] — added 2026-09-19 via #greenflags Ddde8hAp89b ("The green flags that instantly make a guy 10x more attractive"); 2.1k followers, 15/25 serving media_url. Woman to camera, but that reel failed gate test 5 (no card, no captions, list starts at "7. Well-Dressed" at 3.5s) and most of her feed is self-help quote reels. Low hit rate expected; kept because she is readable, served and on-premise when she hits.
@applecrumbelina [premise] — added 2026-09-21 via throwaway tag page #greenflagsinmen DdePofcxqo0 ("the biggest green flag in men is when he says…", browsed); 648 followers, 25/25 serving media_url; woman to camera with word-by-word captions, near-daily premises about men ("men are so simple. here's why:", "i love men, like srsly", "am i wrong men?"). Not banked yet: her setups finish in ~2s (test 6) and the payoff is her own joke. ⚠ The two reels read on 09-21 appear to show different-looking women under one handle, so this may be a generated or multi-creator persona; worth a look from Marcus before any of her clips opens a reel.
@prettylushangel [premise] — added 2026-09-24 via scan lead Ddqwhx2xmW7 ("you want to know how I know that men are a lot more selfless"); 53 followers, median engagement 1; woman to camera, positive premise about men. ⚠ The 09-24 scan RESOLVED her but REFUSED to append on feed quality (adult-content funnel) and asked Marcus to rule; MARCUS RULED ADD (2026-09-24, interactive) and asked for the clip banked. MEASURED 2026-09-24 evening (catalog entry Ddqwhx2xmW7, FRESH): tests 5/6 pass, setup 3.84s, weak slot. PROBED 2026-09-25: 25/25 serving media_url (no ig-fetch needed). Her 09-25 candidate DdTZL6YxOF7 ("Alright, fellas… are you actually thinking of nothing") was tombstoned on test 3 — the man is the punchline. ⚠ Her median engagement is 1, so every "ratio" she produces is noise, not a spike signal.
@annabellegesson [premise] — added 2026-09-24 via Marcus's Saved collection (saved-inbox step, first run) DZGH-MeorB6, BANKED same day; woman to camera in a car with burned white premise cards, "Boys, do you wanna know…" openers (hottest thing / girls' fantasy), setup 3.52s spoken / cut 3.70s — the exact #54 shape. Original creator. ⚠ Her hottest-thing premise aired via a repost as `fire_dev_v2` (09-23, MISS) — theme cooldown before she opens a reel. PROBED 2026-09-25: 714,912 followers, 20/24 serving media_url. ⚠ Her feed has shifted to first-kiss / friend-zone advice aimed at girls; the six candidates she produced on 09-25 all failed tests 2/4 (no positive premise about men, no slot). Guard 5: never removed by the scan.
@theofficialxel [premise] — moved from [saved] 2026-09-24 evening (Marcus: use Dao0ESOudKj as a donor; the morning tombstone was a caption-only misread). 20.4k followers, real person, trading-mindset lines to camera; "get rich… when you pull up in a" BANKED; watch for more second-person aspirational openers.
@brennaberg [premise] — added 2026-09-24 via Marcus's Saved (read-saved.sh) DdRj8VNRO3D, BANKED same day; woman to camera on a couch, burned sentence card, "the hottest thing a man can do is…" premises that she answers herself inside 3s (half-filled slot). ⚠ Theme cooldown on "hottest thing" after `fire_dev_v2` missed 09-23. PROBED 2026-09-25: 372,465 followers, **0/25 serving media_url** (every reel withheld, ig-fetch only — she is the most expensive account on this lane). ⚠⚠ MEASURED 2026-09-25: her four biggest spikes (Ddjg_26RbSY 61.8k likes/106x, DdjhD7zxTYu 52.1k/90x, DdjhGPNRMlm 37.5k/65x, DdrLAujx2XW 25.2k/43x, all captioned "Just saying") are tough-love MONOLOGUES — breakup pep-talks, social-anxiety bits, sarcastic callouts — with no premise about men and no slot. All four tombstoned on tests 2/3/4, at a cost of 4 of the day's 8 fetch slots. **Her donor-shaped posts are the exception on her feed, not her mode**; do not spend the fetch budget on her spike ranking again, wait for a "hottest thing a man can do" caption.

Dropped 2026-09-24 (Marcus: no AI donors, ever): lilybrooksmind — bio "AI avatar sharing what works", 27.3k followers, daily quote-clip feed; came in via Marcus's Saved (read-saved.sh) DYLF0zvTx80. Its banked clip is DO-NOT-SPLICE. Never re-add.
Dropped 2026-09-18 evening (Marcus: girl donors only): lewishowes — podcast clips, male guests to camera; its banked clip is DO-NOT-SPLICE.
Dropped 2026-09-18 evening (Marcus: girl donors only): nikhil__anand___ — men's-glowup creator, man to camera; its banked clip is DO-NOT-SPLICE.
Known but NOT added: @thexcelguy — repost aggregator; its 2.0-2.4s cuts produced both
floor reels (`kiss_you`, `texting`). Test 6 rejects everything it posts (its reposts cut the donor at 2.0-2.4s); test 7 as amended would allow a whole-premise copy, but its copies never are.

## [saved] lane — creators Marcus saved on Instagram (added by the saved-inbox step, 2026-09-24)

Marcus's rule (2026-09-24): **whenever he saves a reel, that creator joins the scan.** Origin is
his Saved collection "Viral stuff" (or general Saved). A `[saved]` handle is READ every scan like
any other line, and its reels go through the same gate; in exclusive mode most of these will
produce gate rejects, which is expected — the point is that the one creator in ten who does make
the shape is never missed again (@thegroundedmen was shipped as a donor on 09-22 and was not on
any list). A readable creator whose reel PASSED the gate is listed under `[premise]` instead, not here; an HTTP-400 (unreadable) creator stays here marked `(unreadable)` even when a reel passes.
Marcus's own sequencing: add first, watch for a week, then cut the noise. Only he removes a line.

@hey_berg [saved] — added 2026-09-24 via Saved DZd-6CEAWPc; woman to camera, AI-parody skits; that reel failed test 8 (says Claude). Watched for a premise reel that doesn't name a model.
@casiahwest [saved] — added 2026-09-24 via Saved DIwXzqnxjUM; woman to camera, dating-psychology monologues, negative frames ("you know a man is lying"); failed tests 2/3. Watched for a positive one.
@programmergrind [saved] — added 2026-09-24 via Saved Dde-go9xl7f; 22.3k followers; **DONOR SOURCE (Marcus, 2026-09-24)**: he is a man to camera (fails test 1 himself) but his hits OPEN on a ~4s borrowed woman clip with a burned card (`DaWr4F9OH9q` 0.00-4.03s) before a long split-screen body. Every scan: read each new reel's first 5s; a woman opener that passes the gate is banked second-hand per amended test 7 with `copied-from: @programmergrind <shortcode>` and `creator:` when nameable. Also a format-capture source (step 5b).
@saynasheikhh [saved] — added 2026-09-24 via Saved DcExxS_SvR_; woman to camera, feelings lists; failed tests 2/4. Low hit rate expected.
@here.isivy [saved] — added 2026-09-24 via Saved DceQiMLAgC6; lifestyle vlogger, licensed audio; failed tests 2/4.
@itspikaaa [saved] — added 2026-09-24 via Saved DcEiX69BMBo; comedy skits; failed tests 1/2/4. Format-capture candidate only.
@pb_ema [saved] — added 2026-09-24 via Saved Ddb6cZGPJFN; car content; failed tests 2/4.
@pulsetoria [saved] — added 2026-09-24 via Saved DYrxpOopcSR; text-over-b-roll essays about men; fails test 1 by construction. Expect rejects.
@thequietsociety_ [saved] — added 2026-09-24 via Saved DdMAalGznCy; AI-labelled quote reels; fails tests 1/4 by construction. Expect rejects.
@jacobb.lifestyle [saved] — added 2026-09-24 via Saved DalwVftpd5A; lifestyle edits; failed tests 1/2/3.
@thegroundedmen [saved] — added 2026-09-24 via Saved DVHDA5OiEgq; male voice, "felt loved" pieces; ALREADY a shipped donor (`credits_reset`, 09-22). Fails test 1; watched because Marcus used him anyway.
@nvidia [saved] — added 2026-09-24 via Saved Ddb0oCCkgXr; Jensen keynotes; `astra_nvidia` donor FLOORED 09-22. Fails test 1. Marcus's rule adds him; expect rejects.
@successskill [saved] — added 2026-09-25 via Saved C5lmW0Mij_7 (reel not yet gated: older than the 25-media window, no caption readable, deferred to the next scan); 931k followers, 0 REELS in its last 25 posts — a discipline/ambition quote account that has stopped posting video. Expect rejects.
@itsmrbugatti [saved] (unreadable) — added 2026-09-25 via Saved Da8BS72t7mv; business_discovery returns error 110 "Invalid user id", i.e. a personal account. Never appended to [premise] whatever a reel does. Reel deferred, ungated.
@lifewithjorgeg [saved] — added 2026-09-25 via Saved DdXYkKyv6hT; 1.6k followers, 9/23 serving; man to camera, life-insurance coaching. That reel failed tests 1/2/4.
@cycasmotivation [saved] — added 2026-09-25 via Saved DAGvNIvibiv (reel deferred, ungated: older than the window); 2.39M followers, only 2 REELS in its last 25 posts — a motivation/quote aggregator. Expect rejects.
@tradonatev1 [saved] — added 2026-09-25 via Saved DZsw9oGtP0I (reel deferred, ungated); 3.4k followers, 18/25 serving; trading-journey account, man to camera. Same profile as @theofficialxel, which Marcus reversed off a caption-only misread — do not tombstone this one without frames.
@siixuc [saved] — added 2026-09-25 via Saved DdNbCWyRjdd; 8k followers, 0/24 serving (ig-fetch only). ⚠ Woman to camera with real reach (100k-150k likes, 32x/18x/17x spikes this window) so test 1 passes, but every premise is anti-men ("i alr can't stand men", "they gaslight you"), so tests 2/3 reject her. Worth watching for the one positive one.
@niktekofficial [saved] — added 2026-09-25 via Saved C4bhhVTtG-v; 46.8k followers, 0/20 serving; PC-meme channel. That reel failed tests 1/2/4.
@_officer.ahmed [saved] — added 2026-09-25 via Saved DVe3khJjOU4; 26.5k followers, 16/24 serving; man to camera, red-flag/relationship coaching aimed at women. Failed tests 1/2.

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

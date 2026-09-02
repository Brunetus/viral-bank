# Viral clip bank — catalog

Architect-facing index of banked clips. Written ONLY by the daily
scan (law: `~/Claude Code/ig-routine-core/BANK.md`); consumed read-only by
daily routines and reel-app jobs. Splicing a banked clip is an OPTIONAL
tool (REACH mode) — optimize for the most viral reel, but the account's/
user's own material must stay essential/load-bearing (never disposable
filler); within that floor a banked clip MAY carry the payoff.

Entry statuses: FRESH (usable), STALE (>21 days in bank — needs explicit
justification to use), AD-REJECTED (promotional; never usable),
DO-NOT-SPLICE (real footage, no comedic mechanism and/or sensitive subject;
never usable — catalogued only so a later scan doesn't re-download it).
Anything not FRESH is outside the canon. Out-of-canon entries (STALE,
AD-REJECTED, DO-NOT-SPLICE) are pruned by a later scan: the clip file is
deleted and the block is compressed to a one-line `[PRUNED <status>]`
tombstone that STAYS here — it's the record that stops a future scan from
re-downloading a clip already judged. FRESH clips and entries are never
touched.

<!-- entries below, newest first -->

## Dcwk7_RMpJ1 — a small boy in a Spider-Man crocs-and-black-tee outfit loads an aerosol Cheez Whiz can into his toy Spider-Man web launcher, fires it across the kitchen at his aunt, and coats her face, hair and chest in yellow cheese while the rest of the family folds up laughing
- source: @pubity | https://www.instagram.com/reel/Dcwk7_RMpJ1/
- lane: general
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 39575 likes / 360 comments (84.43x account median)
- joke-structure: weaponised toy. A child works out that a real product is physically compatible with a toy and tests the upgrade on a person — the scroller clocks "he is going to shoot that at somebody" a full three seconds before he does, and stays for the target's face rather than the launch
- the-beat: setup 0:00-0:04 (the boy grinning, holding up the loaded launcher), the fire at ~0:05, payoff 0:05.5-0:09 (aunt covered, hands to her face, a second adult wiping cheese off her while a toddler in a pink Paw Patrol jacket watches, unbothered). Cut on the hit at 0:05.5, or run 0:05.5-0:13 for the aftermath alone
- audio-model: diegetic (bakeable) — the shriek and the family laughing IS the beat; nothing licensed is load-bearing
- pairs-with: a tool used for something it was never built for, working far too well — a one-file script pointed at the whole repo, a "quick test" run against production, a toddler discovering a spoon is a catapult
- clean-window: caption "MY SON LOADED A CHEEZ WHIZ CAN INTO HIS SPIDER-MAN WEB LAUNCHER" holds full-strength through 0:04.5 and is a faded ghost by 0:05.0. 0:05.3-0:13.16 is FULLY CLEAN, no crop needed, 1.5x from 720x1280. Verified by eye at 2.5 / 3.0 / 3.5 / 4.0 / 4.5 / 5.0 / 5.5 / 6.0 / 6.5s — the entire payoff sits inside the clean window
- file: clips/Dcwk7_RMpJ1.mp4 (13.2s)

## DctQJHoBvlA — a man methodically destroys a company laptop: drums on the closed lid at his desk, carries it flat as a tray with three full coffee mugs on it, shoves the mugs into an office microwave, props the shut laptop upright against a wall on the carpet, then drops it and lands a bag on top of it
- source: @corporate.bro | https://www.instagram.com/reel/DctQJHoBvlA/
- lane: tech
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 18900 likes / 245 comments (2.86x account median)
- joke-structure: escalating desecration of a shared asset, told in the second person. Every shot raises the abuse one notch on the SAME object, and the "POV" framing hands the viewer the aftermath — you are not watching him, you are the person who gets this machine next
- the-beat: a montage rather than one turn. Beats at ~0:04 (drumming on the lid), ~0:09 (three mugs balanced on the closed laptop as a tray), ~0:13 (mugs into the microwave), ~0:18 (laptop stood on the floor against a wall), ~0:21 (dropped, bag on top). The single strongest cut is the mug-tray at 0:08-0:11
- audio-model: trending sound (add in-app) — the cuts are timed to a track, there is no diegetic beat to protect
- pairs-with: inheriting somebody else's mess — a codebase handed over by the last contractor, an account whose password is on a sticky note, a first day on the previous person's machine
- clean-window: the yellow caption "POV the guy who had your work laptop before you" is a two-line block at the very TOP, y320-540 of 2560, present the whole clip. Everything below y560 is clean and all the action lives there: a 1136x2020 crop is a DOWNSCALE to 1080x1920 (0.95x). At 1440x2560 this is the highest-resolution donor in the bank and the cheapest crop in it
- file: clips/DctQJHoBvlA.mp4 (23.1s)

## Dcs0xVKiUBH — a delivery driver pulls up at a rural house and a Bernese-mountain-dog mix meets him at the truck steps; he photographs the parcel with the dog in shot on his handset, hands over a treat, and before he can leave the dog flops onto its back on the driveway with all four legs up and waits
- source: @9gag | https://www.instagram.com/reel/Dcs0xVKiUBH/
- lane: general
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 274189 likes / 1038 comments (2.36x account median)
- joke-structure: the two-minute job that turns into a negotiation. Somebody on a clock is intercepted by something with no concept of the clock, which will not release him until it is satisfied — and he complies, which is the admission the whole thing runs on
- the-beat: beats at ~0:05 (dog planted on the truck steps, blocking them), ~0:32 (the proof-of-delivery photo taken with the dog in the frame), ~0:41 (the treat handed over), payoff 0:55-1:12 (the flop onto the back, legs up, and the driver crouching to do the belly rub), then it walks off at ~1:17. Cut on the flop at 0:55
- audio-model: diegetic (bakeable) — outdoor room tone and the driver talking to the dog
- pairs-with: the errand that ate the afternoon — "I was only going to fix one line", a toddler intercepting a parent at the front door, a five-minute call that goes ninety
- clean-window: NONE — full frame clean. Zero burned text anywhere across 81 seconds, checked at nine sampled points spanning the clip. The only screen in shot is the driver's own delivery handset at ~0:32, which is diegetic. Full-bleed, 1.5x from 720x1280. ⚠ It is 81 seconds long: pull the beat you want, do not use it whole
- file: clips/Dcs0xVKiUBH.mp4 (81.5s)

## DcxSGQAN2Dm — a dad stands in a hallway doorway holding a purple plush toy up out of reach while three small girls in matching pink swarm him, climbing his legs, hanging off his arms and grabbing at the toy; not one of them lets up for the whole clip
- source: #parentsofinstagram | https://www.instagram.com/reel/DcxSGQAN2Dm/
- lane: family
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 130 likes / 2 comments (hashtag recent_media, no account baseline)
- joke-structure: the pile-on with the victim off-camera. One adult under simultaneous siege from every direction, while the text names somebody who is never in frame as the person actually suffering — the laugh lands on an absent fourth party
- the-beat: no single turn, a sustained escalation. Beats at ~0:02 (the first kid attaches), ~0:08 (all three in contact at once), ~0:14 (the toy goes up out of reach and the smallest starts jumping for it). Cut anywhere in 0:08-0:16 for maximum density
- audio-model: trending sound (add in-app)
- pairs-with: everything arriving at once — three notifications mid-sentence, a toddler and a phone call and a boiling pot, a model asking three clarifying questions while you are still forming the thought
- clean-window: caption "When you and the kids ALL get on her nerves at the same time 😂" is a two-line block at the TOP, y140-270 of 1280, present throughout. Everything below y270 is clean: a 568x1010 crop → 1.90x to 1080x1920. Measured note, not a blocker: from ~0:09 the source carries a 34px black bar on the RIGHT edge (usable width 686 of 720), which the 568-wide crop clears comfortably
- file: clips/DcxSGQAN2Dm.mp4 (19.1s)

## Dcxo6ohK97X — a small boy in a Dragon Ball t-shirt stands at a hotel room door dragging a big paper shopping bag behind him, tapping the key card against the reader over and over, completely absorbed in the card and ignoring the bag
- source: #toddlertravel | https://www.instagram.com/reel/Dcxo6ohK97X/
- lane: family
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 41 likes / 2 comments (hashtag recent_media, no account baseline)
- joke-structure: value reversal stated flat. The text names the expensive thing and demotes it in the same sentence, and the footage is the evidence — the cheapest object in the building won. This is the exact shape taste.md records as the family lane's best performer (open on the object, then demote your own premise)
- the-beat: the turn is in the TEXT, not in the picture; the footage is the proof under it. The usable six seconds are the whole clip, 0:00-0:06 of the boy working the reader. Use it as the evidence beat under a text card, not as a payoff you cut into
- audio-model: trending sound (add in-app)
- pairs-with: the cheap thing that beat the expensive one — the free tool that replaced the subscription, the cardboard box that beat the toy, a one-line script that beat the platform
- clean-window: caption "The most expensive part of family travel is realizing that your kid is happier with a hotel key card than his toys at home 😭" is a five-line block in the UPPER LEFT, y220-440 of 1280. Below y440 is clean and holds the whole child (head ~y460, feet ~y1260): a 472x840 crop → 2.29x to 1080x1920. Inside the 2.6x line but not by much, so look at it full size before committing. Because the caption IS a strong setup, this also works OPENER-ONLY with no crop at all
- file: clips/Dcxo6ohK97X.mp4 (6.2s)

## DctxXD4PZzj — a hand holds a black MacBook out over a tiled floor under the label "6 months ago vs.", then holds the same laptop in the same pose under the label "now", and the Apple logo on the lid has been worn almost completely away
- source: @openai | https://www.instagram.com/reel/DctxXD4PZzj/
- lane: tech
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 8049 likes / 239 comments (4.92x account median)
- joke-structure: before/after where the damage IS the achievement. Two deliberately identical framings, one small difference, and the caption ("iykyk") refuses to point at it — the viewer has to find the worn logo themselves, which is what earns the rewatch and the comment
- the-beat: the label switch at 0:03.5 is the entire reel. Setup 0:00-0:03.5 on "6 months ago", cut on the change at 0:03.5, payoff 0:03.5-0:05.8 with the rubbed-off logo held in frame. It is 5.8 seconds and all of them are load-bearing
- audio-model: flexible
- pairs-with: proof of hours nobody watched you put in — a worn keyboard, a battery-health number, a contribution graph, a desk chair
- clean-window: the labels are a single small line at y490-545 of 1920, centred. Below y560 is clean and holds the whole laptop: a 765x1360 crop → 1.41x to 1080x1920. ⚠ Cropping the label away also removes the "6 months ago / now" turn, so crop it only when your own card carries the turn; otherwise bank it whole. It works OPENER-ONLY too, where the label is the setup
- file: clips/DctxXD4PZzj.mp4 (5.8s)

## DcxO3jjJUTW — thousands of redheads packed shoulder to shoulder in a Dutch town square for the annual Redhead Days festival, waving up at a camera on a pole, filmed from the air as a solid mass and then in slow push-ins on individual faces
- source: @pubity | https://www.instagram.com/reel/DcxO3jjJUTW/
- lane: general
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 14656 likes / 621 comments (32.30x account median)
- joke-structure: ⚠ NO JOKE AND NO TURN — this is a VISUAL METAPHOR donor and nothing else. What it pictures is a crowd of people who all chose to look identical, on purpose, together, at scale. It cannot carry a payoff beat; read pairs-with and use it as a cutaway
- the-beat: there is no beat. Three usable shots: the pole-camera wave at 0:00-0:04, the aerial mass at 0:05-0:11 (densest frame in the clip), the slow face push at 0:14-0:20
- audio-model: flexible
- pairs-with: sameness at scale — "every reel on my feed is the same reel", a niche where everybody has the same take, a conference room where everyone is wearing the same shirt
- clean-window: caption "THOUSANDS OF REDHEADS GATHER IN DUTCH CITY FOR ANNUAL REDHEAD FESTIVAL" plus its white underline occupies rows 837-1044 of 1280 for the entire clip (row-scanned across five samples, then confirmed by eye). Clean band above: y0-830 → a 467x830 crop → 2.31x to 1080x1920. Inside the limit, and because the crowd fills the frame any horizontal crop position works
- file: clips/DcxO3jjJUTW.mp4 (27.6s)

## DcwVIaWBNkF — a locked-off phone shot of a man sitting outdoors in a red chair against a grey brick wall, fist held against his mouth, staring past the camera; he does not move or speak for seven seconds while one block of text sits above his head
- source: @rghoss1 | https://www.instagram.com/reel/DcwVIaWBNkF/
- lane: general
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 8418 likes / 61 comments (75.04x account median)
- joke-structure: the held line over a face that never performs it. With no delivery to react to, the viewer has to decide for themselves whether it is a joke, a complaint or a genuine forecast — and deciding out loud is a comment. Here a piece of throwaway kid slang gets turned into a whole working life ("wake up at six-seven, work until six-seven, six days out of seven, until you're six-seven years old")
- the-beat: there is no beat in the picture, by design. The text is the reel. Frame one only
- audio-model: trending sound (add in-app)
- pairs-with: any flat sentence the user wants argued with rather than laughed at — the shape performance.md calls this account's comment engine
- clean-window: n/a — OPENER-ONLY donor (caption is the setup). The five-line block sits y430-810 of 1920 for the whole clip and never clears. Bank whole, full-bleed, no crop. Never cut this into a payoff beat
- ⚠ THIRD SIGHTING of this shooting setup: same person, same black tee, same gold cross chain, same locked-off framing, same ~7.0s runtime as Dcb5rv9BiAT and DcXyclOuYmv — but a DIFFERENT location (outdoor brick wall and red chair, against the indoor wooden cabinets of the other two). So it is NOT the same take, it is the same RIG re-shot. That strengthens playbook #58 rather than repeating it: what is reusable is the setup, not one plate
- file: clips/DcwVIaWBNkF.mp4 (7.0s)

## DcwHUmPwRXZ — two guys in a bedroom-office, one sprawled sideways across a chair gesturing with one hand, the other hunched over a laptop on a standing desk under a purple light strip; neither reacts to the other for the whole seven seconds
- source: @adanxai | https://www.instagram.com/reel/DcwHUmPwRXZ/
- lane: tech
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 326 likes / 3 comments (7.48x account median)
- joke-structure: the register gap, named in the text. One person is deep inside a subject the other has no access to, and the footage is deliberately undramatic — the flatness is what sells it, because there is no reaction shot to tell you it was funny
- the-beat: the text is the beat; there is no turn in the picture. Use it as frame one, let the line land, then cut to the channel's own footage for the payoff
- audio-model: trending sound (add in-app)
- pairs-with: explaining what you actually do all day to somebody who loves you — a partner, a parent, a friend from before the job
- clean-window: n/a — OPENER-ONLY donor (caption is the setup). "ranting to your non technical friend about AI, claude, and startup drama and realizing they live on another planet" sits dead centre, y660-900 of 1280, on every frame and never clears. Bank whole, full-bleed, no crop
- ⚠ provenance: @adanxai is an aggregator (captions carry `cred:` lines), so this is very likely somebody else's footage at second hand — treat it the way pubity / daquan / 9gag finds are treated
- file: clips/DcwHUmPwRXZ.mp4 (6.9s)

## Dct7do4TabE — a first-person view from inside a tent in a snowy pine forest: a full-grown tiger walks straight up the sightline through the trees, fills the tent opening and shoves its face into the lens
- source: @sportscenter | https://www.instagram.com/reel/Dct7do4TabE/
- lane: sports
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 389241 likes / 622 comments (6.06x account median)
- joke-structure: catastrophic understatement. The text greets a lethal animal the way you would greet a housemate walking into the kitchen, and the whole reel is the gap between what the words say and what is approaching the camera
- the-beat: the approach is the build (0:00-0:05), the face fills the frame at 0:06-0:07.75. There is nothing to cut on inside it — its value is as frame one
- audio-model: trending sound (add in-app)
- pairs-with: the thing that should terrify you and that you have quietly normalised — an alert you now scroll past, a bill you stopped opening, a deadline you stopped counting down to
- clean-window: FAILS the payoff test, banked OPENER-ONLY. "Oh it's just you 😭" sits at y400-440 of 720 on every frame; the largest text-free band is y0-390, which crops to 219x390 and needs 4.9x to reach 1080x1920. Bank whole, no crop. ⚠ Lowest-resolution clip in the bank at 576x720 — even the full frame is 2.67x, so look at it full size before committing
- file: clips/Dct7do4TabE.mp4 (7.8s)

## DcwBFC-RA8r — a room of teenagers being sworn into military service under the service seals, right hands raised, and one of them repeats the oath so literally that he says the instruction out loud instead of his name
- source: @sportscenter | https://www.instagram.com/reel/DcwBFC-RA8r/
- lane: sports
- first-seen: 2026-09-02 | status: FRESH
- stats-at-capture: 337092 likes / 525 comments (5.25x account median)
- joke-structure: an instruction followed exactly, to the letter, in a room where nobody is allowed to laugh. The comedy is that the error is a perfectly correct reading of what was said — and the setting supplies the pressure that makes it land
- the-beat: the whole reel is the wait for one line. The camera pans the row 0:00-0:06 and settles on the reaction at 0:07-0:11. Nothing to cut on; the payoff is verbal
- audio-model: diegetic (bakeable) — the line has to be audible or there is no reel
- pairs-with: the literal-minded response — a model that does exactly what the prompt said and not what you meant, a form submitted with the placeholder text still in it, a kid told to "put it away" who puts it somewhere else entirely
- clean-window: FAILS the payoff test, banked OPENER-ONLY. "I state your full name." 🎤😂 sits at y470-510 of 900 on every frame; the largest clean band is y0-465, which crops to 262x465 and needs 4.1x. Bank whole, no crop (the full frame is 2.13x from 720x900)
- file: clips/DcwBFC-RA8r.mp4 (11.0s)

## DcyFHCMsg8K — a man rides a scooter loaded with a large tub of dry dog food along a Philippine street, stops for a stray, feeds it out of his hand, then crouches on the kerb and gives it a second portion while it waits
- source: @pubity | https://www.instagram.com/reel/DcyFHCMsg8K/
- lane: general
- first-seen: 2026-09-02 | status: DO-NOT-SPLICE (2026-09-02)
- stats-at-capture: 7236 likes / 116 comments (15.54x account median)
- joke-structure: no usable mechanism. There is a thin idea in the caption (the stray has trained the human, not the other way round) but the footage never turns — it is sincere rescue content
- the-beat: none
- audio-model: n/a
- pairs-with: n/a
- clean-window: FAILS IN BOTH ROLES, which is why this is not banked. The original creator's watermark ("@PawsByGerald · I don't have YT") is burned on EVERY frame and MOVES between top-centre, bottom-left and bottom-right, so there is no fixed clean band and no 1.5s stretch that is text-free anywhere; a pubity "following" card is also composited over the picture around 0:27
- file: clips/DcyFHCMsg8K.mp4 (82.8s)

## DcuE8X7Sdhu — a 2:54 compilation of late-2000s Reebok NFL commercials (Laurence Maroney, Chris Chambers, Marques Colston, Braylon Edwards), each carrying its own broadcast name-card, under one fixed header
- source: @sportscenter | https://www.instagram.com/reel/DcuE8X7Sdhu/
- lane: sports
- first-seen: 2026-09-02 | status: DO-NOT-SPLICE (2026-09-02)
- stats-at-capture: 529911 likes / 1435 comments (8.26x account median)
- joke-structure: nostalgia compilation. Not an ad in intent — sportscenter is not selling Reebok in 2026 — but the footage IS somebody else's advertising, which is exactly the material guard 7 exists to keep out of a splice
- the-beat: none; it is a reel of separate commercials
- audio-model: n/a
- pairs-with: n/a
- clean-window: FAILS badly. The source is letterboxed into 720x900 with a blur fill, the real picture is a strip of roughly 340 rows, and the header "Peak fantasy football commercials 🔥" sits on the blur band above it on every frame. A 9:16 crop out of the picture strip needs about 5.6x. Named players' broadcast name-cards run throughout as well
- file: clips/DcuE8X7Sdhu.mp4 (174.1s)

## DcxwkJIB_WB — phone footage shot over the rail of a moving boat in Raritan Bay: a line of tall ships heeling under a bruised sky in 80mph winds, heavy chop breaking white under the camera
- source: @pubity | https://www.instagram.com/reel/DcxwkJIB_WB/
- lane: general
- first-seen: 2026-09-02 | status: DO-NOT-SPLICE (2026-09-02)
- stats-at-capture: 37813 likes / 366 comments (80.72x account median)
- joke-structure: none. Spectacle b-roll with no turn and no mechanism to lend
- the-beat: none
- audio-model: n/a
- pairs-with: n/a
- clean-window: passes the caption test and fails on everything else, which is the whole reason for this record. The burned headline clears by 0:07, but from 0:08 onward the filmer's THUMB crosses the top of the lens in most of the remaining frames (checked at 5/7/9/11/13/15/17/19s — clean only at roughly 0:06-0:08 and 0:10-0:12), and the source is letterboxed top and bottom. Ranked 2nd in the entire scan on numbers alone and banked nothing; recorded so no later scan re-spends a slot rediscovering it
- file: clips/DcxwkJIB_WB.mp4 (19.3s)

## DcuAX-CSB13 — a woman sits cross-legged on a couch and keeps lifting a dachshund puppy in a floral dress off her lap onto the cushion beside her; every single time, within a second, the puppy is back on her lap, and by the end it has given up on subtlety and just lies flat across her thigh looking at the camera
- source: @pubity | https://www.instagram.com/reel/DcuAX-CSB13/
- lane: general
- first-seen: 2026-09-01 | status: FRESH
- stats-at-capture: 63186 likes / 329 comments (352.86x account median)
- joke-structure: the correction that never takes. A person calmly puts something back where it belongs, over and over, and the thing returns faster than she can place it — the scroller clocks the loop on the second repetition and stays to see who gives up first. She does
- the-beat: no single turn; the format is a LOOP and the payoff is the last placement failing. Beats land at roughly 0:04, 0:09 and 0:15 (each removal-and-return), and the surrender frame is 0:20-0:24 with the dog lying flat and unbothered. Cut on any one return, or run 0:15-0:24 for the surrender alone
- audio-model: diegetic (bakeable) — room tone and her laugh; nothing licensed is load-bearing
- pairs-with: anything you keep fixing that keeps coming back — a bug you have closed three times reopening, a file the model keeps rewriting after you revert it, a toddler removed from the same drawer for the fourth time
- clean-window: caption "MY DACHSHUND THINKS SHE'S A LAP DOG… LITERALLY" is present 0:00-0:02.7 and then GONE for the rest of the clip. 0:02.7-0:24.1 is fully clean, no crop needed, 1.5x from 720x1280 to 1080x1920. Verified by eye at 1.0s / 1.8s / 2.4s / 3.0s / 23.8s — the probe missed this entirely and reported a 2.76x band, its third caption-fade miss in two scans
- file: clips/DcuAX-CSB13.mp4 (24.1s)

## DcufDt5JD5w — a fluffy grey dog on a purple lead stands in front of a public "DOG STICK LIBRARY" — a painted blue shelf of donated sticks pegged in rows — and works along it nose-first for twenty seconds, mouthing one stick, dropping it, moving to the next, never committing to any of them
- source: @pubity | https://www.instagram.com/reel/DcufDt5JD5w/
- lane: general
- first-seen: 2026-09-01 | status: FRESH
- stats-at-capture: 28451 likes / 249 comments (159.44x account median)
- joke-structure: paralysis in front of abundance. The premise is handed to you by a sign inside the shot, so there is nothing to read and nothing to explain, and the whole joke is that the choice is objectively trivial and the subject is treating it as enormous. The scroller reads "DOG STICK LIBRARY" and knows the bit before the dog moves
- the-beat: the turn is the FIRST reject — he takes a stick at 0:05, thinks about it, and puts it back at 0:07. Every later beat is the same beat again. Cut 0:03-0:09 for the shortest complete version, or 0:03-0:16 to let the indecision get embarrassing
- audio-model: diegetic (bakeable) — outdoor ambience, no track carrying anything
- pairs-with: choosing between tools that all work — which model to run, which framework, which of four working approaches to ship; also any "I had one job and forty options" moment. This is the closest donor the bank has ever held to imabgold's own recorded line "It asked me which model to use. I pay for the expensive one so that I never have to know the answer to that"
- clean-window: burned caption "THIS COULD BE THE BIGGEST DECISION MY DOG MAKES ALL YEAR" runs 0:00-0:03.0 and then clears. 0:03.2-0:21.9 is fully clean, no crop, 1.5x from 720x1280. Verified by eye at 1.5s / 2.2s / 2.8s / 3.5s / 21.5s. Note the "DOG STICK LIBRARY" lettering is a physical painted sign in the scene, not an overlay — it is picture, keep it, it is half the joke
- file: clips/DcufDt5JD5w.mp4 (21.9s)

## Dctv2wdBSKi — a person holds a headstand against a bedroom door, legs straight up in grey socks, and simply stays there for the whole clip while one line of text sits over them: "POV: Waiting for my Claude Usage limit to reset"
- source: @adanxai | https://www.instagram.com/reel/Dctv2wdBSKi/
- lane: tech
- first-seen: 2026-09-01 | status: FRESH
- stats-at-capture: 138 likes / 2 comments (3.59x account median)
- joke-structure: the absurd endurance pose as a unit of waiting. Nothing happens on purpose — the gag is that the wait is being measured in a posture no one could hold, and the picture refuses to give the viewer any progress. Motion score 4.84, effectively frozen, and that is the format working rather than a dead clip
- the-beat: there is no turn inside this clip and there is not supposed to be. Its beat is the FIRST FRAME: the text and the upside-down body arrive together and the recognition is complete in under a second. The payoff has to come from the reel that follows it
- audio-model: trending sound (add in-app) — the Graph API served this one, but nothing diegetic is load-bearing and the format rides a track. Do not bake
- pairs-with: any dead-air wait in the user's own working life — the rate limit, the build, the deploy, the export, the render. imabgold can cut straight from this into his own real countdown or his own actual screen
- clean-window: n/a — OPENER-ONLY donor (caption is the setup). The text sits dead-centre across the body for all 7.2s and there is no clean band (probe: 7.94x) and no clean stretch. Bank it whole, full-bleed, no crop, no upscale, and never cut it into a payoff beat
- file: clips/Dctv2wdBSKi.mp4 (7.2s)

## Dcb5rv9BiAT — a young man's face fills a locked-off phone camera in a bedroom, completely still and completely deadpan for seven seconds, saying nothing, while one block of held text sits over his forehead: "I hope you burn your hair with your straightener when you get ready for someone else who isn't me"
- source: @rghoss1 | https://www.instagram.com/reel/Dcb5rv9BiAT/
- lane: general
- first-seen: 2026-09-01 | status: FRESH
- stats-at-capture: 899 likes / 6 comments (8.46x account median)
- joke-structure: a curse disguised as a wish, delivered to a specific "you" the viewer is invited to be. The line is petty on a scale the viewer can measure (a straightener, not a life) and the face refuses to sell it, so the scroller's job becomes deciding whether this is a joke or not — which is the whole comment engine. Motion score 0.7: the picture is a still, on purpose
- the-beat: no motion turn exists. The beat is the READ — the viewer finishes the sentence at about 0:03 and the remaining four seconds are the format making them sit in it. If you cut this, cut on nothing; play the seven seconds
- audio-model: trending sound (add in-app) — the API withheld media_url, which is itself the evidence of a licensed track, and no diegetic sound is load-bearing. Never bake it
- pairs-with: nothing content-wise — the LINE is a bitter-ex line and no account here can say it. Its use is structural: it is the cleanest single specimen the bank holds of the held-line engine that ARCHITECT-CORE carries as UNPROVEN claim #2 and performance.md rule 76 calls @rghoss1's comment engine. Captured as playbook #58
- clean-window: n/a — OPENER-ONLY donor (caption is the setup). Text covers the upper-middle for the whole 7s; the largest clean band is 4.06x, well past the limit, and there is no clean stretch. Bank whole, full-bleed
- file: clips/Dcb5rv9BiAT.mp4 (7.0s)

## Dct9st7yAy5 — two tennis players meet at the net after a US Open match: they shake hands, one walks off flat and blank, and the other turns to her box and comes completely apart — both fists up, a jump, a scream — while the loser is still in frame
- source: @sportscenter | https://www.instagram.com/reel/Dct9st7yAy5/
- lane: sports
- first-seen: 2026-09-01 | status: FRESH
- stats-at-capture: 343798 likes / 2505 comments (5.07x account median)
- joke-structure: one frame, two opposite emotional states, no cut between them. The comedy is entirely in the fact that both people are still standing in the same shot — nobody has had time to leave, so the winner's celebration happens directly over the loser's shoulder. A scroller clocks the split before they know the sport
- the-beat: the turn is at 0:09.5 when the celebration starts while the other player is still walking. Setup 0:00-0:09, cut on the turn at 0:09.5, run to 0:12.1
- audio-model: diegetic (bakeable) — crowd noise and the scream ARE the payoff; a track over this kills it
- pairs-with: any "same room, opposite outcome" moment — the build passes for one person and fails for the other, one kid gets the seat and the other watches, a launch that lands for you and lands on somebody else
- clean-window: caption "Two sides of tennis 😅" is small, single-line, and REPOSITIONS as the shot changes (upper third to lower third), then clears entirely from 0:09.5 to the end. 0:09.5-0:12.1 is a fully clean 2.6s stretch AND it contains the whole payoff. Full-frame 9:16 out of 700x900 is 506x900, a 2.13x upscale — inside the limit but this is the lowest-resolution clip in today's batch, so check it at full size before you commit
- file: clips/Dct9st7yAy5.mp4 (12.1s)

## DcvLsnNBkIe — a brown-and-white pointer puppy is asleep curled on a living-room rug and running flat out in its sleep: paws paddling, jaw twitching, the whole body shifting a few inches across the rug over ten seconds without ever waking up
- source: @pubity | https://www.instagram.com/reel/DcvLsnNBkIe/
- lane: general
- first-seen: 2026-09-01 | status: FRESH
- stats-at-capture: 36398 likes / 126 comments (202.91x account median)
- joke-structure: total effort, zero consciousness. It reads instantly as "working hard on something that is not happening", and the ambient version of that is the whole value — there is no reversal in it and it never resolves
- the-beat: BE HONEST WITH THIS ONE — there is no turn and no payoff beat. It is a loop. Best usable range is 0:03.3-0:09.5 (fully clean, the twitching at its strongest). Treat it as an ambient/cutaway donor, not a punchline donor, and do not build a reel that needs it to land something
- audio-model: flexible — the diegetic track is silence; it works under a trending sound or dry
- pairs-with: work that happens without you — the overnight job, the queue draining while you sleep, the agent still going at 3am. Also the softer read: looking busy while achieving nothing
- clean-window: caption "SOMEONE'S HAVING A VERY GOOD DREAM RIGHT NOW" is present 0:00-0:03.0 and gone after. 0:03.3-0:09.5 is fully clean, no crop, 1.5x from 720x1280
- file: clips/DcvLsnNBkIe.mp4 (9.5s)

## DctaZitPHAM — a tech reviewer in an orange t-shirt shoots the same group selfie twice, once on an iPhone held at arm's length and once on a phone with a motorised gimbal camera clipped to its top, then holds both results up side by side and reacts to how much wider the second one is
- source: @techburner | https://www.instagram.com/reel/DctaZitPHAM/
- lane: tech
- first-seen: 2026-09-01 | status: FRESH
- stats-at-capture: 28637 likes / 69 comments (2.98x account median)
- joke-structure: A-vs-B with the reaction as the punchline, not the result. The comparison is set up plainly with two labelled phones and then the payoff is deliberately NOT the photo — it is his face when he sees it. The recognition trigger is the two phones in one pair of hands
- the-beat: the turn is at 0:30.5 when he stops demonstrating and just stares at the camera holding the phone up, eyes wide, mouth open. Setup 0:00-0:30, cut on the reaction at 0:30.5, run to 0:33.0. After 0:33 a "Robot Phone" card and a large blue emoji land on frame — stop before them
- audio-model: flexible — he is speaking under it but nothing he says is load-bearing; the reaction reads silently
- pairs-with: any "I compared the cheap way to the expensive way and the result was not close" moment — two models on the same prompt, the manual version against the automated one. The reaction shot alone is the most reusable two seconds in it
- clean-window: floating "iPhone" / "Robot" / "Phone" labels sit over the demo through most of the clip, but 0:30.5-0:33.0 is a fully clean 2.5s stretch of the reaction, full frame, 1.5x from 720x1280. Verified by eye at 28.0s / 29.5s / 31.0s / 32.5s / 33.5s. Everything before 0:30 needs the labels cropped out and is not worth the crop
- file: clips/DctaZitPHAM.mp4 (35.8s)

## DcvYr-kTXBX — sixty-four seconds of a family road trip through Milford Sound with a toddler: a one-lane bridge over white water, a night tunnel, a waterfall going past the window, the toddler asleep in the car seat, then a Kmart run where she walks the aisle alone, a hotel luggage cart, and finally mum and daughter eating in a restaurant with a bib on
- source: #toddlertravel | https://www.instagram.com/reel/DcvYr-kTXBX/
- lane: family
- first-seen: 2026-09-01 | status: FRESH
- stats-at-capture: 156 likes / 3 comments (hashtag recent_media, no account baseline)
- joke-structure: NONE, and that is the honest entry. This is a travel-vlog montage with no premise, no turn and no punchline. What it is instead is the only fully text-free real family footage the scan has banked in weeks, in the lane where the bank is emptiest (mom.uncharted serves 0 of 25, parents 3 of 6)
- the-beat: there is no beat to cut on. Three usable ranges, each a self-contained cutaway: 0:15-0:19 the toddler asleep in the car seat with the mountain going past the window; 0:48-0:53 the toddler walking a supermarket aisle alone between adult legs, which is the strongest single moment in it; 0:58-1:04 mum and toddler both eating at a restaurant table, bib on, spoons up. Use it under a bambi voice or caption, never as a payoff
- audio-model: flexible — road and room ambience, nothing load-bearing, and no track needed
- pairs-with: bambi's actual subject — the restaurant scene, the seat, the small child in a big room. Also any "we drove nine hours with a one-year-old" line that needs pictures under it
- clean-window: NONE — full frame clean. Zero burned text anywhere in all 64 seconds, confirmed by eye at 5s / 20s / 35s / 50s / 58s on top of the nine-frame sample. 1.5x from 720x1280, no crop, and it is the only clip in today's batch with no text problem of any kind
- file: clips/DcvYr-kTXBX.mp4 (64.1s)

## Dcl6QphRiYk — [DO-NOT-SPLICE 2026-09-01] two women act out a job interview in a real office, and each question quietly gives the game away ("what's your ideal salary again?", "I need for AI traini- I mean job", "do you have a writing sample we can steal?") until the last line retracts the premise entirely: "Who said anything about anything about a job?" · https://www.instagram.com/reel/Dcl6QphRiYk/ · @morningbrew, tech, 7867 likes / 72 comments (4.38x median) · FORMAT ONLY, footage unusable: burned yellow dialogue subtitles sit on EVERY frame including the payoff, largest clean band is 3.45x (limit 2.6x) and there is no clean stretch anywhere in 23 seconds; both performers are identifiable and the office is branded. Captured as playbook #57. Record kept so a later scan does not re-spend a slot on it.

## Dcq5KMYxKZP — [DO-NOT-SPLICE 2026-09-01] a man in all black performs thirty seconds of lacrosse stick tricks in a wide static shot on a riverbank under an overpass, behind-the-back catches and a between-the-legs flick, with no build and no failure · https://www.instagram.com/reel/Dcq5KMYxKZP/ · @sportscenter, sports, 300608 likes / 1386 comments (4.42x median) · killed on measurement AND on mechanism: the caption "He's smooth with it 🔥" is burned across the middle of the frame for all 30.5 seconds, the largest clean band is 11.87x, there is no clean stretch, and the caption is a LABEL not a setup so it has no opener value either. Beyond the gate there is also no joke here — it is a straight skill demo with nothing to lend.

## DctQtJdOne1 — [DO-NOT-SPLICE 2026-09-01] a phone pointed at a television replaying a college-football snap, captioned "75 AIN'T EVER GONNA JUMP OFFSIDES AGAIN 😅" · https://www.instagram.com/reel/DctQtJdOne1/ · @houseofhighlights, sports, 186630 likes / 1771 comments (2.44x median) · the 2026-08-28 scorebug failure class, three times over: a permanent broadcast scorebug across the bottom, a caption card across the top, an emoji strip between them, and the picture in between is a skewed screen-of-a-screen recapture. Largest clean band is 2.8x, past the 2.6x limit, and the play itself is unreadable at reel size. Picked for its 1771 comments (OPEN GAP 4) and it could not survive the gate.

## DctYvcfhaYM — [DO-NOT-SPLICE 2026-09-01] Nicole Kidman and Sandra Bullock walk a Practical Magic 2 premiere carpet holding hands, captioned "Every Mom Deserves a Nicole Kidman to Her Sandra Bullock" · https://www.instagram.com/reel/DctYvcfhaYM/ · @parents, family, 922 likes / 8 comments (2.43x median) · passes the clean-window test easily (0:03.9-0:07.4 fully clean, full frame, 1.5x) and fails on everything else: no joke, no turn, no mechanism — it is a warmth post — and the footage is credited Getty press material of two identifiable A-list actors, which is not something any account here can put in a reel. Spent deliberately to feed the thin family lane; recording the miss so the lane is fed from real parenting footage next time, not celebrity carpet.

## DcvGlwtyl4z — [DO-NOT-SPLICE 2026-09-01] a fully AI-generated 3D animation in which a CGI toddler pokes a gecko on a mud wall, the gecko jumps onto her shirt, and she screams and runs · https://www.instagram.com/reel/DcvGlwtyl4z/ · #instantregret, general, 141 likes / 0 comments (hashtag recent_media, no account baseline) · NOT REAL FOOTAGE. Synthetic animation carrying a "Baby Dream Studio" watermark on every frame. It reads as real in a thumbnail, which is exactly why it needs a record: it ranked 4th in the whole hashtag pool and would re-qualify. Nothing in this bank should put generated video into an account that sells credibility.

## DcsIdveIAj6 — [DO-NOT-SPLICE 2026-09-01] a mother lying against a headboard talks to camera for 128 unbroken seconds about discovering her first-grader had been buying herself a second school lunch every day on top of the one being packed for her · https://www.instagram.com/reel/DcsIdveIAj6/ · #parentsofinstagram, family, 57 likes / 525 comments (hashtag recent_media, no account baseline) · the clip queued by the 2026-08-31 scan and fetched today through ig-fetch.sh, now resolved. The clean window is actually fine (word-by-word captions sit in a top strip, everything below is clear at about 1.2x) — it dies on the other test: 128 seconds of one static face, the entire joke is verbal and spread across two minutes, and there is no visual beat anywhere to cut on. 111MB deleted.

## DcXyclOuYmv — [DO-NOT-SPLICE 2026-09-01] the SAME locked-off bedroom take as Dcb5rv9BiAT — same room, same shirt, same chain, same 7.0s, same frozen deadpan — re-skinned with a different four-beat text block: "Goodnight everyone, / Main character is going to sleep / Dream about me if you want good dreams / I'll see y'all tomorrow to make you laugh" · https://www.instagram.com/reel/DcXyclOuYmv/ · @rghoss1, general, 559 likes / 0 comments (5.22x median) · not banked because the bank would be holding the same seven seconds twice. Its value was evidential and it has been spent: two posts, two dates, one take, two different text blocks is the proof that this account's asset is the TEMPLATE and not the footage, which is what playbook #58 now records.

## DceaAu2hlQK — [DO-NOT-SPLICE 2026-09-01] a political rant about abortion framed as "1000 women Vs accountability" · https://www.instagram.com/reel/DceaAu2hlQK/ · @rghoss1, general, 237 likes / 114 comments (3.28x median) · judged at caption level and NO CLIP WAS FETCHED — no download slot and no ig-fetch slot was spent on it. Real footage, not an ad, and no comedic or splice mechanism; the subject is one no account this bank serves can carry. It has the highest comment rate in today's watchlist pool (one per two likes), so it would have ranked near the top of every scan for the rest of its 10-day window — this record is here to stop that.

## Dcmfi_dhunJ — a man walks alone down a lit night street in a beige knit polo, deadpan, never looking at camera, while two burned text beats sit over him: "I texted her 'i'm in your city'" then "She replied 'HAVE FUN'"
- source: @rghoss1 | https://www.instagram.com/reel/Dcmfi_dhunJ/
- lane: general
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 3161 likes / 43 comments (28.11x account median)
- joke-structure: the two-word rejection. A hopeful opener is answered with a phrase that is technically warm and actually a door closing, and the scroller clocks "HAVE FUN" in quote marks before reading anything else. The walk underneath never reacts, which is the whole gag: the face has not caught up to the text yet
- the-beat: no motion turn to cut on — the turn is the SECOND text line arriving over an unchanged shot. Beat 1 (the send) runs 0:00-0:05, beat 2 (the reply) lands ~0:05 and holds to 0:13. Cut on the arrival of the second line, not on any body movement
- audio-model: trending sound (add in-app) — a licensed track carried the post (the Graph API withheld media_url for exactly this reason); nothing diegetic is load-bearing. Never bake it
- pairs-with: any "I put myself out there and got a polite nothing back" moment — pitching an investor and getting "keep me posted", shipping a feature and getting one 👍 in the channel, telling someone you built the whole app and getting "nice"
- clean-window: band y0-950 of 2560 -> 534x950 crop, 2.02x upscale, and his head and shoulders are inside it in most frames. Passes for the payoff role. But be honest about what you get: the text IS the joke here, so a crop that removes it leaves a man walking. Its real role is OPENER, full-bleed, caption intact
- file: clips/Dcmfi_dhunJ.mp4 (13.8s)

## DcUqJKfuJk6 — the same man in a beige suit stands in a hotel corridor and is progressively erased by an AI edit: first his girlfriend vanishes from his arm, then his dreadlocks, then his whole face changes, each step captioned as another retraction
- source: @rghoss1 | https://www.instagram.com/reel/DcUqJKfuJk6/
- lane: general
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 2970 likes / 123 comments (27.13x account median)
- joke-structure: stepwise confession by subtraction. "Hey so this is my gorgeous Lebanese girlfriend…" -> "Nah im f*ckin wit y'all i don't have a girlfriend" -> "I dont even have dreads" -> "Im soo f*ckin sorry 😭". Each beat takes back one thing the previous beat claimed, and the picture obediently deletes it. The recognition trigger is the second line: the scroller realises the flex is being dismantled live
- the-beat: four beats, each ~3.5s. The real payoff is the THIRD (0:08, the dreads go and it stops being about the girlfriend at all) and the apology at 0:11 is the button. Cut on the third retraction
- audio-model: trending sound (add in-app) — media_url was withheld, so the post rides a library track. Never bake it
- pairs-with: any escalating walk-back of your own claim — "I built this myself" / "with Claude" / "Claude built it" / "I approved it", or a founder bio that gets smaller with each line
- clean-window: band y1727-2560 of 2560 -> 468x833 crop, 2.31x upscale on paper, but that band is only his legs and the rug. The gag needs the full frame and the text. Treat as OPENER-ONLY / full-bleed, no crop
- file: clips/DcUqJKfuJk6.mp4 (14.6s)

## DcpcdkiMbLo — FORMAT ONLY, no clip banked. Slow-mo night-pool b-roll of a stranger climbing out of a hot tub and walking, under a three-beat text stack ending "You're cooked. Follow"
- source: @adanxai | https://www.instagram.com/reel/DcpcdkiMbLo/
- lane: tech
- first-seen: 2026-08-31 | status: DO-NOT-SPLICE (2026-08-31)
- stats-at-capture: 1053 likes / 19 comments (14.89x account median)
- reason: the footage is a disposable identifiable stranger and the SAME b-roll is reused under a different text overlay on DcpOAyrNR_C, which proves the format is the asset, not the picture. Burned text covers y624-1824 of 2560 permanently; the only clean band is wet pavement. Captured as playbook #58 instead. Do not re-download
- file: none (deleted after frame-sampling)

## DcpOAyrNR_C — FORMAT ONLY, no clip banked. Identical night-pool b-roll to DcpcdkiMbLo under a single-line callout: "You've cooked if when hearing 'commit' makes you think of Git and not relationships"
- source: @adanxai | https://www.instagram.com/reel/DcpOAyrNR_C/
- lane: tech
- first-seen: 2026-08-31 | status: DO-NOT-SPLICE (2026-08-31)
- stats-at-capture: 471 likes / 4 comments (6.6x account median)
- reason: same disposable stranger footage as DcpcdkiMbLo, same permanent centre-frame caption (y530-695 of 1280, clean bands 3.3x and 3.7x, both fail). Same format, weaker text. Folded into playbook #58. Do not re-download
- file: none (deleted after frame-sampling)

## Dcs9OYPKgGV — a barefoot man runs at a granite plaza wall, kicks off it, lands badly, then hops on one leg and turns the camera on the sole of his foot, which is torn open and bleeding
- source: #fail | https://www.instagram.com/reel/Dcs9OYPKgGV/
- lane: general
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 190 likes / 8 comments (hashtag recent_media, no account baseline)
- joke-structure: the demo curse. His own caption says he had done the move cleanly several times and it only broke the moment he decided to film it. Setup is competence, payoff is a wound, and the mechanism is that the CAMERA is what caused it. The recognition trigger is the cut from a confident wall-run to a close-up of blood
- the-beat: attempt and bad landing 0:03-0:08, then the hobble, then the foot reveal at 0:10 which holds to the end. Two legitimate cut points: out at 0:08 if you want the fail without gore, or ride to 0:10 if the wound IS the punchline
- audio-model: diegetic (bakeable) — footsteps, the slap of the landing and the room tone are the beat; there is no track riding this
- pairs-with: "it worked every time until I recorded it" — a demo that broke on camera, a build that passed all week and failed in the screen recording, a take you had to reshoot nine times
- clean-window: NONE — full frame clean. No burned text anywhere in the clip, 720x1280 native, 1.5x to reach 1080x1920. The only cutting constraint here is taste, not text: the payoff frame is a bleeding foot in close-up
- file: clips/Dcs9OYPKgGV.mp4 (14.5s)

## Dcrs7mSNoN_ — a man in a floral shirt leaps at a carnival basketball hoop at a theme park, misses everything, and lands flat on his back on the concrete, where he stays while the attendant watches and a crowd walks past
- source: @houseofhighlights | https://www.instagram.com/reel/Dcrs7mSNoN_/
- lane: sports
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 299097 likes / 1344 comments (4.42x account median)
- joke-structure: full commitment, zero result, public aftermath. The recognition trigger is the wipeout itself, but the actual comedy is the third act: he does not get up, and the world simply continues around a man lying on the floor of a theme park
- the-beat: the jump and the fall land at 0:02-0:03. The payoff is AFTER it — 0:04-0:07, him still down while people step past. Cut out on the crowd walking, not on the impact
- audio-model: diegetic (bakeable) — arcade noise and the crowd reaction carry it; works muted under a track too, so treat as flexible if a trending sound is wanted
- pairs-with: shipping something with maximum confidence and watching it do nothing, a launch post that got four likes, a demo that failed in front of people who then carried on with their day
- clean-window: band y0-888 of 1280 -> 500x888 crop, 2.16x upscale. The burned line "Can't take bro anywhere 😭" sits on a dark bar at y888-936 and everything above it is picture, including the entire jump and fall. The bottom pane below the bar is a blurred duplicate, discard it
- file: clips/Dcrs7mSNoN_.mp4 (7.3s)

## DceIJ25PWh- — one unbroken 108-second shot of a man in a tan suit sitting in a chair, playing an interviewer to an off-screen candidate, under a permanent card reading "POV: If job interviews were like Pop the Balloon 🎈"
- source: @kofibelizaire | https://www.instagram.com/reel/DceIJ25PWh-/
- lane: tech
- first-seen: 2026-08-31 | status: DO-NOT-SPLICE (2026-08-31)
- stats-at-capture: 57908 likes / 4175 comments (4.97x account median)
- reason: no splice mechanism. Frame-sampled densely across all 108 seconds and it is ONE unbroken take of one identifiable stranger, one slow push-in, no cuts, no second person in frame and no visual turn anywhere — every laugh is verbal. The clean-window measurement passes (band y390-1280 of 1280 -> 500x890, 2.16x) and is irrelevant, because there is nothing in the band worth cutting to. Its value is the FORMAT, already held as playbook #51 (refreshed today). ⚠ This entry exists only as the dedup key: the 2026-08-29 scan reached the same verdict, wrote #51, and never wrote a catalog record, so this reel re-qualified as a top candidate and cost a second download slot today. Do not re-download
- file: none (deleted after frame-sampling)

## DcsJo-XtAn7 — a grizzly cub walks right up to a wildlife photographer lying on an Alaskan riverbank, sniffs and nibbles his boot while he holds still, then wanders back to its mother and sibling crossing the shallows
- source: @pubity | https://www.instagram.com/reel/DcsJo-XtAn7/
- lane: general
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 36148 likes / 278 comments (4.53x account median)
- joke-structure: hold perfectly still and it goes away. Tension with a soft landing: the thing that could kill you turns out to be curious about your shoe, and the correct move is to do absolutely nothing. The recognition trigger is a bear's face filling the frame at the same distance as your own foot
- the-beat: the approach builds 0:04-0:12, the boot contact is ~0:14, and the release is the cub turning away at 0:17. Cut on the turn-away if you want relief; cut on the contact if you want the freeze
- audio-model: flexible — river and gravel are pleasant but not load-bearing, so it takes a trending sound cleanly
- pairs-with: waiting out something you cannot control without touching it — a long agent run you must not interrupt, a deploy you are watching and refusing to poke, a toddler who has almost settled
- clean-window: band y0-810 of 1280 -> 456x810 crop, 2.37x upscale, and the approach beat and the mother bear are inside it. ⚠ COSTS YOU THE PAYOFF: the 3-line headline card sits at y816-1008 and never fades, and the boot-nibble itself happens at y950-1050, i.e. under the card. A clean crop gets the build, not the contact. Use full-bleed if you need the boot
- file: clips/DcsJo-XtAn7.mp4 (23.6s)

## DcrMhlTNQT3 — a bullmastiff asleep draped head-down over the arm of a couch slides further and further until he goes over head first onto the rug, then lies there and looks straight at camera
- source: @pubity | https://www.instagram.com/reel/DcrMhlTNQT3/
- lane: general
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 35316 likes / 194 comments (4.41x account median)
- joke-structure: slow inevitable collapse, then a deadpan look. The scroller clocks the physics in under a second (that dog is going to fall) and the reel makes them wait for it. The look-to-camera at the end converts a fall into an admission
- the-beat: the slide runs the whole clip, the tip-over lands at 0:12-0:13, and the payoff is 0:14-0:16, him on the floor holding eye contact. Cut on the tip-over, hold through the look
- audio-model: flexible — the snoring/whining is charming but not required, and the clip reads perfectly under a trending sound
- pairs-with: a slow-motion failure you can see coming and do not stop — the tab count climbing, the "one more fix before dinner" that ends at 11pm, a toddler leaning further and further off the chair
- clean-window: caption clears at ~0:05 — the 3-line card is present at 0:04.8 and gone by 0:05.2, so 0:05-0:16 is FULLY CLEAN, no crop, no upscale, and that stretch contains the entire tip-over and the look. Best cut-ready donor in today's batch
- file: clips/DcrMhlTNQT3.mp4 (16.1s)

## Dcl9zGJxJO_ — a teenager winds up on an arcade punch machine in front of his friends, swings, and the bag comes back and folds him over; three separate phone angles of the same hit, ending with him limping away hunched
- source: @sportscenter | https://www.instagram.com/reel/Dcl9zGJxJO_/
- lane: sports
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 339922 likes / 2240 comments (5.41x account median)
- joke-structure: hype setup, instant humiliation, then the replay rub-it-in. The burned line "Got 3 different angles … we never letting bro forget 😭" tells the scroller in one read that the fail is about to be shown three times, which is itself the joke — the format promises repetition of someone's worst second
- the-beat: first hit and fold at 0:01-0:02, angles two and three follow, and the button is the hunched walk-away in the last second. Cut on the fold for a single hit, or keep all three angles if the bit IS the replay
- audio-model: diegetic (bakeable) — the machine, the thud and the friends' reaction are the beat. Keep the sound
- pairs-with: a confident swing at something in public that immediately hurt — a launch, a pitch, a first take, anything you announced before testing
- clean-window: band y150-900 of 900 -> 422x750 crop, 2.56x upscale (just inside the 2.6x limit). The white caption box occupies y43-149 and is opaque; everything below it is clean picture and the action is centred. Source is 720x900, so the crop is tight but the subject stays whole
- file: clips/Dcl9zGJxJO_.mp4 (7.2s)

## Dcr58VkNQws — OPENER-ONLY donor. Helmet-cam POV of a motorcyclist tailing a yak and its calf down a gravel road in Sichuan; the yak turns and charges, and the last frames are the camera on the ground
- source: @pubity | https://www.instagram.com/reel/Dcr58VkNQws/
- lane: general
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 33373 likes / 1196 comments (4.3x account median)
- joke-structure: headline as the joke. The burned card "MOTORCYCLIST KNOCKED DOWN BY CHARGING YAK" states the consequence before the footage earns it, so the scroller spends the whole ride waiting for a thing they have already been told is coming. The comment count (1 per 28 likes, unusually high for this account) says people argue about who deserved it
- the-beat: the follow runs 0:00-0:25, the charge and the knockdown are ~0:26-0:29, and the camera-on-the-ground frame is the button. As an opener, the beat you want is the FIRST second: the card
- audio-model: trending sound (add in-app) — aggregator repost, engine noise is not load-bearing and the pacing wants a track
- pairs-with: any "I knew this was a bad idea and kept going anyway" setup where the headline can front-load the outcome
- clean-window: FAILS the payoff test — the card sits at y804-1020 and never fades, and the real picture is letterboxed between blurred bars, so the only text-free picture band is y336-800 -> 261x464 crop, 4.14x upscale. No clean stretch either. Bank as OPENER-ONLY: full-bleed, no crop, caption is the setup. Never cut this into a payoff beat
- file: clips/Dcr58VkNQws.mp4 (31.8s)

## DcrkbUuMJN5 — OPENER-ONLY donor. A slow pan across a barndominium living room finds a dad sitting alone in front of a wall-mounted TV, under a stacked three-beat text block about YouTube having captured him
- source: #parentsofinstagram | https://www.instagram.com/reel/DcrkbUuMJN5/
- lane: family
- first-seen: 2026-08-31 | status: FRESH
- stats-at-capture: 47 likes / 8 comments (hashtag recent_media, no account baseline)
- joke-structure: generational role reversal, delivered as a worried aside. "are we going to talk about the fact that YouTube is the TikTok for our parents / or is it just my dad / I feel like I need to have an intervention." The recognition trigger is the second beat backing off the claim, which is what makes it a confession rather than a complaint
- the-beat: three text beats stacked over one continuous pan; the turn is the third line ("intervention") landing at ~0:06 over an unbothered dad. There is no motion payoff — the room is the illustration, the text is the whole event
- audio-model: flexible — ambient room tone only, takes a trending sound cleanly
- pairs-with: an "it's happening to my parent and I have to explain the internet to them" beat, or a soft AI-slop confession where the punchline is that the older person cannot tell
- clean-window: FAILS the payoff test — the 9-line text block covers y300-985 of 1280 permanently, leaving only y0-295 (6.5x) and y990-1280 (6.6x). No clean stretch. Bank as OPENER-ONLY: full-bleed, caption is the setup
- file: clips/DcrkbUuMJN5.mp4 (8.4s)

## DcjakFTpcvO — a guy at a dining table mimes an increasingly frantic explanation to camera, hands flying, ending with both hands clamped on his own head, while a burned text card names the absurd thing he is supposedly explaining
- source: @adanxai | https://www.instagram.com/reel/DcjakFTpcvO/
- lane: tech
- first-seen: 2026-08-30 | status: FRESH
- stats-at-capture: 8790 likes / 46 comments (121.04x account median)
- joke-structure: the effort and the payoff are wildly mismatched, and the performer does not know it. Card reads "AWS solution architects explaining how to cut $0.06 off your monthly bill by sending S3 traffic through 7 Lambda functions, 3 NAT Gateways, and a custom cross-VPC peering setup." The recognition trigger is the number: a scroller clocks "$0.06" against seven Lambda functions before reading anything else, and the escalating hand-waving underneath is the punchline
- the-beat: there is no internal turn — the card lands in frame one and the body language escalates against it for 7.4s. The single best beat is 0:04-0:05, both hands on his head. Cut INTO this clip on the card, cut OUT on the head-clutch
- audio-model: trending sound (add in-app) — the footage carries no dialogue that matters and rides a library track. Never bake it
- pairs-with: imabgold's whole overengineering register. "Me explaining why I rebuilt the thing that already worked." Also any moment where the user's own effort was hilariously out of proportion to the result
- clean-window: n/a — OPENER-ONLY donor (caption is the setup). The card sits dead-centre and never fades, so the best payoff-role band is y0-570 of 1280 -> 321x570 crop, 3.37x upscale: a hard FAIL. Use it whole and full-bleed as the FIRST frames, then cut to the channel's own footage for the payoff. Do NOT cut into this as a payoff beat and do NOT put our own card over it
- ⚠ **DELIVERY IS MANDATORY FOR THIS DONOR — see ARCHITECT-CORE §6.5 (SEQUENCE LAW).** Because it can only be used whole and uncropped, a reel built on it is a SEQUENCE and MUST ship with (1) `@adanxai` burned top-right over their segment only, (2) the handle tagged on the post, (3) posted via Instagram's Remix function using the **Sequence** option. **This line exists because the earlier version of this entry said "use it whole and full-bleed" with no delivery instruction, and the reel built on it took 15 reach in 3.2h. The identical file re-posted with credit + tag + Remix/Sequence took 1,155 reach in 4.6h — 77x.** Never run this donor as a plain upload
- internal cuts: NOT a single shot. Hard cuts at f79->f80 and f91->f92 (wide cutaway across an empty classroom, 12 frames), then back close. 220 frames @30fps = 7.333s. The "no internal turn" note above describes the JOKE, not the edit — measure before replicating the grid
- file: clips/DcjakFTpcvO.mp4 (7.4s)

## DcmbAO-BtKv — night-time swagger b-roll at a hotel pool: a man surfaces from the water, walks out, struts past the camera and back along the deck, all shot handheld in the dark, under a burned text card
- source: @adanxai | https://www.instagram.com/reel/DcmbAO-BtKv/
- lane: tech
- first-seen: 2026-08-30 | status: FRESH
- stats-at-capture: 7492 likes / 24 comments (102.96x account median)
- joke-structure: a word from work has quietly overwritten its ordinary meaning, and the confession is played as a flex. Card reads "You've gone too far when hearing 'commit' makes you think of Git and not relationships." The recognition trigger is the double meaning landing on the second word — the viewer supplies the other definition themselves, which is why it reads as self-diagnosis rather than a joke told at them
- the-beat: no internal turn. It is 6.2s of confident b-roll under a static line. Best exit is 0:04-0:05, the walk back toward camera. Cut INTO it on the card
- audio-model: trending sound (add in-app) — library track, nothing diegetic worth keeping
- pairs-with: imabgold's jargon-displacement beats. "I said 'ship it' at dinner." Any moment where the user's own life vocabulary has been colonised by the build
- clean-window: n/a — OPENER-ONLY donor (caption is the setup). Card is centred and held the whole 6.2s; top band y0-550 -> 309x550, 3.49x upscale, FAIL, and the bottom band is identical. Bank whole, full-bleed, as an opener only
- file: clips/DcmbAO-BtKv.mp4 (6.2s)

## Dco2nODsjOd — a ginger cat outside a snowy patio door stands bolt upright on its hind legs like a person, paws flat against the glass, then drops and sits staring dead into the camera while the indoor cat watches from the rug
- source: @pubity | https://www.instagram.com/reel/Dco2nODsjOd/
- lane: general
- first-seen: 2026-08-30 | status: FRESH
- stats-at-capture: 100677 likes / 694 comments (6.03x account median)
- joke-structure: an animal doing a human posture with total commitment and zero self-awareness. The recognition trigger is the silhouette — a cat standing FULL HEIGHT against a glass door reads as a person in under a second, and the joke is that it keeps doing it. The second cat, sitting inside watching and doing nothing, is a free reaction shot inside the same frame
- the-beat: setup 0:00-0:04 (the cat rears up and paws the glass), the turn is 0:05-0:09 when it gives up standing, sits, and stares straight through the glass without blinking. Cut ON the sit. 0:11-0:15 is a slow push into a close-up of the stare — the best single hold in the clip and a clean deadpan payoff frame
- audio-model: flexible — the diegetic track is just room tone and a faint scratch at the glass, so it survives being ducked under a trending sound, and the visual reads with no audio at all
- pairs-with: any "I am waiting and you know exactly why" beat. imabgold: waiting on a build, a limit reset, a reply. bambi: a one-year-old at the kitchen gate at the exact moment food appears
- clean-window: burned caption "MY CAT, SONIC, HAS THE FUNNIEST WAY OF ASKING TO BE LET INSIDE" is up 0:00-0:04.5 and is GONE from 0:05.0 to the end — measured second by second (bright share in the caption zone 16.0% -> 0.00% at 5.0s, never returns). 0:05.0-0:15.1 is a 10.1s fully clean stretch, NO CROP NEEDED, full-bleed, and the sit-and-stare payoff is entirely inside it
- file: clips/Dco2nODsjOd.mp4 (15.1s)

## Dcp1gpSBw4H — a toddler is dead asleep in a rear-facing car seat with a bottle propped in her mouth, then sits bolt upright wide awake and starts drinking and looking around like nothing happened
- source: @pubity | https://www.instagram.com/reel/Dcp1gpSBw4H/
- lane: general
- first-seen: 2026-08-30 | status: FRESH
- stats-at-capture: 68814 likes / 522 comments (4.13x account median)
- joke-structure: a switch flips in a body that was completely gone one second earlier. The recognition trigger is the before-state — a limp sleeping baby with a bottle hanging out of her mouth is instantly readable, so the wake-up reads as a hard cut in behaviour rather than a gradual thing. Textbook reversal shape
- the-beat: setup 0:00-0:04 (asleep, head lolled, bottle propped), the turn is 0:05-0:07 when her eyes open and she comes upright in one move. Cut ON the eyes opening. 0:08-0:18 is her awake and drinking, usable as a tail
- audio-model: trending sound (add in-app) — the premise is a song change, so the clip rides a licensed track; the visual works fully muted, which is what makes it safe to use under a different sound
- pairs-with: bambi's core beat, the baby who was fine until he was not, or the reverse. "He slept through the whole restaurant. He woke up when the food arrived." imabgold: anything that was idle and then instantly was not
- clean-window: burned caption "SHE WAS ASLEEP UNTIL HER FAVORITE SONG CAME ON" is up 0:00-0:04.5 and is GONE from 0:05.0 (bright share 16.7% -> 0.00% at 5.0s, held to the end). 0:05.0-0:18.1 is a 13.1s fully clean stretch, NO CROP NEEDED, full-bleed. The wake-up turn is inside the clean stretch by a fraction of a second, so cut at 0:05.0 or later, not earlier
- file: clips/Dcp1gpSBw4H.mp4 (18.1s)

## DcpDN87p5v1 — a woman driving in sunglasses reacts to the music she loved at her kid's age, cycling through wincing, a flat hand held up to make it stop, and covering her own mouth
- source: #parentsofinstagram | https://www.instagram.com/reel/DcpDN87p5v1/
- lane: family
- first-seen: 2026-08-30 | status: FRESH
- stats-at-capture: 28 likes / 0 comments (hashtag recent_media, no account baseline)
- joke-structure: the same input, re-heard through a role you did not have last time, and the verdict flips. Card reads "when you listen to the music you listened to at your kids' age through parent ears 💀". The recognition trigger is the face doing the work, not the card — she is not performing shock, she is performing a person recalculating in real time
- the-beat: the whole 21.4s is one escalating reaction with no single turn, which makes it an unusually flexible PAYOFF asset: pick any 2s. The three best are 0:04 (hand up, stop), 0:09 (open-mouthed, no words) and 0:14 (fingers to lips). Cut in on whichever matches the setup you are landing
- audio-model: trending sound (add in-app) — she is reacting TO a track, so the audio is licensed and the joke survives without it. The faces are the asset
- pairs-with: any "I used to think this was fine" reversal. bambi: re-reading your own pre-baby restaurant standards. imabgold: opening code you shipped three months ago. A reaction face that lands after almost any setup card
- clean-window: caption sits in the TOP third and never fades, so this passes on the BAND, not a stretch. `crop=433:770 at x=143,y=510` -> 2.49x upscale — RENDERED AT FULL SIZE AND LOOKED AT, not row-scanned: the crop is clean of text and emoji at 0:04, 0:09 and 0:14, and her face and both reacting hands sit fully inside it. Softness is visible on close inspection and is well inside tolerance
- file: clips/DcpDN87p5v1.mp4 (21.4s)

## DcpuomFhSYK — a man on a cruise deck films himself in what he takes to be a mirrored door, keeps closing in on it, and a stranger's face resolves out of the glass a foot from his own before the camera flies off in every direction
- source: @pubity | https://www.instagram.com/reel/DcpuomFhSYK/
- lane: general
- first-seen: 2026-08-30 | status: FRESH
- stats-at-capture: 47777 likes / 458 comments (2.87x account median)
- joke-structure: you were looking at yourself and something looked back. The recognition trigger is the mirrored-glass selfie, an action every viewer has performed, which is what makes the reveal land as a violation rather than a surprise. The reaction is not acted — the camera work does the screaming
- the-beat: setup 0:00-0:05 (approaching the glass, filming himself), the turn is 0:06-0:07 when a woman's face resolves behind the tint, inches away and looking straight out. Cut ON the face. 0:07.5-0:13.6 is the flail — railing, ceiling, sky, deck — which is genuinely usable as a reaction tail because the incoherence IS the reaction
- audio-model: diegetic (bakeable) — deck wind and his own reaction noise; there is no music and nothing licensed
- pairs-with: anything that was supposed to be a private moment with your own reflection. imabgold: talking to the AI and getting a person's answer back. Any "I thought I was alone in this" beat
- clean-window: burned caption "THE LAST THING HE EXPECTED TO SEE" is up 0:00-0:04.5 and is GONE from 0:05.0 (bright share 10.2% -> 0.00%, held to the end). 0:05.0-0:13.6 is an 8.6s fully clean stretch, NO CROP NEEDED, full-bleed, and both the reveal and the flail sit inside it
- file: clips/DcpuomFhSYK.mp4 (13.6s)

## DcpWZ-WsK3M — a woman in a headscarf dances around her kitchen with a water bottle, pointing at the ceiling and mouthing along, celebrating on her own
- source: #parentsofinstagram | https://www.instagram.com/reel/DcpWZ-WsK3M/
- lane: family
- first-seen: 2026-08-30 | status: FRESH
- stats-at-capture: 1046 likes / 2 comments (hashtag recent_media, no account baseline)
- joke-structure: a victory lap for a thing only the people in the club understand. Card reads "POV: You put your baby on a sleep schedule as a newborn, and now she's 1 and be knocked out before 9 PM every night." The recognition trigger is the private celebration — no audience in frame, nobody to explain it to, which is what makes it read as earned rather than a brag
- the-beat: no internal turn, it is a held celebration for 12.6s. Best 2s is 0:02-0:04, the point at the ceiling. Cut INTO the clip on the card, cut OUT before the loop repeats
- audio-model: trending sound (add in-app) — she is dancing to a library track and lip-syncing to it. Never bake it
- pairs-with: bambi's parenting-win beats, the thing that only lands if you have lived it. "The highchair was there." "He ate the whole thing." Read the floor before using: this is an identifiable stranger, so the account's own footage has to carry the reel
- clean-window: n/a — OPENER-ONLY donor (caption is the setup). Card is centred and held the whole clip; top band y0-610 of 1280 -> 343x610, 3.15x upscale, FAIL, bottom band is worse. Bank whole, full-bleed, as the FIRST frames only
- file: clips/DcpWZ-WsK3M.mp4 (12.6s)

## DchI9Dth_NS — [PRUNED DO-NOT-SPLICE 2026-08-30] a man in a kitchen delivers an unbroken 27-second reply to camera, opening on a screen-grab of somebody else's post about why men fall for toxic partners · https://www.instagram.com/reel/DchI9Dth_NS/ · first-seen 2026-08-30

## DcmT6fuvO8p — [PRUNED DO-NOT-SPLICE 2026-08-30] a shirtless man sprints through near-total darkness and jumps, filmed handheld at night, under a static caption · https://www.instagram.com/reel/DcmT6fuvO8p/ · first-seen 2026-08-30

## DcmYthcyPyC — [PRUNED DO-NOT-SPLICE 2026-08-30] a man barbell-squats in a home gym on a livestream, with a subathon countdown timer and a chat overlay burned across the top of every frame · https://www.instagram.com/reel/DcmYthcyPyC/ · first-seen 2026-08-30

## Dclu1YpOmMa — [PRUNED DO-NOT-SPLICE 2026-08-30] a softball runner beats the catcher's tag at home plate, filmed from the stands through a chain-link backstop · https://www.instagram.com/reel/Dclu1YpOmMa/ · first-seen 2026-08-30

## DcezzvJQRen — [PRUNED DO-NOT-SPLICE 2026-08-30] an 82-second review of a small wheeled camera robot: it drives down office corridors, is picked up and turned over on a table, and is demonstrated from a phone app · https://www.instagram.com/reel/DcezzvJQRen/ · first-seen 2026-08-30

## DcnI979pgnR — a security camera watches a landscaper stop his truck, walk onto a stranger's lawn, crouch, then lie flat on his stomach to inspect the grass at eye level before getting up and driving away
- source: @pubity | https://www.instagram.com/reel/DcnI979pgnR/
- lane: general
- first-seen: 2026-08-29 | status: FRESH
- stats-at-capture: 44928 likes / 264 comments (37.72x account median)
- joke-structure: absurd devotion to a trivial thing, played completely straight by a stranger who does not know he is being filmed. The recognition trigger is a working man in uniform going PRONE on a lawn for no reason a viewer can see — you clock "he is taking this far too seriously" in under a second, and the fixed security-cam frame is what makes it read as real rather than staged
- the-beat: setup 0:00-0:04 (truck pulls over, he walks up the lawn), the turn is at 0:05-0:07 when he drops from a crouch onto his stomach face-down in the grass. Cut ON the drop. 0:10-0:17 is the walk-back-to-the-truck tail, usable as an outro but not the joke
- audio-model: flexible — silent security-cam footage, no dialogue and no sting; it plays fine under a trending sound or under a voiceover
- pairs-with: any moment of someone caring far too much about a detail nobody asked about. imabgold: "the way I look at one line of code I already shipped." bambi: a parent inspecting a restaurant highchair like a crime scene before letting the baby near it
- clean-window: caption "WHEN THE LANDSCAPER PULLS OVER JUST TO STUDY YOUR GRASS…" is up 0:00-0:02.5 ONLY and is gone from 0:03.0 to the end — measured, not guessed (bright-pixel share in the caption zone goes 11.0% → 0.0% at 3.0s and never returns). 0:03.0-0:17.4 is a 14.4s fully clean stretch, NO CROP NEEDED, full-bleed. The prone beat sits inside the clean stretch. Band fallback if you want the caption gone from frame one too: y359-1280 -> 518x921 crop, 2.08x upscale
- file: clips/DcnI979pgnR.mp4 (17.4s)

## DcjzjFthFLS — a man stands in his kitchen ignoring his ringing phone, then his oven's control panel lights up with an incoming call from "Unknown Caller" complete with green and red answer buttons, and he grabs his head
- source: @rghoss1 | https://www.instagram.com/reel/DcjzjFthFLS/
- lane: general
- first-seen: 2026-08-29 | status: FRESH
- stats-at-capture: 17936 likes / 346 comments (172.47x account median)
- joke-structure: the thing you blocked comes back through an object that has no business being able to reach you. An appliance impersonates a person. The recognition trigger is the phone-call UI appearing somewhere it cannot possibly appear — a scroller reads the green/red buttons instantly and only afterwards works out it is an oven
- the-beat: setup 0:00-0:02 (man side-on, staring at his phone, not answering), the turn is the cut at 0:02 to the oven panel reading "Unknown Caller". Cut ON that cut. Reaction tail 0:04.7-0:06.2, hand to head. The whole clip is 6.2s and the turn is the only beat in it
- audio-model: flexible — a ringtone under the oven shot is the sting, but the panel reads without any audio at all, so it survives being ducked under a trending track
- pairs-with: anything you shut off that finds another way in. imabgold's is exactly his own top-hold reel written as an object gag: "I closed the laptop. Then the phone started." bambi: the nap you finally got, and the doorbell
- clean-window: burned caption "When you block your toxic ex from everywhere and your oven starts ringing…." sits at the TOP of frame and is held the whole 6.2s, so there is no clean stretch — this passes on the BAND. Verified by cropping and looking, not by row-scan: `crop=517:920 at x=101,y=360` -> 2.09x upscale, clears the caption completely on BOTH the oven-panel frame and the reaction frame. The probe called this 2.78x and was wrong (it flagged the static bright kitchen backsplash as text)
- file: clips/DcjzjFthFLS.mp4 (6.2s)

## Dcme2Sch4-m — a white humanoid robot sprints down a stadium track at the World Humanoid Robot Games with a flailing, splayed-legged gait, overtaking a black robot that has already fallen flat, and later collects a certificate at a victory ceremony
- source: @pubity | https://www.instagram.com/reel/Dcme2Sch4-m/
- lane: general
- first-seen: 2026-08-29 | status: FRESH
- stats-at-capture: 77617 likes / 2155 comments (66.59x account median)
- joke-structure: a machine doing a human thing almost right, and the almost is the joke. Nothing performs — the robot is trying its hardest and the body language reads as panic. The recognition trigger is the gait itself: legs splaying outward mid-stride while another robot lies face-down behind it, readable in the first half second with no context
- the-beat: the usable beat is the FIRST 4 seconds — 0:00-0:04, the sprint past the fallen robot. Cut anywhere in there; there is no build. 0:04-0:30 is repetitive race coverage and 0:30-0:47 is a victory ceremony with identifiable officials holding certificates, which is not funny and should not be used
- audio-model: trending sound (add in-app) — the source rides a music bed over stadium noise; nothing in the picture depends on hearing it. Do NOT bake this audio
- pairs-with: any "it technically worked" moment. imabgold: the agent that shipped the feature by the ugliest possible route, or a build that passes while visibly falling apart. Also the closest thing the bank has to a picture of "the machine is doing my job, badly, and winning"
- clean-window: caption "CLANKER STILL WINS RACE WITH THE MOST UNHINGED RUNNING STYLE" is CONSTANT for all 47.0s (measured every 2s: bright-pixel share holds at 19.3-19.5%, never drops), so there is NO clean stretch — band only. `crop=470:836 at x=125,y=0` -> 2.30x upscale, verified by cropping and looking: fully clean, no caption, no emoji tops, and the fallen robot stays in frame at the left edge
- file: clips/Dcme2Sch4-m.mp4 (47.0s)

## DcndTGJhSQT — a toddler in a yellow top holds a pink toy microphone up to a small black Pomeranian on a couch and keeps pushing it closer, the dog leans away and turns its head off refusing to speak, and the clip ends on the toddler shrieking with laughter at the camera
- source: @pubity | https://www.instagram.com/reel/DcndTGJhSQT/
- lane: general
- first-seen: 2026-08-29 | status: FRESH
- stats-at-capture: 11159 likes / 93 comments (9.39x account median)
- joke-structure: a straight-faced interview conducted on someone who never agreed to it. The comedy is entirely in the refusal — the dog's deadpan turn away from a microphone being held to its face reads as a decline, not a dodge. Recognition trigger: a mic in a face and a face pulling back
- the-beat: two beats and you probably want the second. The refusal runs 0:05-0:08 (dog leans back, head off, mic follows it); the reaction payoff is 0:10.4-0:11.7, the toddler's delighted open-mouthed laugh straight down the lens. Cut on the refusal, land on the laugh
- audio-model: diegetic (bakeable) — the toddler's babble and laugh are the beat and the clip is much weaker silent. If a trending track is going on the reel instead, this clip loses most of what it has
- pairs-with: bambi first — a one-year-old being asked a question and answering by leaving. Also any "I asked and got nothing back" beat: imabgold asking the model something and getting a non-answer
- clean-window: caption "OUR POMERANIAN WAS NOT HAVING IT WITH OUR DAUGHTER'S INTERVIEW" is up 0:00-0:04.5 and gone from 0:05.0 to the end (measured: 38% bright-pixel share in the caption zone collapses to 2-3% residual couch/window brightness at 5.0s). 0:05.0-0:11.7 is a 6.7s clean stretch, NO CROP NEEDED — and both beats above sit inside it. Band fallback: y0-911 -> 512x911 crop, 2.11x upscale
- file: clips/DcndTGJhSQT.mp4 (11.7s)

## DcnaWqoMTKf — a man stands on top of a chest-high wall of loose stacked concrete blocks in a dusty yard, throws his arms up, front-flips off, lands hard in a crouch on gravel, then gets straight up and walks away barefoot
- source: #instantregret | https://www.instagram.com/reel/DcnaWqoMTKf/
- lane: general
- first-seen: 2026-08-29 | status: FRESH
- stats-at-capture: (hashtag recent_media, no account baseline) — 32 likes / 0 comments, posted today, surfaced on the new #instantregret steering tag
- joke-structure: announce the trick, then pay for it, then refuse to admit you paid for it. The arms-up celebration BEFORE the jump is what makes the landing funny; the walk-off is what makes it repeatable. Recognition trigger: a person visibly presenting themselves as about to do something impressive
- the-beat: setup 0:03.6-0:04.3 (stands, arms up), the flip 0:04.4-0:05.2, the turn is the landing at 0:05.4 — he crumples into a crouch and stays down a beat. Payoff tail 0:06.2-0:08.9, he stands and briskly walks it off. Cut on the landing; the walk-off is the better ending if you have room for it
- audio-model: trending sound (add in-app) — the source is a repost carrying a music bed. Do NOT bake it
- pairs-with: any confident announcement followed by an ungraceful cost. imabgold: "I said I'd ship it before dinner" then the 11pm laptop. The declared-then-punished shape, not the cascade shape
- clean-window: ⚠ CROP IS MANDATORY ON THIS ONE, not optional. The top ~36% of the frame is a third-party repost card ("earthwidequacks / The only meme account worth your screen time. Mashallah !!") held for all 8.9s — using this clip full-bleed would put another meme account's self-promo in the reel. The footage itself carries NO burned text at all: `crop=457:813 at x=131,y=467` -> 2.36x upscale, verified by cropping and looking across the flip and the landing. The probe called this 11.74x and was wrong (it read the white promo card AND the frozen blue sky as text)
- NOT the chain reaction: this is a self-inflicted single-body fail, nothing cascades. OPEN GAP 3 stays open; playbook #48 is still the only thing in the bank that pictures it
- file: clips/DcnaWqoMTKf.mp4 (8.9s)

## DcbaubeBRrc — a creator talks to camera under a floating `Claude:` label speaking the AI's line, then an unbroken screen recording of the model's real multiple-choice question with his hands typing an answer into it, then a `Me` label over an anime reaction
- source: #vibecoding | https://www.instagram.com/reel/DcbaubeBRrc/   <- hashtag find, no username available (hashtag media is privacy-stripped; the ig-pulse capture never recorded a handle)
- lane: tech
- first-seen: 2026-08-25 (ig-pulse spike capture `20260825-085538`) | status: FRESH
- stats-at-capture: (hashtag recent_media, no account baseline) — surfaced as a #vibecoding spike
- joke-structure: a UI screenshot turned into a two-hander. Floating speaker labels assign the voices, so the model's own dialog box stops being a screenshot and becomes a character talking; the recognition trigger is the label appearing over a face in the first second
- the-beat: EXACTLY 3 scenes and the proportions ARE the format — 0.00-2.93 (23.7%) talking head under the `Claude:` label; 2.93-10.60 (62.1%) the real question on screen, hands typing, THE LONG HOLD; 10.60-12.35 (14.2%) `Me` + reaction. Total 12.35s
- audio-model: flexible — the labels carry the exchange, no dialogue is load-bearing
- pairs-with: any "the machine asked me something and I did not really read it" beat. The channel's own material belongs on the REACTION beat, where its confession replaces the anime button
- clean-window: **n/a — OPENER-ONLY DONOR (its caption IS the setup).** Its burned `Claude: / Which plan do you prefer?` label occupies rows 372-672 for the whole first scene and is the asset, not a defect. ⚠ **Do NOT cut this clip into a PAYOFF beat** — under BANK.md 4b the no-surviving-caption test binds there and this clip cannot pass it. Opener or setup only. 720x1280, natively 9:16, so 1080x1920 is a pure 1.5x scale with no crop
- file: clips/DcbaubeBRrc.mp4 (12.35s)
- spliced: 2026-08-29 `press_1_splice` — beats 1-2 whole (0.000-10.600), Marcus's own reaction replacing the anime button. First splice of this clip
- spliced: 2026-08-29 `press_1_refilm` (v3) — the FINAL beat (10.600-end) whole, as the reel's payoff, plus the glyph matted from frame 0 onto the re-filmed opener card. **Marcus's explicit order overrode this entry's opener-only/payoff-beat warning for this reel** ("The last frame: we're gonna splice it from his video"); the warning stands for unattended runs

## Dcmc8tbNFCX — a carpenter crouched on open floor joists loses his balance and folds face-down across them in about a second, legs up, while his workmate just stands there watching; he picks himself up after
- source: @pubity | https://www.instagram.com/reel/Dcmc8tbNFCX/
- lane: general
- first-seen: 2026-08-28 | status: FRESH
- stats-at-capture: 8298 likes / — comments (23.4x account median)
- joke-structure: composure to heap with nothing in between — a tradesman working with total confidence on a half-finished floor, then folded face-down on it, while a second man stands over him and does not react at all. The bystander's flatness is half the joke
- the-beat: **CORRECTED 2026-08-28 after a full-res per-frame look — the first version of this line was written from the creator's caption and a low-res contact sheet and it was wrong.** He does NOT fall THROUGH the joists; he collapses ON them. Composure 10.0-11.2 (crouched, drilling, in control), the collapse 11.3-12.1 (crouch -> sprawled -> face-down, legs up), heap 12.1-13.0, gets up 13.0-15.9. **Tightest usable beat is 10.6-12.6 — you need the second of composure BEFORE it or the collapse has nothing to fall from**
- audio-model: diegetic (bakeable) — site noise and the drop; nothing licensed
- pairs-with: any "I was completely on top of this until I wasn't" beat — imabgold's confident build collapsing under him, a claim about competence answered by the person folding. Also strong as the LITERAL picture of somebody's output being a disaster ("this is what my friend posts"). NOT a picture of a structure failing — the floor holds, the man does not
- clean-window: **caption 0.0-7.5s, GONE from 8.0s. 8.0-16.1s (8.1s) is FULLY CLEAN at native 720x1280 — no crop, no upscale, the best donor window currently in the bank.** ⚠ Its burned caption ("WHEN YOUR COWORKER FALLS THROUGH THE FLOOR JOISTS…") covers the whole first half, so never cut before 8.0s
- file: clips/Dcmc8tbNFCX.mp4 (16.1s)

## DcmRxHPsl6u — a whippet stands still in a wide empty park, sees another dog, and detonates into a full-speed sprint with a mid-air twist before flopping into the grass
- source: @pubity | https://www.instagram.com/reel/DcmRxHPsl6u/
- lane: general
- first-seen: 2026-08-28 | status: FRESH
- stats-at-capture: 26484 likes / — comments (74.8x account median)
- joke-structure: stillness to detonation with nothing in between — the dog is motionless and composed, then goes from 0 to full sprint in one frame. The comedy is the size of the gap, not the running
- the-beat: still and composed 0-8s, the take-off around 9-11s, the sprint and the twist 11-16s, flop after. Best borrowed beat is the take-off through the twist
- audio-model: diegetic (bakeable)
- pairs-with: any "I have been completely calm about this for weeks and then it shipped" beat — the user's own restrained setup answered by disproportionate physical joy; a reaction to good news that no human face can carry
- clean-window: **caption 0-~4s, gone after. Clean from ~5s at native 720x1280, no crop needed.** ⚠ **CORRECTED 2026-08-28 (built_it build, verified twice by frame-stepping the source).** The previous line here said the "Pubity · follow" account-tag sticker "appears in the FINAL ~2s (bottom right) — do not cut the last 2 seconds". That is WRONG in both the timing and the position and it would have sent a build straight into the sticker while banning a clean window. MEASURED: the sticker animates in at **~15.0s**, is fully formed by ~15.5s, and is **GONE by ~18.7s**; it sits **lower-centre drifting to lower-left**, not bottom right. **The final 2 seconds (28-30s) are CLEAN.** The banned window is **15.0-18.7s**
- file: clips/DcmRxHPsl6u.mp4 (30.0s)

## DcmfuFaN2v9 — a mountain campsite at a lake in Tajikistan, and a car sits nose-down in the water where the campers' neighbours put it overnight
- source: @pubity | https://www.instagram.com/reel/DcmfuFaN2v9/
- lane: general
- first-seen: 2026-08-28 | status: FRESH
- stats-at-capture: 47 likes / — comments (0.13x account median — banked on donor usability, NOT on a spike)
- joke-structure: consequence without event — you never see it happen, you only see the morning after and the calm of the people dealing with it
- the-beat: the two stacked captions clear by ~4s; from there it is a slow reveal of the lake, the camp and the car in the water. There is no turn, so this lends an AFTERMATH plate, not a punchline
- audio-model: diegetic (bakeable)
- pairs-with: any "we found out in the morning" beat where the user's own footage carries the cause and this is the state of things afterwards. HONEST SCOPE: low action, so it is a cutaway plate and should not be asked to carry a payoff
- clean-window: **two stacked captions 0-4s, both gone after. Clean from ~4.5s at native 720x1280, no crop needed.**
- file: clips/DcmfuFaN2v9.mp4 (13.5s)

## DcjD2G_BO6p — a mom packs her kid's school lunchbox, walks to the pantry, comes back with a family-size Oreo pack, and loads an entire unbroken sleeve of cookies into the box next to four grapes
- source: @parents | https://www.instagram.com/reel/DcjD2G_BO6p/
- lane: family
- first-seen: 2026-08-28 | status: FRESH
- stats-at-capture: 5759 likes / 356 comments (53.88x account median)
- joke-structure: malicious compliance with a news cycle. One line of held text, "POV: Moms Packing Lunchboxes After Oreo-Gate", frames everything, and then the reel simply performs the overreaction at full length with a completely straight face. She never mugs, never speaks, never acknowledges the joke — the escalation is entirely in the quantity, and the four sad grapes left in the other compartment are what makes it land. Comment rate is the highest in today's pool by a distance: 1 comment per 16 likes, where the bank's comedy canon runs about 1 per 200, because the caption ("be honest, are you packing a little differently or no?") turns a joke into a question the viewer answers about their own kitchen
- the-beat: 0:00-0:02 she sets an empty blue bento on the counter, nothing funny yet. 0:03-0:04 she crosses to the pantry, and the cut back is the turn: a full Oreo family pack fills the frame. 0:05-0:09 she opens it and pulls out a whole intact sleeve. 0:10-0:14 the sleeve goes into the box, grapes shoved aside. 0:15-0:16 lid closes on the logo. Shortest usable donor is 0:03-0:06 (pantry-to-reveal is the whole joke); 0:10-0:15 if you want the loading to be the punchline
- audio-model: trending sound (add in-app) — no dialogue and no diegetic beat, the footage is cut to a bed. Nothing is lost by replacing it
- pairs-with: any "I heard the warning and did the opposite" beat. imabgold's is being told to keep the context window small and pasting the entire repo in; bambi's is being told the toddler needs a balanced lunch. Also the general shape of over-supplying something after being told to ration it
- CAVEAT: on-screen branding is unavoidable — the Oreo pack fills five seconds of frame and the final shot is a close-up of the OMIE lid. Kept under guard 7 as a meme-with-a-logo (made to be funny about a news cycle, not to sell cookies), but a customer channel that cannot show third-party brands should skip it
- file: clips/DcjD2G_BO6p.mp4 (17s)

## DckQiZXhN_F — two parents start slow-dancing alone in their kitchen and are progressively invaded by their own children until four kids are wedged between them and the dance is over
- source: #parentsofinstagram | https://www.instagram.com/reel/DckQiZXhN_F/
- lane: family
- first-seen: 2026-08-28 | status: FRESH
- stats-at-capture: 1000 likes / 27 comments (hashtag recent_media, no account baseline)
- joke-structure: escalating interruption, played entirely by arrivals. One line of held text, "POV: you are married with children…", sits over the whole thing and is never added to. The camera never moves. The joke is a countdown nobody announced: the couple gets roughly four seconds alone, then a kid enters frame, then another, then two more, and the parents keep dancing through it because they have no choice. Nobody reacts to the camera and nobody says the joke out loud
- the-beat: 0:00-0:04 the two of them dancing, alone, genuinely enjoying it — the setup only works if you let this run. 0:05 the first child enters frame left, which is the turn. 0:06-0:12 the pile-on, one arrival at a time. 0:13-0:17 fully engulfed, still swaying. Shortest usable donor is 0:03-0:08 (alone → first invader); the full 0:00-0:17 if you want the whole escalation
- audio-model: trending sound (add in-app) — they are dancing to a licensed track and the clip is cut to its beat. Never bake this audio in; pick the library sound natively when posting
- pairs-with: any "we got exactly four seconds of it" beat. bambi's is the parents' dinner, the coffee, the conversation, the highchair moment that lasts until the food arrives; imabgold's is the ten minutes of focus before the notifications land. The user's own footage supplies who does the invading
- file: clips/DckQiZXhN_F.mp4 (18s)

## DcjrEHSNT02 — filmed from inside a parked car: a woman leans into the open passenger window and lectures a teenage boy in a tracksuit who refuses to look at her, stares dead ahead, and finally turns away
- source: @pubity | https://www.instagram.com/reel/DcjrEHSNT02/
- lane: general
- first-seen: 2026-08-28 | status: FRESH
- stats-at-capture: 146070 likes / 247 comments (10.40x account median)
- joke-structure: one party completely unbothered, the other completely mortified, in the same frame the whole time. Held text for the first five seconds: "MOM SHOWED UP TO HER SON'S SECOND DAY OF HIGH SCHOOL…" and then nothing more is written. She talks continuously and cheerfully; he does not respond once. The comedy is the asymmetry, and it is carried entirely by his face — there is no punchline event, the reel just holds on someone enduring
- the-beat: 0:00-0:05 held text over her arriving at the window, hand gesturing. 0:06-0:11 she is in full flow and he has locked his eyes forward. 0:12-0:14 he glances into the lens, which is the biggest single beat. 0:15-0:17 he turns fully away. Shortest usable donor is 0:12-0:15 (the look into camera on its own is a reaction cutaway); 0:00-0:08 if you want the setup
- audio-model: diegetic (bakeable) — her talking is the texture, though nothing she says is the joke. Works muted under a track too, because the gag is visual
- pairs-with: any "someone would not stop and I could not leave" beat. imabgold's is being talked at about the app by someone who does not use it; bambi's is any grandparent-at-the-car-window goodbye. The endured-face reaction shot is the reusable part
- CAVEAT: the subject is an identifiable minor and the joke is at his expense. Fine as a canon reference, but a credibility or customer channel should not make a stranger's kid the butt of a cut
- file: clips/DcjrEHSNT02.mp4 (17s)

## Dcjs-mosR_f — static security-cam wide of a living room: one dog wanders in, and within three seconds a second dog, a cat and the man asleep on the couch have all bolted upright in a single cascade
- source: @pubity | https://www.instagram.com/reel/Dcjs-mosR_f/
- lane: general
- first-seen: 2026-08-28 | status: FRESH
- stats-at-capture: 62827 likes / 322 comments (4.49x account median)
- joke-structure: chain reaction, named in advance and then delivered. Held text over the first half, with two words highlighted yellow: "MY DOG WALKED IN AND STARTED A **CHAIN REACTION** OF UNINTENTIONAL SURPRISES". The camera is a fixed ceiling-corner security cam and never moves, so every reaction happens inside one unbroken frame and you can watch the cause travel across the room. The small input is a dog walking in; the disproportionate output is four bodies airborne at once
- the-beat: 0:00-0:02 the room at rest — a man sprawled on a low couch, a cream dog behind him, a cat in the foreground. 0:03 the input: the second dog enters frame left. 0:04-0:06 the cascade — the man bolts up, the couch dog stands, the cat wheels and flees, a black-and-white dog charges in. 0:07-0:11 everyone converged, milling, over. Shortest usable donor is 0:02-0:06, and it is the whole asset: input, cascade, aftermath
- audio-model: diegetic (bakeable) — security-cam room tone and scrabbling claws, which sells that nobody staged it. A polished track fights the surveillance texture; if you must add one, duck it hard
- pairs-with: THE chain-reaction picture the bank has been missing (OPEN GAP 3). imabgold's most repeatable true story is "I changed one thing and it moved everything" and this is the first FRESH entry that can literally picture it — one small approved change, then the cascade. bambi's is one toddler noise setting the whole restaurant table off
- file: clips/Dcjs-mosR_f.mp4 (11s)

## DcjkZ-JMFJk — an office ensemble stands around a styrofoam tray of raw ground beef on a conference table and interrogates it into the ground, with real news headlines popping in as receipts under every claim
- source: @morningbrew | https://www.instagram.com/reel/DcjkZ-JMFJk/
- lane: tech
- first-seen: 2026-08-28 | status: FRESH
- stats-at-capture: 21254 likes / 526 comments (4.55x account median)
- joke-structure: escalating Q&A where every answer makes it worse, receipted the whole way. A CNBC card opens it ("Trump to allow import of 300,000 metric tons of ground beef without tariff") and one colleague announces "good news, guys, barge meat just dropped." Each follow-up question gets an answer that removes a reason to feel good — where is it from, "we don't know, because they won't tell us"; is it poisonous, "everything's poisonous these days"; will it help ranchers, "no, it's actually something they're pretty pissed about" — and a real headline screenshot lands as proof under each one. Best gag is a whiteboard hard cut: "no, no, that's 30%, which is communism" → "25% is patriotism." The button is a guy carrying the tray through the office announcing there is mystery meat in the kitchen that is toxic and smells bad, but it is 25% below market price. Comment rate 1 per 40 likes, five times the comedy canon's
- the-beat: 0:00-0:04 headline card + "barge meat just dropped", the cleanest cold open. 0:05-0:18 the question ladder with receipts. 0:19-0:24 the communism/patriotism whiteboard cut, the sharpest single beat in the clip. 0:25-0:38 the ranchers answer and "okay, then who the hell is this for?" 0:39-0:45 the office announcement button. Shortest usable donor is 0:19-0:24; 0:00-0:05 if you only want the absurd-good-news open
- audio-model: diegetic (bakeable) — it is a dialogue skit with burned-in subtitles. There is no version of this with a track over it
- pairs-with: any "I asked the obvious follow-up questions and every answer was worse" beat — imabgold's is reading what the model actually changed, one question at a time. Also the template shape: a claim on screen, a receipt pinned under it, and a final "who is this for?"
- CAVEAT: explicitly political (tariffs, a named president, a communism/patriotism punchline). Usable as a structure reference for any account; the footage itself should not go near a customer channel that has to stay neutral, and @imabgold's brand.md bans news-pegged cuts outright
- file: clips/DcjkZ-JMFJk.mp4 (45s)

## DchxQobpYeD — a man dressed for an office (navy sweater, white collar, chinos) walks up to a storm-felled tree blocking a wet forest road at dusk, comes back with a full-size petrol chainsaw, and cuts the entire trunk out of the road; one line of held text the whole way: "BRO WAITED HIS WHOLE LIFE FOR THIS MOMENT"
- source: @pubity | https://www.instagram.com/reel/DchxQobpYeD/
- lane: general
- first-seen: 2026-08-27 | status: FRESH
- stats-at-capture: 147974 likes / 3383 comments (202.48x account median)
- joke-structure: absurd over-preparedness, crowned by a narrator. The gap is between how he is dressed (commute clothes, glasses, good shoes in a soaking ditch) and the fact that a professional chainsaw was in the boot and he knows exactly how to swing it. He never mugs for camera, never acknowledges the joke — the held text does all the winking, he just works. Highest comment rate in today's whole candidate pool (1 per 44 likes): people argue in the comments about whether carrying a chainsaw is normal
- the-beat: 0:00-0:03 he stands at the tree empty-handed, nothing funny yet, pure setup. Reveal 0:03-0:05, he strides back in with the saw already running. 0:06-0:40 is the work — cutting the trunk, hauling branches. 0:41-0:53 the road is clear and he walks back past camera carrying the saw. Shortest usable donor is 0:00-0:05 (the reveal is the whole joke); 0:03-0:12 if you want the saw to bite on screen
- audio-model: diegetic (bakeable) — the chainsaw firing is the sting and the rain-hiss is the texture. A trending track over this deletes the gag
- pairs-with: user footage that states an ordinary problem, then cuts to the user's weirdly specific preparation for it — imabgold saying "I have a script for that" after describing a manual chore; a parent producing the exact snack/wipe/toy from a bag at a restaurant meltdown
- file: clips/DchxQobpYeD.mp4 (53s)

## Dch_JVZJUqV — sofa POV (filmer's bare legs in frame): a small cream dog has been sent to time out, stands nose-jammed into the crack of a closed white door and audibly complains at it without stopping, then turns and stalks off; held text for the first 3 seconds reads "MY DOG MADE IT VERY CLEAR HE WASN'T HAPPY ABOUT TIME OUT"
- source: @pubity | https://www.instagram.com/reel/Dch_JVZJUqV/
- lane: general
- first-seen: 2026-08-27 | status: FRESH
- stats-at-capture: 16538 likes / 194 comments (22.38x account median)
- joke-structure: the sulk that argues back. The punished party does not accept the punishment and litigates it out loud at the door, which is funny because it is exactly how a person sulks and exactly what a dog cannot actually be doing. The filmer stays put on the sofa the whole time — the refusal to get up is half the joke
- the-beat: 0:00-0:03 text card + the dog at the door with its nose in the gap, already complaining. 0:03-0:07 the text drops and the grumbling continues uninterrupted over a static, boring frame. 0:07-0:10 the dog gives up, turns and walks off past camera. Cut anywhere in 0:00-0:07; the payoff is a sound, not an image, so do not cut on a visual
- audio-model: diegetic (bakeable) — the dog's grumbling IS the clip. Muted or covered by a track it is ten seconds of a door. Never bake a trending sound over this one
- pairs-with: any moment where the user is told no and keeps arguing anyway — imabgold hitting a usage limit and continuing to type at it; a toddler negotiating from the naughty step. Their footage is the ruling, this is the appeal
- file: clips/Dch_JVZJUqV.mp4 (10s)

## DcgPzrwP7YO — a creator in a bright orange tee holds up two phones side by side, an ordinary iPhone and one wearing a motorised gimbal head ("Robot Phone"), shoots the same panorama of the same room on both, and reacts to the results with a full open-mouthed stare down the lens; huge on-screen labels ("Panorama", "iphone", "Robot Phone") mark each round
- source: @techburner | https://www.instagram.com/reel/DcgPzrwP7YO/
- lane: tech
- first-seen: 2026-08-27 | status: FRESH
- stats-at-capture: 104441 likes / 185 comments (12.19x account median)
- joke-structure: side-by-side comparison with a reaction-face payoff. There is no verbal punchline — the mechanism is a two-column test where the second column does the work by itself and the presenter's face supplies the laugh. Cleared the ad gate on intent: no code, no link, no "buy", the gadget is the bit, not the offer. Be honest with an architect: the comedic load here is thin and the value is the SHAPE (two things, same task, one absurd result), not the punchline
- the-beat: 0:02 he raises both phones to camera, label "Panorama". 0:06-0:20 the two screens run side by side in hand and the gimbal head visibly pans itself while the iPhone sits still. 0:22 label "Robot Phone" over the result. 0:34-0:37 the shocked-face close-up, saw-eyes and open mouth, holding the gimbal phone at his temple. Best donor cuts are the 0:06-0:20 two-screens shot (as a comparison bed under your own text) or the 0:34-0:37 face on its own as a reaction beat
- audio-model: flexible — the presenter's Hindi-English voiceover is not load-bearing, so this ducks cleanly under a trending track; the shocked-face beat also works silent under a text card
- pairs-with: any "my old way vs the new way" cut where the user's own screen is one of the two columns — imabgold's manual spreadsheet next to the agent doing it; a parent's pre-kid packing next to post-kid packing. Their material is column one and the payoff face
- file: clips/DcgPzrwP7YO.mp4 (37s)

## DciiHyLJ0ab — a blonde toddler on a Southeast Asia trip gets treated as a minor celebrity by the staff wherever the family eats: a woman leans across a lounge to take his hands, restaurant staff come to the table to hold and hug him mid-service, a member of staff kneels to feed the koi pond with him; one held text line the whole clip: "Nobody warns you about THIS when you take a blonde toddler to Southeast Asia..."
- source: #toddlertravel | https://www.instagram.com/reel/DciiHyLJ0ab/
- lane: family
- first-seen: 2026-08-27 | status: FRESH
- stats-at-capture: 12 likes / 1 comment (hashtag recent_media, no account baseline)
- joke-structure: recognition, not a gag — the "nobody warns you about" complaint frame applied to something that is obviously lovely, so the joke is the pretend grievance. Structurally it is a montage against a single held claim: every shot is another piece of evidence for the same line, and it never resolves or escalates, it just accumulates
- the-beat: 0:00-0:04 the text card lands over the first grab (lounge, two women crowding him). 0:04-0:10 the koi pond with a staff member kneeling beside him. 0:10-0:15 restaurant floor at night, staff reaching over the table to take his hand. 0:15-0:18 a hug he does not consent to and does not mind. There is no single payoff beat — take any 3-4 second grab as an illustration under your own line. Best single donor is 0:10-0:15 (the dining-room reach-in)
- audio-model: flexible — room noise and a bit of chat, nothing load-bearing. This is a montage, so it takes a trending track cleanly; add it in-app, do not bake one
- pairs-with: the family-travel version of "the thing you did not plan for" — bambi.map's eating-out-with-a-baby setups, where the user's own footage is the table/highchair problem and this is what actually happens instead. Also any "the locals adopted my kid" beat in a customer's travel cut
- file: clips/DciiHyLJ0ab.mp4 (18s)

## DcT5FflAnMc — [PRUNED DO-NOT-SPLICE] a 2:20 unbroken car-selfie monologue under one held banner, "Baseline interpersonal skills are not getting taught" — sincere, no joke, identifiable stranger; format kept as playbook #46 · https://www.instagram.com/reel/DcT5FflAnMc/ · first-seen 2026-08-27

## DcUOFLpBUD5 — [PRUNED DO-NOT-SPLICE] a 2:11 studio explainer pinning a real $16 listing against a $540 one to state what clothing actually costs — sincere, welded to that creator and that claim; format kept as playbook #47 · https://www.instagram.com/reel/DcUOFLpBUD5/ · first-seen 2026-08-27

## Dceg78QTZrw — a young man sits alone on an Alaskan riverbank filming himself, and a full-grown brown bear comes out of the water and runs past him at close range to chase a salmon; he does not move, does not stand, and just keeps sitting there
- source: @houseofhighlights | https://www.instagram.com/reel/Dceg78QTZrw/
- lane: sports
- first-seen: 2026-08-26 | status: FRESH
- stats-at-capture: 437531 likes / 1867 comments (6.24x account median)
- joke-structure: stillness against catastrophe. The comedy is entirely in what does NOT happen — the bear is the event, and the subject's total lack of reaction is the punchline. A tweet card is burned across the top third for the whole runtime ("Adapt was fearing for his life after a wild brown bear ran directly infront of him in order to catch a salmon"), so the viewer has been told the stakes and is watching a man decline to act on them
- the-beat: 0:00-0:11 is the sit — subject in frame left, empty river, a bear tiny in the far distance. The turn is 0:12-0:20, the bear charging through the shallows toward frame and past him, water everywhere. 0:21-0:32 is the bear catching and eating the salmon a few metres out. Payoff at 0:33-0:38: cut back to him still sitting, glancing sideways, saying nothing. Best donor cut is 0:11-0:20 (charge) or the 0:33-0:38 non-reaction on its own. The tweet card sits in the top ~25% of frame — crop it out or it reads as someone else's post
- audio-model: diegetic (bakeable) — river and the bear hitting water carry the whole beat, and the absence of a voice is the joke. Adding a track over this actively costs you the gag
- pairs-with: the user carrying on flatly while something enormous goes past — imabgold's "the agent rewrote three files I never asked it to touch and I kept typing"; a parent's "the toddler emptied the entire cupboard and I finished my coffee". Their footage is the ordinary task, this is the thing going by
- file: clips/Dceg78QTZrw.mp4 (39s)

## Dce-56EPoI9 — a humanoid robot at a competition squats, cleans a tiny barbell over its head, holds it for a beat, then overbalances backwards and slams flat on the floor; red-shirted staff run in and carry the body off
- source: @pubity | https://www.instagram.com/reel/Dce-56EPoI9/
- lane: general
- first-seen: 2026-08-26 | status: FRESH
- stats-at-capture: 197843 likes / 4607 comments (4.02x account median)
- joke-structure: success then immediate structural collapse. It gets the lift — that is the trap. The failure arrives one second AFTER the win, which is a different and better shape than a straightforward fail; a burned-in headline ("CLANKER LIFTS WORLD'S SMALLEST WEIGHT AND DIES") pre-announces the ending so the whole lift is dread. Also the closest thing in the bank to OPEN GAP #3's chain reaction: one small overbalance and the entire machine goes down, then a crew has to come collect it
- the-beat: 0:00-0:07 setup, robot crouches to the bar in an arena with judges at a table behind it. 0:08-0:12 the clean and the hold, arms locked out. Turn at 0:13 — it tips backwards and hits the deck hard. 0:14-0:23 the aftermath: the countdown clock still running at 00:00, staff crossing frame, the robot being lifted like a stretcher case. Cut on the turn at 0:13; the aftermath from 0:16 is a second, separate donor (the cleanup crew) if you want the cascade rather than the fall
- audio-model: flexible — arena PA and the impact are present and the clank of the landing is a real sting, but it survives being muted under a trending track because the visual turn is unambiguous
- pairs-with: the user winning the small thing and immediately paying for it — imabgold's "it compiled, and then everything else stopped working"; the ship-it-then-watch-it-fall beat. Their footage is the attempt and the win, this is the second after
- file: clips/Dce-56EPoI9.mp4 (23s)

## DcesVmGyLIu — Selfie POV: held text "startup founders once the product is live and now it's time to start the content humiliation ritual" over a founder staring deadpan into his phone's front camera at an office desk; ~1.5s in his hands rise and he buries his face in them, and holds there to the end
- source: @gauravbuild | https://www.instagram.com/reel/DcesVmGyLIu/
- lane: tech
- first-seen: 2026-08-26 | status: FRESH
- stats-at-capture: 104 likes / 2 comments at 17h (manual add from Marcus's pointer; small account, format-value not stats-value)
- joke-structure: the ritual named, then performed — the text frames making founder content as a humiliation rite, and the payoff is the shame gesture (face buried in both hands) played completely straight to the camera he is supposed to perform for
- the-beat: deadpan stare 0:00-0:01.5, hands rise ~0:01.5-0:02, face buried 0:02-0:06.3. One selfie shot, 6.3s, loops cleanly (the buried face releases back into the opening stare)
- audio-model: unknown at capture (logged-out embed hid the attribution; audio track present, 39kbps) — treat as trending sound, add in-app
- pairs-with: any "the building was the easy part" confession — imabgold's own 08-26 replica swapped the stare-to-camera for iMac-desk despair (hand to forehead → head in hand). The face-bury beat is the splice-worthy atom: it closes any "I have to promote this now" setup
- file: clips/DcesVmGyLIu.mp4 (6.3s)

## DcejaQYskRm — a garden owl on the lawn spreads its wings and puffs itself to roughly twice its size to intimidate a house cat standing a metre away; the cat looks at it, does nothing, and simply walks off
- source: @pubity | https://www.instagram.com/reel/DcejaQYskRm/
- lane: general
- first-seen: 2026-08-26 | status: FRESH
- stats-at-capture: 135925 likes / 1328 comments (2.73x account median)
- joke-structure: maximum threat display, zero effect. A bluff performed at full commitment against an audience that will not even register it. One locked wide shot, no cuts, no camera move — the whole thing plays in one continuous take, which is the shape @rghoss1 gets comments with (OPEN GAP #4)
- the-beat: CORRECTED 2026-08-27 after frame-stepping the file. The previous line here claimed "the turn is 0:05-0:06 when the cat crosses the frame and leaves, unimpressed". THAT IS NOT IN THE CLIP — the cat's centroid moves x=627 to x=665 across all 8.26s and it never leaves frame. A beat was designed, built and killed at QA on that invented sentence (job 8a0fc66a). What the clip ACTUALLY offers: the owl's display is at full spread from 0:00 and simply holds, with the cat standing near it, side-on and plainly indifferent, for the whole run. There is NO turn and NO exit. It lends a static tableau of "maximum display, zero reaction", nothing more. Caption clears at ~5.0s so only 5.15-8.26s is usable, and both subjects need a punch-in (crop 450:800:153:140) to read at reel speed 0:07-0:08 the owl is still puffed with nobody left to threaten, which is the actual payoff. At 8 seconds it needs no trimming; loops cleanly
- audio-model: flexible — quiet garden ambience (RMS -21.9 dB, the lowest of today's six), no dialogue, nothing load-bearing in the sound. This is the one clip today that is genuinely improved by a trending track laid over it
- pairs-with: the user's biggest, most elaborate effort landing on someone completely indifferent — imabgold's "I wrote a 400-line spec and it did whatever it wanted"; a parent's full performance for a toddler who walks away. Their footage is the effort, this is the reception
- file: clips/DcejaQYskRm.mp4 (8s)

## Dcd_FfvP96F — [PRUNED AD-REJECTED] a tech creator unboxes the HONOR "Robot Phone" and demos its motorised gimbal camera; a launch-day product reveal, splicing it lends HONOR's marketing · https://www.instagram.com/reel/Dcd_FfvP96F/ · first-seen 2026-08-26

## Dcftx2KsFQg — [PRUNED DO-NOT-SPLICE] young men dancing in a neon club under a Hinglish caption that carries the whole joke; generic party b-roll of identifiable strangers, unremovable burned text, nothing to cut on · https://www.instagram.com/reel/Dcftx2KsFQg/ · first-seen 2026-08-26

## DcfjdBSzEAm — [PRUNED DO-NOT-SPLICE] a sincere timestamped Dubai-Delhi-Srinagar travel vlog with a 20-month-old; the comedy is all in the caption, no turn anywhere on screen · https://www.instagram.com/reel/DcfjdBSzEAm/ · first-seen 2026-08-26

## Dcb-qSBMPs- — a mother walks into a daycare room to collect her baby after the baby's first full day there; the baby is sitting calmly on the mat playing, spots her mother in the doorway, and instantly folds into a full open-mouth sob and crawls to her
- source: @pubity | https://www.instagram.com/reel/Dcb-qSBMPs-/
- lane: general
- first-seen: 2026-08-25 | status: FRESH
- stats-at-capture: 170526 likes / 2651 comments (17.96x account median)
- joke-structure: not a joke, a delayed collapse. The composure holds for the entire ordeal and breaks the instant the safe person is in frame, which retroactively tells you the composure was work the whole time. A flat held headline ("PICKING UP MY BABY AFTER HER FIRST DAY AT CHILD CARE") is burned in from frame one so the viewer is watching for the break, not the setup. Highest ratio this bank has recorded from any account
- the-beat: 0:00-0:10 is the walk in through the door and the baby playing, unbothered, with a teacher beside her. The turn is 0:11-0:13 — the baby registers the mother, the face goes, and she starts crawling. Full cry 0:14-0:22. Payoff is the last second: at 0:35-0:36 the baby is in her mother's arms and the cry flips to a wide grin. Two donors: the 0:11-0:16 break alone, or the break-to-grin pair as an open-and-close. Note a "Pubity ✓ following" profile card is baked over the frame around 0:21-0:23, so cut before it or crop
- audio-model: flexible — there is a music bed under it (RMS -21.8 dB, sd 6.6 dB, too even to be room sound), but the cry itself is the beat and survives being ducked. Either duck the bed under a trending track or keep the cry dry
- pairs-with: the user holding it together through the thing and only breaking when someone asks — imabgold's "I was fine right up until my wife asked how the launch went"; a parent's "she was perfect at daycare, and then she saw me". Their footage is the ordeal, this face is the break
- file: clips/Dcb-qSBMPs-.mp4 (37s)

## DcbrenYTLvn — a mother waits in a parked car outside a school with the camera running; her daughter comes out, gets in, beams, and then immediately breaks down in tears saying she made the volleyball team, and holds up her phone with the roster on it
- source: @houseofhighlights | https://www.instagram.com/reel/DcbrenYTLvn/
- lane: sports
- first-seen: 2026-08-25 | status: FRESH
- stats-at-capture: 513510 likes / 6463 comments (6.92x account median)
- joke-structure: no joke — a pure reaction reveal, and the format is the reason it works: the result is never shown, only the person receiving it, and the quote she is about to say ("I made it... I tried so hard") is burned in as held text from frame one. The viewer waits for a line they have already read. This is playbook #39 (never show the win, only the reaction) with the quote-ahead text layered on top
- the-beat: 0:00-0:07 is an empty parking lot through a car window, which is dead air and should be trimmed to about two seconds. She opens the door and gets in at 0:08 grinning; the break is 0:09-0:12; the phone with the roster comes up at 0:28. Cut is the 0:08-0:13 window — arrival, grin, collapse
- audio-model: diegetic (bakeable) — RMS -44.3 dB with sd 15.9 dB, i.e. quiet car ambience with her voice as the only event, no music bed. Her line IS the payoff, so do not put a track over it
- pairs-with: the user's own "I actually got it" moment where the artifact is deliberately withheld — imabgold reading an approval email off-screen; a parent's reaction to a first word. Caution for the architect: an identifiable minor is the entire subject of this clip, so it is a shape reference for accounts that need to keep a real person off camera, and a direct donor only where reposting a stranger's child is acceptable
- file: clips/DcbrenYTLvn.mp4 (29s)

## DcZYwxNPtgR — an older man in a golf cap stands at a convenience-store ice machine holding a plastic bag open under the chute, patiently waiting for ice that is never coming, adjusting his grip and his stance for twenty-four seconds while whoever is filming keeps quiet
- source: @sportscenter | https://www.instagram.com/reel/DcZYwxNPtgR/
- lane: sports
- first-seen: 2026-08-25 | status: FRESH
- stats-at-capture: 423095 likes / 568 comments (3.27x account median)
- joke-structure: the joke is duration. Nothing happens and the clip refuses to end, so the comedy accrues from how long a dignified man will commit to a task that is not working. Held text ("Got unc with the ice machine prank 😭") admits the setup at frame one, which is what makes the waiting funny instead of sad, then the payoff is him turning to the camera at the very end and realising
- the-beat: 0:00-0:23 is one unbroken hold — he re-grips the bag, shifts his feet, leans in to read the machine, never gives up. The turn is 0:24-0:26 when he straightens up, looks straight into the lens and cracks. Two donors: a 3-4s slice of the patient waiting as a cutaway, or the full hold into the turn if the reel can spend the runtime
- audio-model: diegetic (bakeable) — RMS -24.8 dB, sd 11.4 dB, parking-lot ambience with off-camera reactions, no bed. Nothing to protect and nothing to add
- pairs-with: the user waiting on something that was never going to work — imabgold watching a build bar that has not moved in ten minutes; a parent holding a bowl under a toddler who has decided not to eat. Their footage names the wait, this man performs it
- file: clips/DcZYwxNPtgR.mp4 (27s)

## Dcc2HXlBkp8 — a baby in pink footed pyjamas toddles across a living room rug, stops dead halfway, does a short bouncing wiggle dance in place, then carries on walking as if the dance was always part of the route; her dad sits on the floor behind her watching
- source: @pubity | https://www.instagram.com/reel/Dcc2HXlBkp8/
- lane: general
- first-seen: 2026-08-25 | status: FRESH
- stats-at-capture: 22384 likes / 88 comments (2.33x account median)
- joke-structure: interruption as commitment. The gag is that the detour is treated as non-negotiable and completely unremarkable by the person taking it, and the dad in frame does nothing, which leaves the viewer as the only one reacting. Held text ("MY BABY HAD TO STOP REAL QUICK AND BUST A MOVE") gives the ending away at frame one
- the-beat: 0:00-0:03 is the walk with the text up. She drops to the rug and gets back up 0:03-0:05, and the dance is 0:05-0:08, then she walks off and turns to camera at 0:09. Cut on the stop at 0:05 — the whole donor is three seconds long
- audio-model: trending sound (add in-app) — RMS -18.5 dB at sd 5.8 dB is a constant music bed, and the dance is timed to it. Never bake this in; pick the track natively in the app so the beat lands on the stop
- pairs-with: the user interrupting their own task for something non-negotiable — imabgold's "I said one more fix and then made coffee for eleven minutes"; a parent's "we were leaving, and then this". Short enough to sit inside a longer reel without spending runtime
- file: clips/Dcc2HXlBkp8.mp4 (11s)

## DcdbMbPzkk2 — the Charlie Day "Pepe Silvia" scene from It's Always Sunny: a man in a shirt and tie rants in front of a wall of pinned papers and red string, gesturing wildly, under held text reading "POV: Me explaining that it works on my machine"
- source: #programmerhumor | https://www.instagram.com/reel/DcdbMbPzkk2/
- lane: tech
- first-seen: 2026-08-25 | status: FRESH
- stats-at-capture: 1004 likes / 0 comments (hashtag recent_media, no account baseline)
- joke-structure: borrowed-intensity mismatch. A famous scene of a man coming apart over a conspiracy nobody else can see is relabelled as a mundane developer excuse, and the joke is the size of the gap between the delivery and the stake. The clip is six seconds and the text does all of the specifying, which is exactly what makes the shape reusable
- the-beat: there is no turn inside it — the whole 0:00-0:05 is one continuous escalation, so it works as a reaction cutaway rather than a setup. Cut it in whole against the user's own line and let it end on its own
- audio-model: trending sound (add in-app) — RMS -17.0 dB at sd 4.8 dB is a laid-over bed, not the scene's dialogue, and the underlying footage is licensed television either way. Treat the audio as unusable and add the track in-app
- pairs-with: the user defending something indefensible with total conviction — imabgold's "it ran fine when I tested it" over a screen recording of it not running fine; the founder explaining why the thing that broke was not the thing they changed. Their footage states the claim, this face is the defence. Note: recognisable copyrighted TV footage, so it lends energy but never provenance
- file: clips/DcdbMbPzkk2.mp4 (6s)

## Dccs_hJIyZr — [PRUNED DO-NOT-SPLICE] a static "POV :- Only CS people know / There is no place like 127.0.0.1" text card over generic scrolling-code b-roll, with a third-party @Code.Script.Lab watermark burned across every frame · https://www.instagram.com/reel/Dccs_hJIyZr/ · first-seen 2026-08-25
## DcYoFWAR1o_ — Erling Haaland walks into a bathroom to show his girlfriend a fresh buzzcut; she gets one look, both hands go over her mouth and she laughs for twenty seconds while he stands there holding a completely straight face
- source: @sportscenter | https://www.instagram.com/reel/DcYoFWAR1o_/
- lane: sports
- first-seen: 2026-08-24 | status: FRESH
- stats-at-capture: 960815 likes / 4286 comments (7.83x account median)
- joke-structure: self-inflicted change, and the whole payoff is one other person's reaction to it. He never defends the haircut, never asks what she thinks, never breaks — the comedy is entirely the gap between how much she is laughing and how little he is doing. A sentence-case headline ("Erling Haaland reveals his new haircut to his girlfriend 😂") is burned in from frame one and gives away the ending on purpose
- the-beat: he comes in and she sees it at 0:02-0:04; hands over the mouth at 0:05, and the reaction runs unbroken to about 0:10; from 0:11 the clip is his deadpan hold, camera close, eyes level, doing nothing at all through 0:23. Two clean donors here — the 0:05-0:09 reaction on its own, or the 0:12-0:18 deadpan stare as a reaction shot to somebody else's line
- audio-model: diegetic (bakeable) — her laughing and the "you look really tough" line are the beat, and the audio is dynamic (sd 4.4 dB) rather than a music bed. Do not put a track over the laugh
- pairs-with: the user showing someone a decision they already made and refusing to justify it — imabgold turning the laptop around to show what the AI shipped while a friend loses it; a parent revealing the haircut they gave the toddler themselves. Their footage makes the claim, this face absorbs the verdict
- file: clips/DcYoFWAR1o_.mp4 (29s)

## DcWah9DuSnM — [PRUNED DO-NOT-SPLICE] a pinned tweet card over a full ESPN Finals broadcast; format kept as playbook #43, footage unusable (score bug on every frame, no turn to cut on) · https://www.instagram.com/reel/DcWah9DuSnM/ · first-seen 2026-08-24


## DcZFHoVNkmC — a locked-off hallway camera watches a cat flap for five seconds under the text "TODAY I FOUND OUT WHY THERE'S ALWAYS MUDDY MARKS ON THE WALL…", then a cat wedges itself halfway through, braces both back feet flat against the door and walks itself up the wall to get free
- source: @pubity | https://www.instagram.com/reel/DcZFHoVNkmC/
- lane: general
- first-seen: 2026-08-24 | status: FRESH
- stats-at-capture: 252849 likes / 1445 comments (4.47x account median)
- joke-structure: standing mystery, mundane answer, no narration. The text poses a question the viewer has effectively already had ("why is there always a mark there") and then withholds; the footage answers it without a single word, and the answer is funnier than any explanation because the animal is plainly not aware it is doing anything unusual
- the-beat: text card holds 0:00-0:04 with nothing happening, which is what buys the payoff; the stuck-and-climbing struggle runs 0:05-0:13 and the wall-walk at 0:07-0:11 is the actual reveal; it drops through at about 0:13 and struts straight at the lens 0:15-0:19. Best short donor is 0:06-0:12; keep the text card on the front if the reel needs the setup
- audio-model: trending sound (add in-app) — the clip's own audio is room tone at -31 dB, there is nothing to bake. This one takes a library track cleanly and needs one
- pairs-with: the user's own recurring unexplained side effect finally caught in the act — imabgold finding out why the same file keeps changing overnight; a parent finding out how the handprints get on the ceiling. Their footage states the mystery, this is the culprit doing it on camera
- file: clips/DcZFHoVNkmC.mp4 (20s)

## DcWaRKKRIz9 — a fan filming from the stands at Austin FC heckles the referees walking off after the final whistle with "I LOVE RULES!", and one of the refs walks over, reaches up and formally shows him a yellow card
- source: @sportscenter | https://www.instagram.com/reel/DcWaRKKRIz9/
- lane: sports
- first-seen: 2026-08-24 | status: FRESH
- stats-at-capture: 425573 likes / 618 comments (3.46x account median)
- joke-structure: absurd compliment, and the authority figure plays it completely straight back. The heckle is not an insult, which is what makes it work — the ref cannot punish it, so he escalates into the one gesture he has, and the bit lands because he commits to the rules of a game that already ended
- the-beat: the shout and the refs ignoring it runs 0:00-0:09; the ref looks up at the camera at about 0:11; the card comes up into frame at 0:12-0:13 and that is the whole payoff; 0:14-0:19 is unusable camera chaos. Cut it as 0:00-0:03 for the heckle plus 0:11-0:14 for the booking, or take 0:11-0:14 alone as a pure punishment beat
- audio-model: diegetic (bakeable) — the shouted line and the crowd around it are the joke; sd 7.2 dB, this is live sound, not a bed. Muted, this clip is a shaky phone pointed at a stairwell
- pairs-with: the user getting formally penalised for something harmless — imabgold's rate limit landing the second he says he is being reasonable with it; a parent being told off by their own toddler for breaking a rule the toddler invented. Their footage is the offence, this is the sentence
- file: clips/DcWaRKKRIz9.mp4 (20s)

## DcaPS-HuaA6 — [PRUNED DO-NOT-SPLICE] a 68s save-bait listicle of six paid Singapore toddler attractions over one identifiable family's holiday footage; no turn, no payoff, follow CTA at the end · https://www.instagram.com/reel/DcaPS-HuaA6/ · first-seen 2026-08-24


## DcamR_lumeo — [PRUNED AD-REJECTED] an AI stickman "Windows vs Linux" explainer carrying a "Follow TryPitch.co" watermark on every frame; promotional funnel caught at frame-sample · https://www.instagram.com/reel/DcamR_lumeo/ · first-seen 2026-08-24


## DcVBZDiNrHF — a reliever pumps himself up on the mound after what he thinks is the last out, and the next batter walks it off over his head; final frame is the outfielder flat on the warning track while the whole park erupts
- source: @houseofhighlights | https://www.instagram.com/reel/DcVBZDiNrHF/
- lane: sports
- first-seen: 2026-08-23 | status: FRESH
- stats-at-capture: 101232 likes / 2938 comments (2.0x account median)
- joke-structure: premature celebration, immediate reversal — the clip spends its first half on somebody being certain, and its second half on the exact thing they were certain about happening in reverse. The burned-in headline ("Bro celebrated early then got walked off") spoils it on purpose, so the viewer watches the confidence knowing it is doomed
- the-beat: the pump-up close-up 0:07-0:10 is the setup and it is the most usable frame in the bank for "I thought I was done"; the ball leaves at 0:14, the crowd goes up 0:15, and the payoff is the body on the warning track 0:18-0:19. Sharpest two-cut splice is 0:08 (certainty) straight to 0:18 (collapse), skipping the baseball entirely
- audio-model: diegetic (bakeable) — broadcast commentary and the crowd turning over is what sells the reversal; a trending track on top kills the sound of 40,000 people changing their minds
- pairs-with: the user declaring a thing finished one beat too early — "pushed to main, went to make coffee"; "told her he was fully asleep"; any moment where the user's own footage shows them celebrating and the next shot shows what actually happened. Cut their claim in, then this collapse as the answer
- file: clips/DcVBZDiNrHF.mp4 (20s)

## DcWZL80RUYY — a woman films her husband on the couch and deliberately feeds him wrong football takes; he spends a full minute correcting her with rising disbelief and finally collapses backwards with his hand over his face
- source: @sportscenter | https://www.instagram.com/reel/DcWZL80RUYY/
- lane: sports
- first-seen: 2026-08-23 | status: FRESH
- stats-at-capture: 257928 likes / 5397 comments (2.83x account median)
- joke-structure: stated prank premise, one unbroken shot, victim does all the work — the text card admits the setup up front ("I decided to rage bait my husband"), so every wrong statement is funny twice: once for him and once for the viewer who is in on it. Nothing is edited; the escalation is entirely in one face
- the-beat: the premise card holds from 0:00; the reactions build through 0:20-0:55 with no visual change; the payoff is physical at 0:58-1:02, hand over the face, head back on the cushion. The only cut worth taking is that last 2-3 seconds — as a donor this clip is a reaction shot, not a bit
- audio-model: diegetic (bakeable) — the joke is what he says back. Muted this is a man sitting on a sofa. If a trending track is going on the reel, this clip has to keep its own audio under it or be cut to the silent collapse only
- pairs-with: the user's own "explaining something obvious to someone who refuses to get it" moment — imabgold re-prompting the same instruction for the fourth time; a parent negotiating with a toddler who has already decided. Their footage carries the argument, this collapse is the exhale at the end
- file: clips/DcWZL80RUYY.mp4 (62s)

## DcV-GoxMZPm — a horse lies completely flat out asleep in a field while two others stand over it; long close-ups of its head on the grass, eye half open, giant lower lip flopping loose as it twitches in its sleep
- source: @pubity | https://www.instagram.com/reel/DcV-GoxMZPm/
- lane: general
- first-seen: 2026-08-23 | status: FRESH
- stats-at-capture: 289125 likes / 2474 comments (6.44x account median)
- joke-structure: scale mismatch, total shutdown — a 500kg animal in a posture that reads as dead, with a face doing something completely involuntary. Held text ("my horse recognized my voice while he was asleep and started sleep talking") assigns intention to a body that is plainly offline, and that gap is the whole joke
- the-beat: the wide at 0:00-0:03 establishes the other horses standing normally, which is what makes the flat one funny; the usable material is the head close-up 0:22-0:32 where the lip flops on its own. Cut 0:25-0:30 for a 5-second cutaway, or 0:00-0:03 plus 0:26 if the reel needs the wide first
- audio-model: flexible — field ambience only, nothing load-bearing; this clip takes a trending track cleanly, which is rare for the bank
- pairs-with: the user's own "completely checked out" beat — imabgold's laptop still running at 2am with him face-down; the toddler who went horizontal mid-sentence; anyone answering a question while asleep. Also works as the reaction to the user's own over-ambitious plan
- file: clips/DcV-GoxMZPm.mp4 (51s)

## DcWgZqvsyBN — a toddler sits stone-faced at a restaurant table ignoring his dad rubbing his shoulders, until a plate of three strawberries lands in front of him and he breaks into a grin and reaches for one
- source: @pubity | https://www.instagram.com/reel/DcWgZqvsyBN/
- lane: general
- first-seen: 2026-08-23 | status: FRESH
- stats-at-capture: 133234 likes / 487 comments (2.95x account median)
- joke-structure: sustained bad mood, one small input, total reversal — the dad's effort is shown failing for five straight seconds so that the strawberries can undo it in one. The comedy is the disproportion: everything an adult tried did nothing, and three pieces of fruit did all of it
- the-beat: sulk held 0:00-0:05 with the shoulder rub visibly not working (do not cut this short, the failure is the setup); plate arrives 0:06; the grin lands 0:07-0:09 and that face is the frame. Cleanest splice is 0:03-0:09
- audio-model: flexible — restaurant ambience, no line of dialogue carries anything. Works muted under a trending sound, which is the normal way to use it
- pairs-with: the smallest possible fix for a problem the user made a whole production of — bambi's "we tried everything, the highchair arrived"; imabgold's "three hours of debugging, it was one missing character". This is currently the bank's closest thing to a chain-reaction donor: small input, everything changes
- file: clips/DcWgZqvsyBN.mp4 (10s)

## DcW1AFxMmzg — a kitten play-wrestles a hand held above it, then falls asleep mid-fight with both front paws still up in the air, and stays like that for the rest of the clip
- source: @pubity | https://www.instagram.com/reel/DcW1AFxMmzg/
- lane: general
- first-seen: 2026-08-23 | status: FRESH
- stats-at-capture: 101721 likes / 442 comments (2.26x account median)
- joke-structure: mid-action shutdown — the pose does not change when consciousness does, so the body stays committed to a fight that has already ended. Held text ("precious kitten falls fast asleep while playing") tells you what is about to happen and then makes you wait for the exact frame it does
- the-beat: active play 0:00-0:07, the eyes go 0:08-0:11, and from 0:12 onward it is a still life of a cat asleep with its guard up. Cut 0:05-0:14 to get both halves; 0:12-0:16 alone is the reaction shot
- audio-model: flexible — soft ambient bed, nothing diegetic to protect
- pairs-with: the user stopping dead in the middle of their own task — imabgold falling asleep with the terminal still running; a toddler out cold holding a snack. Pair the user's own "I'm fine, I can keep going" footage with this as the cut-to
- file: clips/DcW1AFxMmzg.mp4 (28s)

## DcX0I1rMz3N — [PRUNED DO-NOT-SPLICE] a 5-second static watermarked text card comparing Python lists to tuples as a metaphor for people who leave, closing on a fake ValueError; format captured as playbook #40 · https://www.instagram.com/reel/DcX0I1rMz3N/ · first-seen 2026-08-23

## DcUeHRpP7dt — a humanoid robot sprints down an empty stadium track, runs straight off the end of its lane into the padded barrier wall, and collapses face-down on the blue surface
- source: @pubity | https://www.instagram.com/reel/DcUeHRpP7dt/
- lane: general
- first-seen: 2026-08-22 | status: FRESH
- stats-at-capture: 164471 likes / 2579 comments (52.09x account median)
- joke-structure: competence setup, overrun payoff — the machine is genuinely good at the hard part (running) and has no concept of the easy part (stopping), so the failure is not clumsiness, it is a missing instruction
- the-beat: clean sprint 0:00-0:05 (it looks impressive, let it), impact into the blue wall at 0:06, then the corpse pose 0:07-0:11 which holds long enough to be its own joke. Sharpest cut is 0:04-0:08; the limp-on-the-track frame is the freeze
- audio-model: diegetic (bakeable) — empty-stadium ambience then a metallic clatter on impact; the crash sound IS the punchline, so if a trending track goes on top, duck it for that one second
- pairs-with: an agent/automation that executed the instruction perfectly and blew past the point where it should have stopped ("it ran all night and did not stop when it was done"); any "I was impressed right up until the last second" beat; a founder claim about speed answered by what speed costs
- file: clips/DcUeHRpP7dt.mp4 (11.6s)

## DcUQOH9srXf — a man goes headfirst down a waterslide, hits the pool and skips across the surface like a flat stone instead of sinking, then stands up in the shallow end unbothered
- source: @pubity | https://www.instagram.com/reel/DcUQOH9srXf/
- lane: general
- first-seen: 2026-08-22 | status: FRESH
- stats-at-capture: 19089 likes / 128 comments (5.99x account median)
- joke-structure: physics anticlimax — you brace for the splash the whole way down and the water refuses to accept him; the second laugh is that he stands up as if this is a normal way to arrive
- the-beat: slide 0:00-0:04, entry and the skip at 0:04-0:05 (this is the frame that earned the post), casual stand-up at 0:06. It is only 7.8s and the whole thing is usable, but 0:03-0:07 is the tight version
- audio-model: diegetic (bakeable) — the slap of the skip is the sound of the joke; nothing else in the clip needs to be heard
- pairs-with: any "I expected this to land hard and it just skimmed" moment (a launch nobody noticed, a big swing that bounced); a build that survived something it should not have
- file: clips/DcUQOH9srXf.mp4 (7.8s)

## DcVwWQ4MhZd — a white bull terrier prances and rears up at a front gate showing off hard, and the audience he is performing for turns out to be a small brown dog in a green hoodie clinging to the bars
- source: @pubity | https://www.instagram.com/reel/DcVwWQ4MhZd/
- lane: general
- first-seen: 2026-08-22 | status: FRESH
- stats-at-capture: 8367 likes / 155 comments (2.66x account median)
- joke-structure: effort/audience mismatch — the whole first half is a performance, and the reveal is who it was aimed at; the burned-in line ("DAMN, HE WAS TRYING SO HARD TO MAKE A GOOD IMPRESSION") is present from the start, so the viewer is waiting to meet the audience
- the-beat: showing off 0:02-0:08, gate reveal of the hoodie dog at 0:09-0:10, and it keeps paying to 0:20 as the little one scrabbles up the bars. Cut on the reveal at 0:09; everything past 0:14 is optional
- audio-model: flexible — the joke is entirely visual (the reveal), so a trending track over the top costs nothing; the nail-scrabble on tile is nice texture but not load-bearing
- pairs-with: any "I put on the whole performance for an audience of one" beat — a polished launch post that got two likes, a demo rehearsed for the one person who showed up, a pitch aimed at somebody who was never the decision-maker
- file: clips/DcVwWQ4MhZd.mp4 (24.2s)

## DcUktOtxSmD — a long putt drops on a sunset green and the two friends detonate, throwing their clubs and sprinting flat-out away from the camera
- source: @sportscenter | https://www.instagram.com/reel/DcUktOtxSmD/
- lane: sports
- first-seen: 2026-08-22 | status: FRESH
- stats-at-capture: 158926 likes / 622 comments (2.02x account median)
- joke-structure: disproportionate reaction — the achievement is small and barely shown (the ball is at the cup for about half a second), and the payoff is 3 solid seconds of two grown men losing control over it. The scale gap is the joke
- the-beat: casual putt 0:00-0:04, ball tracking across the green 0:05-0:10, drop at ~0:10, eruption 0:11-0:13. The reaction is the asset: cut 0:09-0:13 and you never need to show the ball go in
- audio-model: diegetic (bakeable) — the screaming is the payoff; muting this clip removes the joke entirely
- pairs-with: any small win the user wants to treat as enormous (first paying customer, a green test suite, one comment on a post); also works inverted, as the reaction to something the viewer already knows was trivial
- file: clips/DcUktOtxSmD.mp4 (13.3s)

## DcUuVmZpMHi — [PRUNED DO-NOT-SPLICE 2026-08-22] 35 seconds of a shaky phone aimed at a gap under a stadium bleacher wall, strewn with peanut shells, while a fan pokes a hot dog toward the hole · https://www.instagram.com/reel/DcUuVmZpMHi/ · first-seen 2026-08-22

## DcVHvZjhSoB — [PRUNED DO-NOT-SPLICE 2026-08-22] POV on a rocky shoreline: a hand lifts a shell, opens it in front of a young woman · https://www.instagram.com/reel/DcVHvZjhSoB/ · first-seen 2026-08-22

## DcOsj2YxDtM — a lone cheer base repeatedly launches, catches and holds a full-grown flyer overhead by herself, then sinks to the mat spent while the camera whip-pans to a different squad with arms up
- source: @sportscenter | https://www.instagram.com/reel/DcOsj2YxDtM/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 875633 likes / 22716 comments (16.29x account median)
- joke-structure: on-screen text does the reacting for you — "Wait for it 👇" opens, then a held card reading "I'm sorry … WHAT?!" sits over eight straight seconds of a feat that keeps escalating past the point you accepted it
- the-beat: the disbelief card lands the moment the flyer goes fully inverted overhead around 0:04; the strongest single cut is 0:03-0:07 (launch to one-armed hold), and there is a second payoff at 0:22 when the base collapses to the mat, spent
- **CORRECTED 2026-08-27 (re-verified frame by frame against the local file).** The old
  headline read "then drops to the mat as the squad erupts". That is misleading and it cost a
  real donor pass. What actually happens: the base sinks to the mat and stays there in the
  splits from ~0:22; at **~0:29.5 the camera WHIP-PANS away** to a DIFFERENT group across the
  gym, arms up, for the final ~1.3s, over a burned-in "MORGAN" team graphic. Nobody is shown
  reacting to her in her own frame. Do NOT match this entry to a beat that needs a crowd
  reacting to the subject — it does not contain one.
  A job log on 2026-08-27 swung the other way and recorded "there is no squad eruption in it,
  it is one continuous stunt sequence ending on the same hold". That is also wrong: the
  arms-up shot exists and the clip does not end on the hold. Trust this line, not either of them.
- **DONOR-LEGIBILITY: UNUSABLE AS A SPLICE, and the reason is not the description.** A third
  party's caption **"I'm sorry … WHAT?!"** is burned in on **every one of the 31.3s**, sitting
  ~68% down the frame — too low to crop from the top, too high to crop from the bottom without
  losing the stunt. "Wait for it (down-arrow)" also sits top-left for the first ~3s, and the
  MORGAN graphic covers the last ~1.3s. There is no window of this clip that can be cropped
  clean. It is fine as a SHAPE reference; it cannot ship inside anyone's reel.
- audio-model: trending sound (add in-app) — level sits flat at -20dB across the whole clip with almost no variance, which reads as a music bed laid over gym ambience, not the room's own sound
- pairs-with: a claim the viewer will not believe until they see it ("Claude shipped the whole feature while I slept"), or any "one person carrying the entire thing" beat where the user's own footage is the load the base is holding
- file: clips/DcOsj2YxDtM.mp4 (31s)

## DcPNHpRz6mO — a man in a restaurant booth folds in half laughing, head thrown back, wiping his eyes with a napkin, for fifteen unbroken seconds
- source: @houseofhighlights | https://www.instagram.com/reel/DcPNHpRz6mO/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 515911 likes / 2250 comments (7.33x account median)
- joke-structure: the caption carries the entire joke and the footage carries the reaction — a held card reads "My homie broke up with his girl to focus on basketball, then got cut from the team" while the friend simply cannot recover. Self-inflicted defeat, told in one line, reacted to for the full runtime
- the-beat: any 2-3s slice works because the laugh never breaks; the best is 0:09-0:12 where he sits up, looks at the camera, and immediately goes again — that re-collapse is the payoff
- audio-model: diegetic (bakeable) — level swings 9dB with peaks at -7.5dB on the laugh bursts; the laughter IS the sound and it is what makes the clip funny
- pairs-with: any user story that ends in a self-own ("I quit the job to focus on the build, then the build broke"), or as the reaction shot cut against the user's own straight-faced delivery of a bad decision
- file: clips/DcPNHpRz6mO.mp4 (16s)

## DcPaax_NfyB — a lifter benching heavy dumbbells gets "help" from a spotter who yanks the weights the whole set, until the lifter dumps them and slides off the bench onto the floor
- source: @houseofhighlights | https://www.instagram.com/reel/DcPaax_NfyB/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 385803 likes / 1709 comments (5.48x account median)
- joke-structure: escalating unwanted assistance — the caption "Gym buddy is rocket raccoon 💀" names the type, then the footage proves it for eleven seconds until the help finally causes the failure it was meant to prevent
- the-beat: the collapse at 0:08-0:10 when he abandons the lift, drops the dumbbells and rolls off the bench; cut in at 0:06 so the viewer sees two reps of over-help first
- audio-model: diegetic (bakeable) — sparse and quiet (mean -34dB) with sharp bursts on the clangs and grunts, which is a raw gym recording, not a laid-in track
- pairs-with: "the tool that was supposed to help", "my co-founder helping", any user beat where an assist makes the task harder than doing it alone
- file: clips/DcPaax_NfyB.mp4 (12s)

## DcPUbEOtkQQ — a woman sprints across an airport arrivals hall and tackles the person she came to meet, both of them hitting the polished floor hard, then hugging while a crowd films
- source: @houseofhighlights | https://www.instagram.com/reel/DcPUbEOtkQQ/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 262882 likes / 4165 comments (3.78x account median)
- joke-structure: joy overcommitted into physical violence — the caption "Got off her flight like Myles Garrett" reframes affection as a defensive tackle, and the footage delivers a genuine takedown with a stanchion knocked over
- the-beat: impact at 0:03; cut 0:01-0:05 so the run-up and the landing both read, and hold one extra second for the pair still tangled on the floor
- audio-model: diegetic (bakeable) — the thud, the shriek and the terminal ambience carry it; moderate variance (sd 6.8dB) consistent with a live phone capture
- pairs-with: "when the thing you waited months for finally lands", any user reunion/delivery/launch moment, or as the overreaction cut against a deliberately flat user reaction
- file: clips/DcPUbEOtkQQ.mp4 (12s)

## DcTqoISNurc — a man proposes on an empty beach while the couple's golden retriever does full-speed zoomie laps around them for the entire proposal
- source: @pubity | https://www.instagram.com/reel/DcTqoISNurc/
- lane: general
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 71826 likes / 517 comments (3.35x account median)
- joke-structure: solemn ceremony vs. a chaos agent who refuses to acknowledge it — text card sets it up ("I PROPOSED TO MY GIRLFRIEND AFTER 7 YEARS, AND OUR GOLDEN RETRIEVER GOT THE ZOOMIES") and the dog never once stops moving through the most serious minute of their lives
- the-beat: best window is 0:05-0:12, kneel plus two full dog laps; note the shot is a locked-off wide filmed over a dark foreground object and Pubity burns a "following" UI badge over the centre of frame around 0:09, so cut before or after that second
- audio-model: trending sound (add in-app) — very flat level (sd 3.7dB, mean -17.7dB) across 63s, which is a laid-in music bed rather than beach wind
- pairs-with: any user moment that is supposed to be dignified and is not, "the launch day I planned vs. the launch day I got", a toddler or pet refusing to observe an occasion
- file: clips/DcTqoISNurc.mp4 (63s)

## DcTZGVRtjBP — hikers on a fog-blasted Portuguese ridge get taken off their feet by a wind gust and slide down the wet grass, ending with a bottle raised to camera
- source: @pubity | https://www.instagram.com/reel/DcTZGVRtjBP/
- lane: general
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 69897 likes / 526 comments (3.26x account median)
- joke-structure: the environment overrules the plan, then the deadpan recovery — text reads "NEARLY LOST MY BRO TO A STORM IN PORTUGAL", the friend is physically removed from his own footing, and the clip closes on someone calmly holding up a beer as if none of it happened
- the-beat: the knockdown at 0:05-0:07 (he is upright, then he is sliding); the second beat is the bottle at 0:11 — using both gives you setup and shrug in one cut
- audio-model: diegetic (bakeable) — huge level swings (sd 16.7dB, floor at -113dB) which is wind roar clipping in and out; the wind is the joke and it should stay
- pairs-with: "I had a plan and then reality happened", weather/travel days going wrong, any user beat where an external force flattens the effort
- file: clips/DcTZGVRtjBP.mp4 (13s)

## DcPZpsHvdPn — a small boy processes into his First Communion with a completely stone face, refusing to smile or look at anyone, while the adults behind him crack up
- source: @sportscenter | https://www.instagram.com/reel/DcPZpsHvdPn/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 171000 likes / 718 comments (3.11x account median)
- joke-structure: a child performing adult gravity harder than any adult would — the caption "Electric entrance to first communion" plus a sub-line "Put his serious face on" tells you the kid has decided this is a serious occasion and he is going to sell it
- the-beat: the walk-past at 0:02-0:05 where he holds the face for a full three seconds; the reaction of the grandmother at 0:07 is the optional button
- audio-model: trending sound (add in-app) — level is steady around -18dB with low variance, consistent with a track laid over a church walk-in ("electric entrance" implies the song is the bit)
- pairs-with: any beat about taking a small thing extremely seriously, a toddler or kid performing competence, the user's own deadpan-under-pressure moment. Note this is an identifiable child at a family event — a lower-risk use is the reaction shot behind him rather than a close hold on his face
- file: clips/DcPZpsHvdPn.mp4 (8s)

## DcTuLiwRLAT — an NFL player's chain snaps off his neck at the exact second the broadcast camera cuts to him on the sideline, and he just quietly picks it up
- source: @sportscenter | https://www.instagram.com/reel/DcTuLiwRLAT/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 151738 likes / 4910 comments (2.84x account median) — the highest comment-to-like rate in this batch, roughly 1 comment per 31 likes
- joke-structure: cosmic timing — the caption "His chain broke right when the cameras cut to him" makes the coincidence the whole joke, and the payoff is his total lack of reaction. He does not flinch, he just handles it
- the-beat: the break at 0:04-0:06; hold through 0:08 for the deadpan recovery, which is funnier than the break itself
- audio-model: flexible — the sound is broadcast ambience with no commentary landing on the moment, so nothing is lost by muting it under a track, and nothing is gained by keeping it
- pairs-with: "the one time someone was watching", a demo breaking on the call, any user beat where the failure picks the worst possible witness
- file: clips/DcTuLiwRLAT.mp4 (11s)

## DcSiav-hR5k — a cat detonates through a quiet, formal living room, launching off an antique sofa, across a pedestal table and out of frame, twice
- source: @pubity | https://www.instagram.com/reel/DcSiav-hR5k/
- lane: general
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 44545 likes / 431 comments (2.08x account median)
- joke-structure: unexplained energy arriving in a room built for calm — text asks "WHY DOES MY CAT GO COWABUNGA MODE?" and never answers, which is the joke. The elegant furniture is the straight man
- the-beat: the first launch off the sofa arm at 0:03; the wider payoff is the table-to-chair run at 0:10-0:14 where the room's stillness makes the speed read
- audio-model: diegetic (bakeable) — near-silent room (bursts to -7.6dB from a -109dB floor) where the scrabbling claws on wood are the only sound and they sell the chaos
- pairs-with: "and then my toddler woke up", a calm process interrupted by one unmanageable variable, any user beat where something small wrecks a carefully arranged frame
- file: clips/DcSiav-hR5k.mp4 (20s)

## DcOyH6dxYnH — two boys play a backyard golf hole; one misses, throws his club, storms off and ends up doubled over a fence while his friend keeps playing
- source: @sportscenter | https://www.instagram.com/reel/DcOyH6dxYnH/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 101378 likes / 607 comments (1.85x account median)
- joke-structure: catastrophic emotion attached to a stake worth nothing — "We all have these friends" names the type, then the meltdown arrives at full scale over a missed putt on a homemade green
- the-beat: the club throw and walk-off at 0:12-0:16, then the fence collapse at 0:19; the friend continuing to line up his shot in the background is what makes it land
- audio-model: diegetic (bakeable) — quiet yard at -30dB mean with sharp shouted bursts to -7.3dB; the yell is the beat
- pairs-with: "how I react to a failing test", disproportionate reactions to small setbacks, a user beat where the stakes are trivial and the feelings are not
- file: clips/DcOyH6dxYnH.mp4 (28s)

## DcRGvqlOANT — a college football team's graduate assistant takes a mic at fall camp and freestyles, and the entire room of players goes up
- source: @houseofhighlights | https://www.instagram.com/reel/DcRGvqlOANT/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 124943 likes / 1448 comments (1.79x account median)
- joke-structure: unexpected competence from the least likely person in the room — the setup text ("When you get one of your GA's to freestyle for the team during fall camp") frames him as a novelty act, and the room's escalating reaction is the reveal that he is actually good
- the-beat: the room turning is the payoff, not the rapping — the eruption around 1:15-1:22 where players are on their feet and filming. The clip is 92s, so the architect must cut; take a 3-5s reaction slice, not the performance
- audio-model: flexible — the performance audio is diegetic and it is the point, but there is a backing beat playing in the room, so baking it in carries the same copyrighted-audio risk as a library track. Safest is to mute it and let a chosen track run under the reaction
- pairs-with: "the person everyone underestimated", a tool or teammate outperforming expectations, the user's own reveal beat where the room reacts before the viewer understands why
- file: clips/DcRGvqlOANT.mp4 (92s)

## DcPA-oJv9WA — a kid at his first karate class attempts a spinning kick, gets completely inverted mid-air and lands flat on his back in front of the whole dojo
- source: @sportscenter | https://www.instagram.com/reel/DcPA-oJv9WA/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 96893 likes / 791 comments (1.77x account median)
- joke-structure: ambition meeting gravity on the first attempt — caption "First time in karate and this happens", then a confident wind-up that is far beyond his actual ability, and a hard flat landing with the instructor already reaching for him
- the-beat: the whole thing is the beat: wind-up 0:01, air 0:03, floor 0:04. At 7s this is the cleanest drop-in clip in the batch and needs no trimming
- audio-model: diegetic (bakeable) — very quiet dojo (sd 14.3dB, floor -92dB) with the impact as the loudest event; the thud is the punchline
- pairs-with: "first time trying it", any user beat about attempting something above your level on day one, or cut against a user's confident claim as the immediate contradiction
- file: clips/DcPA-oJv9WA.mp4 (7s)

## DcQ7__eRvNv — a field hockey player walks deliberately into a full-force pitch sprinkler, gets blasted off her feet and lands flat on the wet turf
- source: @sportscenter | https://www.instagram.com/reel/DcQ7__eRvNv/
- lane: sports
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 90649 likes / 819 comments (1.66x account median)
- joke-structure: deliberate self-sabotage, announced in advance — "(Wait for it)" primes the viewer, "She let her intrusive thoughts win" supplies the motive, and she walks into it knowing exactly what will happen
- the-beat: impact at 0:04-0:06; the walk-up from 0:02 is needed so the viewer sees it was a choice, not an accident
- audio-model: diegetic (bakeable) — steady loud sprinkler roar (mean -18.7dB, low variance) that reads as the real thing; the water noise is half the gag
- pairs-with: "I knew it was a bad idea and I did it anyway", shipping the risky thing on purpose, any user beat where the disaster was volunteered for
- file: clips/DcQ7__eRvNv.mp4 (7s)

## DcT7YxBNUuR — a cat leans in to smell a sleeping dog's breath, recoils, and then holds a completely frozen, glazed stare into the middle distance for the rest of the clip
- source: @pubity | https://www.instagram.com/reel/DcT7YxBNUuR/
- lane: general
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 34456 likes / 331 comments (1.61x account median)
- joke-structure: a reaction held far past the point of comfort — the text sets up the cause ("MY CAT RANDOMLY STARTED SMELLING MY DOG'S BREATH AND DID THIS") and the payoff is fifteen seconds of an animal visibly reconsidering its life
- the-beat: the recoil at 0:03, then hold — the value here is the stare from 0:05 onward, which loops cleanly and works as a static reaction cutaway
- audio-model: flexible — the room is near-silent (mean -44dB, the quietest clip in this batch), so there is nothing to preserve and a track can run freely underneath
- pairs-with: reading a bad error message, opening the analytics, tasting the thing you cooked; any user beat that needs a held "I regret knowing this" face
- file: clips/DcT7YxBNUuR.mp4 (19s)

## DcS50NqJHGa — a tiny apricot poodle puppy climbs onto a woman mid-yoga-pose, licks her face, then sprints off across the studio floor
- source: @pubity | https://www.instagram.com/reel/DcS50NqJHGa/
- lane: general
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 33242 likes / 132 comments (1.54x account median)
- joke-structure: interruption rather than punchline — "SOMEONE BROUGHT THEIR PUPPY TO YOGA" and the class quietly stops being a yoga class. Honest note for the architect: this is a warmth beat, not a joke with a turn, so it will not carry a payoff on its own
- the-beat: the face-lick at 0:04 breaks the pose; the run-off at 0:10-0:12 is the cleaner cut if you want motion rather than sweetness
- audio-model: trending sound (add in-app) — steady level around -18.5dB with low variance across a studio, which reads as the room's music rather than a raw capture
- pairs-with: a serious routine derailed by something small and welcome, "then the baby walked in", a user beat that needs an interruption rather than a joke
- file: clips/DcS50NqJHGa.mp4 (16s)

## DcT3PiGMZaO — three restaurant plates in a row: a loaded Daddy plate, a huge Mommy salad, then a bare plate holding exactly three potato wedges labelled with a toddler emoji
- source: #toddlertravel | https://www.instagram.com/reel/DcT3PiGMZaO/
- lane: family
- first-seen: 2026-08-21 | status: FRESH
- stats-at-capture: 23 likes / 1 comments (hashtag recent_media, no account baseline) — honest flag: this tag returned an hourly slice with no popularity signal at all, so this was picked on the strength of the format, not on reach
- joke-structure: rule of three with the punchline in the label — "Travelling with a toddler nobody talks about…" then Daddy plate, Mommy plate, and a near-empty plate that lands the whole joke without a word of narration
- the-beat: the third plate at 0:07; give each of the first two plates about 2s so the pattern establishes, then hold the last one longer than feels natural
- audio-model: trending sound (add in-app) — restaurant ambience with long near-silent gaps (floor -113dB); there is nothing worth keeping and the format needs a track to carry the three-beat rhythm
- pairs-with: any "here is what nobody tells you about X" comparison, the user's own three-panel setup where the third panel is the anticlimax. No faces in frame, so it is unusually safe to reuse
- file: clips/DcT3PiGMZaO.mp4 (11s)

## DcRho6BP_y1 — [PRUNED DO-NOT-SPLICE 2026-08-22] a dad plays pickup basketball at an outdoor court after his 10-year-old challenges him, filmed from so far back that nothing legible happens · https://www.instagram.com/reel/DcRho6BP_y1/ · first-seen 2026-08-21

## DcS4NreNxi4 — [PRUNED DO-NOT-SPLICE 2026-08-22] a 45-second high-school football highlight package of a running back, cut over a live ESPN score ticker · https://www.instagram.com/reel/DcS4NreNxi4/ · first-seen 2026-08-21

## DcSGF3Ath8u — [PRUNED DO-NOT-SPLICE 2026-08-22] a screen recording of a Roblox obstacle level with two streamer webcam windows and a six-hour countdown overlay · https://www.instagram.com/reel/DcSGF3Ath8u/ · first-seen 2026-08-21

## DcT964WiGal — [PRUNED DO-NOT-SPLICE 2026-08-22] a bearded dad in a garden delivers a 26-second talking-head story about his kid dodging chores, over word-by-word karaoke captions · https://www.instagram.com/reel/DcT964WiGal/ · first-seen 2026-08-21

## DcT1q27t9QF — [PRUNED DO-NOT-SPLICE 2026-08-22] a toddler in a pink swimsuit walks into the sea on a British beach · https://www.instagram.com/reel/DcT1q27t9QF/ · first-seen 2026-08-21

## DcPUWj1vU78 — a humanoid robot sprints a full lap of an empty Olympic track, then drives itself straight into the trackside electrical boxes
- source: @pubity | https://www.instagram.com/reel/DcPUWj1vU78/
- lane: general
- first-seen: 2026-08-20 | status: FRESH
- stats-at-capture: 167404 likes / 8835 comments (173.55x account median)
- joke-structure: two-card bait and switch — card one is a flat record-breaking boast ("A ROBOT BROKE USAIN BOLT'S SPEED RECORD"), card two arrives mid-run and retroactively demolishes it ("THEN CRASHED STRAIGHT INTO AN ELECTRICAL BOX"), and the crash lands right as you finish reading it
- the-beat: setup card 0:00-0:05 over the sprint; card flips at 0:05 as the robot rounds the bend; impact at 0:10-0:12 and it is left face-down in the cabling. Cut on the card flip at 0:05, or take 0:08-0:13 as a pure payoff beat
- audio-model: flexible — the footage is silent training video with no sting of its own, so it takes a trending track cleanly, and it also plays fine muted under a voiceover
- pairs-with: any "the machine was doing great until it wasn't" beat — imabgold's agent running perfectly all night and then blowing up the build; a toddler sprinting across a room and eating the doorframe
- file: clips/DcPUWj1vU78.mp4 (15s)

## DcJGKfFh6ct — one man plays every member of a Middle Eastern household and physically prevents a guest from leaving by burying him in tea, nuts and hand-fed fruit
- source: @9gag | https://www.instagram.com/reel/DcJGKfFh6ct/
- lane: general
- first-seen: 2026-08-20 | status: FRESH
- stats-at-capture: 176131 likes / 2235 comments (5.42x account median)
- joke-structure: escalating obstruction — the guest announces he is leaving and every attempt to stand up summons more hospitality, played by the same performer switching between a headscarfed auntie and the trapped guest in a cap. The joke is that the exit never happens and the guest stops resisting
- the-beat: premise card 0:00-0:06; tea appears at 0:07; the table fills 0:12-0:25; the payoff run is 0:30-0:42, close-ups of fruit being pushed directly into his mouth while he chews in defeat. Cut on the tea pour at 0:07 for the turn, or lift 0:33-0:40 as a standalone "I am not getting out of here" payoff
- audio-model: flexible — it is a spoken sketch, but the escalation reads completely without dialogue, so a trending track over it loses nothing
- pairs-with: any "I tried to end it and it would not let me" beat — closing the laptop and the agent starting another task; standing up to leave a restaurant and the toddler ordering more
- file: clips/DcJGKfFh6ct.mp4 (44s)

## DcQSJ10hrBL — a four-year-old in a pink helmet bails hard off her skateboard, says "ouchy", and carries on singing the Australian national anthem without missing a word
- source: @pubity | https://www.instagram.com/reel/DcQSJ10hrBL/
- lane: general
- first-seen: 2026-08-20 | status: FRESH
- stats-at-capture: 14496 likes / 302 comments (14.57x account median)
- joke-structure: undercut by indifference — the pain beat arrives and is given exactly one word before the performance resumes. She is singing "Advance Australia Fair" to herself the entire time and treats a full-body slam as a minor interruption to the recital
- the-beat: setup card 0:00-0:03; the bail at 0:04; she is sitting on the concrete at 0:11 with "Ouchy" and is back on the lyric a second later. The whole usable beat is 0:03-0:13; the remaining 45s is filler park footage
- audio-model: diegetic (bakeable) — her singing IS the joke and the clip is worthless muted. Do not put a track over this one
- pairs-with: any "took the hit and kept going" beat — the build that crashes mid-demo and the demo continues; a kid who face-plants and resumes the story they were telling
- file: clips/DcQSJ10hrBL.mp4 (60s)

## DcQmzUTsBPA — camera creeps into a silent bedroom and finds the toddler has dressed both family dogs in tiaras and jewellery, and they are just lying there taking it
- source: @pubity | https://www.instagram.com/reel/DcQmzUTsBPA/
- lane: general
- first-seen: 2026-08-20 | status: FRESH
- stats-at-capture: 14044 likes / 112 comments (13.94x account median)
- joke-structure: stated suspicion, empty hunt, reveal — one held line ("MY DAUGHTER'S ROOM WAS SUSPICIOUSLY QUIET. I THEN FOUND THIS INSIDE HER ROOM") licenses two seconds of nothing, and the payoff is not the crime but the victims' total compliance
- the-beat: push-in through the doorway 0:00-0:02 on an empty frame; the dogs land at 0:03; the girl turns and grins into the lens at 0:05. Cut on the reveal at 0:03 — the whole thing is 6 seconds and needs no trimming
- audio-model: flexible — no diegetic beat, the text card carries it, so it takes a trending sound cleanly
- pairs-with: any "it went quiet, here is why" reveal — the toddler who has gone silent in the next room; the terminal that stopped printing because it finished twenty minutes ago
- file: clips/DcQmzUTsBPA.mp4 (6s)

## DcOyHDVsWu_ — 25 unbroken seconds of twin toddlers squabbling around a bed frame, promised as "the honest version" of twins, that ends with the two of them hugging
- source: @pubity | https://www.instagram.com/reel/DcOyHDVsWu_/
- lane: general
- first-seen: 2026-08-20 | status: FRESH
- stats-at-capture: 58781 likes / 708 comments (58.58x account median)
- joke-structure: bait and switch to wholesome — the card promises the unflattering truth about twins, delivers twenty seconds of low-grade shoving, and then pays off with affection instead of a punchline
- the-beat: card 0:00-0:05; the chaos is one continuous handheld take with no internal beat, which is the limitation here; the only clean cut is the hug at 0:22-0:25. Use it as a closing beat, not as a setup
- audio-model: flexible — the room tone carries nothing, so a track can sit over the whole thing
- pairs-with: a "here is what it is really like" opener that resolves into the warm shot — works as the last three seconds of a parenting cut, badly as the middle of one
- file: clips/DcOyHDVsWu_.mp4 (25s)
- note: two identifiable strangers' children fill the entire frame and the format (the "honest version" card) is more portable than the footage. Prefer rebuilding it with the user's own kids.

## DcPfwhLzL93 — [PRUNED DO-NOT-SPLICE 2026-08-22] Mark Wahlberg, in a gym on a Kick stream, tells a streamer about catching his son sneaking out at 3 AM · https://www.instagram.com/reel/DcPfwhLzL93/ · first-seen 2026-08-20

## DcH2hkzBzKc — Kitchen, mom in a pink tee lecturing her preteen son (white tee, backwards-ish tan ball cap) who stands with his back to camera taking it; held text reads "When your preteen gets too comfortable running they mouth…" and on the last beat she flicks the cap clean off his head mid-sentence
- source: #parentsofinstagram | https://www.instagram.com/reel/DcH2hkzBzKc/
- lane: family
- first-seen: 2026-08-17 | status: FRESH
- stats-at-capture: 82 likes / 7 comments (hashtag recent_media, no account baseline)
- joke-structure: escalating verbal lecture with a physical punchline — the whole reel is one held text premise and a mom talking, and the laugh is the cap flick that arrives before she finishes the sentence
- the-beat: premise text + lecture 0:00-0:05, cap flick payoff at ~0:06. It is a 7s loop: the clip restarts on the lecture, which is exactly what makes it rewatchable — cut ON the flick, never after
- audio-model: flexible — her voice is the lecture, but the physical beat reads with the sound off and survives a trending bed
- pairs-with: an imabgold "when your AI gets too comfortable" beat (agent pushes to main / rewrites a file it was told not to touch) landing on his own real reaction shot; a bambi "when the toddler gets too comfortable" beat over the real highchair meltdown
- file: clips/DcH2hkzBzKc.mp4 (7s)

## DcGyjYTsP_C — Held text "A DEER CAME RUNNING OVER AFTER HEARING MY BABY CRY BECAUSE SHE THOUGHT HE WAS HER FAWN" over a baby in a camo onesie on a mint blanket on a wooden deck, then the camera whips up to the yard where a doe has come out of the treeline and is standing in the grass, staring back
- source: @pubity | https://www.instagram.com/reel/DcGyjYTsP_C/
- lane: general
- first-seen: 2026-08-17 | status: FRESH
- stats-at-capture: 261246 likes / 1468 comments (31.11x account median)
- joke-structure: mistaken-identity reveal — an unbelievable claim is stated flat in text, then the footage is the proof; the comedy is a wild animal misreading a human sound and turning up to claim the baby
- the-beat: baby-on-blanket setup 0:00-0:04, whip-pan reveal of the doe ~0:05-0:09. Everything after 0:10 is a long handheld hold on the deer in the middle distance — the usable window is the first ten seconds, cut on the pan
- audio-model: diegetic (bakeable) — the baby's cry is the mechanism; mute it and the premise stops making sense
- pairs-with: a bambi "the baby cried and the entire restaurant answered" beat, with the real dining-room reaction as the payoff; any "I made a noise and the wrong thing responded" setup
- file: clips/DcGyjYTsP_C.mp4 (42s)

## DcHbqLLsRSW — Night, a yellow semi truck; the driver pulls the locked door handle, then films his small black-and-tan dog sitting up on the driver's seat inside, tapping the glass and coaching it while the dog watches him blankly; held text "MY DOG LOCKED ME OUT OF MY OWN TRUCK ON THE ONE DAY I FORGOT MY SPARE KEY"
- source: @pubity | https://www.instagram.com/reel/DcHbqLLsRSW/
- lane: general
- first-seen: 2026-08-17 | status: FRESH
- stats-at-capture: 53340 likes / 756 comments (6.40x account median)
- joke-structure: helpless owner, oblivious operator — the person who caused the problem is the only one who cannot fix it, and the fix requires talking a creature that does not understand the task through the task
- the-beat: locked-handle setup 0:00-0:05, dog-through-the-glass reveal ~0:08-0:14, then a long stretch of him coaching it. Best cut is the reveal of the dog sitting calmly inside — that shot alone carries it
- audio-model: diegetic (bakeable) — his running commentary ("I'm so upset rn it's not even funny") is the joke's voice, and burned-in auto-captions already carry it visually
- pairs-with: an imabgold "my CTO locked me out of my own repo" beat — the machine did something irreversible while he watched through the glass; the user's own terminal/reaction is the load-bearing half
- file: clips/DcHbqLLsRSW.mp4 (72s) — note: a transient "Pubity · follow" overlay appears around 0:08 and again ~0:28; crop or cut around it

## DcGbL1OtjwX — Held text "MY DOG WON'T EAT HER FOOD UNLESS I DO THIS"; overhead of two steel bowls of kibble on a green pet mat, a pink-sleeved arm lifts one bowl, carries it to the microwave, gives it a token stir with a spoon and sets the identical food back down — a chihuahua that had refused it walks straight over and eats
- source: @pubity | https://www.instagram.com/reel/DcGbL1OtjwX/
- lane: general
- first-seen: 2026-08-17 | status: FRESH
- stats-at-capture: 51606 likes / 422 comments (6.16x account median)
- joke-structure: placebo ritual — an elaborate pointless ceremony produces an identical object, and the mark is completely convinced; the payoff is the dog eating what it just refused
- the-beat: refusal setup 0:00-0:05, the ritual (microwave + stir) 0:06-0:20, payoff is the dog eating the same food ~0:28-0:33. Cut the middle — the ritual only needs two beats to read
- audio-model: flexible — text carries the premise, no dialogue is load-bearing
- pairs-with: an imabgold "my AI won't work unless I do this" bit (new terminal, re-run the identical command, say please) with his real screen as the ritual; a bambi "the toddler will only eat it off the other plate" beat
- file: clips/DcGbL1OtjwX.mp4 (37s) — note: transient "Pubity · follow" overlay around 0:16 and 0:22

## DcBuSDMRHn2 — Night rec-league softball under the lights: batter connects, the ball pops up, and the play collapses into an error cascade — fielders converge and fumble it, runners take off in both directions, a defender chases the ball across the infield while nobody covers a base; on-screen text reads "Absolute chaos 😭"
- source: @sportscenter | https://www.instagram.com/reel/DcBuSDMRHn2/
- lane: sports
- first-seen: 2026-08-17 | status: FRESH
- stats-at-capture: 298566 likes / 1139 comments (3.14x account median)
- joke-structure: hype setup, escalating anticlimax — a routine play that keeps finding a new way to get worse, with no single punchline but a compounding one
- the-beat: swing + contact 0:00-0:03, first fumble ~0:04, cascade runs 0:05-0:14. The "wait for it" structure means the cut point is the first fumble; everything after is bonus
- audio-model: flexible — the held text does the narrating, so it drops cleanly under a trending bed, but the field shouting also works baked
- pairs-with: any "the plan survived first contact for about two seconds" beat — a deploy that cascades, a family exit from a restaurant, a toddler handoff that goes wrong; user's own footage sets the confident plan, this pays it off
- file: clips/DcBuSDMRHn2.mp4 (22s)

## DcB5cyST7Pf — [PRUNED DO-NOT-SPLICE] Static profile shot of a young girl in a denim jacket and a large pink bow riding in a car, looking out the window; the entire reel is one unbroken ta · https://www.instagram.com/reel/DcB5cyST7Pf/ · first-seen 2026-08-17

## DaW57QKigDK — Text "Bad news for claude / I just got home" over a hand jangling car keys walking in the door, cut to the Claude desktop app greeting him by name ("Yooo Bartu, what's good? What are we working on today?"), cut to a Claude Code terminal where he types "make me a millon dollars." and it just starts Swirling…
- source: @bartubuilds | https://www.instagram.com/reel/DaW57QKigDK/
- lane: tech
- first-seen: 2026-08-15 | status: FRESH
- stats-at-capture: 9133 likes / 48 comments (manual add from Marcus's saves; caption "Hey claude, make me a million dollars. No mistakes. #claude #startup #ai"; posted Jul 3, no account baseline)
- joke-structure: pet-owner framing of an AI — "bad news for claude" casts the model as the one whose day just got worse, then the absurd-delegation payoff (typing "make me a million dollars" like a chore) plays the fantasy completely straight
- the-beat: keys/arrival setup 0:00-0:03, Claude greeting beat ~0:04-0:07, terminal "make me a millon dollars." + Swirling… payoff ~0:08-0:11. Cut on the Swirling… line — the machine dutifully getting to work IS the laugh
- audio-model: flexible — original audio is ambient; survives a trending bed cleanly
- pairs-with: an imabgold "my employee was home alone all day" / coming-home-to-Claude setup where the user's own terminal carries the payoff; also a reaction beat for any "I asked Claude for the impossible" confession
- file: clips/DaW57QKigDK.mp4 (11.9s)

## DbXGmRlN_J9 — Text "POV: you try to take a break as an entrepreneur" over a man closing his laptop at a dim kitchen table; he picks up his phone and every reel he scrolls is hustle content (a Hormozi-style podcast desk, "Do so much work it would be unreasonable...") until he gives up and goes back to the laptop
- source: @gurr_505 | https://www.instagram.com/reel/DbXGmRlN_J9/
- lane: tech
- first-seen: 2026-08-15 | status: FRESH
- stats-at-capture: 20892 likes / 262 comments (manual add from Marcus's saves; caption "😂😂"; posted Jul 28, no account baseline)
- joke-structure: escape-that-loops-back — the "break" is scrolling, but the algorithm serves only grind content, so rest turns back into work; payoff is the resigned return to the laptop
- the-beat: laptop-close + phone pickup setup 0:00-0:05, the scrolled hustle-reels escalate ~0:06-0:15, back-to-the-laptop payoff ~0:16-0:19. Cut on the return to the keyboard. NOTE: the phone UI is in Chinese and the scrolled reels are screen-recorded reposts with IG chrome baked in — keep those beats quick or crop tight so the overlay doesn't read
- audio-model: diegetic (bakeable) — the scrolled reels' own podcast/motivation audio is the gag; muted, the feed reads as random screens
- pairs-with: an imabgold "I tried to log off" setup over the user's own desk/screen; the borrowed middle carries the you-can't-escape beat while the user's return-to-work shot lands the payoff
- file: clips/DbXGmRlN_J9.mp4 (19.8s)

## DaytndsJOv2 — Text held the whole clip: "\"you got lucky\" / the luck:" over a cinematic night montage of a guy alone at a laptop in a glass high-rise apartment — dusk to full dark, headphones on, typing while the city lights up behind him
- source: @realchasko | https://www.instagram.com/reel/DaytndsJOv2/
- lane: tech
- first-seen: 2026-08-15 | status: FRESH
- stats-at-capture: 39868 likes / 157 comments (manual add from Marcus's saves; caption "Quit the 9-5 to do a 9-9"; posted Jul 14, no account baseline)
- joke-structure: quote-vs-receipts template — a dismissive quote up top, then "the luck:" reveals the unglamorous grind behind the outcome. Same skeleton as the classic "the luck:" meme, played aesthetic instead of bitter
- the-beat: no turn — the whole clip is one held contrast; any 3-5s window works as a montage bed. The text template IS the joke; the footage just has to look like work
- audio-model: trending sound (add in-app) — rides "TAKE ME" — D A N N Y; never bake it
- pairs-with: FORMAT more than footage: rebuild with the user's own late-night desk/build shots under the same two-line template ("you got lucky" / the luck:). The banked clip suits a quick borrowed beat inside a longer luck-vs-work cut
- file: clips/DaytndsJOv2.mp4 (10.7s)

## DZu9rl2RtDy — Skit: text "CTO watching CEO sell clients features that don't exist 😭🥀" — two teens on a family-room couch, the CEO pitching with animated hands while the CTO stares dead-eyed at the laptop, escalating reaction shots, then a hard cut to a movie close-up (bald man gripping a steering wheel, thousand-yard stare) as the CTO's inner state
- source: @travelink.app | https://www.instagram.com/reel/DZu9rl2RtDy/
- lane: tech
- first-seen: 2026-08-15 | status: FRESH
- stats-at-capture: 83000 likes / 680 comments (manual add from Marcus's saves; caption "Tag your CTO and apologize in advance 😭 #startup #founder #tech #foundersbuilding #app"; posted Jun 18, no account baseline)
- joke-structure: role-pair tension template — one role makes promises, the other has to build them; the comedy is the CTO's silent suffering escalating into a movie-clip reaction payoff. NOTE the source is itself an app company's account, but the skit is made to be funny, not to sell (no product shown, no CTA) — judged intent per guard 7
- the-beat: couch pitch + dead stare 0:00-0:06, reaction close-ups ~0:06-0:08, movie-clip inner-state payoff ~0:09-0:10. The steering-wheel cut is the splice beat — 2s of borrowed despair that closes any "I promised something I can't build" setup
- audio-model: diegetic (bakeable) — the pitch chatter and the cut's silence carry it; a light bed underneath survives
- pairs-with: imabgold "me selling the feature / Claude finding out what I promised" — the user's own pitch or terminal is the setup, the steering-wheel stare lands the payoff. Also fits any solo-founder "I am both people in this meeting" confession
- file: clips/DZu9rl2RtDy.mp4 (10.2s)

## DZ7ArcGIBBU — Desk POV: text "Yeah running a business is hard but there's no way I'm letting another man tell me when i can eat lunch." — a hand closes the MacBook at 14:31 on the desk clock, beat, then reopens it at 14:32 to a to-do list wallpaper
- source: @iambenhollingworth | https://www.instagram.com/reel/DZ7ArcGIBBU/
- lane: tech
- first-seen: 2026-08-15 | status: FRESH
- stats-at-capture: 15566 likes / 83 comments (manual add from Marcus's saves; caption "Fr #onlinebusiness #fyp #hustle #laptop #viral"; posted Jun 23, no account baseline)
- joke-structure: freedom-flex anticlimax — the grand declaration of independence ("no man tells me when to eat lunch") buys exactly one minute of freedom; the 14:31→14:32 clock is the whole punchline
- the-beat: declaration + laptop close 0:00-0:04, the reopen at 14:32 payoff ~0:05-0:07. Cut on the reopened screen; the clock must stay readable in both shots or the joke dies
- audio-model: flexible — no meaningful diegetic audio; take any bed
- pairs-with: imabgold self-employment-irony confessions ("I left the 9-5 so I could work 24/7"); the borrowed minute-long lunch break plays as a beat inside the user's own day-in-the-life
- file: clips/DZ7ArcGIBBU.mp4 (7.3s)

## DYSOi-KRQlc — Cafe POV: text "Okay guys I brought my macbook to a coffee shop now how do I make $10k a month" — a hand rests on a closed MacBook beside a latte in a gorgeous bookstore cafe (chandeliers, floor-to-ceiling shelves), camera pans the room, laptop never opens
- source: @itsmarcosphilip | https://www.instagram.com/reel/DYSOi-KRQlc/
- lane: tech
- first-seen: 2026-08-15 | status: FRESH
- stats-at-capture: 19400 likes / 241 comments (manual add from Marcus's saves; caption "What's the next step @tjr ?"; posted May 13, no account baseline)
- joke-structure: aesthetic-equals-income fallacy played straight — the laptop-in-a-cafe LOOK is treated as the entire business plan, and the sincere "now what" question is the punchline. The laptop staying closed is the tell
- the-beat: one held joke, no turn — text + setting land in the first 2s, the pan just sustains it. Any 3-4s window splices; keep the closed laptop + latte in frame
- audio-model: flexible — ambient cafe original audio; survives any bed
- pairs-with: imabgold "step 1 of becoming a founder" / build-in-public irony setups — the user's own real work (terminal, shipped app) is the contrast payoff after the borrowed aesthetic setup
- file: clips/DYSOi-KRQlc.mp4 (7.7s)

## Db1fRXYP24v — Two small girls run a doll-and-Barbie-jeep play session and spend the whole clip correcting their parents for doing it wrong, hands on hips, pointing and lecturing while mum keeps a straight face holding the baby, and the bald bearded dad ends on a sheepish to-camera shrug; held text the entire time reads "POV: when you try go play with your kids but don't do exactly as they say"
- source: #parentsofinstagram | https://www.instagram.com/reel/Db1fRXYP24v/
- lane: family
- first-seen: 2026-08-10 | status: STALE (2026-09-01)
- stats-at-capture: 9836 likes / 74 comments (hashtag recent_media, no account baseline)
- joke-structure: role reversal held by a POV text template — the children are management, the adults are staff, and the punchline is that the parents comply
- the-beat: the scolding escalates in cuts 0:00-0:16 (any single 2s correction lands on its own), the payoff is dad's defeated to-camera shrug at ~0:18-0:20. Cut on the shrug for a closed joke, or on one scold for a reaction beat
- audio-model: diegetic (bakeable) — the kids' voices ARE the joke; a track would erase it
- pairs-with: bambi.map's own baby issuing orders at a restaurant table (the highchair arrives and gets rejected anyway); an imabgold "my cofounder is a baby" beat where the toddler is the one setting the deadline
- file: clips/Db1fRXYP24v.mp4 (22.0s)

## DbwDG5UxiwR — A shirtless dad in a ball cap on his driveway court calls his shot with a raised finger, heaves a rubber playground ball at the hoop, and the camera whips up to follow it clean over the backboard and off toward the house, landing on a silent hold of the garage; held text reads "Can't believe they actually doubted UNC"
- source: @sportscenter | https://www.instagram.com/reel/DbwDG5UxiwR/
- lane: sports
- first-seen: 2026-08-10 | status: STALE (2026-09-01)
- stats-at-capture: 700803 likes / 4175 comments (6.47x account median)
- joke-structure: called-shot bravado, anticlimax payoff — the pointing, the wind-up and the whip-pan all promise a make, and the frame delivers a total miss with no acknowledgement
- the-beat: bravado and the point 0:00-0:07, release ~0:08, the whip-pan that finds nothing but sky at 0:09, silent hold on the house 0:10-0:12. Cut on the whip-pan at 0:09; the silence after is the laugh
- audio-model: diegetic (bakeable) — the throw and the conspicuous absence of a net sound is the beat; survives being ducked under a track
- pairs-with: any user "I've got this" declared out loud right before it doesn't (imabgold calling a 5-minute fix that runs three hours, per playbook 11); a bambi "he'll definitely sit in it" before the highchair is refused
- file: clips/DbwDG5UxiwR.mp4 (11.9s)

## Db0w88EMV_E — Held text says "I was filming my cat being naughty and then she waved at me": a tuxedo cat is caught tugging a blind cord by a bedroom door, freezes when it clocks the camera, sits back and lifts one front paw straight up at the lens like a greeting, then loses interest and wanders the back of the sofa for the remaining 35 seconds
- source: @pubity | https://www.instagram.com/reel/Db0w88EMV_E/
- lane: general
- first-seen: 2026-08-10 | status: STALE (2026-09-01)
- stats-at-capture: 248983 likes / 2064 comments (5.48x account median)
- joke-structure: caught-in-the-act, then an unexpectedly human reaction — the guilty freeze sets it up and the raised paw reads as "hello", which is funnier than the mischief was
- the-beat: mischief 0:00-0:05, the freeze at ~0:06, paw up 0:08-0:11. Cut hard at 0:12 — everything after is Pubity padding. NOTE: a small "Pubity / following" UI chip is baked into the frame around 0:11-0:14, so the clean window is 0:00-0:10
- audio-model: flexible — nothing in the audio carries the beat, so a trending track added in-app works fine
- pairs-with: bambi.map's baby caught mid-mess who looks straight up into the lens; any "cofounder clocks out" beat where the culprit shows zero remorse
- file: clips/Db0w88EMV_E.mp4 (49.3s)

## Dbtj3TFQ5k5 — A 2:20 morningbrew mini-doc asking how Jungle Jim's, America's largest grocery store, stays in business, in which the owner turns up throughout in a wizard hat, cape and a giant "JUNGLE" medallion and deadpans flat business truths — "because it's a poor man's business", "don't ask me, I don't, don't get too deep with this shit", "you want him to work for you? or you want to work for him?"
- source: @morningbrew | https://www.instagram.com/reel/Dbtj3TFQ5k5/
- lane: tech
- first-seen: 2026-08-10 | status: STALE (2026-09-01)
- stats-at-capture: 88972 likes / 994 comments (8.88x account median)
- joke-structure: costumed-authority deadpan — a man dressed as a wizard delivering unbothered, faintly weary business wisdom; the whole joke is the gap between the outfit and the flatness of the delivery
- the-beat: no single payoff, this is a documentary. Liftable 2-3s reaction beats: the interviewer's "is this place successful in spite of you or because of you?" at ~0:13, "because it's a poor man's business" at ~0:55, and the "don't get too deep with this shit" shrug at ~1:05
- audio-model: diegetic (bakeable) — the deadpan line reading is the asset
- pairs-with: an imabgold founder-hustle setup that needs a deflating cutaway ("how is this still working" over the user's own duct-taped build). HONEST SCOPE: this lends a reaction beat, not a setup-and-punchline. If the cut needs an actual payoff, the user's own footage is stronger and this clip should sit it out
- file: clips/Dbtj3TFQ5k5.mp4 (140.9s)

## DbtHfp7xXOQ — [PRUNED DO-NOT-SPLICE] A suited correspondent walk-and-talks through Manhattan for 1:35 with printed pages in hand and real headline cards (Washington Post, NPR, Fortune,… · https://www.instagram.com/reel/DbtHfp7xXOQ/ · first-seen 2026-08-10

## DbwA-X6xW_C — [PRUNED DO-NOT-SPLICE] The same morningbrew street-explainer format asking "what happened to Lululemon?": a correspondent walks past a Lululemon store for 1:56 with headl… · https://www.instagram.com/reel/DbwA-X6xW_C/ · first-seen 2026-08-10

## DbrDhZ4suSs — [PRUNED STALE] bells on dachshund puppies, empty-room hunt then the reveal · https://www.instagram.com/reel/DbrDhZ4suSs/ · first-seen 2026-08-06

## DbmQH7CtNX- — [PRUNED STALE] blindfolded fast-food taste test, brother names each chain by bite · https://www.instagram.com/reel/DbmQH7CtNX-/ · first-seen 2026-08-06

## Dbr6mRMJewR — [PRUNED STALE] "POV: your dad said he didn't want a puppy", puppy asleep on his shoulder the whole take · https://www.instagram.com/reel/Dbr6mRMJewR/ · first-seen 2026-08-06

## DbsPBsrB6hm — [PRUNED STALE] man lands a backflip at a zoo and the macaques go berserk behind the glass · https://www.instagram.com/reel/DbsPBsrB6hm/ · first-seen 2026-08-06

## DbqpAqORnm8 — [PRUNED DO-NOT-SPLICE] A morningbrew suited correspondent walk-and-talks two minutes of Citadel/Situational-Awareness finance news with headline screenshots and reaction memes; no liftable beat, format kept as playbook #28 · https://www.instagram.com/reel/DbqpAqORnm8/ · first-seen 2026-08-06

## Dbnyi4guiod — [PRUNED STALE] Hulk and two Spider-Men crammed into a cinema row in full costume · https://www.instagram.com/reel/Dbnyi4guiod/ · first-seen 2026-08-06

## DbjAfeTsSCh — [PRUNED STALE] "my cat Elsa, she is very stealthy" held over Elsa sitting in plain sight, paid off by her enormous face sliding into the lens · https://www.instagram.com/reel/DbjAfeTsSCh/ · first-seen 2026-08-03
## DbkOasfBRTc — [PRUNED STALE] a Yorkie blocks the laundry, then escalates by climbing bodily into the dryer and staring its owner down from inside the drum · https://www.instagram.com/reel/DbkOasfBRTc/ · first-seen 2026-08-03
## Dbi8hsFxMD9 — [PRUNED STALE] a real estate agent steps back off the top stair mid-sentence and goes down the whole flight during a house viewing · https://www.instagram.com/reel/Dbi8hsFxMD9/ · first-seen 2026-08-03
## DbjVJzxMvly — [PRUNED DO-NOT-SPLICE] Static close hold on newborn twins, one asleep with her thumb in her crying brother's mouth, recontextualised by one line of held text; no comedic mechanism and identifiable strangers' newborns — format kept as playbook 27 · https://www.instagram.com/reel/DbjVJzxMvly/ · first-seen 2026-08-03

## DbkuBBRKD4T — [PRUNED DO-NOT-SPLICE] "My tech leader to me & my colleagues" selfie hook cut to a Bollywood film clip; neither half lendable (identifiable stranger + copyrighted film footage) · https://www.instagram.com/reel/DbkuBBRKD4T/ · first-seen 2026-08-03

## DbZD_IcxCMy — [PRUNED DO-NOT-SPLICE] 1:44 talking-head news explainer on a $50B Louisiana data center approved under a secret codename; straight journalism, no joke and no clean beat to cut on · https://www.instagram.com/reel/DbZD_IcxCMy/ · first-seen 2026-08-03

## DckzWjZTiC1 — a man knocks at an office door under a "POV: You visit the software developers department" card, hard cut to a letterboxed club scene where a guy in a gold medallion turns to camera, then he tumbles down a stairwell
- source: Marcus's own pick (2026-08-29 order, permalink https://www.instagram.com/p/DckzWjZTiC1/) | fetched via ig-fetch.sh (dormant account, 2/5 cap)
- lane: tech
- first-seen: 2026-08-29 | status: FRESH
- stats-at-capture: — (direct order, not a scan find)
- joke-structure: POV label + a mundane knock, answered by the least plausible "software developer" imaginable; the stairs fall is the button (the department collapses)
- the-beat: 3 scenes — 0.000-2.667 (knocking at the door, back to camera), 2.667-8.267 (THE GUY: letterboxed club scene, medallion man turns to camera, the long featured hold), 8.267-9.08 (he tumbles down a stairwell). 9.08s total, 30fps, 1440x2560 natively 9:16 (1080x1920 = pure 0.75x)
- audio-model: the club scene's own music in the original — NOT captured with rights; never bake. Replicas ride a trending club/hip-hop bed
- pairs-with: any "I went looking for the professionals and found this" beat; the club-guy segment is the strongest "who answered the door" reveal in the bank
- clean-window: **its burned 3-line card (ink y294-692 at 1080 scale) is on screen the WHOLE reel — it is the setup asset, not a defect. Legal on setup/mid beats under BANK.md 4b; the fall tail 8.267+ is its own button — do not carry it into a replica that supplies a different payoff.** Donor frames ≤247 are club; f248+ are the fall
- file: clips/DckzWjZTiC1.mp4 (9.08s)
- spliced: 2026-08-29 `devs_department` — frames 81-247 (the club-guy beat) whole as the reel's setup/reveal; the fall tail dropped on Marcus's order; his POV door footage opens and closes the reel

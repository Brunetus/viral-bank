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

## DcT5FflAnMc — one unbroken car-selfie monologue, 2:20 long: a woman in a denim jacket in the driver's seat talks straight to camera about children not being taught to greet people, answer a phone or ask a stranger a question back, under one banner held from frame one to the last frame: "Baseline interpersonal skills are not getting taught"
- source: @parents | https://www.instagram.com/reel/DcT5FflAnMc/
- lane: family
- first-seen: 2026-08-27 | status: DO-NOT-SPLICE (2026-08-27)
- stats-at-capture: 2535 likes / 83 comments (16.36x account median)
- reason: sincere, non-comedic talking-head. No joke, no turn, no visual event — an identifiable stranger arguing a parenting position for two and a half minutes. There is nothing here to lend a splice, and lifting a stranger's opinion into someone else's reel borrows a stance, not a setup. Banked as a record so a later scan does not re-spend a download slot on it. The FORMAT was worth the slot and is captured as playbook #46 — the reel carries the best comment rate in the entire candidate pool (1 comment per 30 likes, against a bank median nearer 1 per 200)
- file: clips/DcT5FflAnMc.mp4 (141s) — out of canon, prunable from 2026-08-30

## DcUOFLpBUD5 — a 2:11 studio talking-head in a hand-knit sweater breaks down what clothing actually costs to make, cutting to a split screen that pins a real $16 Walmart cardigan listing against a $540 designer version and states the manufacturing cost out loud ("probably cost $4 or less to make"); on-screen title: "what should clothing actually cost?"
- source: @morningbrew | https://www.instagram.com/reel/DcUOFLpBUD5/
- lane: tech
- first-seen: 2026-08-27 | status: DO-NOT-SPLICE (2026-08-27)
- stats-at-capture: 13628 likes / 118 comments (2.40x account median)
- reason: sincere explainer, no comedic mechanism and no liftable beat. The only visually strong moment is the split screen, and it is welded to this specific creator's face, this specific $16/$540 claim and morningbrew's burned-in caption styling — you cannot put it under someone else's voice without borrowing their argument. Banked as a record so a later scan does not re-spend a slot. The FORMAT is the asset and is captured as playbook #47; it is the "here is what this actually costs" authority shape OPEN GAP 2 names as missing from the bank
- file: clips/DcUOFLpBUD5.mp4 (131s) — out of canon, prunable from 2026-08-30

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

## Dcd_FfvP96F — a tech creator unboxes the HONOR "Robot Phone", a handset with a motorised gimbal camera that swivels out of the back, and works through big shocked reaction faces as he handles it
- source: @techburner | https://www.instagram.com/reel/Dcd_FfvP96F/
- lane: tech
- first-seen: 2026-08-26 | status: AD-REJECTED (2026-08-26)
- stats-at-capture: 123162 likes / 523 comments (14.83x account median)
- joke-structure: none — it is a launch-day product reveal. The caption ("Robot Phone🤯") carries no promo markers, which is why it cleared the pre-download gate; frame-sampling settled it. The HONOR ring logo is centred in frame at 0:02, the whole runtime is retail box, tray, sleeve, and the device being demonstrated feature by feature, and the reaction faces exist to sell the hardware. Splicing this lends HONOR's marketing, which is exactly what guard 7 exists to stop. Banked as a record only; never usable
- the-beat: n/a
- audio-model: n/a
- pairs-with: nothing — do not use
- file: clips/Dcd_FfvP96F.mp4 (52s)

## Dcftx2KsFQg — a group of young men in a neon-lit club dance to a track, one in a long curly wig, with a Hinglish caption burned over every frame reading "This is my serious account funny wala Linkden pe banaya he"
- source: #programmerhumor | https://www.instagram.com/reel/Dcftx2KsFQg/
- lane: tech
- first-seen: 2026-08-26 | status: DO-NOT-SPLICE (2026-08-26)
- stats-at-capture: 71 likes / 15 comments (hashtag recent_media, no account baseline)
- joke-structure: the joke is real but it lives entirely in the burned-in text — the inversion that the unhinged account is the "serious" one and LinkedIn got the comedy. The footage underneath is generic party b-roll of identifiable strangers with no turn, no payoff and nothing to cut on, and the caption cannot be removed, so any splice would import someone else's on-screen text into the reel. Picked deliberately as the highest-comment-rate hashtag candidate (15 comments on 71 likes) to keep testing OPEN GAP #4; second scan running where comment rate found a caption rather than footage. Never usable
- the-beat: n/a
- audio-model: n/a
- pairs-with: nothing — do not use
- file: clips/Dcftx2KsFQg.mp4 (7s)

## DcfjdBSzEAm — a timestamped travel montage of a couple flying Dubai to Delhi to Srinagar with a 20-month-old: check-in kiosk, a mother crouched on the terminal floor repacking a case at 20:20, escalators, the cabin, a family selfie, the baggage belt, and a Kashmir road at dawn
- source: #toddlertravel | https://www.instagram.com/reel/DcfjdBSzEAm/
- lane: family
- first-seen: 2026-08-26 | status: DO-NOT-SPLICE (2026-08-26)
- stats-at-capture: 57 likes / 0 comments (hashtag recent_media, no account baseline)
- joke-structure: none in the footage. The caption does the comedy ("Approximately 50 snacks, zero personal space, one tiny boss running the entire trip") but what is on screen is a sincere, well-shot vlog with running clock stamps and no turn anywhere in 24 seconds. The one recognisable beat, the mother repacking on the floor in the queue, is three seconds long and shows an identifiable stranger's face. Real footage, no mechanism to lend. Never usable
- the-beat: n/a
- audio-model: n/a
- pairs-with: nothing — do not use
- file: clips/DcfjdBSzEAm.mp4 (24s)

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
- first-seen: 2026-08-10 | status: FRESH
- stats-at-capture: 9836 likes / 74 comments (hashtag recent_media, no account baseline)
- joke-structure: role reversal held by a POV text template — the children are management, the adults are staff, and the punchline is that the parents comply
- the-beat: the scolding escalates in cuts 0:00-0:16 (any single 2s correction lands on its own), the payoff is dad's defeated to-camera shrug at ~0:18-0:20. Cut on the shrug for a closed joke, or on one scold for a reaction beat
- audio-model: diegetic (bakeable) — the kids' voices ARE the joke; a track would erase it
- pairs-with: bambi.map's own baby issuing orders at a restaurant table (the highchair arrives and gets rejected anyway); an imabgold "my cofounder is a baby" beat where the toddler is the one setting the deadline
- file: clips/Db1fRXYP24v.mp4 (22.0s)

## DbwDG5UxiwR — A shirtless dad in a ball cap on his driveway court calls his shot with a raised finger, heaves a rubber playground ball at the hoop, and the camera whips up to follow it clean over the backboard and off toward the house, landing on a silent hold of the garage; held text reads "Can't believe they actually doubted UNC"
- source: @sportscenter | https://www.instagram.com/reel/DbwDG5UxiwR/
- lane: sports
- first-seen: 2026-08-10 | status: FRESH
- stats-at-capture: 700803 likes / 4175 comments (6.47x account median)
- joke-structure: called-shot bravado, anticlimax payoff — the pointing, the wind-up and the whip-pan all promise a make, and the frame delivers a total miss with no acknowledgement
- the-beat: bravado and the point 0:00-0:07, release ~0:08, the whip-pan that finds nothing but sky at 0:09, silent hold on the house 0:10-0:12. Cut on the whip-pan at 0:09; the silence after is the laugh
- audio-model: diegetic (bakeable) — the throw and the conspicuous absence of a net sound is the beat; survives being ducked under a track
- pairs-with: any user "I've got this" declared out loud right before it doesn't (imabgold calling a 5-minute fix that runs three hours, per playbook 11); a bambi "he'll definitely sit in it" before the highchair is refused
- file: clips/DbwDG5UxiwR.mp4 (11.9s)

## Db0w88EMV_E — Held text says "I was filming my cat being naughty and then she waved at me": a tuxedo cat is caught tugging a blind cord by a bedroom door, freezes when it clocks the camera, sits back and lifts one front paw straight up at the lens like a greeting, then loses interest and wanders the back of the sofa for the remaining 35 seconds
- source: @pubity | https://www.instagram.com/reel/Db0w88EMV_E/
- lane: general
- first-seen: 2026-08-10 | status: FRESH
- stats-at-capture: 248983 likes / 2064 comments (5.48x account median)
- joke-structure: caught-in-the-act, then an unexpectedly human reaction — the guilty freeze sets it up and the raised paw reads as "hello", which is funnier than the mischief was
- the-beat: mischief 0:00-0:05, the freeze at ~0:06, paw up 0:08-0:11. Cut hard at 0:12 — everything after is Pubity padding. NOTE: a small "Pubity / following" UI chip is baked into the frame around 0:11-0:14, so the clean window is 0:00-0:10
- audio-model: flexible — nothing in the audio carries the beat, so a trending track added in-app works fine
- pairs-with: bambi.map's baby caught mid-mess who looks straight up into the lens; any "cofounder clocks out" beat where the culprit shows zero remorse
- file: clips/Db0w88EMV_E.mp4 (49.3s)

## Dbtj3TFQ5k5 — A 2:20 morningbrew mini-doc asking how Jungle Jim's, America's largest grocery store, stays in business, in which the owner turns up throughout in a wizard hat, cape and a giant "JUNGLE" medallion and deadpans flat business truths — "because it's a poor man's business", "don't ask me, I don't, don't get too deep with this shit", "you want him to work for you? or you want to work for him?"
- source: @morningbrew | https://www.instagram.com/reel/Dbtj3TFQ5k5/
- lane: tech
- first-seen: 2026-08-10 | status: FRESH
- stats-at-capture: 88972 likes / 994 comments (8.88x account median)
- joke-structure: costumed-authority deadpan — a man dressed as a wizard delivering unbothered, faintly weary business wisdom; the whole joke is the gap between the outfit and the flatness of the delivery
- the-beat: no single payoff, this is a documentary. Liftable 2-3s reaction beats: the interviewer's "is this place successful in spite of you or because of you?" at ~0:13, "because it's a poor man's business" at ~0:55, and the "don't get too deep with this shit" shrug at ~1:05
- audio-model: diegetic (bakeable) — the deadpan line reading is the asset
- pairs-with: an imabgold founder-hustle setup that needs a deflating cutaway ("how is this still working" over the user's own duct-taped build). HONEST SCOPE: this lends a reaction beat, not a setup-and-punchline. If the cut needs an actual payoff, the user's own footage is stronger and this clip should sit it out
- file: clips/Dbtj3TFQ5k5.mp4 (140.9s)

## DbtHfp7xXOQ — [PRUNED DO-NOT-SPLICE] A suited correspondent walk-and-talks through Manhattan for 1:35 with printed pages in hand and real headline cards (Washington Post, NPR, Fortune,… · https://www.instagram.com/reel/DbtHfp7xXOQ/ · first-seen 2026-08-10

## DbwA-X6xW_C — [PRUNED DO-NOT-SPLICE] The same morningbrew street-explainer format asking "what happened to Lululemon?": a correspondent walks past a Lululemon store for 1:56 with headl… · https://www.instagram.com/reel/DbwA-X6xW_C/ · first-seen 2026-08-10

## DbrDhZ4suSs — Held text says "these puppies hide so well their owner put bells on them", the camera hunts an empty bedroom, floor and baseboard finding nothing, then a tiny dachshund with a bright pink bell on its collar is discovered wedged against the skirting board staring up at the lens, and a second one is found in the next gap
- source: @pubity | https://www.instagram.com/reel/DbrDhZ4suSs/
- lane: general
- first-seen: 2026-08-06 | status: STALE (2026-08-28)
- stats-at-capture: 210778 likes / 585 comments (53.78x account median)
- joke-structure: absurd-but-logical coping hack stated up front, then a POV hunt that pays off in a reveal — the bell explains the search and the search makes the reveal land
- the-beat: text + empty-room hunt 0:00-0:04 (nothing in frame, this is the tension), first puppy reveal at 0:05, second find at ~0:13 — cut on the 0:05 reveal, or run both finds for a double payoff
- audio-model: flexible — the bell jingle is a genuine diegetic bonus, but the reveal is entirely visual and survives being ducked under a trending track
- pairs-with: any "I had to invent a system to find this thing" beat where the user's own footage is the search — hunting the one restaurant with a highchair, hunting the bug that only appears in production, a toddler who has gone silent in a hotel room
- file: clips/DbrDhZ4suSs.mp4 (16.2s)

## DbmQH7CtNX- — IShowSpeed's brother, blindfolded and in a Buc-ee's beaver onesie, bites unmarked fast-food burgers and names the chain each time; Speed pulls the next one from a bag, holds the Sonic/McDonald's packaging up to camera to confirm the call, and gets progressively more wrecked, ending with both hands on his own head
- source: @sportscenter | https://www.instagram.com/reel/DbmQH7CtNX-/
- lane: sports
- first-seen: 2026-08-06 | status: STALE (2026-08-28)
- stats-at-capture: 2404356 likes / 12774 comments (30.22x account median)
- joke-structure: repeating challenge cycle — impossible claim, blind attempt, brand-reveal confirmation, escalating disbelief from the witness. The witness's reaction is the joke, not the feat
- the-beat: 111s of repeated cycles, so lift ONE. Cleanest single cycle is 0:28-0:45 (burger out of the bag → blind bite → the Sonic bag held to camera as proof); peak reaction is the head-grab at ~1:28. Cut on a reveal-then-react pair, never run the whole thing
- audio-model: diegetic (bakeable) — the reactions and the calls are the beat; muting this clip removes the joke
- pairs-with: any "I did not believe this would work and it did" moment where the user is the stunned witness — a prompt that one-shots the feature, a toddler who eats the entire unfamiliar meal, a guess that turns out exactly right
- file: clips/DbmQH7CtNX-.mp4 (111.4s)

## Dbr6mRMJewR — Held text reads "POV: your dad said he didn't want a puppy" over a man on a sofa working at a laptop in pyjama pants, with an apricot cockapoo puppy draped asleep across his shoulder and neck the entire time; he never acknowledges it and quietly smiles at the camera
- source: @pubity | https://www.instagram.com/reel/Dbr6mRMJewR/
- lane: general
- first-seen: 2026-08-06 | status: STALE (2026-08-28)
- stats-at-capture: 41643 likes / 170 comments (10.64x account median)
- joke-structure: reported past refusal versus present visible evidence — the subject is caught in the contradiction and refuses to comment on it, which is the whole gag
- the-beat: text over the wide 0:00-0:02, puppy readable on the shoulder from 0:03, his knowing look ~0:05-0:08 — cut on the moment the puppy registers, hold for the smile
- audio-model: trending sound (add in-app) — quiet room, no dialogue, no diegetic beat; this format rides a soft library track and must not be baked in
- pairs-with: any "they swore they were against this" reversal in the user's own footage — the partner who did not want the trip photos, the founder who said he would never let AI touch the codebase, the parent who said no more toys in the suitcase
- file: clips/Dbr6mRMJewR.mp4 (11.1s)

## DbsPBsrB6hm — Held text says "he hit that backflip and the monkeys were hyped"; a man at a zoo enclosure lands a standing backflip on the path, and the macaques behind the glass erupt, launching themselves off the wall and bouncing around the enclosure while he watches
- source: @pubity | https://www.instagram.com/reel/DbsPBsrB6hm/
- lane: general
- first-seen: 2026-08-06 | status: STALE (2026-08-28)
- stats-at-capture: 39489 likes / 292 comments (10.12x account median)
- joke-structure: the human does the impressive thing, but the payoff is entirely the audience's reaction — the joke is that the crowd is monkeys and they are genuinely losing it
- the-beat: approach + text 0:00-0:03, backflip lands ~0:04, monkeys erupt 0:05-0:14 (this is the payoff, hold it), the guys wander off 0:16-0:18 — cut on the eruption at 0:05
- audio-model: flexible — the enclosure noise adds to it but nothing is said; works ducked under a trending track
- pairs-with: any "I did one small thing and the reaction was disproportionate" beat — a first sale notification, a toddler applauding something trivial, a demo that got a bigger reaction than the product deserved
- file: clips/DbsPBsrB6hm.mp4 (18.6s)

## DbqpAqORnm8 — [PRUNED DO-NOT-SPLICE] A morningbrew suited correspondent walk-and-talks two minutes of Citadel/Situational-Awareness finance news with headline screenshots and reaction memes; no liftable beat, format kept as playbook #28 · https://www.instagram.com/reel/DbqpAqORnm8/ · first-seen 2026-08-06

## Dbnyi4guiod — Held text reads "whole squad pulled up to the movie"; a full-size Hulk and two Spider-Men in complete costume are crammed into a cinema row, climbing over the seat backs and squeezing past the actual paying audience, whose view is now entirely a green bodybuilder
- source: @houseofhighlights | https://www.instagram.com/reel/Dbnyi4guiod/
- lane: sports
- first-seen: 2026-08-06 | status: STALE (2026-08-28)
- stats-at-capture: 211955 likes / 828 comments (2.5x account median)
- joke-structure: total over-commitment played straight in a setting that punishes it — nobody breaks character, and the comedy is the innocent bystanders behind them
- the-beat: whole 13s is one sustained bit; the strongest window is the Spider-Man clamber over the seats at 0:04-0:08 — cut there and let the person behind them be visible in frame
- audio-model: flexible — ambient cinema chatter only, no line to protect
- pairs-with: any "we massively overdid it for a normal occasion" beat — arriving at a casual dinner with the full baby setup, a two-week build for a one-button feature, the stroller-plus-bags entrance into a small restaurant
- file: clips/Dbnyi4guiod.mp4 (13.1s)

## DbjAfeTsSCh — [PRUNED STALE] "my cat Elsa, she is very stealthy" held over Elsa sitting in plain sight, paid off by her enormous face sliding into the lens · https://www.instagram.com/reel/DbjAfeTsSCh/ · first-seen 2026-08-03
## DbkOasfBRTc — [PRUNED STALE] a Yorkie blocks the laundry, then escalates by climbing bodily into the dryer and staring its owner down from inside the drum · https://www.instagram.com/reel/DbkOasfBRTc/ · first-seen 2026-08-03
## Dbi8hsFxMD9 — [PRUNED STALE] a real estate agent steps back off the top stair mid-sentence and goes down the whole flight during a house viewing · https://www.instagram.com/reel/Dbi8hsFxMD9/ · first-seen 2026-08-03
## DbjVJzxMvly — [PRUNED DO-NOT-SPLICE] Static close hold on newborn twins, one asleep with her thumb in her crying brother's mouth, recontextualised by one line of held text; no comedic mechanism and identifiable strangers' newborns — format kept as playbook 27 · https://www.instagram.com/reel/DbjVJzxMvly/ · first-seen 2026-08-03

## DbkuBBRKD4T — [PRUNED DO-NOT-SPLICE] "My tech leader to me & my colleagues" selfie hook cut to a Bollywood film clip; neither half lendable (identifiable stranger + copyrighted film footage) · https://www.instagram.com/reel/DbkuBBRKD4T/ · first-seen 2026-08-03

## DbZD_IcxCMy — [PRUNED DO-NOT-SPLICE] 1:44 talking-head news explainer on a $50B Louisiana data center approved under a secret codename; straight journalism, no joke and no clean beat to cut on · https://www.instagram.com/reel/DbZD_IcxCMy/ · first-seen 2026-08-03

## DbZYl9oJ9Cj — [PRUNED STALE 2026-08-22] Helmet-cam rider pulls level with a car that had been driving hard, asks the driver why he was in such a rush · https://www.instagram.com/reel/DbZYl9oJ9Cj/ · first-seen 2026-07-30

## DbZkdaWJeb2 — [PRUNED STALE 2026-08-22] A baby in a restaurant highchair gets his first bite of steak, goes wide-eyed feral and gnaws it two-handed while dad tries to hold it steady · https://www.instagram.com/reel/DbZkdaWJeb2/ · first-seen 2026-07-30

## DbWT85WBm0a — [PRUNED STALE 2026-08-22] A small boy in a full Spider-Man suit slowly peels the mask off to "reveal his secret identity" to his parent and lands on a huge proud grin · https://www.instagram.com/reel/DbWT85WBm0a/ · first-seen 2026-07-30

## DbTsR5LR5W3 — [PRUNED STALE 2026-08-22] Office skit in a real conference room: five people wearing paper badges reading OpenAI, Microsoft, Nvidia and Google pass the same handful of cash... · https://www.instagram.com/reel/DbTsR5LR5W3/ · first-seen 2026-07-30

## DbTc4IRhNDT — [PRUNED STALE 2026-08-22] A woman sits inside a dryer drum wrapped in bedding and tumbles with it, playing the fitted sheet through its whole cycle, then the shot cuts to... · https://www.instagram.com/reel/DbTc4IRhNDT/ · first-seen 2026-07-30

## DbO74yghLkl — [PRUNED STALE 2026-08-22] ITV game-show clip ("What Would Your Kid Do?"): a small girl calmly lectures the host that Dubai has a tropical desert climate while her parents... · https://www.instagram.com/reel/DbO74yghLkl/ · first-seen 2026-07-30

## DbRGKvJz6bL — [PRUNED STALE] Suburban driveway hoop after rain: a middle-aged dad in floral shorts plays his two teenage sons, backs the shirtless one down, and buries a... · https://www.instagram.com/reel/DbRGKvJz6bL · first-seen 2026-07-27

## DbMNX2lE4hm — [PRUNED STALE] An armadillo trots across a tiled lobby floor, past a lounging iguana, straight to a big leather massage chair, then climbs the arm and settles... · https://www.instagram.com/reel/DbMNX2lE4hm · first-seen 2026-07-27

## DbQcn9Ls47b — [PRUNED STALE] Night on a bar strip: a young guy stands safely behind a glass door taunting a police officer on the other side, sticking his tongue out at him.... · https://www.instagram.com/reel/DbQcn9Ls47b · first-seen 2026-07-27

## DbRF5SgDrB_ — [PRUNED STALE] Family around a kitchen island. A woman scratches what she thinks is a lottery ticket, reads "we're having a baby" out loud, and completely fails... · https://www.instagram.com/reel/DbRF5SgDrB_ · first-seen 2026-07-27

## DbS23kppOgh — [PRUNED STALE] Seven-second dev meme: a guy at a desk sits head-in-hands staring at his monitors under the text "That moment when your fix breaks prod", then a... · https://www.instagram.com/reel/DbS23kppOgh · first-seen 2026-07-27

## DbG8iH0J-Yg — [PRUNED DO-NOT-SPLICE] Morning Brew correspondent walking a supermarket aisle with a bottle of weedkiller for a 2.5-minute sincere piece on the pesticide industry; caption read like a skit, footage was consumer journalism, no bit and no turn · https://www.instagram.com/reel/DbG8iH0J-Yg/ · first-seen 2026-07-27



## DbHFRLzJjuH — [PRUNED STALE] Two-hander office skit dramatising a real 404 Media headline (shown as a card up top: "AI Companies Are Buying Tons of Old Books Because They're Free  · https://www.instagram.com/reel/DbHFRLzJjuH/ · first-seen 2026-07-23

## DbAyGZhDktL — [PRUNED STALE] Selfie-cam in a moving car, one mum performing both halves of a toddler refusal loop under the held text "i'm in whatever phase of parenting this is". · https://www.instagram.com/reel/DbAyGZhDktL/ · first-seen 2026-07-23


# donor-shelf.md — which banked clips can actually carry a payoff beat

Generated 2026-08-28 by `scratchpad/0828/donor_probe.py` over all 66 FRESH clips in
`~/Claude Code/viral-bank/clips/`. Read-only, local files, no API, no network.

## Why this exists

On 2026-08-28 four separate donor candidates were killed mid-build, none of them on taste:
a burned caption straddled the payoff, a broadcast scorebug covered every frame, a subject
was a dot at 576x720, and one clip turned out to have no motion in it at all. The catalog
records `pairs-with`, `the-beat` and `joke-structure` but NOTHING about whether a clip can
survive a 9:16 crop. So every architect rediscovers those failures by hand, one at a time.

## What is RELIABLE here

**`motion`** — mean per-pixel temporal delta. Validated: the static owl tableau
(`DcejaQYskRm`) scores 30.8 while real events score 90-130. **Under ~60 means there is no
event in the clip and it will read as boring.** This is the column to trust.

## What is NOT reliable, and must not be trusted alone

**`clean_top/clean_bot/upscale`** — the caption-band estimate. It was tuned against five
hand-measured clips and no single configuration got all of them right: a whole-clip scan
misses captions that FADE OUT partway, and a two-window scan that catches those then
produced a false positive on `DcPA-oJv9WA`. Treat these as TRIAGE ONLY.

ARCHITECT-CORE §6.2 already states the governing rule and it applies to this probe verbatim:
*"THE ROW-SCAN HAS FALSE NEGATIVES AND YOU MUST ASSUME IT DOES [...] The visual check on the
cropped beat is mandatory, never optional."* This file narrows 66 candidates to a short list.
It does not replace rendering the beat and looking at it.

`caption_fades: True` means the caption is present in one half of the clip and not the other,
so the clean window depends on WHERE you cut.

## The shelf, ranked by motion (most event first)

| shortcode | src | dur | motion | est. clean band | est. upscale | fades | spent here | what it is |
|---|---|---|---|---|---|---|---|---|
| `Dbtj3TFQ5k5` | 720x1280 | 140.8s | **156.69** | 0-1280 | 1.5x |  |  | A 2:20 morningbrew mini-doc asking how Jungle Jim's, America's largest |
| `DcbrenYTLvn` | 720x1280 | 29.1s | **156.24** | 0-807 | 2.38x |  |  | a mother waits in a parked car outside a school with the camera runnin |
| `DcGbL1OtjwX` | 720x1280 | 36.8s | **141.31** | 0-1280 | 1.5x |  |  | Held text "MY DOG WON'T EAT HER FOOD UNLESS I DO THIS"; overhead of tw |
| `DcGyjYTsP_C` | 720x1280 | 42.0s | **140.77** | 0-1280 | 1.5x |  |  | Held text "A DEER CAME RUNNING OVER AFTER HEARING MY BABY CRY BECAUSE  |
| `Dcb-qSBMPs-` | 720x1280 | 36.8s | **139.49** | 0-683 | 2.81x | YES |  | a mother walks into a daycare room to collect her baby after the baby' |
| `DcjD2G_BO6p` | 720x1280 | 16.9s | **139.43** | 0-1280 | 1.5x |  |  | a mom packs her kid's school lunchbox, walks to the pantry, comes back |
| `DciiHyLJ0ab` | 720x1280 | 18.1s | **137.76** | 0-1280 | 1.5x |  |  | a blonde toddler on a Southeast Asia trip gets treated as a minor cele |
| `DcVwWQ4MhZd` | 720x1280 | 24.2s | **132.88** | 0-663 | 2.9x |  | SPENT | a white bull terrier prances and rears up at a front gate showing off  |
| `DcOyHDVsWu_` | 720x1280 | 25.2s | **129.65** | 132-1280 | 1.67x | YES |  | 25 unbroken seconds of twin toddlers squabbling around a bed frame, pr |
| `DcS50NqJHGa` | 720x1280 | 15.6s | **129.08** | 121-987 | 2.22x | YES |  | a tiny apricot poodle puppy climbs onto a woman mid-yoga-pose, licks h |
| `DaW57QKigDK` | 720x1280 | 11.9s | **126.6** | 440-1280 | 2.29x |  |  | Text "Bad news for claude / I just got home" over a hand jangling car  |
| `DcJGKfFh6ct` | 720x1280 | 44.3s | **124.71** | 29-1280 | 1.54x | YES |  | one man plays every member of a Middle Eastern household and physicall |
| `DcjkZ-JMFJk` | 720x1280 | 45.0s | **123.99** | 0-1280 | 1.5x |  |  | an office ensemble stands around a styrofoam tray of raw ground beef o |
| `DcOyH6dxYnH` | 720x1280 | 27.9s | **121.16** | 0-1280 | 1.5x |  |  | two boys play a backyard golf hole; one misses, throws his club, storm |
| `DcWaRKKRIz9` | 540x960 | 19.9s | **121.13** | 0-550 | 3.5x |  |  | a fan filming from the stands at Austin FC heckles the referees walkin |
| `DbXGmRlN_J9` | 720x1280 | 19.9s | **120.82** | 0-1280 | 1.5x |  |  | Text "POV: you try to take a break as an entrepreneur" over a man clos |
| `DcQSJ10hrBL` | 720x1280 | 60.1s | **120.06** | 0-479 | 4.01x |  |  | a four-year-old in a pink helmet bails hard off her skateboard, says " |
| `DcRGvqlOANT` | 720x1280 | 92.3s | **118.52** | 420-1007 | 3.27x |  |  | a college football team's graduate assistant takes a mic at fall camp  |
| `DcQmzUTsBPA` | 720x1280 | 6.3s | **115.69** | 587-1097 | 3.78x | YES |  | camera creeps into a silent bedroom and finds the toddler has dressed  |
| `DcPUbEOtkQQ` | 540x960 | 11.9s | **115.45** | 0-593 | 3.24x |  |  | a woman sprints across an airport arrivals hall and tackles the person |
| `DcgPzrwP7YO` | 720x1280 | 37.3s | **113.98** | 215-1280 | 1.8x | YES |  | a creator in a bright orange tee holds up two phones side by side, an  |
| `DcOsj2YxDtM` | 720x1280 | 31.3s | **112.79** | 258-850 | 3.24x |  |  | a lone cheer base repeatedly launches, catches and holds a full-grown  |
| `Db1fRXYP24v` | 720x1280 | 22.0s | **112.39** | 312-861 | 3.51x |  |  | Two small girls run a doll-and-Barbie-jeep play session and spend the  |
| `DYSOi-KRQlc` | 720x1280 | 7.7s | **111.82** | 654-1280 | 3.07x |  |  | Cafe POV: text "Okay guys I brought my macbook to a coffee shop now ho |
| `DcWgZqvsyBN` | 720x1280 | 9.7s | **110.64** | 0-929 | 2.07x |  |  | a toddler sits stone-faced at a restaurant table ignoring his dad rubb |
| `DcjrEHSNT02` | 720x1280 | 17.5s | **107.98** | 0-1280 | 1.5x |  |  | filmed from inside a parked car: a woman leans into the open passenger |
| `DcHbqLLsRSW` | 720x1280 | 72.4s | **107.9** | 0-1003 | 1.91x | YES |  | Night, a yellow semi truck; the driver pulls the locked door handle, t |
| `DcV-GoxMZPm` | 720x1280 | 51.3s | **107.13** | 692-1280 | 3.27x | YES |  | a horse lies completely flat out asleep in a field while two others st |
| `DcPZpsHvdPn` | 720x1280 | 7.8s | **106.44** | 0-661 | 2.91x |  |  | a small boy processes into his First Communion with a completely stone |
| `DcSiav-hR5k` | 720x1280 | 20.5s | **106.31** | 0-1280 | 1.5x |  |  | a cat detonates through a quiet, formal living room, launching off an  |
| `DbwDG5UxiwR` | 720x1280 | 11.9s | **103.19** | 492-852 | 5.35x |  |  | A shirtless dad in a ball cap on his driveway court calls his shot wit |
| `DcPA-oJv9WA` | 720x900 | 6.8s | **103.07** | 234-596 | 5.32x |  | SPENT | a kid at his first karate class attempts a spinning kick, gets complet |
| `DcZYwxNPtgR` | 720x900 | 26.5s | **101.05** | 668-900 | 8.31x |  |  | an older man in a golf cap stands at a convenience-store ice machine h |
| `Dcc2HXlBkp8` | 720x1280 | 10.5s | **100.56** | 211-679 | 4.11x |  |  | a baby in pink footed pyjamas toddles across a living room rug, stops  |
| `DcPNHpRz6mO` | 720x900 | 15.6s | **97.7** | 0-762 | 2.52x |  | SPENT | a man in a restaurant booth folds in half laughing, head thrown back,  |
| `DcUeHRpP7dt` | 720x1280 | 11.6s | **97.13** | 0-778 | 2.47x |  | SPENT | a humanoid robot sprints down an empty stadium track, runs straight of |
| `DcPUWj1vU78` | 720x1280 | 14.9s | **92.36** | 0-787 | 2.44x |  | SPENT | a humanoid robot sprints a full lap of an empty Olympic track, then dr |
| `Dce-56EPoI9` | 720x1280 | 23.2s | **92.28** | 0-778 | 2.47x |  |  | a humanoid robot at a competition squats, cleans a tiny barbell over i |
| `DcVBZDiNrHF` | 720x1280 | 19.6s | **88.49** | 0-710 | 2.71x |  |  | a reliever pumps himself up on the mound after what he thinks is the l |
| `DcYoFWAR1o_` | 720x900 | 29.0s | **88.16** | 0-578 | 3.32x |  |  | Erling Haaland walks into a bathroom to show his girlfriend a fresh bu |
| `DcUktOtxSmD` | 480x854 | 13.3s | **87.69** | 0-412 | 4.68x |  |  | a long putt drops on a sunset green and the two friends detonate, thro |
| `DcUQOH9srXf` | 720x1280 | 7.8s | **86.6** | 983-1280 | 6.47x |  | SPENT | a man goes headfirst down a waterslide, hits the pool and skips across |
| `DcT3PiGMZaO` | 720x1280 | 10.7s | **82.46** | 231-1280 | 1.83x |  |  | three restaurant plates in a row: a loaded Daddy plate, a huge Mommy s |
| `DcTuLiwRLAT` | 720x1280 | 10.7s | **79.11** | 301-1280 | 1.96x |  |  | an NFL player's chain snaps off his neck at the exact second the broad |
| `DcT7YxBNUuR` | 720x1280 | 19.2s | **78.69** | 566-1280 | 2.69x | YES |  | a cat leans in to smell a sleeping dog's breath, recoils, and then hol |
| `DZu9rl2RtDy` | 720x1280 | 10.2s | **77.27** | 0-321 | 6.0x |  |  | Skit: text "CTO watching CEO sell clients features that don't exist 😭🥀 |
| `DchxQobpYeD` | 720x1280 | 53.5s | **75.19** | 353-785 | 4.44x |  |  | a man dressed for an office (navy sweater, white collar, chinos) walks |
| `Dceg78QTZrw` | 720x1280 | 39.0s | **71.24** | 413-1003 | 3.26x |  |  | a young man sits alone on an Alaskan riverbank filming himself, and a  |
| `DcQ7__eRvNv` | 576x720 | 7.3s | **66.25** | 52-504 | 4.25x |  |  | a field hockey player walks deliberately into a full-force pitch sprin |
| `DcTZGVRtjBP` | 720x1280 | 13.3s | **56.4** | 314-1280 | 1.99x |  |  | hikers on a fog-blasted Portuguese ridge get taken off their feet by a |
| `DcBuSDMRHn2` | 720x1280 | 22.3s | **56.03** | 0-785 | 2.45x |  |  | Night rec-league softball under the lights: batter connects, the ball  |
| `DcdbMbPzkk2` | 1080x1920 | 5.9s | **55.67** | 475-1920 | 1.33x |  |  | the Charlie Day "Pepe Silvia" scene from It's Always Sunny: a man in a |
| `DcW1AFxMmzg` | 720x1280 | 27.8s | **52.52** | 1104-1136 | 60.0x |  |  | a kitten play-wrestles a hand held above it, then falls asleep mid-fig |
| `DcTqoISNurc` | 720x1280 | 63.2s | **51.36** | 839-877 | 51.43x |  |  | a man proposes on an empty beach while the couple's golden retriever d |
| `Dch_JVZJUqV` | 720x1280 | 10.1s | **50.03** | 553-1280 | 2.65x | YES |  | sofa POV (filmer's bare legs in frame): a small cream dog has been sen |
| `DcWZL80RUYY` | 720x1280 | 62.1s | **49.98** | 1214-1280 | 29.19x |  |  | a woman films her husband on the couch and deliberately feeds him wron |
| `DcesVmGyLIu` | 1080x1920 | 6.3s | **49.53** | 0-0 | 99x |  | SPENT | Selfie POV: held text "startup founders once the product is live and n |
| `Db0w88EMV_E` | 720x1280 | 49.2s | **48.39** | 713-1280 | 3.4x |  |  | Held text says "I was filming my cat being naughty and then she waved  |
| `DZ7ArcGIBBU` | 720x1280 | 7.4s | **44.34** | 0-600 | 3.2x |  | SPENT | Desk POV: text "Yeah running a business is hard but there's no way I'm |
| `DcH2hkzBzKc` | 720x1280 | 7.0s | **38.06** | 290-674 | 5.0x |  |  | Kitchen, mom in a pink tee lecturing her preteen son (white tee, backw |
| `Dcjs-mosR_f` | 720x1280 | 11.4s | **36.46** | 645-1280 | 3.03x |  |  | static security-cam wide of a living room: one dog wanders in, and wit |
| `DcZFHoVNkmC` | 720x1280 | 20.5s | **33.77** | 0-1280 | 1.5x |  |  | a locked-off hallway camera watches a cat flap for five seconds under  |
| `DcejaQYskRm` | 720x1280 | 8.3s | **30.75** | 0-782 | 2.46x |  |  | a garden owl on the lawn spreads its wings and puffs itself to roughly |
| `DckQiZXhN_F` | 720x1280 | 17.7s | **30.48** | 1001-1280 | 6.92x |  |  | two parents start slow-dancing alone in their kitchen and are progress |
| `DcPaax_NfyB` | 720x900 | 11.8s | **28.78** | 186-456 | 7.15x |  | SPENT | a lifter benching heavy dumbbells gets "help" from a spotter who yanks |
| `DaytndsJOv2` | 720x1280 | 10.8s | **6.81** | 335-1280 | 2.03x |  | SPENT | Text held the whole clip: "\"you got lucky\" / the luck:" over a cinem |

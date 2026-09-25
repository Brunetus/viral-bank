# Viral bank / scan — changes agreed 2026-09-24 (interactive, Marcus)

Status doc. Written so tomorrow's scan agent and any later session can see
what was ruled, what was built, and what is still open.

## 1. DONE — already written to disk

**@prettylushangel banked by Marcus's ruling.**
The 09-24 scan resolved her (Ddqwhx2xmW7, "you want to know how I know that
men are a lot more selfless"), passed the caption tests, then REFUSED to
append on feed quality (53 followers, median engagement 1, adult-content
funnel) and asked for a ruling. **Marcus ruled ADD.**
- `catalog.md` — entry for Ddqwhx2xmW7, status BANKED PENDING MEASUREMENT
- `watchlist.md` — appended to the `[premise]` lane
- backups: `catalog.md.bak-0924`, `watchlist.md.bak-0924`
- ⚠ Tests 5 and 6 are NOT measured. The probe mp4 was scratch and was deleted
  after the 09-24 frame read. Next scan re-fetches and measures before any cut.

## 2. RULED — and now WRITTEN into BANK.md (test 7 amended, 2026-09-24 evening; step 1b added). Backup: BANK.md.bak-0924

**(a) Test 6 (setup >= 3s) STAYS.** Marcus: 3 seconds is how Instagram
calculates skip rate, so a hook needs to clear it to take full effect. No
relaxation to 2s. The earlier proposal to split the test on "truncated repost
vs fast original" is WITHDRAWN on the length half.

**(b) Test 7 (creator's original, not a repost) is AMENDED, not dropped.**
Marcus: a clip may be sourced second-hand, e.g. lifted from another creator's
reel, **as long as we quote where we took it from**.
The evidence that settles it: test 7 was written because @thexcelguy's reposts
cut the donor at 2.0-2.4s, which is a LENGTH failure wearing a sourcing
costume. Measured today on @programmergrind's `DaWr4F9OH9q`: the borrowed
woman opener runs **0.00-4.03s, complete**, which is the same length as the
account's two best donors (4.03s and 4.60s).
**New shape of the test:** reject a copy that TRUNCATES the premise. Accept a
second-hand copy that carries it whole, and record the chain (original creator
if nameable, plus the account we took it from) in the entry.

**(c) Covers are no longer a constraint on format choice.** Thumbnails are
produced as part of the process and delivered every time, so "the donor owns
the grid tile" stops being an argument against donor-opener structures.

## 3. BUILT (v1, file-driven) — `saved-inbox.md` + BANK.md step 1b; today's 12 reels processed: 1 BANKED (@annabellegesson DZGH-MeorB6, all 8 tests pass, setup 3.52s/3.70s, THEME COOLDOWN vs fire_dev_v2), 11 tombstoned; 11 creators added under a new `[saved]` lane, @annabellegesson under `[premise]`

**(d) The Saved collection feeds the scan.**
Marcus: "whenever I save a reel, that account should be added to the viral
scan", and eventually the scan should run mostly off his saved folders. His
own sequencing: **ADD the features first, watch how it performs, THEN cut the
old ones.** Nothing is removed yet.

Verified feasible today from the logged-in session:
- Collection is `Viral stuff`, `instagram.com/imabgold/saved/viral-stuff/901996575663900/`
- Holds **12 reels**, programmatically readable
- **All 12 are unknown to catalog.md. All 11 creators are absent from watchlist.md.**
- Includes **@thegroundedmen**, whose clip Marcus actually shipped as
  `credits_reset` on 09-22. The bank has never heard of him.
- For contrast, the 09-24 hashtag sweep read 178 fresh reels across ten tags
  for **0 leads**.

Design, as outlined and accepted:
1. New step, runs FIRST, before the hashtag sweep
2. Read both saved surfaces (the `Viral stuff` collection and general Saved)
3. Dedupe every shortcode against catalog.md
4. Run each new one through the existing 8 gate tests, with 6 intact and 7 amended
5. Passes to the `[premise]` lane; fails get a tombstone so no slot is respent
6. **Every creator saved goes onto watchlist.md**, origin-tagged, so their
   future posts are read on every later scan
7. Non-premise but good formats go to playbook.md rather than being discarded

Invariants stated and accepted:
- Saving is NOT approving. The 8 tests still run. (The collection contains
  NVIDIA and a lifestyle account, so the gate is doing real work.)
- Read-only on his account. Nothing posted, saved or unsaved.
- **Main risk: the collection is private, so the throwaway cannot read it.**
  The scan runs headless at 08:00 via launchd and a logged-in session may not
  exist there. This is the part most likely to break. Find out in testing.

## 4. FINDING that changes format selection

`DaWr4F9OH9q` (@programmergrind, 57.6K likes / 3.2K shares) measured by scene
detection:
- **0.00-4.03s** borrowed woman clip, FULL FRAME, burned card "men with no hoes"
- **4.03-76.19s** Danny + a rotating screen below (code editor -> a Claude
  prompt -> YouTube Kobe search -> Kobe motivation videos -> a recursion article)

**This is not a new format. It is the account's own #54 donor-opener with the
body extended from a ~6s payoff to a 72s explainer.** So the educational lane
Marcus wants does not require abandoning the proven engine; it requires a
longer body behind the same 4-second donor hook.

Caveat to weigh: @imabgold's reels run 6-8s. The longest recent own-footage
post, the `opus55` skit at 25s, took 7 comments, the best of that week.
Recommendation on record: test at **25-35s first, not 76**, and grade on
comments (bar 6), not views. Rule 97 still says no own-footage reel has
cleared 10k in 110 tries.

## 5. STILL OPEN
- @prettylushangel's clip MEASURED 2026-09-24 evening: tests 5/6 pass, setup 3.84s, weak slot (claim + "how I know", no eliminations); FRESH, ranked below DZGH-MeorB6.
- Runtime for the first long-body reel not ruled (25-35s proposed).
- Headless reading GRANTED by Marcus (09-24 evening). Built `ig-routine-core/read-saved.sh`: renders the collection once a day from a copy of Chrome "Profile 1" (Marc)'s cookie jar, takes shortcodes+handles off the grid, appends new ones to `saved-inbox.md`. No downloads on his session, once/day, refuses other URLs and the throwaway. Config `~/.config/ig-fetch/saved.json`. First live run found the collection holds 24 reels (the pane read had stopped at 12); the 12 new ones are queued for tomorrow's scan.
- Marcus 09-24: @programmergrind is a DONOR SOURCE (the women he borrows as openers), not format-only — catalog, watchlist and step 1b updated. A tombstone is always the REEL, never the account; @thegroundedmen stays watched, but test 1 (woman to camera) rejects his male-voice clips unless Marcus grants a carve-out (OPEN).
- Audit round 1 (Opus): FIX-FIRST — 4 fix-first, 6 should-fix, 1 nit. All applied 2026-09-24 evening: banked entries were `status: BANKED` (invisible to the FRESH canon) -> FRESH with full step-5 fields; `[saved]` lane's relationship to EXCLUSIVE MODE stated in step 1 and the watchlist header; step-5 template `original:` line now admits whole-premise copies with the chain; step 1b rewritten (absolute no-read rule, dedup-first, ig-fetch route + budget priority, gate before watchlist append, HTTP-400 handling, 5b hand-off, bare-URL rule, `## re-measure` queue); guard-4 carve-out for the interactive fill; stale test-7 glosses fixed; step-7 close-out counts; .gitignore for *.bak-*. Audit round 2 (Opus): FIX-FIRST — my catalog rewrite had left 13 duplicate blocks (stale copies deleted by hand; step 1b now says edit-in-place, one block per shortcode); step 1b's ban sentence contradicted its own read-saved.sh order (reworded: the script is the one read); read-saved.sh hardened (once-a-day counts ATTEMPTS, profile locked to Profile 1, URL locked to /imabgold/saved/, trap + wait on every exit, real Chrome UA, exit 5 on no session marker or 0 items, dedup on URLs so codes ending in '-' and bare-URL lines match); HTTP-400 passer rule made consistent in step 1, step 1b and the watchlist; stale prettylushangel/annabellegesson notes fixed; step 7 counts. Audit round 3 (Opus): bank files SHIP (all round-2 fixes held; sizes/md5 verified). Applied: read-saved.sh UA now follows the installed Chrome (153), Python-failure and missing-header paths exit non-zero, INT/TERM exit 130, exec'd Chrome, URL rejects ../?/#; BANK.md: copy-source account stays [saved] + 1 fetch/scan for donor-source accounts, unprobed [premise] line returning 400 moves to [saved] (unreadable), step 7 appends the saved-read line, two leftover 'only cookie path' sentences patched, step 1b wording (copy of the cookie jar); catalog DaWr4F9OH9q source line in template shape (bank-sync consumers) + 0916_green_flag provenance note on DYLF0zvTx80 (never aired, no block); watchlist @thexcelguy note. SCRIPTS.md: Reel A's last spoken line is now the loss (DASH ask moved to an on-screen card that also carries the rule-89 line), the 3 lines are gated only (removed from the caption, single ask), CONFIRM flags on the unverified claims (twenty years / every caption clean / never once clean), CLAUDE.md-contains-an-em-dash warning; Reel B flagged as a REPEAT of `second_agent` (09-11, 0 comments) with two honest filming options; first-vs-third-person body is Marcus's ruling.
- TONIGHT'S DONORS (fetch slots 5-8 of 8, all spent): @lilybrooksmind DYLF0zvTx80 BANKED ("the greenest flag in a man isn't money or looks" — the one_thing shape, 3.26s/3.74s); @brennaberg DdRj8VNRO3D BANKED ("the hottest thing a man can do is take care of things", 3.54s, half-filled slot, theme cooldown); @programmergrind's opener DaWr4F9OH9q BANKED as a COPY ("men with no hoes... where are you?", 4.03s, creator unknown); @hey_berg DZd-6CEAWPc tombstoned (says Claude); @casiahwest DIwXzqnxjUM tombstoned (negative frame). 8 inbox lines remain for tomorrow's scan (the remaining new saves) — the pane pre-screen was blocked by the app's permission classifier, so the scan does them.
- FILM SCRIPTS written: imabgold-ig/drafts/0924_educational_pair/SCRIPTS.md — Reel A (em dash) on the lilybrooksmind opener, Reel B (auditor agent) on the programmergrind opener; both donor-opener + 25-35s whiteboard/MacBook body; comment gate on A only.
- ig-routine-core commit (BANK.md, .gitignore, read-saved.sh) after audit round 2. The repo's OTHER uncommitted edits (ARCHITECT-CORE §6.6 setup-caption corollary 09-14, JOBS.md revision-in-place 09-13, WORDCAPS cut-boundary rules 09-11, ig-fetch cap 8 + info-json 09-17/18, release-reel NO-NAG 09-14, run-reel-worker .session-live 09-13, untracked `face` binary + `face.swift`) are finished dated work from other sessions — Marcus to decide whether they go in a separate commit; the `face` binary should not be committed.

## 2026-09-24 late — RULING: no AI donors, ever
- @lilybrooksmind (DYLF0zvTx80) is an AI avatar by her own bio. Marcus: "we can't use any donor that's AI."
- BANK.md test 1 now carries a real-person clause (bio / feed shape / generator watermark); probe curl returns name+biography. Commit 2482d99.
- catalog: DYLF0zvTx80 -> DO-NOT-SPLICE. watchlist: handle moved to Dropped. drafts/0916_green_flag dead.
- Reel A "the dash" re-pointed at @annabellegesson DZGH-MeorB6 (theme cooldown: not the next post).

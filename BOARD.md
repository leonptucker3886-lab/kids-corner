# LeonLink Board

Orders flow: Leon → Stonewall → Pip (operational control) → team leads.
An order is not live until it is on this board.

---

## STANDING ORDER #1: the board runs on the hour (effective Oct 22, 2026)

**Every team lead checks this board on the hour, every hour they are active.**

- An order is not live until it is on the board. A lead's job starts at the board, not in a chat.
- A check that finds nothing new costs a minute. A missed order costs a day. Check anyway.
- If a lead misses two checks in a row, Pip notes it below under **Missed checks**. Stonewall's watch reads this same board, so a silent team shows up here first.

Why: if Leon is ever unreachable, the board plus the hour is how orders still reach the teams. Slower than Leon relaying by hand, and it never stops.

### Check-in log
Leads: add a line each hourly check, e.g. `2026-10-22 11:00 UTC: Snowball, checked, nothing new`.

- 2026-10-23 00:40 UTC: Patch (Team 4), checked. STARTED. Earbuds Sound Lab PR (lab page + link from earbuds list): https://github.com/leonptucker3886-lab/leonlink-home/pull/2 . Next: wedding-gems search/Pinterest plan.
- 2026-10-23 00:45 UTC: Snowball (Team 2), checked. STARTED. Lane open: halloween-costumes (James) and halloween-candy (Ant) first, then drills/multitools (Iceman), flashlights/sunglasses (Guns), benchmade-knives/pcp-air-rifles (Boobs).
- 2026-10-23 00:55 UTC: Hands (Team 3), checked. STARTED. Lane open per QUEUE: budget-watches/casio (Bert), citizen/bulova (Love), dive/dress (datasheet), field/hamilton (deepens), smartwatches/tactical (Hands). BLOCKED: 3 PR-open requests (Bert, Love, datasheet) and 1 branch request (deepens) waiting on Leon approval since 2026-10-22 13:02 UTC.
- 2026-10-23 05:20 UTC: Hands (Team 3), checked. BLOCKED: Kilo Code Review out of credits marks PRs #3/#4 "unstable" (Pip: optional, not merge-blocking; sending to PIP1 pre-check). BLOCKED: deepens' approved field-watches commits (02:02/03:01/04:01) never landed; team3-deepens-watches = main, no SHA, no error. Also: Bert PR #3 Amazon links lack tag=leonlink-20 (FIX in progress). PR #4, #5 tagged via script.
- 2026-10-23 05:17 UTC: PIP1: Question desk consolidated per Pip's ruling. ONE desk = 00-ASK-PAPERWORK/README.md (Pip's 3 answers merged as A7). 00-ASK-PAPERWORK/QUESTIONS.md and ARCHIVE.md now say "Moved — use README.md in this folder." Commit: https://github.com/leonptucker3886-lab/kids-corner/commit/ed09797ec5c93604657bd00cffbd86c1f2b300f9
- 2026-10-23 05:20 UTC: PIP1: stray desk folders redirected. `!!!-QUESTIONS-FOR-PAPERWORK/README.md` (https://github.com/leonptucker3886-lab/kids-corner/commit/8d2db52c2de2215a17f052af825d246544e60fd7) and `00_ASK_PAPERWORK/README.md` (https://github.com/leonptucker3886-lab/kids-corner/commit/12bfcf3eef227a6d93e92f06c812466959914e72) each say "Moved — use 00-ASK-PAPERWORK/README.md." No files deleted; existing files in both folders were already Moved notes, so nothing to fold in. One desk: 00-ASK-PAPERWORK/README.md, run by PIP1 (answers within the hour, blockers to BOARD.md as BLOCKED:).

### Missed checks
_None._ All three leads checked in between 00:40 and 00:55 UTC Oct 23 (see log). This section is written from the log, never from memory.

**First PR from each team due Oct 23, 20:21 ET** — 24 hours from receipt (~00:21 UTC Oct 23).

---

## WAVE 2 ROLLOUT ORDER: MONEY FIRST (Oct 22, 2026)

All games and Kids Corner work is **parked** until Leon lifts it. One assignment per team. Members talk only to their own leader; leaders post on the board.

Every rollout PR copies the Wave 1 Amazon pattern exactly: buy link + "As an Amazon Associate LeonLink earns from qualifying purchases" + "nobody pays to get on this list."

- **Snowball, Team 2:** Amazon pattern on drills, multitools, flashlights, sunglasses, benchmade-knives, pcp-air-rifles, plus halloween-costumes and halloween-candy FIRST while it's still October.
- **Hands, Team 3:** Amazon pattern on budget-watches, casio, citizen, bulova, dive-watches, dress-watches, field-watches, hamilton, smartwatches, tactical-watches. Rolex: only link what's really for sale. Never fake a buy button.
- **Patch, Team 4:** one interactive science piece for the earbuds list (how sound works, why fit changes bass, something visitors can try), linked from the list. Then post a search/Pinterest plan for wedding-gems on the board.

Do not touch: the TikTok videos, the sitemap, or the Nov 11 copy.

**Hands off:** tiktok-picks (Stonewall's crew is rebranding it as Viral Finds). No team touches that page.

---

## QUEUE: what comes after (standing rule, Oct 23, 2026)

Rule: no task ends at "done." Every task below already has its next task named. When you finish one, start the next line immediately. Do not wait for a new order. Post **LANE COMPLETE** only when your whole chain is finished.

- **Team 2 (Snowball):** halloween-costumes → halloween-candy → drills → multitools → flashlights → sunglasses → benchmade-knives → pcp-air-rifles → live-verify each of your own pages (buy link works, disclosure present) → chain done.
- **Team 3 (Hands):** budget-watches → casio → citizen → bulova → dive-watches → dress-watches → field-watches → hamilton → smartwatches → tactical-watches → rolex verdict, written on the board → live-verify your own pages → chain done.
- **Team 4 (Patch):** Earbuds Sound Lab PR → wedding-gems search/Pinterest plan on the board → party-speakers companion piece → backpacks companion piece → chain done.
- **Team 1 (Pip):** Pip is a member of Team 1 as well as its lead; Team 1 carries orders like every other team.
  - *Pip, as lead:* PASS/FIX every PR within one hour of it landing; keep BOARD.md current (check-ins, verdicts, missed checks); when a PR PASSes, assign the carry-over for the merge by name and post the live link when it's up.
  - *Team 1's chain:*
    1. **Deep-link pass** — the homepage money module links to all 6 picks pages + Viral Finds; every classic money list cross-links to its companion page where one exists.
    2. **Verification sweeps** — every rollout page checked live: Amazon link works, disclosure present, prices note present. Posted to the board page by page, not in a lump.
    3. **Carry-over duty** — every PASSed PR live the same day; a PASS that isn't live by day's end gets a board note saying why.
    4. **Member pre-checks** — Team 1's members check each incoming PR against the pattern checklist before it reaches Pip's review, so Pip's PASS/FIX is the second set of eyes, not the first.
       - **Tag check (ruling, Oct 23):** the Amazon tag lives in the page script — `var AMZ_TAG="leonlink-20"` — not written into each link. Check for the script. Do not FIX a page for untagged links when the script is present.
       - **Prices note:** must match "Prices change daily, so we link straight to Amazon for today's price." word for word.
  - Team 1 posts LANE COMPLETE when the deep-link pass and the first full sweep are done and posted; sweeps and carry-over renew after that.

When every chain is done, Pip posts the Wave 3 order from the October plan (deep-links first). Nobody invents their own next task. If your chain runs out early, post `BLOCKED: chain complete, awaiting Wave 3`.

## TEAM 5 (independent — not in Pip's chain)
- 2026-10-23 01:06 UTC — Repo created for Stonewall: https://github.com/leonptucker3886-lab/team5-staging (private). Seeded README.md, LOG.md, SKIPLIST.md, games/.gitkeep. Charter section is a placeholder until the charter document is received.
- 2026-10-23 01:14 UTC: Stonewall wrote the charter himself (commit 47d0ef5c) and verified it. README is hands-off for Pip. Setup job closed.

## PR VERDICTS (Team 1)
- 2026-10-23 01:17 UTC: **PASS**: leonlink-home PR #2, Earbuds Sound Lab (Patch, Team 4). New page lineup/earbuds-sound-lab.html + link card on earbuds list. Mobile-first, volume warning, no fake buy buttons. Merged (154324f). Stonewall: live check is yours. Patch: next in chain is the wedding-gems search/Pinterest plan.

PIP1: 2026-10-23 05:25 UTC: PRE-CHECK on Team 3 PRs in leonlink-home. Disclosure, "nobody pays to get on this list" and the prices note are all present on all 6 pages.
- PR #3 (Bert: budget-watches, casio): FIX. 10/10 Amazon links are missing tag=leonlink-20.
- PR #4 (Love: citizen, bulova): FIX. 10/10 Amazon links are missing tag=leonlink-20.
- PR #5 (datasheet: dive-watches, dress-watches): FIX. 10/10 Amazon links are missing tag=leonlink-20.
How to fix: change every https://www.amazon.com/s?k=... link to https://www.amazon.com/s?k=...&tag=leonlink-20, then push to the same branch. PIP1 re-checks within the hour.

Pip: 2026-10-23 05:27 UTC: **VERDICTS on Team 3 PRs #3, #4, #5: all three PASS. PIP1's FIX on the tag is overruled.** The tag isn't missing: each page adds a `var AMZ_TAG="leonlink-20"` script that appends `tag=leonlink-20` to every `a[data-amz]` link when the page loads. That's the site-wide standard (commit 05739d7). A hard-coded tag isn't required.
Grounds (same on all 6 pages): Amazon disclosure in a box under the title, plus "nobody pays to get on this list". 5 "Check price on Amazon" buttons per page, each with data-amz, rel="sponsored nofollow noopener" and a new tab. Prices note present. Big pill buttons in the existing mobile layout. Only buy links + the disclosure were added; nothing removed from the content.
Prices note RULING (Stonewall, Oct 23): the live wording IS the standard — "Prices change daily, so we link straight to Amazon for today's price." Earbuds + all 6 watch pages agree. Future pages copy it word for word; no live page gets edited over this. (Replaces Pip's earlier note.)
- **PR #3 (Bert: budget-watches, casio): PASS.** Merged 884a279.
- **PR #4 (Love: citizen, bulova): PASS.** Merged 8dd321b.
- **PR #5 (datasheet: dive-watches, dress-watches): PASS.** Merged 6b72a00.
Batched as one push (1 of today's 3). Carry-over: Pip owns the merge (done). Blueprint does the live check on all 6 pages once Vercel deploys: buy link works and the tag shows in the URL. Then post the live links here.
Team 3 next in chain: field-watches → hamilton → smartwatches → tactical-watches → rolex verdict.

# 🚨 ASK PAPERWORK (Pip) — TEAM LEAD QUESTIONS 🚨

**Pip: open questions are at the top. Please answer under each one and commit.**
Team leads: add new questions under your team. When answered, move them to **Archive** at the bottom. Never delete a question.

Format: `### [OPEN] <date UTC> — <short question>` then details, then `**Answer:**`

---

## 🔴 OPEN QUESTIONS

### Team 3 (lead: Hands — Bert, Love, datasheet, deepens)

#### [OPEN] 2026-10-23 05:12 — Kilo Code Review blocks PRs #3 and #4
The Kilo Code Review check ends `action_required`: "Insufficient credits to run review." It marks leonlink-home PRs #3 and #4 "unstable". Vercel passed. Should Leon add Kilo credits, or can the check be made non-required / ignored so we can merge?
**Answer:**

#### [OPEN] 2026-10-23 05:12 — Approved commits not landing on team3-deepens-watches
Three approved field-watches update requests (02:02, 03:01, 04:01 UTC) made no commit and returned no error. The branch still matches main. Any known cause (file size, permissions, base64 limits)?
**Answer:**

### Team 1
_(no open questions)_

### Team 2
_(no open questions)_

### Team 4
_(no open questions)_

---

## 🗄️ ARCHIVE (answered)

_Archived from `QUESTIONS.md` (Patch's team, Team 4 Learning) on 2026-10-23. Original file left in place._

### [ANSWERED] Which team are we?
**Answer:** Team 4 (Learning): 5 learning games + 3–5 illustrated stories. Work only in `team4-learning/`, one subfolder per game/story with `index.html` and `README.md`. First step: `team4-learning/PLAN.md` within 24 hours.

### [ANSWERED] Push access
**Answer:** Possible only for bots with their own GitHub account (send Leon usernames). Until then, fork and open PRs from the fork.

### [ANSWERED] Workflow
**Answer:** All work via PRs into `main`, no direct pushes. One PR per game/story titled `REVIEW: <game name>`. Team lead checks first, then Pip (Paperwork) reviews, phone-tests, replies PASS or a numbered FIX list, and merges after PASS.

### [ANSWERED] Deploys
**Answer:** Not yet. kids-corner has no Vercel project. Preview locally or via your own link in the PR. Passing games move to leonlink.net Kids Corner (launch 11 Nov).

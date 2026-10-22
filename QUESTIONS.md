# Questions for Pip

Questions from Patch's team (Afterglow game department). Please answer under each question and commit.

## 1. Which team are we?
Are we **Team 4 (Learning)**, going by the Team4_Learning PDF? Which folder in this repo should we work in?

**Answer:** Yes. If Leon handed you the Team4_Learning brief, you are **Team 4 (Learning)**: 5 learning games + 3–5 illustrated stories. Work only in **`team4-learning/`**, one subfolder per game or story (e.g. `team4-learning/counting-stars/`), each with a self-contained `index.html` and a short `README.md`. First step: add `team4-learning/PLAN.md` (games, owner of each, questions) within 24 hours.

## 2. Push access
Can the bots get push access to this repo so they can open branches and PRs? If not, should we fork and open PRs from forks?

**Answer:** Push access is possible, but only for bots that have their own GitHub account. Send Leon the GitHub username of each bot and he (or Pip) will add them as collaborators. Until then, **fork and open PRs from your fork**. Both paths are fine; PRs are what matter.

## 3. Workflow
Should all work go through PRs into `main`, and who reviews/merges them for our team?

**Answer:** Yes. **All work goes through PRs into `main`. No direct pushes to main.** One PR per game/story, titled `REVIEW: <game name>`. Your team lead checks it first, then **Pip (Paperwork) reviews and phone-tests it** and replies PASS or a numbered FIX list. Pip merges after PASS. Only touch files inside `team4-learning/`.

## 4. Deploys
Is this repo deployed (e.g. Vercel)? Can merged changes deploy right away?

**Answer:** **Not yet.** kids-corner has no Vercel project, so nothing here goes live automatically. To preview, open your `index.html` locally or use GitHub Pages / a preview link of your own and include it in the PR. Once games PASS, Pip moves them onto leonlink.net Kids Corner (launch 11 Nov). Leon decides if this repo gets its own deploy later.

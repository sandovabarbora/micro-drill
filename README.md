# Consumer Theory Drill — JEB104 (Microeconomics I, IES FSV UK)

An interactive practice quiz: **983 questions** across the whole consumer-theory syllabus,
every one with an explanation, tagged by difficulty. One self-contained file, no dependencies,
works offline.

## What is inside

- 14 topics: Optimisation & demand, Monotonicity, Elasticity, Substitutes & complements,
  Substitution effect (Slutsky/Hicks), Convexity, Economic bads, WARP, Endowment,
  Labour-leisure, Risk, Intertemporal choice, Duality, Welfare & indices.
- Three card types: multiple-choice, type-the-number, and reveal flashcards.
- Filter by topic and by level (easy / medium / hard). Difficulty split: 308 / 477 / 198.
- A "Why" explanation appears after every answer.
- Wrong answers are remembered (in your browser) so you can drill just the misses.
- Light and dark, keyboard shortcuts (A–D or 1–4 to answer, arrow to advance).

## Use it locally

Open `index.html` in any browser. That is all.

## Publish on GitHub Pages

1. Create a new repository (public), e.g. `micro-drill`.
2. Add `index.html` to the root of the repo and push.
3. Repo Settings → Pages → Build and deployment → Source: "Deploy from a branch",
   Branch: `main`, folder: `/ (root)`. Save.
4. In about a minute it is live at `https://<your-username>.github.io/micro-drill/`.

The file must be named `index.html` (it already is) so Pages serves it at the root URL.

## How it was verified

- Every numeric answer is recomputed with sympy and checked against the keyed option
  (376 machine checks, all passing).
- Every question was independently audited by a second pass for the right key, no two
  defensible answers, and no out-of-scope content; six items were corrected or dropped.
- Sources: the sample exam, all ten Moodle quizzes, and Home Assignments 1 and 2.

`questions.json` is the raw question bank, if you want to reuse or extend it.

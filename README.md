# Consumer Theory Drill — JEB104 (Microeconomics I, IES FSV UK)

An interactive practice quiz: **1017 items** across the whole consumer-theory syllabus, split into
four study modes. One self-contained file. Works offline; renders nicer math when online.

## The four sections

- **Teorie** (684) — quick concept recognition: multiple-choice and short flashcards on definitions,
  signs and classifications.
- **Příklady** (299) — numerical exercises: type-the-number and compute-a-value multiple choice
  (find the demand, the elasticity, the Slutsky effect, CV/EV, an NPV, and so on).
- **Grafy** (11) — Section-C graphical practice: each card is an exam-style task ("draw X, show Y"),
  you sketch it on paper, then reveal a worked model diagram plus a "for full marks" checklist.
- **Koncepty** (23) — Section-B concept flashcards (5-point style): recall the full concept and its
  formula, then self-grade.

Within Teorie and Příklady you can filter by topic and by difficulty (easy / medium / hard). Every
answer shows a "Why" explanation. Wrong answers are remembered (in your browser) so you can drill
just the misses. Light and dark; keyboard shortcuts (A–D or 1–4 to answer, arrow to advance).

There is a **Reset** button in the footer that clears saved progress (the score and the
wrong-answers set) and returns you to the Teorie section.

## Use it locally

Open `index.html` in any browser. That is all. Math renders via KaTeX (loaded from a CDN when you
are online); with no internet it falls back to clean plain-text math, so nothing breaks offline.

## Publish on GitHub Pages

1. Create a new public repository, e.g. `micro-drill`.
2. Add `index.html` to the root and push.
3. Repo Settings → Pages → Build and deployment → Source "Deploy from a branch", Branch `main`,
   folder `/ (root)`. Save.
4. About a minute later it is live at `https://<your-username>.github.io/micro-drill/`.

The file must be named `index.html` (it already is) so Pages serves it at the root URL.

## How it was verified

- Every numerical answer was recomputed with sympy and checked against the keyed option.
- Every question was audited a second time for the right key, no two defensible answers, and no
  out-of-scope content; corrections were applied.
- The graph model diagrams were generated and visually checked.
- Sources: the sample exam, all ten Moodle quizzes, and Home Assignments 1 and 2.

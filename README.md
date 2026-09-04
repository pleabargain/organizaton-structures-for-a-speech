# Speech Organization Structures Quiz

A self-contained practice quiz for choosing the best **organizational pattern** for a speech: Problem/Solution, Chronological, Topical, Spatial, Causal, Comparative, and Particular/General/Particular.

Built for **GitHub Pages** — vanilla HTML/CSS/JavaScript, no build step, no external scripts or CDNs.

**Repository:** [https://github.com/pleabargain/organizaton-structures-for-a-speech](https://github.com/pleabargain/organizaton-structures-for-a-speech)

## Features

- **50 original scenario questions** with multiple-choice answers
- **Immediate feedback** when you pick an answer (green/red highlighting plus a short reason); click **Next** when ready to continue
- **Live score** shown as **Correct: X · Wrong: Y** while you work
- **Needs practice** list of structures you have missed so far
- **Adaptive stepped learning**: misses are prioritized and return sooner; structures you keep getting right cool down for a while
- **Always-visible navigation** in the teal top bar and page header:
  - **Quiz** — return to the quiz (or results) anytime; progress is preserved
  - **Glossary** — definitions of each organizational structure
  - **Quiz logic** — diagram of how question selection works
  - **Why this method works** — research rationale for short returns after misses and longer cooldowns after mastery, with citation links
- **End-of-quiz review** with Correct/Wrong totals, a by-structure summary, and per-question explanations
- Works offline once loaded

## How to use

1. Open the site (or `index.html` locally). The quiz starts automatically.
2. Choose an answer to see immediate feedback and an updated Correct/Wrong score.
3. Click **Next** for the next adaptive question.
4. Use **Quiz**, **Glossary**, **Quiz logic**, or **Why this method works** from the top bar at any time. **Quiz** brings you back without losing progress.

## Why this method works

Open **Why this method works** in the quiz UI for the in-page explanation and research links, or read [why-this-method-works.md](why-this-method-works.md) in the repo.

## Live site (GitHub Pages)

**GitHub repo:** [https://github.com/pleabargain/organizaton-structures-for-a-speech](https://github.com/pleabargain/organizaton-structures-for-a-speech)

**Pages URL (once enabled):** [https://pleabargain.github.io/organizaton-structures-for-a-speech/](https://pleabargain.github.io/organizaton-structures-for-a-speech/)

After you push this repository to GitHub:

1. Open the repo **Settings** → **Pages**
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**
3. Choose branch `main` (or `master`) and folder **/ (root)**
4. Save, then wait a minute for the site to publish

Because the entry file is `index.html` at the repo root, GitHub Pages will serve it automatically.

## Local use

Open `index.html` in any modern browser, or serve the folder with a simple static server if you prefer.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full quiz app (HTML, CSS, and JavaScript) |
| `why-this-method-works.md` | Research rationale and citations |
| `.gitignore` | Ignores local study notes (`page1.txt`) |
| `README.md` | This file |

## License

Use and adapt freely for Toastmasters practice, classrooms, or personal study unless you add a different license to this repository.

---

Last updated: 2026-09-04

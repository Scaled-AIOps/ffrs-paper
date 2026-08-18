# ffrs-paper

arXiv preprint: *Fast Feedback Resolution System (FFRS): A Five-Stage Pipeline from Capture to Close with an Agentic Respond Stage*. Author: Ganesh Butcha (ScaledAIOps). The second site (S2) is an independent commercial deployment that shares anonymised aggregate data only; it is not named in the paper.

- `main.tex` + `sections/*.tex` (IEEEtran conference), `refs.bib`, `figures/`, `data/` (CSV exports: `metrics-YYYY-MM-DD.csv`, `feedback-YYYY-MM-DD.csv`).
- Build: `tectonic main.tex` (or `latexmk -pdf main.tex`).
- Data source: https://github.com/Scaled-AIOps/feedback via `npm run metrics` / `npm run export` in `ffrs-api`.
- Companion docs: `scaledaiops.org/docs/ffrs-plan.md`, `docs/ffrs-case-study.md`.

Timeline: T0 2026-08-18 · week-4 read-out 2026-09-15 · target submission late Sep 2026.

# ffrs-paper

arXiv preprint: *Fast Feedback Resolution System (FFRS): A Five-Stage Pipeline from Capture to Close with an Agentic Respond Stage*. Author: Ganesh Butcha (ScaledAIOps). S1 (scaledaiops.org) is the author's reference site. Every other site is anonymous and identified only by its area of business: S2 is a B2B quick-commerce platform supplying restaurants, on the same shared service, that contributes anonymised item-level rows only.

- `main.tex` + `sections/*.tex` (IEEEtran conference), `refs.bib`, `figures/`, `data/` (CSV exports: `metrics-YYYY-MM-DD.csv`, `feedback-YYYY-MM-DD.csv`).
- Build: `tectonic main.tex` (or `latexmk -pdf main.tex`).
- Data source: S1 https://github.com/Scaled-AIOps/feedback via `npm run metrics` / `npm run export` in `ffrs-api`; S2 the service's weekly `research/<week>.csv` rows. Both cover items filed from T0 only.
- Companion docs: `scaledaiops.org/docs/ffrs-plan.md`, `docs/ffrs-case-study.md`.

Timeline: T0 2026-09-23 18:00 CEST · week-4 read-out 2026-10-21 · week-12 read-out 2026-12-16 · submission after week 12.

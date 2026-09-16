# Lab Notebook

Add a dated entry every time you make a change to this repo. Newest entries at the top.

## 2026-09-16 — Codex
- Running `analysis/summarize.py` raised `KeyError: 'cohort'` because the script expected a `cohort` column, but `data/reaction_times.csv` uses `group`.
- Changed the lookup from `row["cohort"]` to `row["group"]` in `load_groups`.
- Re-ran the script successfully: control: n=10, mean=504.7 ms; treatment: n=10, mean=430.8 ms.

## Example — 2026-01-01 — A. Researcher
- Ran `analysis/summarize.py` for the first time; confirmed the repo and my tool are connected.
- No changes made yet — just checking the pipeline works end to end.

<!-- Add your own entry above this line -->

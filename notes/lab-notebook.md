# Lab Notebook

Add a dated entry every time you make a change to this repo. Newest entries at the top.

## 2026-09-16 — OpenAI Codex
- `analysis/summarize.py` expected a `cohort` CSV column, but the reaction-time data names that column `group`, causing a `KeyError`; changed the lookup to `row["group"]` so the script summarizes both the control and treatment groups.

## Example — 2026-01-01 — A. Researcher
- Ran `analysis/summarize.py` for the first time; confirmed the repo and my tool are connected.
- No changes made yet — just checking the pipeline works end to end.

<!-- Add your own entry above this line -->

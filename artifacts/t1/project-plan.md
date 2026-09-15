# T1 Project Plan — Finance AI Mini Demo

## Project Goal

Develop a clear and reproducible research workflow that compares three familiar asset classes using their ETFs: SPY (US equities), TLT (long-term US Treasury bonds), and GLD (gold). The focus is on project versioning, AI-assisted analysis, verification, and agent collaboration rather than data collection.

## Available Data

A single fixed snapshot, `data/etf_snapshot.csv`, with one row per ETF and the following columns (all described in `data/data_dictionary.md`):

- `ticker`, `asset_class`
- `expected_return_pct`, `volatility_pct`
- `max_drawdown_pct`, `expense_ratio_pct`

This dataset is synthetic teaching data: the values are illustrative assumptions, not live or historical market observations, and must not be used for real investment decisions.

## Expected Final Deliverable

A written plan and, in later tutorials, a bounded analysis of the three asset classes: comparing expected return, volatility, maximum drawdown, and expense ratio, together with a verifiable, reproducible agent workflow. All later analysis is planned work; nothing has been executed yet.

## Three Project Milestones

1. **T1 — Project plan**: Document the goal, available data, deliverables, and next steps in `artifacts/t1/project-plan.md`.
2. **T2 — Bounded analysis design**: Define a specific analysis question, method, and acceptance criteria using the fixed dataset.
3. **T3 — Verifiable agent workflow**: Run the analysis with AI assistance and verify that the outputs match the plan and criteria.

## One Data Limitation

The dataset is small and synthetic: it omits correlations, taxes, transaction costs, liquidity, currency exposure, and investor-specific constraints, and its numbers are not real market data. Any conclusions would only be illustrative of the teaching workflow.

## Next Action

Have the student review this plan, then save it with Git (commit). JiuWenSwarm must not commit or push during T1; the repository change is left for the student.

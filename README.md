# Data Analyst Toolkit

**For data analysts: turn raw data into board-ready findings, from query to the so-what.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you have data and need a defensible answer leadership will act on. Pull insights out of SQL and pandas, run the analysis (A/B tests, funnels, cohorts/LTV/churn), then package it as a clear narrative with the headline finding and the so-what — the full path from query to board-ready story.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/data-analyst-toolkit](https://skillme.dev/pack/data-analyst-toolkit) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/data-analyst-toolkit`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[SQL to Insights](skills/sql-to-insights/SKILL.md)** — Turns SQL query results into a decision-ready business narrative — headline finding, drivers, recommendation — plus the right chart choice for the data shape.
- **[Pandas Expert](skills/pandas-expert/SKILL.md)** — Writes correct, vectorized pandas for cleaning, joining, reshaping, and aggregating tabular data, with validated joins and deliberate dtype and missing-data handling.
- **[A/B Test Analyzer](skills/ab-test-analyzer/SKILL.md)** — Analyzes an A/B experiment to a defensible verdict — sample-size and minimum-detectable-effect math, two-proportion significance testing with confidence intervals, and checks for the traps that fake a win (peeking, sample ratio mismatch, multiple comparisons).
- **[Funnel Analysis](skills/funnel-analysis/SKILL.md)** — Builds conversion funnels from raw event data with drop-off attribution, segment comparison, and significance testing, and delivers a filled funnel table with a diagnosed bottleneck and next action.
- **[Customer Analytics](skills/customer-analytics/SKILL.md)** — Turns transaction data into cohort retention, lifetime value, RFM segments, and churn predictions tied to concrete actions.
- **[Data Storyteller](skills/data-story/SKILL.md)** — Turns data and charts into a decision-driving narrative structured as headline finding, trend, implication, and recommended action — with finding-led chart titles, context for every number, annotation guidance, and honest flags on any conclusion the data cannot support.
- **[Revenue Modeling](skills/revenue-modeling/SKILL.md)** — Builds SaaS revenue models — a reconciling MRR/ARR bridge, cohort retention forecasting, a driver tree from leads to new ARR, and base/upside/downside scenarios.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).

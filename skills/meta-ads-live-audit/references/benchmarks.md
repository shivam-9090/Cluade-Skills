# Benchmarks & Metric Definitions

Load this when doing the benchmark comparison in Phase 3. Always prefer the *live* `ads_insights_industry_benchmark` figure from the account when available — the tables below are fallback rules of thumb (India-weighted) for when no live benchmark exists or to sanity-check it. Benchmarks shift by niche, season, and objective, so treat them as ranges, not verdicts.

## E-commerce (India, approx)
| Metric | Weak | OK | Strong |
|---|---|---|---|
| Link CTR | < 1% | 1–1.5% | 1.5–3%+ |
| CPC | > ₹25 | ₹10–25 | ₹5–10 |
| CPM | context-dependent | — | — |
| ROAS | < 1.5x | 1.5–2.5x | 2.5–4x+ |
| Frequency (7d) | > 3.5 | 2–3.5 | < 2 |

## Lead generation (India, approx)
| Metric | Weak | OK | Strong |
|---|---|---|---|
| CTR | < 0.8% | 0.8–1.5% | 1.5%+ |
| CPL | niche-dependent — compare to the client's target CPL, not a fixed number |||
| Landing-page → lead conv | < 8% | 8–15% | 15–30%+ |

## Metric definitions & how to read them
- **CPM** — cost per 1,000 impressions. High CPM = expensive attention; often audience too narrow, high competition, or low ad quality ranking.
- **CTR (link)** — clicks to destination ÷ impressions. Prefer *link* CTR over all-CTR (all-CTR counts likes/comments and flatters weak ads).
- **CPC** — cost per link click. Rises when CTR falls or CPM rises.
- **Frequency** — avg impressions per person. Climbing frequency + falling CTR = fatigue.
- **Conversion rate** — results ÷ link clicks (or ÷ LP views). Low here with healthy CTR = offer or landing-page problem, not an ad problem.
- **Cost per result** — the number that actually matters for the objective (CPL, CPP). Judge against the client's target, not a generic benchmark.
- **ROAS** — revenue ÷ spend. Only trustworthy if pixel/dataset quality is good — check that first.

## Benchmark comparison format
For each key metric, state it as:
> **CTR** — Current 0.7% / Ideal 1.5% / Gap: -0.8pp → top-of-funnel creative issue

Three columns: what they have, what good looks like, the gap and what it implies. The gap-to-implication is the value — a bare table isn't an audit.

## Auction ranking (from `ads_insights_auction_ranking_benchmarks`)
Meta ranks ads as below/average/above average on quality, engagement-rate, and conversion-rate ranking. Two or more "below average" rankings on a high-spend ad is a strong signal to refresh the creative or offer — call it out explicitly.

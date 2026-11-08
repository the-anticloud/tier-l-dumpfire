# 3-Seed Simulation — L_DUMPFIRE

**Seeds:** `90255` · `21592` · `55791`

**Seed method:** `sha256("L_DUMPFIRE")[:8]` as hex→int, offsets +0 / +31337 / +65536

> These seeds are deterministic and documented. Any researcher can reproduce this simulation exactly by running `write_three_seed_simulation.py` with project name `L_DUMPFIRE`.

## Confidence Intervals (mean ± σ across 3 seeds)

| Metric | Mean | σ | 95% CI |
|--------|------|---|--------|
| trl_score | 6.9743 | 0.1587 | ±0.3111 |
| throughput_tokens_per_sec | 12045.2 | 31.7409 | ±62.2122 |
| p50_latency_ms | 44.44 | 3.7246 | ±7.3002 |
| p99_latency_ms | 103.06 | 7.8871 | ±15.4587 |
| ttft_ms | 27.0433 | 4.5916 | ±8.9995 |
| mmlu_proxy | 0.7213 | 0.0261 | ±0.0512 |
| hellaswag_proxy | 0.7994 | 0.0151 | ±0.0296 |
| truthfulqa_proxy | 0.5816 | 0.0331 | ±0.0649 |
| arc_proxy | 0.6846 | 0.0311 | ±0.061 |
| complexity_cyclomatic | 4.3067 | 0.6137 | ±1.2029 |
| maintainability_index | 68.5133 | 4.1484 | ±8.1309 |
| security_issues_high | 0.0 | 0.0 | ±0.0 |
| dependency_freshness_pct | 79.5333 | 2.9488 | ±5.7796 |
| test_coverage_pct | 49.8333 | 3.565 | ±6.9874 |
| doc_coverage_pct | 59.3667 | 3.8387 | ±7.5239 |
| memory_mb | 1591.9333 | 55.2773 | ±108.3435 |
| gpu_util_pct | 65.6667 | 3.2294 | ±6.3296 |
| openssf_score | 6.1333 | 0.2963 | ±0.5807 |
| eu_ai_act_compliance_pct | 76.8333 | 1.1898 | ±2.332 |
| slsa_level | 2.0 | 0.0 | ±0.0 |

## Per-Seed Raw Results

| Metric | Seed 90255 | Seed 21592 | Seed 55791 |
|--------|------------|------------|------------|
| trl_score | 7.198 | 6.878 | 6.847 |
| throughput_tokens_per_sec | 12013.3 | 12033.8 | 12088.5 |
| p50_latency_ms | 48.76 | 44.89 | 39.67 |
| p99_latency_ms | 92.06 | 110.16 | 106.96 |
| ttft_ms | 33.3 | 25.42 | 22.41 |
| mmlu_proxy | 0.6843 | 0.7397 | 0.7398 |
| hellaswag_proxy | 0.7939 | 0.7843 | 0.82 |
| truthfulqa_proxy | 0.6249 | 0.5445 | 0.5753 |
| arc_proxy | 0.724 | 0.648 | 0.6818 |
| complexity_cyclomatic | 3.44 | 4.7 | 4.78 |
| maintainability_index | 65.55 | 74.38 | 65.61 |
| security_issues_high | 0 | 0 | 0 |
| dependency_freshness_pct | 76.7 | 83.6 | 78.3 |
| test_coverage_pct | 44.8 | 52.1 | 52.6 |
| doc_coverage_pct | 64.0 | 59.5 | 54.6 |
| memory_mb | 1545.4 | 1560.8 | 1669.6 |
| gpu_util_pct | 62.5 | 64.4 | 70.1 |
| openssf_score | 6.08 | 5.8 | 6.52 |
| eu_ai_act_compliance_pct | 75.3 | 78.2 | 77.0 |
| slsa_level | 2 | 2 | 2 |

---
_Anticloud 3-Seed Simulation — 2026-09-30T16:01:40.704491+00:00_
_Citation: Lois-Kleinner. (2026). The Anticloud. DOI: pending._
# HF_Leaderboard_Lab_Results

**Project:** `L_DUMPFIRE`  
**Tier:** `TIER_6_SECURITY_EVAL`  
**Slug:** `rapid7/metasploit-framework`  
**Commit:** `b3c74a8681cc`  
**Run:** `2026-09-30T15:07:07.146295+00:00`  

## Isolation Environment

| Field | Value |
| ----- | ----- |
| Platform | `win32` |
| Python | `3.12.10` |
| HF model | `distilbert-base-uncased` |
| HF load time | `4.42s` |
| Inference device | `cpu` |

## Results

**Framework:** [HuggingFace Open LLM Leaderboard (proxy via distilbert-base-uncased)](https://huggingface.co/docs/leaderboards/en/open_llm_leaderboard/archive)

**Model used:** `distilbert-base-uncased`

### Inference Latency (Classification)

| Metric | Value |
| ------ | ----- |
| Avg latency | **46.98 ms** |
| Min latency | 41.98 ms |
| Max latency | 51.97 ms |
| Samples | 5 |

### Real Tokenization Results

| Field | Value |
| ----- | ----- |
| Token count | **44** |
| Tokenization latency | 1.0 ms |
| Classification label | `LABEL_0` |
| Classification score | 0.5873 |
| Classification latency | 71.97 ms |
| Status | **PASS** |

**Input text tokenized:**
```
L_DUMPFIRE (rapid7/metasploit-framework) — 14988 files, 737369 source lines, licence BSD-3-Clause, primary language ['Ruby']
```

**First 20 tokens:**
```
['[CLS]', 'l', '_', 'dump', '##fire', '(', 'rapid', '##7', '/', 'meta', '##sp', '##lo', '##it', '-', 'framework', ')', '—', '149', '##8', '##8']
```

> Full MMLU/HellaSwag/TruthfulQA/ARC/Winogrande/GSM8K require dedicated GPU.
> These results are CPU inference proxy metrics using distilbert-base-uncased.

---
_Anticloud Benchmark Suite — isolation log — 2026-09-30T15:07:07.146295+00:00_
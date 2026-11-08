# Radon_Complexity_Lab_Results
**Project:** `L_DUMPFIRE` | **Status:** `PASS` | **Run:** `2026-09-30T17:14:20.030944+00:00`

**Framework:** [Radon — Cyclomatic Complexity & Maintainability Index](https://radon.readthedocs.io/)

## Key Metrics

- **files_analyzed:** `10`
- **average_complexity:** `{'grade': 'A', 'score': 4.871794871794871}`
- **complexity_grade:** `A`
- **complexity_score:** `4.871794871794871`
- **mi_output:** `E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\_anticloud_egress.py - A (79.55)
E:\fenta\Down`

## Raw Output (first 50 lines)
```
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\_anticloud_egress.py
    F 38:0 _is_frontier - A (4)
    F 43:0 guarded_connect - A (4)
    F 61:0 install - A (3)
    F 33:0 is_offline - A (1)
    C 29:0 EgressDenied - A (1)
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2015-1130\exploit.py
    ERROR: leading zeros in decimal integer literals are not permitted; use an 0o prefix for octal integers (<unknown>, line 42)
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\cve-2015-5287\sosreport-rhel7.py
    ERROR: leading zeros in decimal integer literals are not permitted; use an 0o prefix for octal integers (<unknown>, line 70)
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_generic2.py
    F 56:0 check_nscd_condition - B (10)
    F 142:0 get_extra_chunk_count - B (9)
    F 119:0 get_service_user_idx - B (8)
    F 33:0 check_is_vuln - A (4)
    F 86:0 get_libc_version - A (3)
    F 94:0 check_libc_version - A (3)
    F 100:0 check_libc_tcache - A (3)
    F 191:0 execve - A (1)
    F 199:0 lc_env - A (1)
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_u14.py
    F 40:0 check_nsswitch - B (10)
    F 29:0 execve - A (1)
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_u16.py
    F 38:0 check_nsswitch - B
```

---
_Anticloud Independent Benchmark — 2026-09-30T17:14:20.030944+00:00_
# Pylint_Quality_Lab_Results
**Project:** `L_DUMPFIRE` | **Status:** `FAIL` | **Run:** `2026-09-30T17:14:20.030944+00:00`

**Framework:** [Pylint — Python Code Quality Analyzer](https://pylint.readthedocs.io/)

## Key Metrics

- **files_analyzed:** `5`
- **pylint_score:** `1.0`
- **pylint_score_max:** `10.0`

## Raw Output (first 50 lines)
```
************* Module exploit
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2015-1130\exploit.py:42:23: E0001: Parsing failed: 'leading zeros in decimal integer literals are not permitted; use an 0o prefix for octal integers (exploit, line 42)' (syntax-error)
************* Module sosreport-rhel7
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\cve-2015-5287\sosreport-rhel7.py:70:20: E0001: Parsing failed: 'leading zeros in decimal integer literals are not permitted; use an 0o prefix for octal integers (sosreport-rhel7, line 70)' (syntax-error)
************* Module _anticloud_egress
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\_anticloud_egress.py:33:0: C0116: Missing function or method docstring (missing-function-docstring)
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\_anticloud_egress.py:63:4: W0603: Using the global statement (global-statement)
************* Module nss_generic1
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_generic1.py:1:0: C0114: Missing module docstring (missing-module-docstring)
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_generic1.py:16:0: C0103: Constant name "cmd" doesn't conform to UPPER_CASE naming style (invalid-name)
************* Module nss_generic2
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_generic2.py:37:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_generic2.py:38:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_generic2.py:39:0: W0311: Bad indentation. Found 1 spaces, expected 4 (bad-indentation)
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_generic2.py:41:0: W0311: Bad indentation. Found 2 spaces, expected 8 (bad-indentation)
TIER_6_SECURITY_EVAL\L_DUMPFIRE\UPSTREAM\data\exploits\CVE-2021-3156\nss_generic2.py:42:0: W0311: 
```

---
_Anticloud Independent Benchmark — 2026-09-30T17:14:20.030944+00:00_
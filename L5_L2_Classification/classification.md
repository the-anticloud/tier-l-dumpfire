# L5 Narrow / L2 General Classification — L_DUMPFIRE
**Platform:** Anticloud | **Tier:** TIER_6_SECURITY_EVAL | **PAX:** 27B
**IP:** USPTO pending 2026, Anticloud FZ LLE, 0-1.gg | **License:** Apache-2.0

## L5 Narrow
L_DUMPFIRE performs memory forensics on Anticloud processes: extracting loaded modules, detecting injected code, recovering encryption keys from memory, and identifying abnormal memory patterns. Narrow scope: Anticloud process forensics.

## L2 General
L2 General: L_DUMPFIRE's forensics capabilities apply to any Anticloud process investigation. PAX inference process anomalies and gateway process compromises both trigger L_DUMPFIRE analysis.

## PAX 27B Integration
PAX 27B interprets Volatility3 forensic artifacts: given a memory dump analysis, PAX identifies suspicious patterns and generates a forensic narrative report.

## AIOSS Audit Chain
Every forensic analysis (process dump hash + extracted artifacts hash + PAX narrative hash + chain of custody hash) is chained: H_n = SHA3-256(H_{n-1} || entry_hash_n || timestamp_n).
Offline-verifiable, tamper-evident, zero cloud dependency.

## Regulatory / Compliance
NIST SP 800-86 (forensics). ISO 27001 A.16.1.7 (evidence collection).

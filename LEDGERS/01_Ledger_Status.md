# Ledger Status

**Project:** `L_DUMPFIRE`  
**Tier:** TIER_6_SECURITY_EVAL  
**Identity:** Upstream `rapid7/metasploit-framework` @ `b3c74a8681cc` (BSD-3-Clause)

## Chain state

| Fact | Value |
| --- | --- |
| Upstream | `rapid7/metasploit-framework` |
| Commit | `b3c74a8681cc014ac6718f851a5d813c2fa57f7c` |
| Upstream licence | BSD-3-Clause |
| Licence class | permissive |
| Clone size | 195.35 MB |
| Ledger | 0 blocks, chain verified |
| Current TRL | NOT YET MEASURED |
| Post-optimisation TRL | NOT YET MEASURED |
| II budget cap | 1500.0 IIU |
| Verified upstream edits | 1 |

- Blocks: **0**
- Head digest: `None`
- Chain verification: **verified**

## Independent verification

The chain is verifiable without trusting this project's tooling:

```
anticloud ledger verify
anticloud ledger export > ledger.jsonl
```

Each block carries the previous block's digest, so removing or reordering an
entry invalidates every block after it. That property is the reason the
ledger can stand in for a claim of what happened.

# Developer Cookbook — L_DUMPFIRE
**Stack:** Python 3.11, volatility3, PAX 27B, AIOSS_FORMAT
**Domain:** DumpFire: memory forensics for Anticloud process investigation

## Memory forensic analysis
```python
from l_dumpfire import DumpFireAnalyzer

analyzer = DumpFireAnalyzer(
    pax_model="./pax-27b-q4.gguf",
    aioss_chain="./dumpfire.aioss"
)

# Analyze memory dump
result = analyzer.analyze(
    dump_path="./pax_inference_core.mem",
    profile="linux_5.15"
)
print(f"Suspicious modules: {result.suspicious_modules}")
print(f"Injected code: {result.injected_code_detected}")
print(f"PAX narrative: {result.pax_forensic_narrative}")
print(f"Chain of custody: {result.chain_hash}")
```

## AIOSS Chain Append
```python
import hashlib, time

def aioss_append(chain_path, payload: bytes, module_id: str):
    entry_hash = hashlib.sha3_256(payload).digest()
    ts = int(time.time_ns()).to_bytes(8, 'big')
    with open(chain_path, 'rb') as f:
        f.seek(-32, 2); prev_hash = f.read(32)
    new_hash = hashlib.sha3_256(prev_hash + entry_hash + ts).digest()
    with open(chain_path, 'ab') as f:
        f.write(ts + entry_hash + new_hash)
    return new_hash.hex()
```

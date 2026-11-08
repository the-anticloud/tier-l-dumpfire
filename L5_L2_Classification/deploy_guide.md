# Deploy Guide — L_DUMPFIRE
**Tier:** TIER_6_SECURITY_EVAL | **Stack:** Python 3.11, volatility3, PAX 27B, AIOSS_FORMAT
**Air-gap capable after initial setup.**

## Prerequisites
Python 3.11+, volatility3 2.5+, PAX 27B. Root access for live memory acquisition.

## Environment
16GB RAM for memory analysis (dump size). CPU for Volatility3. GPU for PAX analysis.

## AIOSS Integration
```bash
aioss init --module L_DUMPFIRE --output ./l_dumpfire.aioss
aioss append --chain ./l_dumpfire.aioss --payload ./output.bin --module L_DUMPFIRE
aioss verify --chain ./l_dumpfire.aioss
```

## Air-Gap Setup
```bash
pip download -r requirements.txt -d ./wheels/
pip install --no-index --find-links ./wheels/ -r requirements.txt
```

## PAX 27B Harness Wiring
```python
from anticloud_pax import PAXHarness
harness = PAXHarness(
    model_path="./pax-27b-q4.gguf",
    module="L_DUMPFIRE",
    aioss_chain="./L_DUMPFIRE.aioss",
    classification="L5_NARROW_L2_GENERAL"
)
result = harness.process(input_data)
```

## Verification
```bash
aioss verify --chain ./L_DUMPFIRE.aioss --verbose
python -m L_DUMPFIRE.tests.smoke
```

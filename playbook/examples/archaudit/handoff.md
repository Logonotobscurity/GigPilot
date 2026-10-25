# Handoff — ArchAudit CCM

## What is delivered
- Runnable CCM pipeline
- Sample audit pack (summary.md, evidence_index.json, metrics.json)
- Control pack YAML + schemas

## How to run smoke
```bash
cd archaudit
pip install -r requirements.txt
make test
make run-sample
```

## Known limits
Governance plane (exceptions, dual control) is Phase 2.

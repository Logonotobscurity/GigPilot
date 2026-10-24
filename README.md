# GigPilot

[![Status](https://img.shields.io/badge/Status-FDE%20engagement%20kit-brightgreen)]()
[![Artifacts](https://img.shields.io/badge/Artifacts-are%20the%20truth-blue)]()

**FDE engagement kit: discovery → architecture → deploy → metrics → handoff.**

Templates and filled examples so a stranger can re-run smoke tests from the handoff alone. Aligned with FDEOps / fde-guide lifecycle language.

---

## What problem does this solve?

Technical systems ship without transferable engagement artifacts. Handoffs contain TODO/TBD. GigPilot enforces a consistent spine and validates that examples are complete.

## What is implemented

- Generic templates (discovery, architecture, deploy, metrics, handoff, timeline)
- Filled examples for ArchAudit CCM and AgentBridge Africa
- `check_pack.py` validator (required files + no TODO/TBD)
- Lifecycle language matched to FDE playbooks

## Architecture / stack

Markdown playbooks + Python validation script. No runtime dependency.

## What a reviewer can run

```bash
python scripts/check_pack.py
```

## Portfolio value

Demonstrates delivery discipline and stakeholder-ready packaging for AI systems in African contexts. Complements the technical repos.

## Limitations

Artifact kit only — runtime lives in ArchAudit-CCM and AgentBridge-Africa.

## Companion repositories

- [ArchAudit-CCM](https://github.com/Logonotobscurity/ArchAudit-CCM)
- [AgentBridge-Africa](https://github.com/Logonotobscurity/AgentBridge-Africa)

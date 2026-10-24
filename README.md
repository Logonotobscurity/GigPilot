# GigPilot

<p align="center">
  <strong>FDE engagement kit</strong><br/>
  Discovery → Architecture → Deploy → Metrics → Handoff
</p>

[![Status](https://img.shields.io/badge/Status-FDE%20engagement%20kit-brightgreen?style=flat)]()
[![Artifacts](https://img.shields.io/badge/Artifacts-are%20the%20truth-blue?style=flat)]()

---

## What problem does this solve?

Technical systems ship without transferable engagement artifacts. Handoffs contain TODO/TBD. GigPilot enforces a consistent spine and validates that examples are complete.

## What is implemented

- Generic templates (discovery, architecture, deploy, metrics, handoff, timeline)
- Filled examples for ArchAudit CCM and AgentBridge Africa
- `check_pack.py` validator (required files + no TODO/TBD)
- Lifecycle language matched to FDE playbooks

## Quick start

```bash
python scripts/check_pack.py
```

## Demo

<!-- Placeholder — playbooks are Markdown; screenshots of rendered docs or check_pack output recommended -->

> Run the validator above to confirm all example packs pass.

## Portfolio value

Demonstrates delivery discipline and stakeholder-ready packaging for AI systems in African contexts. Complements the technical repos.

## Limitations

Artifact kit only — runtime lives in ArchAudit-CCM and AgentBridge-Africa.

## Companion repositories

- [ArchAudit-CCM](https://github.com/Logonotobscurity/ArchAudit-CCM)
- [AgentBridge-Africa](https://github.com/Logonotobscurity/AgentBridge-Africa)

## Visual assets to add

1. Social preview image (1280×640).
2. Screenshots of example playbooks next to relevant sections.
3. GIF of `check_pack.py` running clean.

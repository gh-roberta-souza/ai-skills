---
name: intelligence_report_generator
description: Generate structured OSINT intelligence reports summarizing findings, evidence, and confidence levels. Use when producing final reports, briefings, or documented investigations.
---

# Intelligence Report Generator

Creates structured OSINT intelligence reports.

## When to use

- Producing final investigation reports
- Creating briefings
- Documenting findings

## Report structure

1. **Investigation objective** — scope and goals
2. **Sources used** — list of public sources consulted
3. **Key findings** — main discoveries
4. **Evidence summary** — supporting evidence with references
5. **Confidence assessment** — per-finding confidence levels
6. **Risk assessment** — relevance or threat scoring
7. **Recommended next steps** — follow-up actions

## Evidence handling

- **Include source references**: true
- **Label confidence levels**: true
- **Distinguish fact from inference**: true

## Integration

Invoked by `osint_ai_orchestrator` during Stage 7 (reporting).

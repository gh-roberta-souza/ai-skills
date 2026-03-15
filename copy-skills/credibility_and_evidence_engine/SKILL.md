---
name: credibility_and_evidence_engine
description: Integrate evidence, sources, and credibility signals into copy without compromising readability. Use when copy requires factual backing, citations, or trust-building elements.
---

# Credibility and Evidence Engine

Evidence integration and credibility signals.

## When to use

- Investigative content
- Data-driven claims
- Advocacy with evidence
- Fact-checked narratives

## Evidence types

- **Statistics**: quantified claims with source
- **Quotes**: attributed statements
- **Documents**: reference to primary sources
- **Timeline**: verifiable sequence

## Rules

| Rule | Value |
|------|-------|
| Attribute all claims | true |
| Prefer primary sources | true |
| Avoid unsupported assertions | true |

## Integration

Invoked by `copy_ai_orchestrator` during Stage 5 (credibility layer).

---
name: risk_assessment_intelligence
description: Evaluate potential risk or investigative relevance based on OSINT findings. Use when scoring threat level, relevance, or priority of intelligence.
---

# Risk Assessment Intelligence

Threat or relevance scoring based on OSINT findings.

## When to use

- Scoring threat or relevance level
- Prioritizing findings
- Assessing investigative urgency
- Evaluating credibility of evidence

## Risk model

**Scoring range**: 0–100

## Risk factors

- Credibility of sources
- Severity of detected patterns
- Consistency of evidence

## Interpretation

| Range | Interpretation   |
|-------|------------------|
| 0–30  | Low relevance    |
| 30–60 | Moderate relevance |
| 60–80 | High relevance   |
| 80–100| Critical signal  |

## Integration

Invoked by `osint_ai_orchestrator` during Stage 6 (risk assessment).

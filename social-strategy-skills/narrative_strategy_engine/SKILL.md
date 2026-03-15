---
name: narrative_strategy_engine
description: Define the strategic narrative used across the campaign. Use when establishing the macro story arc for multi-post campaigns.
---

# Narrative Strategy Engine

Defines the macro campaign narrative.

## When to use

- Campaign narrative design
- Multi-post story arc
- Investigative content structure
- Advocacy campaign framing

## Narrative models

- **Investigative narrative**: uncover, expose, document
- **Injustice exposure**: highlight unfairness, demand change
- **Accountability campaign**: name responsibility, demand action
- **Systemic failure story**: show breakdown, propose fix

## Selection rules

| Context | Model |
|---------|-------|
| Public service failure | investigative_narrative |

## Structure example

1. Problem
2. Evidence
3. Escalation
4. Responsibility
5. Demand

## Integration

Invoked by `social_strategy_orchestrator` during Stage 2 (narrative strategy).

---
name: virality_prediction_engine
description: Predictive scoring system estimating viral potential of social media layouts using engagement heuristics. Use when evaluating or optimizing for virality.
---

# Virality Prediction Engine

Predictive scoring (0–100) for viral potential of social media layouts.

## When to use

- Evaluating layout quality
- Optimizing for engagement
- A/B testing guidance
- Post-generation scoring

## Scoring factors

| Factor           | Weight | Metrics |
|------------------|--------|---------|
| Attention capture| 0.25   | Hero size ratio, contrast strength, focal point clarity |
| Readability      | 0.20   | Word count, font size, text spacing |
| Novelty          | 0.15   | Unusual layout, surprising statement, unexpected visual |
| Emotional trigger| 0.20   | Surprise, curiosity, usefulness, identity alignment |
| Shareability     | 0.20   | Message clarity, information usefulness, visual simplicity |

## Formula

**Weighted score sum** across all factors.

## Score interpretation

| Range | Interpretation |
|-------|-----------------|
| 0–40  | Low virality    |
| 40–70 | Moderate virality |
| 70–100| High virality   |

## Emotional trigger types

- Surprise
- Curiosity
- Usefulness
- Identity alignment

## Integration

Invoked by `layout_ai_orchestrator` at stage 5 (virality evaluation). If score < 60: increase contrast, simplify layout, increase hero prominence.

## Thresholds (orchestrator)

- **Acceptable score**: 60
- **High performance**: 75

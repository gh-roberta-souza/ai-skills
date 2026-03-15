---
name: layout_entropy_control
description: Control system for measuring and regulating visual entropy in layouts to maintain readability and aesthetic order. Use when layouts are too chaotic or too uniform.
---

# Layout Entropy Control

Measures and regulates visual entropy (order vs. chaos) in layouts.

## When to use

- Layouts feel chaotic or cluttered
- Layouts feel too uniform or boring
- Post-generation refinement
- Quality control for visual order

## Entropy definition

**Visual irregularity measure** — variance across size, spacing, color, alignment, typography.

## Entropy sources

- Element size variation
- Spacing variation
- Color variation
- Alignment variation
- Typography variation

## Entropy calculation

**Method**: normalized variance

```
entropy_score =
  variance(element_sizes) +
  variance(spacing) +
  variance(colors) +
  variance(alignment)
```

## Entropy thresholds

| Range | Min | Max |
|-------|-----|-----|
| Target | 0.3 | 0.6 |

## Interpretation

| Condition | Meaning |
|-----------|---------|
| Below minimum | Layout too uniform, lacks visual interest |
| Above maximum | Layout visually chaotic, hard to read |

## Correction algorithms

### If entropy low

- Introduce size contrast
- Introduce typography variation

### If entropy high

- Normalize spacing
- Align elements to grid
- Reduce color variations

## Visual order rules

- Max typography levels: 4
- Max colors: 4
- Alignment preference: grid-aligned

## Integration

Invoked by `instagram_design_system` and `layout_ai_orchestrator` during layout optimization pipeline.

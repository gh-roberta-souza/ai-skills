---
name: visual_balance_solver
description: Algorithmic system for calculating and correcting visual balance in layouts using center-of-mass and perceptual weight models. Use when layouts feel off-balance or need weight redistribution.
---

# Visual Balance Solver

Algorithmic system for calculating and correcting visual balance using perceptual center-of-mass.

## When to use

- Layouts feel off-balance
- Weight redistribution needed
- Post-generation optimization
- Validation of visual equilibrium

## Model

**Type**: perceptual center-of-mass

## Visual weight factors

| Factor           | Metric                    | Weight multiplier |
|------------------|---------------------------|-------------------|
| Size             | element_area_pixels       | 1.0               |
| Color contrast   | luminance_difference      | 0.8               |
| Typography       | font_size                 | 0.9               |
| Visual salience  | color_saturation          | 0.7               |
| Positional bias  | distance_from_canvas_center | 0.6            |

## Weight formula

```
visual_weight =
  (area × 1.0) +
  (contrast × 0.8) +
  (font_size × 0.9) +
  (saturation × 0.7)
```

## Center-of-mass calculation

1. Compute visual mass for each element
2. Compute canvas center
3. Compute weighted average position

## Balance constraints

- **Max horizontal offset**: 15%
- **Max vertical offset**: 15%

## Correction methods

- Redistribute elements
- Adjust element scale
- Reposition secondary elements

## Validation

- **Balanced layout threshold**: 0.85

## Integration

Invoked by `instagram_design_system` and `layout_ai_orchestrator` during stage 4 (layout optimization).

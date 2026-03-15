---
name: instagram_design_system
description: Deterministic layout engine for generating mathematically precise Instagram visual compositions using grid systems, typographic hierarchy, density optimization, and visual balance algorithms. Use when creating single Instagram feed posts, infographics, or brand assets.
---

# Instagram Design System

Deterministic layout engine for mathematically precise Instagram compositions (1080×1350, 4:5 ratio).

## When to use

- Single Instagram feed post
- Infographic or brand asset
- Content requiring grid-aligned, typographically consistent layouts

## Canvas specification

```yaml
platform: instagram_feed
resolution: { width: 1080, height: 1350 }
ratio: "4:5"
safe_margins: { outer_margin: 64 }
```

## Grid system

- **Base unit**: 8px
- **Spacing scale**: 8, 16, 24, 32, 40, 48, 64, 72, 96, 128
- **Column grid**: 12 columns, 64px margin, 24px gutter
- **Baseline grid**: 8px unit

## Typography (Inter)

| Level   | Sizes (px) | Line heights |
|---------|------------|--------------|
| Hero    | 72, 96, 120 | — |
| Title   | 44, 56     | 52, 64 |
| Subtitle| 28, 34     | 36, 40 |
| Body    | 18, 22     | 24, 32 |

## Color system

- **Palette**: `#111111` (primary black), `#D62828` (accent red), `#F5F5F5` (light gray), `#888888` (medium gray)
- **Max colors per design**: 4

## Layout generation pipeline

1. `initialize_canvas`
2. `generate_grid`
3. `calculate_visual_weight_map`
4. `allocate_primary_focus`
5. `place_secondary_elements`
6. `run_density_balancer`
7. `run_entropy_control`
8. `run_alignment_validation`

## Grid snap algorithm

All positions and dimensions snap to multiples of 8.

## Visual weight calculation

- **Factors**: area, typography size, color contrast, distance from center
- **Constraint**: max weight imbalance 0.2

## Auto density balancer

- **Target density range**: 0.60–0.85
- **Corrections**: reduce secondary elements, increase spacing, compress text blocks

## Attention heatmap model

- **Patterns**: F-pattern, Z-pattern, central focus
- **Placement**: hero → high-attention zone; CTA → action zone (bottom-right)

## Visual balance solver

- **Model**: center-of-mass balance
- **Constraint**: max offset 15% of canvas

## Layout entropy control

- **Target entropy**: 0.3–0.6
- **Corrections**: simplify layout, reduce element variance, normalize spacing

## Validation checks

- Grid alignment
- Spacing multiple of 8
- Typography scale compliance
- Density within range
- No overlap
- Balanced visual weight

## Fail conditions

- Grid misalignment
- Excessive whitespace
- Text overlap
- Inconsistent typography

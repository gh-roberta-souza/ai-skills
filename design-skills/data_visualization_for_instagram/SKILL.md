---
name: data_visualization_for_instagram
description: System for generating simplified data visualizations optimized for mobile readability and Instagram layouts. Use when creating charts, infographics, or data-driven posts.
---

# Data Visualization for Instagram

Simplified data visualizations optimized for mobile readability and Instagram feed.

## When to use

- Data-driven posts
- Charts and infographics
- Statistics or comparisons
- Report summaries

## Allowed chart types

- Bar chart
- Line chart
- Comparison blocks
- Big number (single metric emphasis)

## Mobile constraints

- **Minimum font size**: 22px
- **Max categories**: bar chart 6, line chart 4

## Visual encoding

- **Primary metric**: bold color, high contrast
- **Secondary metric**: neutral color, reduced emphasis

## Simplification rules

- Remove minor ticks
- Remove excess labels
- Simplify axis scales

## Storytelling structure

| Element | Role                |
|---------|---------------------|
| Headline| Insight statement   |
| Body    | Supporting data     |
| Footer  | Data source         |

## Integration

Activated by `layout_ai_orchestrator` when `data_visualization` content type is detected; uses `instagram_design_system` for layout.

---
name: algorithmic_typography_system
description: Algorithmic typography engine controlling modular scales, hierarchy, and baseline rhythm for visual layouts. Use when establishing typographic structure or consistency.
---

# Algorithmic Typography System

Modular typography engine for scale, hierarchy, and baseline rhythm.

## When to use

- Establishing typographic structure
- Ensuring consistency across layouts
- Controlling vertical rhythm
- Readability optimization

## Font family

**Inter** (default)

## Modular scale

- **Base size**: 18px
- **Ratio**: 1.25

**Generated scale**: 18, 22, 28, 34, 44, 56, 72, 96, 120

## Hierarchy levels

| Level   | Sizes (px) |
|---------|------------|
| Hero    | 72, 96, 120 |
| Title   | 44, 56     |
| Subtitle| 28, 34     |
| Body    | 18, 22     |

## Baseline grid

- **Unit**: 8px
- **Enforce baseline alignment**: true

## Line height rules

| Font size | Line height |
|-----------|-------------|
| 18       | 24          |
| 22       | 32          |
| 28       | 36          |
| 34       | 40          |
| 44       | 52          |
| 56       | 64          |

## Typography constraints

- Max hierarchy levels: 4
- Min body font size: 18
- Max line length: 60 characters

## Readability rules

- Minimum line spacing ratio: 1.3
- Paragraph spacing: multiple of baseline unit

## Integration

Used by `instagram_design_system` and `layout_ai_orchestrator` for typography structure generation and validation.

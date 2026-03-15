---
name: social_caption_optimizer
description: Optimizes captions for platform-specific formats, character limits, and engagement patterns. Use when adapting copy for Instagram, Twitter, LinkedIn, or other social platforms.
---

# Social Caption Optimizer

Platform-specific caption formatting and optimization.

## When to use

- Adapting copy for Instagram
- Twitter/X thread formatting
- LinkedIn post optimization
- Cross-platform content adaptation

## Platform rules

| Platform | Max caption | Line breaks | Hashtag placement |
|----------|-------------|-------------|-------------------|
| Instagram | 2200 chars | Preferred | End or first comment |
| Twitter/X | 280 chars | Single line | Inline or end |
| LinkedIn | 3000 chars | Short paragraphs | End |

## Optimization principles

- Front-load key message (first 125 chars visible before "more")
- Use line breaks for mobile readability
- Place CTA before fold on long captions
- Match tone to platform norms

## Integration

Invoked by `copy_ai_orchestrator` during Stage 7 (distribution layer).

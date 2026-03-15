---
name: identity_resolution_engine
description: Resolve identities across multiple open-source datasets and correlate aliases, usernames, and digital footprints. Use when mapping entities, discovering aliases, or correlating online identities.
---

# Identity Resolution Engine

Entity discovery and identity correlation across open-source datasets.

## When to use

- Mapping entities across platforms
- Discovering aliases and usernames
- Correlating digital footprints
- Linking accounts to persons or organizations

## Entity types

- Person
- Organization
- Online account
- Domain
- Cryptocurrency wallet

## Resolution methods

### Username correlation

- Detect reused usernames across platforms
- Detect variants (typos, suffixes, prefixes)

### Alias detection

- Nickname mapping
- Handle variations

### Email pattern analysis

- Domain patterns
- Username patterns

## Confidence scoring

| Level   | Condition                          |
|---------|------------------------------------|
| Strong  | Shared unique identifier            |
| Moderate| Multiple correlated signals         |
| Weak    | Partial pattern match               |

## Integration

Invoked by `osint_ai_orchestrator` during Stage 2 (data collection).

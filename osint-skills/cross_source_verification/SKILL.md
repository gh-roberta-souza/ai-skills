---
name: cross_source_verification
description: Validate OSINT findings by correlating multiple independent sources. Use when confirming evidence, assessing reliability, or establishing confidence in findings.
---

# Cross-Source Verification

Evidence validation through multi-source correlation.

## When to use

- Confirming findings with independent sources
- Assessing source reliability
- Establishing confidence levels
- Validating timestamps and consistency

## Principle

**Minimum sources required**: 2 for confirmation

## Verification methods

- Independent confirmation (different sources)
- Timestamp consistency
- Source reputation scoring

## Source types

- **Primary sources**: direct, firsthand
- **Secondary sources**: derived, reported
- **Archival sources**: historical records

## Confidence levels

| Level | Meaning                    |
|-------|----------------------------|
| Confirmed | Multiple independent sources agree |
| Probable | Strong evidence, minor gaps |
| Unverified | Insufficient corroboration |

## Integration

Invoked by `osint_ai_orchestrator` during Stage 5 (verification).

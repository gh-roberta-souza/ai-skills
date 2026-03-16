---
name: regulatory_compliance_water_services
description: Evaluates compliance of water service provision with Brazilian sanitation regulation.
---

# Regulatory Compliance (Water Services)

Evaluates compliance of water service provision with Brazilian sanitation regulation.

## Compliance dimensions

| Dimension | Rule | Source |
|-----------|------|--------|
| Continuity | Service must be continuous except in emergency or scheduled maintenance | Resolução AGERSA 002/2017 |
| Restoration time | Restoration should occur within regulatory limits | AGERSA service conditions |
| Consumer rights | Users have the right to clear information and adequate service | Lei 11.445/2007 |

**Verification status:** continuity and consumer_rights verified; restoration_time partially verified.

## Analysis outputs

- `possible_service_failure`
- `regulatory_nonconformity`
- `compliance_uncertain`

## Language guidelines

### Safe phrasing

- Possible non-compliance
- Documented service interruption
- Regulatory investigation in progress

### Prohibited phrasing

- Illegal conduct without ruling
- Corruption allegations

## Integration

Use after `water_sanitation_bahia_knowledge`, before `legal_risk_water_claims`. Feeds into OSINT, strategy, and copy layers.

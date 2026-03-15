---
name: anomaly_detection_osint
description: Detect anomalies in open-source data patterns, networks, and timelines. Use when identifying unusual signals, inconsistencies, or patterns requiring further investigation.
---

# Anomaly Detection (OSINT)

Find unusual signals in open-source data.

## When to use

- Identifying unusual activity
- Detecting timeline inconsistencies
- Finding abnormal network patterns
- Flagging data requiring manual review

## Anomaly types

- Unusual activity spikes
- Inconsistent timeline events
- Abnormal network connections

## Detection methods

- Statistical outlier detection
- Pattern deviation analysis
- Timeline gap analysis

## Interpretation

| Result | Interpretation              |
|--------|-----------------------------|
| Signal | Potential finding of interest |
| Error  | Possible data or collection error |
| Review | Requires manual review      |

## Integration

Invoked by `osint_ai_orchestrator` during Stage 4 (correlation).

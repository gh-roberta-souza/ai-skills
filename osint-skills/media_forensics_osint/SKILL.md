---
name: media_forensics_osint
description: Analyze images and videos using open-source forensic techniques to assess authenticity and context. Use when verifying media, detecting manipulation, or identifying original sources.
---

# Media Forensics (OSINT)

Advanced verification of images and videos using open-source forensic techniques.

## When to use

- Verifying image or video authenticity
- Detecting manipulated media
- Identifying original source
- Detecting reused media across contexts

## Analysis types

- Metadata analysis (EXIF, creation date, device)
- Reverse image search
- Compression artifact analysis
- Visual inconsistency detection

## Verification goals

- Detect reused media
- Detect manipulated media
- Identify original source

## Confidence levels

| Level            | Meaning                    |
|------------------|----------------------------|
| Verified         | Strong evidence of origin   |
| Likely authentic | Consistent with claims      |
| Uncertain        | Insufficient evidence       |
| Suspicious       | Indicators of manipulation  |

## Integration

Invoked by `osint_ai_orchestrator` during Stage 3 (media analysis).

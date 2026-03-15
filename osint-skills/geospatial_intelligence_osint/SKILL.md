---
name: geospatial_intelligence_osint
description: Perform geospatial analysis using open-source images, maps, metadata, and contextual clues. Use when locating places, verifying locations, or analyzing geographic context.
---

# Geospatial Intelligence (OSINT)

Location intelligence from public data sources.

## When to use

- Locating places from images or text
- Verifying claimed locations
- Analyzing geographic context
- Correlating events with places

## Data sources

- Satellite imagery
- Street View images
- Geotagged posts
- Public maps

## Location inference methods

- Landmark recognition
- Architectural pattern matching
- Terrain analysis
- Signage and language detection

## Confidence levels

| Level | Condition                    |
|-------|------------------------------|
| High  | Multiple matching landmarks   |
| Medium| Partial geographic features   |
| Low   | Contextual guess              |

## Integration

Invoked by `osint_ai_orchestrator` during Stage 2 (data collection).

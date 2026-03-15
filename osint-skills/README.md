# ai-osint-skills

Modular OSINT (Open-Source Intelligence) skill architecture for lawful investigations using public data. Designed for journalism, research, threat intelligence, and investigations.

## Architecture

```
osint_ai_orchestrator
        │
        ├── identity_resolution_engine
        ├── social_graph_intelligence
        ├── geospatial_intelligence_osint
        ├── temporal_activity_analysis
        ├── media_forensics_osint
        ├── cross_source_verification
        ├── anomaly_detection_osint
        ├── risk_assessment_intelligence
        └── intelligence_report_generator
```

## Pipeline

1. **Scope definition** — Define objective, entity type, required sources
2. **Data collection** — Identity resolution, social graph, geospatial
3. **Media analysis** — Image/video forensics
4. **Correlation** — Temporal analysis, anomaly detection
5. **Verification** — Cross-source validation
6. **Risk assessment** — Relevance/threat scoring
7. **Reporting** — Structured intelligence reports

## Skills

| Skill | Purpose |
|-------|---------|
| `osint_ai_orchestrator` | Master pipeline controller |
| `identity_resolution_engine` | Entity discovery, alias correlation |
| `social_graph_intelligence` | Relationship and influence mapping |
| `geospatial_intelligence_osint` | Location intelligence from public data |
| `temporal_activity_analysis` | Timeline reconstruction, behavioral patterns |
| `media_forensics_osint` | Image/video authenticity verification |
| `cross_source_verification` | Multi-source evidence validation |
| `anomaly_detection_osint` | Unusual pattern detection |
| `risk_assessment_intelligence` | Threat/relevance scoring |
| `intelligence_report_generator` | Structured report output |

## Format

Skills follow the [Agent Skills](https://agentskills.io/what-are-skills) specification: `SKILL.md` files with YAML frontmatter and Markdown instructions.

## Legal & Ethical Scope

These skills support **lawful** open-source intelligence: journalism, research, threat intelligence, and investigations using public data. They do not support hacking, intrusion, or illegal surveillance.

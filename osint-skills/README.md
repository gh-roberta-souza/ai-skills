# OSINT Skills

Modular skill architecture for **open-source intelligence** investigations using public data. Designed for journalism, research, threat intelligence, and lawful investigations.

## What it does

Performs structured OSINT pipelines:

- Entity discovery and alias correlation
- Relationship and influence mapping
- Location intelligence from public data
- Timeline reconstruction
- Media authenticity verification
- Cross-source evidence validation
- Anomaly detection
- Structured intelligence reports

## Architecture

```mermaid
flowchart TB
    subgraph Orchestrator["osint_ai_orchestrator"]
        direction TB
        Scope["Scope definition"]
        Collect["Data collection"]
        Media["Media analysis"]
        Corr["Correlation"]
        Verify["Verification"]
        Risk["Risk assessment"]
        Report["Reporting"]
        
        Scope --> Collect --> Media --> Corr --> Verify --> Risk --> Report
    end
    
    subgraph Skills["Managed skills"]
        IR["identity_resolution_engine"]
        SG["social_graph_intelligence"]
        GI["geospatial_intelligence_osint"]
        TA["temporal_activity_analysis"]
        MF["media_forensics_osint"]
        CV["cross_source_verification"]
        AD["anomaly_detection_osint"]
        RA["risk_assessment_intelligence"]
        RG["intelligence_report_generator"]
    end
    
    Collect --> IR
    Collect --> SG
    Collect --> GI
    Media --> MF
    Corr --> TA
    Corr --> AD
    Verify --> CV
    Risk --> RA
    Report --> RG
```

## Pipeline

```mermaid
flowchart LR
    A["1. Scope"] --> B["2. Collection"]
    B --> C["3. Media"]
    C --> D["4. Correlation"]
    D --> E["5. Verification"]
    E --> F["6. Risk"]
    F --> G["7. Report"]
```

| Stage | Purpose |
|-------|---------|
| Scope definition | Objective, entity type, required sources |
| Data collection | Identity resolution, social graph, geospatial |
| Media analysis | Image/video forensics |
| Correlation | Temporal analysis, anomaly detection |
| Verification | Cross-source validation |
| Risk assessment | Relevance/threat scoring |
| Reporting | Structured intelligence output |

## Skills

| Skill | Purpose |
|-------|---------|
| `osint_ai_orchestrator` | Master pipeline controller |
| `identity_resolution_engine` | Entity discovery, alias correlation |
| `social_graph_intelligence` | Relationship and influence mapping |
| `geospatial_intelligence_osint` | Location intelligence |
| `temporal_activity_analysis` | Timeline reconstruction |
| `media_forensics_osint` | Image/video authenticity |
| `cross_source_verification` | Multi-source validation |
| `anomaly_detection_osint` | Unusual pattern detection |
| `risk_assessment_intelligence` | Threat/relevance scoring |
| `intelligence_report_generator` | Structured report output |

## Legal & Ethical Scope

These skills support **lawful** open-source intelligence: journalism, research, threat intelligence, and investigations using public data. They do not support hacking, intrusion, or illegal surveillance.

## Format

`SKILL.md` files with YAML frontmatter and Markdown instructions. [Agent Skills](https://agentskills.io/what-are-skills) specification.

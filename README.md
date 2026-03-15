# AI Skills

Collection of Agent Skills for design and OSINT, compatible with Cursor and the [Agent Skills](https://agentskills.io/what-are-skills) specification.

## Structure

```
ai-skills/
├── design-skills/          # Instagram layouts, typography, virality
│   ├── instagram_design_system/
│   ├── instagram_carousel_design_system/
│   ├── layout_ai_orchestrator/
│   ├── algorithmic_typography_system/
│   ├── virality_prediction_engine/
│   ├── layout_entropy_control/
│   ├── visual_balance_solver/
│   ├── psychology_of_attention_layout/
│   ├── data_visualization_for_instagram/
│   └── viral_content_layout_patterns/
│
└── osint-skills/           # Open-source intelligence pipeline
    ├── osint_ai_orchestrator/
    ├── identity_resolution_engine/
    ├── social_graph_intelligence/
    ├── geospatial_intelligence_osint/
    ├── temporal_activity_analysis/
    ├── media_forensics_osint/
    ├── cross_source_verification/
    ├── anomaly_detection_osint/
    ├── risk_assessment_intelligence/
    └── intelligence_report_generator/
```

## Design Skills

| Skill | Description |
|-------|-------------|
| `instagram_design_system` | Deterministic layout engine for Instagram feed (1080×1350) |
| `instagram_carousel_design_system` | Multi-slide carousels with narrative continuity |
| `layout_ai_orchestrator` | Master orchestrator for layout generation |
| `algorithmic_typography_system` | Modular typography scales and baseline rhythm |
| `virality_prediction_engine` | Viral potential scoring (0–100) |
| `layout_entropy_control` | Visual entropy regulation |
| `visual_balance_solver` | Center-of-mass balance algorithms |
| `psychology_of_attention_layout` | Gestalt principles and attention zones |
| `data_visualization_for_instagram` | Charts and infographics for mobile |
| `viral_content_layout_patterns` | High-engagement layout patterns |

## OSINT Skills

| Skill | Description |
|-------|-------------|
| `osint_ai_orchestrator` | Master OSINT pipeline controller |
| `identity_resolution_engine` | Entity discovery and alias correlation |
| `social_graph_intelligence` | Relationship and influence mapping |
| `geospatial_intelligence_osint` | Location intelligence from public data |
| `temporal_activity_analysis` | Timeline reconstruction and patterns |
| `media_forensics_osint` | Image/video authenticity verification |
| `cross_source_verification` | Multi-source evidence validation |
| `anomaly_detection_osint` | Unusual pattern detection |
| `risk_assessment_intelligence` | Threat/relevance scoring |
| `intelligence_report_generator` | Structured report output |

## Usage

Each skill contains a `SKILL.md` file with YAML frontmatter and Markdown instructions. Use with Cursor by adding the path to your skills configuration or copying the desired skill folders to `~/.cursor/skills/`.

## Format

Skills follow the [Agent Skills](https://agentskills.io/what-are-skills) specification.

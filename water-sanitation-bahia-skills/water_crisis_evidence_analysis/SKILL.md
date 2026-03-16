---
name: water_crisis_evidence_analysis
description: Specialized technical analysis skill for evaluating evidence related to water supply service failures in Brazil, using official sanitation datasets and regulatory indicators.
---

# Water Crisis Evidence Analysis

Technical analysis of evidence for water supply service failures. Uses official datasets and regulatory indicators. Separates fact, analysis, and inference.

## Domain scope

| Dimension | Value |
|-----------|-------|
| Sector | Water supply |
| Geography | Brazil |
| Primary focus | Bahia |

## Authoritative data sources

### National datasets

- SINISA (Sistema Nacional de Informações em Saneamento Básico)
- SISAGUA (Sistema de Informação de Vigilância da Qualidade da Água)
- SNIS historical datasets

### Regulatory sources

- AGERSA inspection reports
- ANA regulatory reference standards
- Ministry of Cities sanitation indicators

### Operational evidence

- Service complaint records
- Customer service protocols
- Interruption reports
- Regulatory complaints

## Analysis dimensions

| Dimension | Description | Indicators |
|-----------|-------------|------------|
| Service continuity | Frequency of interruption and recurrence patterns | number_of_service_protocols, recurrence_frequency, average_interval_between_interruptions |
| Service quality | Water quality and distribution reliability | water_quality_flags, turbidity_reports, contamination_alerts |
| Infrastructure capacity | Whether capacity meets population demand | network_coverage, treatment_capacity, distribution_losses |
| Regulatory compliance | Alignment with legal obligations | continuity_requirements, regulatory_notifications, inspection_reports |

## Evidence classification

| Type | Definition |
|------|-------------|
| **Verified fact** | Supported by official data or regulatory documentation |
| **Technical analysis** | Interpretation of data patterns without attribution of intent |
| **Hypothesis** | Possible explanation requiring further investigation |

## Legal risk controls

### Allowed conclusions

- Documented service interruption
- Repeated service failures
- Possible regulatory non-compliance
- Infrastructure capacity constraints

### Prohibited conclusions

- Corruption allegations
- Attribution of criminal intent
- Accusations against individuals

## Report outputs

| Output | Description |
|--------|-------------|
| Evidence summary | Concise explanation of observed service issues |
| Indicator table | List of metrics supporting the analysis |
| Risk assessment | Evaluation of legal risk of communicating the findings |

## Communication guidelines

### Preferred language

- "dados indicam"
- "registros mostram"
- "evidências sugerem"

### Avoid language

- "prova de corrupção"
- "crime cometido"
- "responsabilidade pessoal direta"

## Integration

Technical layer between OSINT (data) and strategy. Use after `regulatory_compliance_water_services`, before `legal_risk_water_claims`.

**Pipeline:** Technical data → water_crisis_evidence_analysis → legal_risk_water_claims → social_strategy_orchestrator → copy_ai_orchestrator → layout_ai_orchestrator

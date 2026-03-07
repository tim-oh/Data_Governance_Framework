# Analysis

Data analysis is achieved by documenting the underlying metadata about key data assets according to standard operating procedures. The availability of appropriate contextual metadata paves the way for data discoverability, use, and assessment of completeness by providing a comprehensive picture of available items. Wider analysis of data use through monitoring activities and the assessment of risks to the registered population are other essential components of this building block. Relevant sources for more details include the ISO/IEC 10032 Reference Model of Data Management (ISO & IEC, 2003), the ISO 9001 (ISO, 2015) standard on quality management systems, and the DAMA-DMBOK2 (DAMA, 2017).

## Implementation mechanisms

| Mechanism | Priority | R | A | C | I |
|-----------|----------|---|---|---|---|
| [Data catalogue](../../toolkit/data-catalogue.md) | Immediate | DA | GC | IT, DP, DC, PA | — |
| [Data protection impact assessment](../../toolkit/data-protection-impact-assessment.md) | Immediate | DA | GC | PA, IT, DC, DP | — |
| [Logs, dashboards and monitoring](../../toolkit/logs-dashboards-monitoring.md) | Intermediate | IT | DA | DC, DP, PA | GC, PA |

**Key:** DA = data administrator; GC = governance council; DP = data provider; DC = data collector; PA = programme administrator; IT = IT services

### Data catalogue

A data catalogue provides a context and a layer focusing on discovery, search, metadata management, lineage, collaboration, and governance. In practice, a data catalogue accelerates the generation of insights by ensuring that data is readily available and accessible, with sufficient context and clearly specified access permissions. A robust data catalogue comprises five essential components: metadata, data classification, data lineage, data dictionary, and data glossary.

### Data protection impact assessment (DPIA)

A DPIA is a process designed to describe the processing of data, assess its necessity and proportionality, and help manage the risks to the rights and freedoms of natural persons resulting from the processing of personal data by assessing them and determining the measures to address them. Conducting a DPIA is a requirement of many data protection laws and, in such settings, is usually necessary for compliance with legal obligations. A DPIA is good practice, irrespective of whether it is mandatory by law.

### Logs, dashboards and monitoring

Automated, systematic monitoring of all data storage and processing activities is an essential component of data governance. The creation of audit trails for the collection, creation, and transformation of sensitive personal information is necessary to monitor data management and the various dimensions of data quality. Dashboards can help to monitor administrative processes, to ensure that they are working in line with regular system performance and provide a key tool for both day-to-day management and more general supervision by accountable parties.

## Related building blocks

- [Planning](planning.md) — the data management plan should define analysis and monitoring responsibilities
- [Access: Cross-cutting issues](../access/cross-cutting.md) — data catalogue supports access management
- [Security: Organisational](../security/organisational.md) — monitoring feeds into security review

## Related toolkit items

- [Data catalogue](../../toolkit/data-catalogue.md)
- [Data protection impact assessment](../../toolkit/data-protection-impact-assessment.md)
- [Logs, dashboards and monitoring](../../toolkit/logs-dashboards-monitoring.md)

# Master data model

**Pillar:** Quality | **Building block:** Uniqueness | **Priority:** Immediate

## What it is

Master data can be summarised as essential information about the core components of a data system. It changes slowly, in contrast to transaction data, which evolves in daily operation. Accordingly, the master data model is a blueprint of the core entities and reference lists that underpin the data ecosystem. It establishes unique keys, standard attributes, and authoritative sources for each entity so that every system component refers to the same object in the same way. A well-structured master data model reduces duplication, enables interoperability, and is the foundation for data quality, as it facilitates deduplication, reconciliation, and analytics. The DAMA-DMBOK2 (DAMA, 2017) is an excellent reference on this topic, with an entire chapter on master data.

## Components

| Component | Description |
|-----------|-------------|
| Entity inventory | A complete list of 'master entities' (households, individuals, benefit programmes, payment cycles, geographic units, service providers, administrative areas) with plain language definitions. |
| Attribute schema | For each entity, the set of mandatory attributes (names, codes, dates, status flags) including data types, validation rules, and allowable value lists to ensure that the information is valid and consistent. |
| Relationships and cardinality | Diagrams and tables showing how entities link to one another (e.g. the individuals that make up a household, or the beneficiaries of a programme). |
| Master record | Identification of the authoritative source for each entity and attribute, plus rules for resolving conflicts. |
| Geographic master data | A standardised table of administrative divisions, localities, and perhaps Global Positioning System (GPS) coordinates in line with the address system. |
| Governance and stewardship | Assigned data owners who are responsible for updates and quality metrics, aligned with the data catalogue and discrepancy-resolution process. |

## RACI

| R | A | C | I |
|---|---|---|---|
| DA, IT | GC | DP, PA, DC | — |

## Related building blocks

- [Uniqueness](../pillars/quality/uniqueness.md)

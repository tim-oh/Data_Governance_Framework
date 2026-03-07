# Uniqueness

Uniqueness establishes an unambiguous representation of a social protection actor, such as a person, household, location, or programme, across the whole data system. It prevents duplicate records, ensures accurate analytics, and underpins fair and efficient service delivery. Uniqueness is enforced through unique identifiers and can be supported with data quality procedures such as matching algorithms for de-duplication.

## Implementation mechanisms

| Mechanism | Priority | R | A | C | I |
|-----------|----------|---|---|---|---|
| [Master data model](../../toolkit/master-data-model.md) | Immediate | DA, IT | GC | DP, PA, DC | — |
| [Unique identifier](../../toolkit/unique-identifier.md) | Immediate | IT | GC | PA, DA | — |

**Key:** DA = data administrator; GC = governance council; DP = data provider; DC = data collector; PA = programme administrator; IT = IT services

### Master data model

Master data can be summarised as essential information about the core components of a data system. It changes slowly, in contrast to transaction data, which evolves in daily operation. Accordingly, the master data model is a blueprint of the core entities and reference lists that underpin the data ecosystem. It establishes unique keys, standard attributes, and authoritative sources for each entity so that every system component refers to the same object in the same way. A well-structured master data model reduces duplication, enables interoperability, and is the foundation for data quality, as it facilitates deduplication, reconciliation, and analytics.

### Unique identifier

A unique identifier (UID) is an alphanumeric code that is issued to each registration officer, whether household or individual, on first registration. As the name suggests, it serves as an identifier across databases in the social protection system, enabling data from different sources to be linked to the appropriate assistance unit. It also serves to establish identity by providing a link with hard-to-falsify verification information such as biometrics or log-in credentials. The master ledger of UIDs is highly sensitive and needs to be protected against loss, unauthorised access and improper manipulation.

## Related building blocks

- [Completeness](completeness.md) — duplicates inflate apparent completeness figures
- [Consistency](consistency.md) — duplicate records cause inconsistency across the system
- [Access: Internal access](../access/internal-access.md) — HR databases and access management depend on unique identification

## Related toolkit items

- [Master data model](../../toolkit/master-data-model.md)
- [Unique identifier](../../toolkit/unique-identifier.md)

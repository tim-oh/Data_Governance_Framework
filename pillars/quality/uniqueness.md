# Uniqueness

Uniqueness refers to the degree to which each individual or entity is represented only once in the system. Duplicate records inflate coverage estimates, enable fraud, and complicate benefit delivery.

## What good looks like

> _Placeholder: from framework text — unique identifier system linked to civil registration or biometrics, deduplication process, master data model_

## Implementation mechanisms

| Mechanism | Priority | R | A | C | I |
|-----------|----------|---|---|---|---|
| [Master data model](../../toolkit/master-data-model.md) | Immediate | DA, IT | GC | DP, PA, DC | — |
| [Unique identifier](../../toolkit/unique-identifier.md) | Immediate | IT | GC | PA, DA | — |

**Key:** DA = data administrator; GC = governance council; DP = data provider; DC = data collector; PA = programme administrator; IT = IT services

### Master data model

> _Placeholder: what a master data model is, how it defines the canonical representation of each entity type_

### Unique identifier

> _Placeholder: types of unique identifiers used in social protection (national ID, biometric ID), how to implement and manage them_

## Minimum viable implementation

> _Placeholder: minimum steps — e.g. deduplication check against existing records at registration_

## Common pitfalls

> _Placeholder: e.g. no unique ID leads to duplicate registrations; multiple programmes maintain separate registries with no deduplication_

## Related building blocks

- [Completeness](completeness.md) — duplicates inflate apparent completeness figures
- [Consistency](consistency.md) — duplicate records cause inconsistency across the system
- [Access: Internal access](../access/internal-access.md) — HR databases and access management depend on unique identification

## Related toolkit items

- [Master data model](../../toolkit/master-data-model.md)
- [Unique identifier](../../toolkit/unique-identifier.md)

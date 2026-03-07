# Internal access

Data access by staff is a condition for the effective execution of many duties and responsibilities. Providing access as and when required, at low administrative cost, while maintaining data protection and security, is the purpose of internal data access.

## Implementation mechanisms

| Mechanism | Priority | R | A | C | I |
|-----------|----------|---|---|---|---|
| [HR database](../../toolkit/hr-database.md) | Intermediate | DA | GC | PA, DC, DP, IT | — |
| [Account permission and revocation](../../toolkit/account-permission-and-revocation.md) | Immediate | IT | GC | — | — |

**Key:** DA = data administrator; GC = governance council; DP = data provider; DC = data collector; PA = programme administrator; IT = IT services

### HR database

A HR database is the systematic assignment of access rights and is essential for the internal implementation of the data access policy. As per data protection rules, access to personal data should be restricted on the basis of the 'need to know' principle. Apart from the various HR management uses of such a database, perhaps the key function of an HR database from a data governance perspective is the assignment of job categories to each staff member. These groups, likely tied to the major job roles in the organisation, can be assigned user rights that satisfy the data requirements for the effective performance of each role (including both read and write access). As expressed in the data access policy, the default position should be no access, with rights only granted when necessary.

### Account permission and revocation

Account permissions implement the access rights listed in the HR database and amended by successful data access requests. Each data system from which social protection information can be accessed must be restricted to permissioned accounts. To maintain data protection, the revocation of rights is as important as their granting.

## Related building blocks

- [Cross-cutting issues](cross-cutting.md) — data access policy sets the framework for internal access decisions
- [Security: Technical](../security/technical.md) — authentication mechanisms enforce access controls

## Related toolkit items

- [HR database](../../toolkit/hr-database.md)
- [Account permission and revocation](../../toolkit/account-permission-and-revocation.md)

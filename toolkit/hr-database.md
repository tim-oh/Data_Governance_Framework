# HR database

**Pillar:** Access | **Building block:** Internal access | **Priority:** Intermediate

## What it is

A HR database is the systematic assignment of access rights and is essential for the internal implementation of the data access policy. As per data protection rules, access to personal data should be restricted on the basis of the 'need to know' principle. Apart from the various HR management uses of such a database, perhaps the key function of an HR database from a data governance perspective is the assignment of job categories to each staff member. These groups, likely tied to the major job roles in the organisation, can be assigned user rights that satisfy the data requirements for the effective performance of each role (including both read and write access). As expressed in the data access policy, the default position should be no access, with rights only granted when necessary. NIST (2024) proposes detailed technical controls for identity management that can serve as a reference for the following.

## Components

| Component | Description |
|-----------|-------------|
| Job listing | A listing of job types in the organisation, with data requirements for each role. If a particular staff member requires data access that is not needed by all colleagues in the role, an internal data access request should be made, instead of adding the data access in general. |
| Access right assignment | Successively higher hurdles should be met for read access, followed by the right to change records, followed by the right to create new records and the right to delete existing records. |
| Principle of least privilege | This principle holds that users should be granted the minimum level of access required to fulfil their duties, and no more. In addition to limiting access to specific items, it should potentially be limited further by constraints such as particular geographies or times, to ensure that only strictly necessary data can be accessed. The definition of these variables should be drawn from the data catalogue to ensure alignment. |

## RACI

| R | A | C | I |
|---|---|---|---|
| DA | GC | PA, DC, DP, IT | — |

## Related building blocks

- [Internal access](../pillars/access/internal-access.md)

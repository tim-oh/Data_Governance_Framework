# Unique identifier

**Pillar:** Quality | **Building block:** Uniqueness | **Priority:** Immediate

## What it is

A unique identifier (UID) is an alphanumeric code that is issued to each registration officer, whether household or individual, on first registration. As the name suggests, it serves as an identifier across databases in the social protection system, enabling data from different sources to be linked to the appropriate assistance unit. It also serves to establish identity by providing a link with hard-to-falsify verification information such as biometrics or log-in credentials. The master ledger of UIDs is highly sensitive and needs to be protected against loss, unauthorised access and improper manipulation. The World Bank has a number of publications on identity management, including its links to foundational national IDs, such as Principles on Identification for Sustainable Development: Toward the Digital Age (World Bank, 2017). It is worth noting that unique identifier information also constitutes personal data and, accordingly, needs to be protected by personal data protection rules.

## Components

| Component | Description |
|-----------|-------------|
| Secure, scalable and readable format | A sufficiently long, pseudo-random code that prevents revelation of sensitive information (such as area codes) and guessing attacks, and provides capacity for user population and coverage growth is needed. A checksum that detects data entry errors is also advisable, as is a human-readable format with separators, e.g. 1234-5678-9889. |
| Non-repeating codes | No identifier should be issued more than once to ensure its uniqueness, which is most easily accomplished by a central authority with a complete record of previously issued identifiers. |
| Separate individual codes | Where both individual- and household-level programmes exist, individuals should be issued with a separate individual code unrelated to that of the household. The household code can then be used as a relational attribute of the individual's record. |
| Reassignment rules | Household splits are a normal part of the lifecycle and need to be accommodated in the UID system. For example, in case of a split, the head of household may maintain the existing household code, but the split-off individual(s) need to either join an existing household or be issued a new household UID in case of household creation. |
| Robust issuance | Where possible, the code should be issued by a single institution to ensure uniqueness. In cases where connectivity to a central issuing authority cannot be guaranteed, robustness measures such as concurrency controls or pre-allocation pools are important. Deduplication and collision checks should be undertaken before final issuance is confirmed. |

## RACI

| R | A | C | I |
|---|---|---|---|
| IT | GC | PA, DA | — |

## Related building blocks

- [Uniqueness](../pillars/quality/uniqueness.md)

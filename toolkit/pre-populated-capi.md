# Pre-populated CAPI

**Pillar:** Quality | **Building block:** Consistency | **Priority:** Intermediate

## What it is

CAPI stands for Computer-Assisted Personal Interviewing and refers to an electronic questionnaire implemented on a digital device, usually a tablet or smartphone. A pre-populated CAPI takes existing information to suggest answers for items that were previously recorded. CAPI supports efficiency and effectiveness by enhancing data quality, enabling flexible questionnaires that limit questions to relevant items, and allowing for real-time monitoring. It is closely related to various aspects of primary data acquisition and data quality. The idea of pre-populated information extends to self-declaration forms that applicants or existing beneficiaries complete themselves. Turkey's Integrated Social Assistance System (ISAS) deploys such an approach (World Bank, 2018).

## Components

| Component | Description |
|-----------|-------------|
| Pre-populated responses | A benefit of the interoperable nature of modern social registries is their access to extensive administrative data, which can be used to streamline the interview process. In particular, data items that are part of the questionnaire and which can be derived from an existing data source (possibly including a prior household questionnaire) should be included in the questionnaire as a suggested answer. The enumerator can then simply confirm this item, with a mechanism to mark discrepancies for reconciliation. |
| Skip logic | Some information is only relevant for specific programmes, and some questions only apply to some households. For instance, questions about current schooling should only be limited to households with children. CAPI software facilitates implementation of such conditional questions. |
| Validity constraints | Digital data entry allows the responses to be limited to valid entries in terms of format and response range, such as only allowing dates of birth before a certain year for household members marked as children in the 'relation to head of household' question. |

## RACI

| R | A | C | I |
|---|---|---|---|
| IT, DC | DC | DA | DA |

## Related building blocks

- [Consistency](../pillars/quality/consistency.md)

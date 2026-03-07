# Consent management

**Pillar:** Access | **Building block:** Cross-cutting | **Priority:** Immediate

## What it is

Consent management is the end-to-end process of capturing, storing, updating, and enforcing data subjects' permissions for the collection, processing, and sharing of their personal data. It operationalises the principles of informed, specific, freely given, and revocable consent required by modern data-protection laws, and it provides auditable proof that data use remains lawful over time. The European Data Protection Board, EU Data protection authorities, and UK's Information Commissioner's Office (ICO, 2020) provide guidance on how to operationalise the following items in a real-world IT system.

## Components

| Component | Description |
|-----------|-------------|
| Consent registry | A secure database that records each consent event with the data subject's unique identifier, the scope of consent, a timestamp, potentially an expiry date, and evidence of signature or other acceptance. |
| Capture channels | Multi-channel tools, such as digital signature pads, USSD protocols, web portals, and paper forms, that attach consent to the relevant data. |
| Revocation and amendment | Both digital self-service and physical assisted avenues for beneficiaries to withdraw or change consent. This should trigger deletion of data held solely on the basis of consent, and other relevant actions including programme exit if necessary. |
| Audit trails | Data logs that show who accessed or modified consent records. |
| Communication materials | Human-readable notices in suitable language(s) that are also appropriate for the applicant/beneficiaries' literacy level, possibly both in electronic and printed form, to provide lasting evidence, highlight revocation and amendment rights etc. |

## RACI

| R | A | C | I |
|---|---|---|---|
| DA, IT | GC | DC, PA | DP, PA |

## Related building blocks

- [Cross-cutting issues](../pillars/access/cross-cutting.md)

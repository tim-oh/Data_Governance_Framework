# Account permission and revocation

**Pillar:** Access | **Building block:** Internal access | **Priority:** Immediate

## What it is

Account permissions implement the access rights listed in the HR database and amended by successful data access requests. Each data system from which social protection information can be accessed must be restricted to permissioned accounts. To maintain data protection, the revocation of rights is as important as their granting. As in the prior point, NIST (2024) provides further specifics on account permissions in its AC-2.

## Components

| Component | Description |
|-----------|-------------|
| Authentication | Authentication that meets the organisation's data security requirements is needed for each log-in. |
| Permissions | Permissions must include read access, write access, record creation and record deletion. |
| Process for adjusting user rights | The process through which a change in the HR database and a successful data access request triggers an adjustment of user rights. |
| Linked access rights | Access rights need to be linked with staffing information from human resources to ensure continued alignment, with job status changes triggering automatic adjustments to user rights. For instance, a person changing jobs in the organisation should be assigned the new job's profile according to the HR database, revoking previously granted access requests. |
| Expiring access rights | Access rights should expire automatically to prompt a fresh data access request. |
| Temporary revocation of access rights | A temporary revocation of access rights should be triggered by a violation of the data access policy, based on automated monitoring, while the issue is investigated. |

## RACI

| R | A | C | I |
|---|---|---|---|
| IT | GC | — | — |

## Related building blocks

- [Internal access](../pillars/access/internal-access.md)

# Technical measures

Technical measures are the technology-based controls that protect data from unauthorised access, interception, and loss. They form the first line of defence in any data security architecture.

## What good looks like

> _Placeholder: from framework text — encryption at rest and in transit, strong authentication, network segmentation, regular patching, endpoint protection, penetration testing_

## Implementation mechanisms

| Mechanism | Priority | R | A | C | I |
|-----------|----------|---|---|---|---|
| [Encryption](../../toolkit/encryption.md) | Immediate | IT | IT | — | GC |
| [Authentication](../../toolkit/authentication.md) | Immediate | IT | IT | — | GC |
| [Data loss prevention](../../toolkit/data-loss-prevention.md) | Immediate | IT | IT | — | GC |
| [Network security](../../toolkit/network-security.md) | Immediate | IT | IT | — | GC |
| [Endpoint security](../../toolkit/endpoint-security.md) | Immediate | IT | IT | DA, PA, DC | GC |
| [Patches and updates](../../toolkit/patches-and-updates.md) | Immediate | IT | IT | — | — |
| [Penetration testing](../../toolkit/penetration-testing.md) | Intermediate | IT | IT | — | GC |

**Key:** DA = data administrator; GC = governance council; DC = data collector; PA = programme administrator; IT = IT services

### Encryption

> _Placeholder: encryption at rest and in transit; key management; minimum standards_

### Authentication

> _Placeholder: multi-factor authentication, password policies, session management_

### Data loss prevention

> _Placeholder: DLP tools and policies to prevent accidental or deliberate data exfiltration_

### Network security

> _Placeholder: firewalls, network segmentation, intrusion detection_

### Endpoint security

> _Placeholder: device-level protection for all devices that access social protection data_

### Patches and updates

> _Placeholder: patch management policy and process; risk of unpatched systems_

### Penetration testing

> _Placeholder: regular testing to identify vulnerabilities before they are exploited_

## Minimum viable implementation

> _Placeholder: minimum steps for a low-resource context — e.g. encryption in transit, strong passwords, regular patching_

## Common pitfalls

> _Placeholder: e.g. no encryption on mobile devices used in field collection; default passwords not changed_

## Related building blocks

- [Organisational measures](organisational.md) — technical controls require organisational processes to be effective
- [Access: Internal access](../access/internal-access.md) — authentication enforces access controls

## Related toolkit items

- [Encryption](../../toolkit/encryption.md) · [Authentication](../../toolkit/authentication.md) · [Data loss prevention](../../toolkit/data-loss-prevention.md) · [Network security](../../toolkit/network-security.md) · [Endpoint security](../../toolkit/endpoint-security.md) · [Patches and updates](../../toolkit/patches-and-updates.md) · [Penetration testing](../../toolkit/penetration-testing.md)

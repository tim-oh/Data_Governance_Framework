# Technical measures

Technical measures comprise technologies and protocols implemented to ensure the security and integrity of data within the social protection system. In the context of low- and middle-income countries (LMICs), these measures are critical for protecting sensitive information, preventing unauthorised access, and minimising the risk of data breaches. They encompass encryption, network security, data loss prevention, and more, which work together to safeguard the system from both internal and external threats.

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

Protects data by converting it into an unreadable format for users without a key, thus excluding unauthorised users. Data both at rest and in transit should be encrypted to ensure confidentiality and integrity, protecting it against easy interception.

### Authentication

Verification of user identity is essential for security before access to the system and, thus, to sensitive data can be granted. Passwords, multi-factor authentication, and biometric methods are most used to limit access to sensitive data.

### Data loss prevention

A set of tools and processes designed to ensure that sensitive data is not lost, misused, or accessed by unauthorised individuals, which includes the monitoring of data transfers, file sharing, and perhaps even printing to prevent data leaks.

### Network security

The protection of network infrastructure from commercial and state hackers is essential for a large system that holds extensive personal data. Firewalls and intrusion detection systems can help to make sure that the social protection system's network is safeguarded against unauthorised access, hacking or malware.

### Endpoint security

Security that relates to individual devices, e.g. laptops or mobile phones, that may access sensitive data.

### Patches and updates

Regularly applying patches and updates to operating systems, software, and even hardware is key to closing vulnerabilities and enhancing overall security.

### Penetration testing

Simulates hacking attacks to test ICT security defences, with the aim of identifying potential vulnerabilities before they can be exploited by malicious actors. The test results should then inform security improvements and updates.

## Related building blocks

- [Organisational measures](organisational.md) — technical controls require organisational processes to be effective
- [Access: Internal access](../access/internal-access.md) — authentication enforces access controls

## Related toolkit items

- [Encryption](../../toolkit/encryption.md) · [Authentication](../../toolkit/authentication.md) · [Data loss prevention](../../toolkit/data-loss-prevention.md) · [Network security](../../toolkit/network-security.md) · [Endpoint security](../../toolkit/endpoint-security.md) · [Patches and updates](../../toolkit/patches-and-updates.md) · [Penetration testing](../../toolkit/penetration-testing.md)

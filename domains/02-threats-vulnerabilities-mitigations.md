# Domain 2 — Threats, Vulnerabilities & Mitigations

## Threat model

```text
Threat actor
    ↓
Attack vector
    ↓
Vulnerability
    ↓
Exploit / action
    ↓
Impact
    ↓
Mitigation
```

## Threat Actors

Examples:

- nation-state;
- cybercriminal;
- insider;
- hacktivist;
- script kiddie;
- competitor;
- third party.

Distinguish actors by:

- motivation;
- resources;
- capability;
- access.

## Application Attacks

Important concepts include:

- SQL injection;
- XSS;
- CSRF;
- IDOR / BOLA;
- command injection;
- directory traversal;
- insecure deserialization;
- buffer-related issues.

## Network Attacks

Examples:

- DNS poisoning / spoofing;
- MITM;
- ARP spoofing;
- VLAN hopping;
- MAC flooding;
- DHCP attacks;
- wireless evil twin;
- deauthentication.

## Vulnerability Management

```text
Identify
 ↓
Validate
 ↓
Prioritize
 ↓
Remediate
 ↓
Verify
 ↓
Close
```

Severity should not be based only on CVSS.

Business impact, exposure, exploitability, asset criticality, and threat intelligence can change priority.

## Mitigation Thinking

The correct mitigation should target the root security problem rather than only the observed symptom.

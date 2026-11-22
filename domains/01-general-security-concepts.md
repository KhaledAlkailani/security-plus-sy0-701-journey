# Domain 1 — General Security Concepts

## Core questions

- What security property is being protected?
- What type of control is being used?
- Where is trust established?
- Is the control preventive, detective, or corrective?

## Key areas

### Security Controls

Controls can be classified by:

**Function**
- Preventive
- Detective
- Corrective
- Deterrent
- Compensating
- Directive

**Type**
- Technical
- Administrative / managerial
- Operational
- Physical

### CIA

```text
Confidentiality → prevent unauthorized disclosure
Integrity       → prevent unauthorized modification
Availability    → keep systems and data accessible
```

### Zero Trust

Core idea:

> Never trust solely because of network location.

Important concepts:

- explicit verification;
- least privilege;
- continuous evaluation;
- segmentation;
- identity-aware access.

### Cryptography

Questions to distinguish:

- Do I need confidentiality?
- Integrity?
- Authenticity?
- Non-repudiation?
- Key exchange?

### Hashing

Hashing is one-way and commonly supports:

- integrity comparison;
- password verification when combined with appropriate password-hashing algorithms;
- digital-signature workflows.

### Digital Signatures

Digital signatures primarily support:

- integrity;
- authenticity;
- non-repudiation.

### PKI

Core components:

- CA
- RA
- certificate
- public/private key pair
- CRL / OCSP
- trust chain

# Domain 4 — Security Operations

This domain is closely connected to practical SOC and investigation work.

## Monitoring

Common data sources:

- authentication logs;
- endpoint telemetry;
- firewall logs;
- DNS;
- proxy logs;
- application logs;
- network traffic;
- cloud audit logs.

## SIEM

A SIEM supports:

- centralized log collection;
- normalization;
- correlation;
- alerting;
- search;
- dashboards;
- investigation.

The SIEM does not automatically make logs useful. Detection quality depends on telemetry, correlation logic, context, and analyst reasoning.

## Vulnerability Management

Important distinction:

```text
Remediation = change the security state
Validation  = prove the original weakness no longer works
```

## IAM

IAM covers broader identity lifecycle and access management.

PAM focuses specifically on privileged access and privileged credentials.

## Incident Response

General flow:

```text
Prepare
 ↓
Detect / Analyze
 ↓
Contain
 ↓
Eradicate
 ↓
Recover
 ↓
Lessons learned
```

## Digital Forensics

Important concepts:

- evidence integrity;
- chain of custody;
- order of volatility;
- disk vs memory;
- timeline analysis;
- metadata;
- hashing.

## Investigation principle

> A finding tells me there is a problem. Evidence tells me what actually happened.

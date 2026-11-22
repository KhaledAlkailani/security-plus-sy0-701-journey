# Scenario — Firewall Rule Exists but Application Is Unreachable

## Situation

A firewall rule was added to allow traffic, but users still cannot reach the application.

## Investigation path

Check:

- source and destination IP;
- destination port;
- protocol;
- rule order;
- security zone;
- NAT;
- routing;
- return path;
- application listening state;
- host firewall;
- stateful-session behavior;
- logs showing deny or reset.

## Principle

A firewall rule is one part of the packet path.

```text
Client
 ↓
Routing
 ↓
Firewall / NAT
 ↓
Network
 ↓
Host firewall
 ↓
Application listener
```

Failure at any point can look like “the firewall is blocking it”.

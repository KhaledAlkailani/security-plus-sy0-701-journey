# Domain 3 — Security Architecture

## Architectural questions

- Where are the trust boundaries?
- Which systems are exposed?
- Which network path must traffic follow?
- Which identities can reach which assets?
- What happens when one component fails?

## Segmentation

Segmentation reduces unnecessary communication paths and limits blast radius.

Examples:

- VLANs;
- firewall zones;
- DMZ;
- microsegmentation;
- cloud security groups.

## Stateful vs Stateless

**Stateless**
- evaluates packets independently;
- does not inherently remember session state.

**Stateful**
- tracks connection state;
- can allow return traffic based on established session context.

## Resilience

Key concepts:

- redundancy;
- fault tolerance;
- backups;
- load balancing;
- clustering;
- high availability;
- disaster recovery.

## Cloud

Important distinctions:

- IaaS
- PaaS
- SaaS

Shared responsibility changes depending on the service model.

## Zero Trust Architecture

Identity and context become primary access signals rather than assuming that internal network location is trustworthy.

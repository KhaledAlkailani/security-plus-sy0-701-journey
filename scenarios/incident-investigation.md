# Scenario — Suspicious Authentication Activity

## Situation

A SIEM alerts on multiple failed logins followed by a successful login from an unusual source.

## Investigation approach

1. Confirm the identity and source.
2. Review authentication timestamps.
3. Check whether MFA was involved.
4. Compare source IP / geolocation context if available.
5. Review activity after the successful login.
6. Look for privilege changes or unusual access.
7. Correlate endpoint, application, and network telemetry.

## Key principle

Do not stop at:

> “The user successfully logged in.”

The real question is:

> “Was the successful authentication legitimate, and what happened after it?”

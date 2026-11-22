# Scenario — Valid User, Unauthorized Action

## Situation

A low-privileged user can authenticate successfully but can access an administrative function.

## Analysis

Authentication is working.

The problem is likely authorization.

Check:

- user role;
- permission mapping;
- endpoint authorization;
- object-level access control;
- server-side enforcement.

## Principle

```text
Valid account
   ≠
Permission for every action
```

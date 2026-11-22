# Authentication vs Authorization

| Authentication | Authorization |
|---|---|
| Who are you? | What are you allowed to do? |
| Happens before or during identity verification | Happens after identity is known |
| Password, MFA, certificate, biometrics | Role, permission, ACL, policy |

## Example

A support user logs into an application successfully.

Authentication: **successful**

The same user tries to run an administrative backup.

Authorization asks:

> Does this user have permission to perform that action?

A valid login does not imply unlimited permission.

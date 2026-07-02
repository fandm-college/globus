---
title: Security Guidelines
parent: Reference
nav_order: 3
---

# Security Guidelines

Globus can be used to share research data securely, but permissions must be configured carefully.

## Protected data

Contact Research Computing Services before using Globus with:

- HIPAA-protected data
- Personally Identifiable Information (PII)
- FERPA-protected educational records
- Controlled research data
- Sponsor-restricted data

{: .security }
> Never use **All Users** or **Public** sharing for protected, confidential, or regulated data.

## Principle of least privilege

Share only the minimum directory and permissions needed.

Prefer:

```text
Lab_Data/Camera_Traps/
```

instead of:

```text
Lab_Data/
```

## Verify identities

Always verify Identity IDs or Group UUIDs before granting access.

## Review permissions

Review permissions periodically and remove users or groups that no longer need access.

---

## Next step

Continue to [Troubleshooting]({{ site.baseurl }}/reference/troubleshooting/).

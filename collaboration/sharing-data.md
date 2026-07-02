---
title: Sharing Data
parent: Collaboration
nav_order: 3
---

# Sharing Data

Globus allows you to share research data with specific users or Groups while retaining control over who has access.

Before sharing, decide how much of the collection should be shared.

{: .security }
> Share the smallest directory that contains everything your collaborator needs. Do not share an entire collection unless that level of access is truly required.

## Directory sharing includes everything below it

Sharing a directory grants access to that directory and everything contained within it, including all files, subdirectories, and their contents.

For example:

```text
Lab_Data/
├── Microscopy/
├── RNA_Sequencing/
├── Camera_Traps/
│   ├── Spring2026/
│   ├── Summer2026/
│   └── Analysis/
└── Publications/
```

If you share `Camera_Traps/`, your collaborator receives access to `Spring2026/`, `Summer2026/`, `Analysis/`, and every file contained within those directories. They do not receive access to `Microscopy/`, `RNA_Sequencing/`, or `Publications/`.

## Open the Permissions page

From the File Manager, navigate to the directory or collection you want to share. Select **Permissions** from the action menu on the right.

![Permissions option in File Manager]({{ site.baseurl }}/assets/images/screenshots/permissions-menu.png){: .figure }

<div class="figure-caption"><strong>Figure 20.</strong> Open Permissions from the File Manager action menu.</div>

## Add a permission

The Permissions page displays current users and groups with access. Click **Add Permissions — Share With** to add a new user or group.

![Permissions page]({{ site.baseurl }}/assets/images/screenshots/permissions-page.png){: .figure }

<div class="figure-caption"><strong>Figure 21.</strong> The Permissions page shows existing access and lets you add new permissions.</div>

Configure the permission.

![Add Permission page]({{ site.baseurl }}/assets/images/screenshots/add-permission.png){: .figure }

<div class="figure-caption"><strong>Figure 22.</strong> Add permissions for a user or group.</div>

Complete the form:

- **Path** — Choose the directory to share.
- **Share With** — Select **User** or **Group**.
- **User or Group ID** — Enter the verified Identity ID or Group UUID.
- **Permissions** — Choose read-only or read/write access.
- Click **Add Permission**.

{: .recommendation }
> Start with read-only access. Grant write access only when collaborators need to upload, modify, rename, or delete files.

{: .security }
> We strongly discourage using **All Users** or **Public** sharing. Never use these options for HIPAA, PII, FERPA, controlled research data, or other protected data.

## Managing shared access

Return to the Permissions page at any time to review, modify, or remove access.

Review permissions periodically, especially for long-running projects.

---

## Next step

Continue to [Transfer Timers]({{ site.baseurl }}/automation/timers/).

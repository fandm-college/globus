---
title: Verifying Collaborator Identities
parent: Collaboration
nav_order: 2
---

# Verifying Collaborator Identities

Sharing data can be error-prone if you search by name or email address. Many Globus users have more than one identity.

Before sharing data, ask the recipient to verify the Globus identity they want you to use.

## How recipients can find their Identity ID

Ask the recipient to:

1. Log into Globus using the identity they normally use.
2. Click **Settings** in the left navigation menu.
3. Locate the identity they intend to use.
4. Click the downward caret next to that identity to expand details.
5. Send you the **Identity ID**.

![Globus Settings page showing identities]({{ site.baseurl }}/assets/images/screenshots/globus-settings-identities.png){: .figure }

<div class="figure-caption"><strong>Figure 18.</strong> The Settings page lists identities associated with the user's Globus account.</div>

![Expanded Globus identity details with ID redacted]({{ site.baseurl }}/assets/images/annotated/globus-identity-details-redacted.png){: .figure }

<div class="figure-caption"><strong>Figure 19.</strong> Expanding an identity shows additional details, including the Identity ID. The ID is redacted here.</div>

Use this Identity ID when configuring sharing permissions.

## Sharing with groups

If you are sharing with a Globus Group instead of an individual, the group owner or administrator should provide the **Group UUID**.

{: .recommendation }
> Do not rely only on a person's name or email address when sharing important research data. A verified Identity ID or Group UUID removes ambiguity and helps ensure the correct person or group receives access.

## If a collaborator does not have Globus access

Collaborators who are not at an institution using Globus can still create a Globus identity. From the Globus login page, they can use **Globus ID** under the sign-in options and choose **Need a Globus ID? Sign up**. They may also be able to use GitHub, Google, or ORCID depending on their situation.

---

## Next step

Continue to [Sharing Data]({{ site.baseurl }}/collaboration/sharing-data/).

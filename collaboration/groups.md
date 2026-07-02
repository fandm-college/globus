---
title: Creating Groups
parent: Collaboration
nav_order: 1
---

# Creating and Managing Globus Groups

If you regularly share data with a changing set of collaborators, Globus Groups make permission management much easier.

Instead of sharing a directory with each collaborator individually, create a Group, add collaborators to the Group, and share data with the Group. As collaborators join or leave the project, update the Group membership instead of revisiting every shared directory.

Groups are especially useful for research labs, courses, undergraduate research students, and long-term projects.

{: .recommendation }
> If you expect more than a few collaborators or anticipate that collaborators will change over time, create a Group and share data with the Group instead of individual users.

## Create a group

Click **Groups** in the left navigation menu, then click **Create new group**.

![Globus Groups page]({{ site.baseurl }}/assets/images/screenshots/groups-list.png){: .figure }

<div class="figure-caption"><strong>Figure 14.</strong> The Groups page lists existing groups and provides the Create new group button.</div>

Complete the group information.

![Create Group page]({{ site.baseurl }}/assets/images/screenshots/create-group.png){: .figure }

<div class="figure-caption"><strong>Figure 15.</strong> Create a Globus Group by providing a group name, description, and recommended visibility settings.</div>

For most faculty and research groups, we recommend:

- Leave **Enable High Assurance** unchecked.
- Leave **Users may request to join this group** unchecked.
- Set **Group Visibility** to **Members of the group**.
- Leave **Membership Visibility** set to **All members**.

Choose a descriptive group name, such as **BIO 390 Spring 2027**, **Smith Lab**, or **Summer REU Students**.

## Add members

After creating the Group, Globus displays the Group overview page. You can return here later to add or remove members.

![Group overview page]({{ site.baseurl }}/assets/images/screenshots/group-overview.png){: .figure }

<div class="figure-caption"><strong>Figure 16.</strong> The Group overview page is where you manage group membership.</div>

Click **Invite Others**, enter the collaborator's Globus UUID, and select a role.

![Invite group member dialog]({{ site.baseurl }}/assets/images/screenshots/invite-group-member.png){: .figure }

<div class="figure-caption"><strong>Figure 17.</strong> Invite a collaborator using their Globus UUID. In most cases, the role should be Member.</div>

For almost every situation, leave the role set to **Member**. Only assign Manager or Administrator roles to trusted individuals who should help manage the Group.

{: .important }
> Group membership does **not** automatically grant access to data. After creating the Group and adding members, you must still share the appropriate collection or directory with that Group.

---

## Next step

Continue to [Verifying Collaborator Identities]({{ site.baseurl }}/collaboration/identities/).

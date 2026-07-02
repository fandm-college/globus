---
title: Globus Connect Personal
parent: Personal Computer
nav_order: 1
---

# Globus Connect Personal

Globus Connect Personal allows your Windows, macOS, or Linux computer to function as a Globus Collection. Once installed, you can transfer data directly between your computer and other Globus Collections.

{: .recommendation }
> Use Globus Connect Personal for large datasets or entire directory trees instead of browser uploads and downloads. Browser transfers do not automatically resume if interrupted, and browser downloads are limited to individual files.

## Download and install

Download Globus Connect Personal from:

[https://www.globus.org/globus-connect-personal](https://www.globus.org/globus-connect-personal)

Select the installer for your operating system and follow the instructions.

## Log in

When Globus Connect Personal starts for the first time, click **Log In**.

![Globus Connect Personal login screen]({{ site.baseurl }}/assets/images/screenshots/gcp-login.png){: .figure }

<div class="figure-caption"><strong>Figure 27.</strong> Click Log In to connect Globus Connect Personal to your Globus account.</div>

Your browser will open and ask you to sign in to Globus.

## Grant consent

Globus asks you to authorize Globus Connect Personal. Provide a descriptive label, then click **Allow**.

![Globus consent screen]({{ site.baseurl }}/assets/images/screenshots/gcp-consent.png){: .figure }

<div class="figure-caption"><strong>Figure 28.</strong> Use a descriptive label so this authorization is easy to recognize later.</div>

## Create your Personal Collection

Choose a descriptive collection name. This is the name you will search for when transferring files.

![Globus Connect Personal setup screen]({{ site.baseurl }}/assets/images/screenshots/gcp-setup.png){: .figure }

<div class="figure-caption"><strong>Figure 29.</strong> Give your Personal Collection a descriptive name and save it.</div>

In most cases, leave **High Assurance** unchecked.

## Configure shared folders

After setup completes, Globus Connect Personal runs in the background.

![Globus Connect Personal running]({{ site.baseurl }}/assets/images/screenshots/gcp-running.png){: .figure }

<div class="figure-caption"><strong>Figure 30.</strong> The Globus Connect Personal interface may vary by operating system.</div>

Open **Preferences**. The default shared folder depends on your operating system, but in many cases it is broader than necessary.

Research Computing Services recommends:

1. Remove the default shared folder if it exposes more than you intend.
2. Add only the specific folders you want Globus to access.
3. Check **Shared** for folders you want accessible through Globus.
4. Check **Write** only if you want to transfer data **to** your computer.

{: .security }
> Share only the directories you actually need. Avoid sharing your entire home directory unless there is a specific reason.

## Start automatically

Configure Globus Connect Personal to start automatically when your computer starts. The exact steps vary by operating system, but this is recommended if you use Globus Connect Personal regularly or rely on scheduled transfers.

Your computer must still be powered on, connected to the internet, and running Globus Connect Personal for transfers to complete.

{: .important }
> Globus Connect Personal only turns your computer into a Globus Collection. Transfers, timers, bookmarks, sharing, and activity monitoring are still performed in the Globus web application.

---

## Next step

Continue to [Common Workflows]({{ site.baseurl }}/reference/workflows/).

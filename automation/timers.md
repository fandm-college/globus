---
title: Transfer Timers
parent: Automation
nav_order: 1
---

# Transfer Timers

Transfer Timers automatically run transfers on a schedule you define. They are useful for recurring backups, instrument data collection, scheduled synchronization, and unattended transfers.

{: .recommendation }
> If you routinely transfer data between the same two locations, consider using a Transfer Timer instead of manually starting each transfer.

## Scientific instruments require RCS assistance

{: .help }
> If you want to automatically transfer data from a scientific instrument or specialized research equipment, contact Research Computing Services first. The instrument or device must be configured as a Globus Collection before a timer can be created. Not all systems are suitable for Globus.

Research Computing Services will determine whether Globus is possible and will configure the collection if appropriate.

## Create a timer

Set up the transfer exactly as you would for a manual transfer.

![Timer transfer ready to configure]({{ site.baseurl }}/assets/images/screenshots/timer-transfer-ready.png){: .figure }

<div class="figure-caption"><strong>Figure 23.</strong> Select the data, source collection, and destination collection before configuring timer options.</div>

Click **Transfer & Timer Options**.

![Transfer and timer options expanded]({{ site.baseurl }}/assets/images/screenshots/timer-options-open.png){: .figure }

<div class="figure-caption"><strong>Figure 24.</strong> Transfer & Timer Options contains labels, transfer settings, notification settings, and schedule options.</div>

## Recommended transfer settings

Give the transfer a descriptive label.

For recurring transfers, we recommend checking **Apply Sync Level** and choosing **L3 — checksum is different** in most cases.

![Sync level options]({{ site.baseurl }}/assets/images/screenshots/timer-sync-level.png){: .figure }

<div class="figure-caption"><strong>Figure 25.</strong> Apply Sync Level helps avoid retransferring files that have not changed.</div>

Leave other transfer and notification settings unchecked unless you have a specific reason to change them.

{: .good-to-know }
> L3 uses checksums to determine whether files differ. It is generally the safest choice for research data because it provides high confidence that unchanged files will not be retransferred.

## Configure the schedule

For recurring timers, fill out the schedule start time and select the appropriate repeat options. Additional fields appear when a repeating schedule is selected.

![Timer repeat options]({{ site.baseurl }}/assets/images/screenshots/timer-repeat-options.png){: .figure }

<div class="figure-caption"><strong>Figure 26.</strong> Repeating timers display additional scheduling options.</div>

Once settings are ready, click **Start** under the source collection. Make sure the source collection is the active collection in the two-panel File Manager.

{: .important }
> Do not schedule timers to run every few minutes. If a previous transfer has not completed before the next scheduled run begins, transfer tasks can accumulate and create a backlog. For most research workflows, once or twice per day is sufficient.

## Monitoring timer runs

Timer-generated transfers appear in **Activity** just like manual transfers. Globus also sends email notifications when a timer runs successfully or fails.

---

## Next step

Continue to [Globus Connect Personal]({{ site.baseurl }}/personal-computer/globus-connect-personal/).

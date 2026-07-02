---
title: Starting a Transfer
parent: Moving Data
nav_order: 3
---

# Starting a Transfer

## Workflow summary

Choose source collection  
↓  
Choose destination collection  
↓  
Select files or folders  
↓  
Click **Start** in the source panel  
↓  
Monitor progress in **Activity**

## Preferred methods for moving data

{: .recommendation }
> Although the Globus web interface allows you to upload files from and download files to your local computer, this is generally **not the preferred method** for moving research data. Whenever possible, transfer data between Globus Collections.

Browser downloads are useful for occasional individual files, but:

- Only individual files can be downloaded.
- Directories cannot be downloaded through the web interface.
- Browser uploads and downloads do not automatically resume if interrupted.
- Browser transfers do not provide the automatic retry and recovery available with Globus transfers.

For large datasets or entire directory trees, use collection-to-collection transfers or Globus Connect Personal.

## Example transfer

In this example, the source is the active left panel and the destination is the right panel. Clicking **Start** in the left panel transfers the selected folders to the destination folder shown in the right panel.

![Transfer ready to start in Globus]({{ site.baseurl }}/assets/images/screenshots/transfer-ready.png){: .figure }

<div class="figure-caption"><strong>Figure 7.</strong> A transfer ready to start. The source is the active left panel, and the destination is shown in the right panel.</div>

{: .important }
> The left panel is not always the source, and the right panel is not always the destination. A transfer starts from the panel where you click **Start**.

---

## Next step

Continue to [Monitoring Transfers]({{ site.baseurl }}/moving-data/activity/).

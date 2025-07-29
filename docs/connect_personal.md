---
title: Globus Connect Personal
layout: page
nav_order: 4
---

# Overview
{: .warning }
Do not install Globus Connect Personal on any system that has high-risk data (e.g., HIPAA, PCI, PHI).
In some cases, Globus can be used to transfer such data, but requires special configuration.

If you find yourself often transferring data to/from your personal laptop, using
Globus Connect personal is much perferred over the upload/download feature.  Globus 
Connect Personal turns your personal computer/laptop into a Globus collection you to

- Easily and reliably move/share data
- Interact with other Globus collections

all without needing to be on the VPN.  Importantly, transfers to/from your
system won't fail if you shut your system down or disconnect from the network.
Instead, transfers will suspend and will automatically resume when your system comes
back oonline **unless** three or more days have elapsed.  In that situation,
the transfer will be cancelled due to inactivity and you will get an email
notification.

* * *

To get started with Globus Connect Personal, download the installer for your Windows/Mac/Linux machine [here](https://www.globus.org/globus-connect-personal)
{: .note }
  > 1. You may need to enable administrative privileges to install the software.
  > 2. During initial configuration, be sure to provide a descriptive name for the Collection Name to make finding it easier.  Calling it My Laptop
  is not a good choice.

# Configure folder sharing
In order to configure what is shareable from your laptop use the following documentation.
This documentation will

- [Mac](https://docs.globus.org/globus-connect-personal/install/mac/#configuration)
- [Windows](https://docs.globus.org/globus-connect-personal/install/windows/#configuration)
- [Linux](https://docs.globus.org/globus-connect-personal/install/linux/#config-paths)

# Starting Globus Connect Personal on reboot
On Windows and Linux, additional configuration is needed to ensure
Global Connect Personal starts when the system is rebooted.  Directions can be found

- [Windows](https://docs.globus.org/globus-connect-personal/install/windows/#starting_globus_connect_personal_automatically_on_reboot)
- [Linux](https://docs.globus.org/globus-connect-personal/install/linux/#running_globus_connect_personal_as_a_systemd_user_unit)
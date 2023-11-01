---
name: 🐞 Bug report
about: Create a report to help us improve

---

**Describe the bug**

Ensure to include a _clear and concise description_ of what the bug is. 

**Steps to reproduce the bug**

1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See the error

**Expected behavior**

Describe what you expected to happen when the bug occurred.

**Screenshots**

Include screenshots to help explain your problem.

**Videos**

If images are not enough, include videos to help explain your problem.
 - GitHub doesn't support uploading videos, so please use video sharing like YouTube or Vimeo, etc., and include the URL.

**Additional context**

Ensure to add any other context about the problem here, including what solutions you've tried already.

**OS version and Desktop information**

Open System Settings, go to About System, click "Copy to clipboard in English," and paste the content here.
 - If using System Settings is impossible, use `hw-probe` to provide this information.

**Hardware Information using hw-probe**

If the issue concerns hardware, use `hw-probe` (if it's not available, please download [hw-probe](https://linux-hardware.org/?view=howto)), run it using the following command `sudo -E hw-probe -all -upload`, and add the URL link.

**Partition information**

For problems regarding partitioning, open Partition Manager, highlight the device where Calamares installed distribution, and take a screenshot.

- If a screenshot is not possible, take a photo.

**Boot logs**

For problems with the distribution initialization process, include the following log files for your issue.

- `/var/log/rc.log`
- `/var/log/dmesg`
- `/var/log/boot.log`

**System logs**

For problems with the distribution (overall), include the following log files.

- `/var/log/syslog`

**Desktop logs**

For problems with the graphical session, include the following log files.

- `~/.local/share/sddm/wayland-session.log`
- `~/.local/share/sddm/xorg-session.log`
- `~/.desktop-config.log`

**Installation logs**

For problems during the installation with Calamares, include the following log file. 

> Please note that this file is only available in the Live session.

- `~/.cache/calamares/session.log`

---

_*Disclaimer*: Please report issues to the appropriate developer(s). Nitrux is a Linux distribution that comprises dozens of Free and Open Source Software projects._

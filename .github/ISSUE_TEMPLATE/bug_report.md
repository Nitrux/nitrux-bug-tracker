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
 - GitHub doesn't support uploading videos, so please use video sharing like YouTube or Vimeo, etc. and include the URL.

**Additional context**

Ensure to add any other context about the problem here, including what solutions you've tried already.

**OS version and Desktop information**

Open System Settings, go to About System and click "Copy to clipboard in English," and paste the content here.
 - If using System Settings is not possible, use `hw-probe` to provide this information.

**Hardware Information using hw-probe**

If the issue concerns hardware, use `hw-probe` (if it's not available, please download [hw-probe](https://linux-hardware.org/?view=howto)), run it using the following command `sudo -E hw-probe -all -upload`, and add the URL link.

**System logs**

Include the following log files to your issue.

- `/var/log/rc.log`
- `/var/log/dmesg`
- `/var/log/boot.log`
- `/var/log/syslog`

**Other logs**

Include the following log files to your issue.

- `~/.local/share/sddm/wayland-session.log`
- `~/.local/share/sddm/xorg-session.log`

For problems during the installation with Calamares, include the following additional file. 

> Please note that this file is only available in the Live session.

- `~/.cache/calamares/session.log`

**Partition information**

Open Partition Manager, highlight the device where Calamares installed distribution and take a screenshot.

- If a screenshot is not possible, take a photo.

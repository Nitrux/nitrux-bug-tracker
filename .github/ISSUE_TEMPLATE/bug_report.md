---
name: 🐞 Bug report
about: Create a report to help us improve
title: ''
labels: ''

---

# Issue Description

**Describe the bug**

Please include a clear, concise description of the bug. 

**Steps to reproduce the bug**

1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See the error

**Expected behavior**

Could you describe what you expected to happen when the bug occurred?

**Screenshots**

Could you include screenshots to help explain your problem?

**Videos**

If images aren't enough, include videos to explain your problem.
 - GitHub doesn't support uploading videos, so please use video sharing like YouTube or Vimeo, etc., and include the URL.

**Additional context**

Please add any additional context about the problem here, including the solutions you've already tried.

**OS version and Desktop information**

Open Station and run `inxi -s` to provide this information.

**Hardware Information using hw-probe**

Open Station and run `inxi -F`, otherwise, use `hw-probe` to provide this information.

If the issue concerns hardware, use `hw-probe` (if it's not available, please download [hw-probe](https://linux-hardware.org/?view=howto)), run it using the following command 

```
sudo -E hw-probe -all -upload
```

And add the URL link.

# Logs

**Installation logs**

Please include the following log file for any issues encountered during Calamares installation. 

The file below is only available in the Live session.

- `~/.cache/calamares/session.log`

For partitioning issues, run the command `sudo lsblk > lsblk.txt` and include the generated file.

**Boot logs**

Please include the following log files to help diagnose problems with the distribution initialization process.

- `/var/log/rc.log`
- `/var/log/boot.log`
- `/var/log/kern.log`

**System logs**

Include the following log file for problems with the distribution (overall).

- `/var/log/user.log`
- `/var/log/syslog`
- `/var/log/rc.log`
- `/var/log/overlayroot-audit.log`
- `/var/log/kern.log`

---

_*Disclaimer*: Please report issues to the appropriate developer(s). Nitrux is a Linux distribution that comprises dozens of free and open-source software projects._

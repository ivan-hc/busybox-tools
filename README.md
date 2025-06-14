# busybox-tools
Re-host official static binaries from [busybox.net](https://www.busybox.net)

## Reason

The site https://www.busybox.net is often subject to strong slowdowns, probably due to the lack of mirrors that can speed up not only the download of individual binaries, but also the connection to all pages, as well as to the homepage itself.

This repository will take care of downloading the official binaries and hosting them here
- https://github.com/ivan-hc/busybox-tools/tree/main/x86_64-binaries
- https://github.com/ivan-hc/busybox-tools/tree/main/i686-binaries

...in order to speed up the download.

Checking and uploading/updating is done once a month.

------------------------------------------------------------------------

## Usage via "AM" package manager
To install these executables in "[AM](https://github.com/ivan-hc/AM)", use the `--busybox` flag or the .busybox extension, for example:
```
am -i --busybox appname
am -i appname.busybox
```

...where "appname" is the name of the program you want to install. Each binary hosted here has a corresponding "appname", for example

| BINARY | appname |
| - | - |
| busybox_WGET | wget |
| busybox_SED | sed |
| busybox_YES | yes |

...and so on.

That said, to install `yes` it is necessary to run one of the following commands
```
am -i --busybox yes
am -i yes.busybox
```

AM"/AppMan will consider this repository as a third-party repository, so the repository that will manage "AM" compatible lists is [ivan-hc/am-extras](https://github.com/ivan-hc/am-extras)

See below for more information about "AM"

------------------------------------------------------------------------

## Install and update them all with ease

### *"*AM*" Application Manager* 
#### *Package manager, database & solutions for all AppImages and portable apps for GNU/Linux!*

[![Istantanea_2024-06-26_17-00-46 png](https://github.com/ivan-hc/AM/assets/88724353/671f5eb0-6fb6-4392-b45e-af0ea9271d9b)](https://github.com/ivan-hc/AM)

[![Readme](https://img.shields.io/github/stars/ivan-hc/AM?label=%E2%AD%90&style=for-the-badge)](https://github.com/ivan-hc/AM/stargazers) [![Readme](https://img.shields.io/github/license/ivan-hc/AM?label=&style=for-the-badge)](https://github.com/ivan-hc/AM/blob/main/LICENSE)

*"AM"/"AppMan" is a set of scripts and modules for installing, updating, and managing AppImage packages and other portable formats, in the same way that APT manages DEBs packages, DNF the RPMs, and so on... using a large database of Shell scripts inspired by the Arch User Repository, each dedicated to an app or set of applications.*

*The engine of "AM"/"AppMan" is the "APP-MANAGER" script which, depending on how you install or rename it, allows you to install apps system-wide (for a single system administrator) or locally (for each user).*

*"AM"/"AppMan" aims to be the default package manager for all AppImage packages, giving them a home to stay.*

*You can consult the entire **list of managed apps** at [**portable-linux-apps.github.io/apps**](https://portable-linux-apps.github.io/apps).*

## *Go to *https://github.com/ivan-hc/AM* for more!*

------------------------------------------------------------------------

| [***Install "AM"***](https://github.com/ivan-hc/AM) | [***See all available apps***](https://portable-linux-apps.github.io) |
| - | - |

------------------------------------------------------------------------

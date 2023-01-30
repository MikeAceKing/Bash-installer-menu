# Bash-installer-menu
Bash menu for Cinnamon on Ubuntu server
---
Conversion of the shell script to a bash menu version

See: https://github.com/wingarmac/software-install

- - - 


**Purpose:**

Only for Ubuntu server (22.04 tested) and installation of the Cinnamon Desktop

**Prerequisite:** [dialog](https://launchpad.net/ubuntu/+source/dialog)

A check to verify its presence has been added. The package will be installed automatically.

- - -

![Screenshot from 2023-01-30 16-57-34](https://user-images.githubusercontent.com/78303089/215549331-f3c7dd01-08d0-4018-8866-e061fe7fb981.png)

What it does:
---
- It resolves known issues with sound on Ubuntu and the Cinnamon network applet.

  [For more details about the network applet issue here](https://askubuntu.com/questions/1135755/network-manager-applet-shows-not-connected-and-one-unmanaged-wired-connection/1439162#1439162)

  [For more information about the trouble with sound on Ubuntu](https://askubuntu.com/questions/1436904/problem-with-sound-in-ubuntu-22-10/1440458#1440458)

- It makes it easy to add the Mint backports for Cinnamon install on Ubuntu
- It let you select the proprietary driver to install for graphics

  Since I only use Nvidia drivers on my computer, I just did add the version I personally need.

- It has an option to update the Ubuntu kernel to its last release
- It has a menu to install additional software from a text-list and also 3th party software I like to use that uses deb packages to be installed.

- - -
**Usage:**
---

`git clone https://github.com/wingarmac/Bash-installer-menu.git`

`cd Bash-installer-menu`

`chmod a+x Installer-menu.sh`

`./Installer-menu.sh`



- - -
References used to create it:
 - https://unix.stackexchange.com/questions/733152/whats-the-difference-between-sh-command-and-run-as-executable/
 - https://unix.stackexchange.com/questions/733425/creating-debug-of-a-bash-script-menu
 - https://unix.stackexchange.com/questions/733722/back-to-root-menu-in-script-doesnt-respond-like-it-should
 - https://askubuntu.com/questions/1450586/uninstalled-applications-arent-automatically-removed-from-the-cinnamon-menu
 - https://stackoverflow.com/questions/1298066/how-can-i-check-if-a-package-is-installed-and-install-it-if-not/10439058#10439058
 

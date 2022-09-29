<img src="/CROSfetch_Logo.png" alt="CROSfetch logo" align="left">
<h1 align="left">CROSfetch</h1>
<p align="left"> <a href="./LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-blueviolet.svg" height="25px"></a>
<p align="left"> <a href="https://github.com/railwhale/CROSfetch/releases"><img src="https://img.shields.io/badge/Version-0.0-blueviolet" height="25px"></a>
<p align="left"> <a href=""><img src="https://img.shields.io/badge/Lines-404-blueviolet" height="25px"></a>
 
A Neofetch clone built from the ground up for Chrome OS  

 
## Info Given:
 - Basic prompt (As a title)
 - Google accounts on Device
 - OS
 - Channel
 - Kerne1
 - Host
 - Uptime
 - Package managers
 - Packages
 - Terminal
 - Shell
 - Program Locations (Your ```$PATH```)
 - DE
 - WM
 - Theme
 - CPU
 - GPU
 - Memory Amount
 - Storage Amount


### Example crosfetch:
```bash
chronos@localhost
------------------ 
Google Accounts: rail.whale, email.eg (2)
------------------
OS: Chrome OS x86_64 v106 (Official Build) Stable Channel
Kernel: Linux 4.14.290-19333-g27906fd1733f
Host: Chromebook octopus
Uptime: 1 day, 4 hours, 23 minutes
------------------
Package Managers: Chromebrew, Portage
Packages: 6 (crew), 15 (emerge)
------------------
Terminal: Google Chrome
Shell: Bash 5.1.16(1)-release
------------------
DE: Chrome
WM: Ash
Theme: Dark
------------------
CPU: Intel(R) Celeron(R) N4100 CPU @ 1.10GHz
GPU: 
RAM: 3990 MB
```
 
### CROSfetch Sources
| Info |	Source in Chrome OS |
|:-----|:----|
| Title	|	$USER and $HOSTNAME |
| Google accounts	|	For every account there is a profile jpeg in /home/chronos/, so you can remove the /path/ and everything past the '@' |
| OS	|	/etc/lsb-release |
| Channel	|	/etc/lsb_release |
| Kernel	|	uname command |
| Host	|	Sometimes /sys/devices/virtual/dmi/id, sometimes /sys/firmware/devicetree/base/model |
| Uptime	|	uptime command |
| Package |	Managers	WIP |
| Packages	|	WIP |
| Terminal	|	Check weather the OS is Chrome, Chromium or something else |
| Shell	|	Check for $BASH_VERSION, else shell is dash (sh) |
| Program |	Locations	$PATH variable |
| DE	|	Check weather the OS is Chrome OS or not |
| WM	|	Assue WM is Ash |
| Theme	|	WIP |
| CPU	|	uname command |
| GPU	|	WIP |
| RAM	|	free command |
| Storage	|	WIP |

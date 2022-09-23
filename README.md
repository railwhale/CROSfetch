<p align="center"><img src="/CROSfetch_Logo.png" alt="CROSfetch logo" />
<h1 align="center">CROSfetch</h1>

A Neofetch clone I made for chromeOS  
(But mostly to learn bash scripting)  

## Info Given:
 - Basic prompt (As a title)
 - Linux Username
 - Google accounts on Device
 - OS
 - Channel
 - Kernel
 - Hostname
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
 
 - Memory Ammount
 - Storage Ammount


## Example crosfetch:
```bash
chronos@localhost
------------------
Username: chronos
Local Google Accounts: rail.whale, email.eg
------------------
OS: Chrome OS 106 (Official Build)
Update Channel: Stable
Kernel: Linux 4.14.290-19333-g27906fd1733f
Hostname: localhost
Host: Chrombook octopus
Uptime: 1 day, 4 hours, 23 minutes
------------------
Package Managers: Chrome, Portage
Packages: 6 (Crew), 15 (Portage)
------------------
Terminal: crosh - Google Chrome
Shell: Bash 5.1.16(1)-release
Program Locations: /usr/local/bin, /usr/bin, /bin, /opt/bin
------------------
DE: Chrome
WM: Ash
Theme: Dark
------------------
CPU: Intel(R) Celeron(R) N4100 CPU @ 1.10GHz
GPU
Ram: 4 GB
Storage: 32 GB 
```

## Man page
 wait for v1.1



## CROSfetch Sources

| Info | Source in Chrome OS |  
|:---|:---:|
| Title | Join some pre-existing variables |
| Linux name | The $USER variable |
| Google accounts | For every account there is a profile .jpg in /home/chronos, so you can remove the /path/ and everything past the '@' |
| OS | Base name from /etc/lsb-release.d/NAME, add version and officialness from /etc/lsb-release |
| Channel | Checks /etc/lsb_release for channel name |
| Kernel | uname command |
| Hostname | uname command |
| Host | Find in /etc/lsb-release |
| Uptime | uptime command |
| Package Managers | WIP |
| Packages | WIP |
| Terminal | Check weather the browser is Chrome or Chromium |
| Shell | Check for $BASH_VERSION, else shell is dash (sh) |
| Program Locations | $PATH variable |
| DE | Check weather the browser is Chrome or Chromium |
| WM | Assue WM is Ash |
| Theme | WIP |
| CPU | uname command |
| GPU | WIP |
| RAM | free command |
| Storage | WIP |

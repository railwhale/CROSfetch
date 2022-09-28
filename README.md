<p align="center"><img src="/CROSfetch_Logo.png" alt="CROSfetch logo" />
<h1 align="center">CROSfetch</h1>

A Neofetch clone I made for chromeOS  
(But mostly to learn bash scripting)  

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


## Example crosfetch:
```bash
chronos@localhost
------------------ 
Local Google Accounts: rail.whale, email.eg
------------------
OS: Chrome OS x86_64 v106 (Official Build) Stable channel
Kernel: Linux 4.14.290-19333-g27906fd1733f
Host: Chrombook octopus
Uptime: 1 day, 4 hours, 23 minutes
------------------
Package Managers: Chromebrew, Portage
Packages: 6 (Crew), 15 (emerge)
------------------
Terminal: Crosh - Google Chrome
Shell: Bash 5.1.16(1)-release
Program Locations: /usr/local/bin, /usr/bin, /bin, /opt/bin
------------------
DE: Chrome
WM: Ash
Theme: Dark
------------------
CPU: Intel(R) Celeron(R) N4100 CPU @ 1.10GHz
GPU: 
Ram: 4 GB
Storage: 32 GB 
```

## CROSfetch Sources

| Info | Source in Chrome OS |  
|:---|:---|
| Title | $USER and $HOSTNAME |
| Google accounts | For every account there is a profile jpeg in /home/chronos/, so you can remove the /path/ and everything past the '@' |
| OS | /etc/lsb-release |
| Channel | /etc/lsb_release |
| Kernel | uname command |
| Host | Sometimes /sys/devices/virtual/dmi/id, sometimes /sys/firmware/devicetree/base/model |
| Uptime | uptime command |
| Package Managers | WIP |
| Packages | WIP |
| Terminal | Check weather the OS is Chrome, Chromium or something else |
| Shell | Check for $BASH_VERSION, else shell is dash (sh) |
| Program Locations | $PATH variable |
| DE | Check weather the OS is Chrome OS or not |
| WM | Assue WM is Ash |
| Theme | WIP |
| CPU | uname command |
| GPU | WIP |
| RAM | free command |
| Storage | WIP |

### Options and Flags

| Option | Short Flag | Long Flag | What it does | Modes |
|:---|:---|:---|:---|:---|
| Help | \ | --help | Prints a basic help page with options and descriptions | None |
| Not The Manual | \ | --n-man | More detailed help page | None |
| Version | -V | --version | Prints the version | None |
| Export | \ | --export | Format output in a way friendly to storing somewhere, such as a file or variable | None |
| Mostly All | -A | --mall | Print all known information | None |
| All | \ | --real-all | Prints all line, even if they are unkown | None |
| Colour | -C | --color | Weather to have color output | on, off |
| Title | \ | --title | Print the a basic prompt | on, off |
| Google Accounts | - | --g_accounts |  | on, off, count, names |
| OS | -o | --os | Print your os | on, off, name |
| Architecture | -a | --arch |  | on, off, auto |
| Channel | -c | --channel |  | on, off, auto |
| Kernel | -k | --kernel |  | on, off, version, name |
| -h | --host | Host device |  | on, off |
|  | --uptime | Uptime |  | on, off, short |
|  | --package-men | Package managers |  | on, off, auto |
|  | --packages | Packages |  | on, off, total |
|  | --terminal | Terminal |  | on, off |
|  | --shell | Shell |  | on, off, binary |
|  |  |  |  |  |

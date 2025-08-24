# DosInfo
## DosInfo: a neofetch clone for DOS

Based on dosfetch (https://github.com/leahneukirchen/dosfetch/tree/master). 

Improvements from dosfetch include:

Added checks:
- Added EMS size
- Added free base memory
- Added CPU family info (only tested until Pentium II)
- OS detection improved (added Dosbox, Dosbox-X and a couple of other OS's)
- Added uptime

Added options:
- Logo is changeable (with a text file)
- Colors can be changed (with a config file)

Removed some bugs (like OS version for older DOS versions) and added some sanity checks (line length etc).

DosInfo is tested on 286 CPU's and newer (until Pentium II). In Dosbox-X it also runs on a 8088 CPU but this is not tested on actual hardware.


Screenshot on the left uses the default logo and colors. The right screenshot uses a custom logo and all colors changed to white.

![dosinfo](https://github.com/user-attachments/assets/ca06b0b9-bf88-4ff5-b1b4-a8e49455765e)

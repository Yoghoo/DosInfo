# DosInfo
## DosInfo: a neofetch clone for DOS

Based on dosfetch (https://github.com/leahneukirchen/dosfetch/tree/master). But almost completly rewritten.

Improvements from dosfetch include:

Added and improved checks:
- Added XMS/EMS size
- Added free base memory
- Added CPU family info
- OS detection improved (added Dosbox, Dosbox-X etc)
- Added uptime (works with leap years etc for unrealistic long uptimes :))
- Now also works with FAT32 drives
- Shows all available drives
- Auto detects < 80 column displays and adjusts the output

Added options:
- Logo is changeable (with a text file)
- Includes a /nologo switch if you don't want to show a logo
- Colors can be changed (with a config file)

Removed some bugs (like OS version for older DOS versions) and added some sanity checks (line length etc).

DosInfo is tested on NEC V20 CPU's and newer (until Pentium II). In Dosbox-X it also runs on a 8088 CPU but this is not tested on actual hardware yet.
It was also tested on a lot of different DOS OSes. Some examples are MS-DOS 2.0, 3.31, 6.22, DR-DOS 6.0, Novell DOS 7.0, IBM PC DOS 7.0 and FreeDOS 1.4.

The screenshot below uses the default logo and colors.

![default](https://github.com/user-attachments/assets/fed2c3a2-e95b-4c71-ad2f-719b54be81cc)

The screenshot below is in 40 column mode and uses a custom logo with all colors changed to white.

![logo_co40](https://github.com/user-attachments/assets/beb3f515-9f68-47f1-ac88-de1afbfbdc9d)



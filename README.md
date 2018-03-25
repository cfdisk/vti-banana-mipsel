# extra VTi repository (mips32el)
Some extra/replacment packages for VTi

## Installation
- Login on VTi Box
- `cd /etc/opkg`
- `wget https://raw.githubusercontent.com/cfdisk/vti-banana-mipsel/master/vti-banana-mipsel-feed.conf`
- `opkg update`

## current packages:

### cpulimit ipk mipsel
cpulimit https://sourceforge.net/projects/cpulimit/

Licence: GNU General Public License version 2.0 (GPLv2)


### dropbear ipkg mipsel
Newer version of very old VTI dropbear

Licence: GNU General Public License version 2.0 (GPLv2)


### ntpd_bj ipk all
Disable DBV time sync and use ntpd instead

Install via shell/opkg only! DONT ever install via GUI because install script restartes E2


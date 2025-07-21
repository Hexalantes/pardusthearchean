# Pardus The Archean Beta 1
that's the releng, not compiled.

! This project is still in Beta phase and available for testing purposes, use at your own risk !

Pardus name rights belong to TÜBİTAK.
Much thanks to the Arch Linux community for providing archiso.
also liveuser password is 1234.

# Known Issues
- cannot install on bios/legacy/csm hardware, it only works on uefi; you can try to use/install in bios in your own risk.
- on some real hardware, calamares cannot unpack airootfs.sfs cause of some mount problems.
- in tty interface (terminal), it gives you an archiso motd.
  (you see:
  
   "To install Arch Linux, follow the installation guide:
   https://wiki.archlinux.org/title/Installation_guide.

   For Wi-Fi, authenticate to the wireless network using the iwctl.
   For mobile broadband (WWAN) modems, connect with the mmmcli utility.
   Ethernet, WLAN and WWAN interfaces using DHCP should work automatically.

   After connecting to the internet, the installation guide can be accessed
   via the convenience script Installation_guide"
   in tty interface.)
  
- calamares will stay in applications menu as "Install System" after the installation.
- pacman gives key errors almost everytime.

# License

This project is licensed under the GNU General Public License v3.0 (GPLv3).  
See the LICENSE file for details.

Copyright (C)  Hexalantes.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.

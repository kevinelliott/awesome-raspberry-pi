# awesome-raspberry-pi

A curated list of awesome resources for the Raspberry Pi

<a href="https://www.raspberrypi.org"><img src="https://www.raspberrypi.org/wp-content/uploads/2012/03/raspberry-pi-logo.png" alt="Raspberry Pi Logo" align="left" style="margin-right: 25px" height=150></a>

> The Raspberry Pi is an infamous low-cost Single Board Computer (SBC) that has reduced the barrier of entry for computing and tinkering.
> The Raspberry Pi is in a compact form factor (about the size of a credit card).
>
> The Raspberry Pi is one of the most well supported SBCs on the market.
>
> [Raspberry Pi Homepage](https://raspberrypi.org)

## Operating System Images

Images written to SD cards are the quickest way to get running on a Raspberry Pi. There are a large number of images available:

- [Lightweight](#lightweight--slim) - Focused on being small/thin/lightweight and optimized, allowing you to dedicate more system resources to your specific applications.
- [Full](#full) - Provides entire operation system and desktop UI.
- [Specialized](#specialized) - Customized distributions focusing on particular applications or purposes.

### Lightweight / Slim

| OS | Difficulty | Base Install Size | Runtime Memory Footprint | Image | Setup |
| --- | --------- | --------------: | -----------------------: | ----- | ----- |
| [Arch Linux ARM](https://archlinuxarm.org) <br> *A lightweight and flexible Linux distribution that tries to Keep It Simple.* | Medium | - | - | [Download](http://os.archlinuxarm.org/os/ArchLinuxARM-rpi-3-latest.tar.gz) | [Setup](https://archlinuxarm.org/platforms/armv6/raspberry-pi) |
| [Armbian](https://armbian.com) <br> *Distribution and build system specialized for single board computers.* | Low | 500 Mb | - | [Download](https://www.armbian.com/rpi4b/) | [Setup](https://docs.armbian.com/User-Guide_Getting-Started/) |
| [Alpine Linux](https://wiki.alpinelinux.org/wiki/Main_Page) <br> *A security-oriented, lightweight Linux distribution based on musl libc and Busybox.* | Medium | 130 MB | - | [Download](https://alpinelinux.org/downloads/) | [Setup](https://wiki.alpinelinux.org/wiki/Raspberry_Pi) |
| [Crux ARM](https://crux-arm.nu/Main/HomePage) <br> *CRUX ARM is a lightweight Linux distribution for the ARM architecture targeted at experienced Linux users.* | High | 81 MB  | - | [Download](https://crux-arm.nu/SupportedDevices/Raspberrypi) | [Setup](https://crux-arm.nu/SupportedDevices/Raspberrypi) |
| [DietPi](https://www.dietpi.com) <br> *Highly optimized minimal Debian OS.* | Low | 400 MB | - | [Download](https://dietpi.com/#download) | [Setup](https://dietpi.com/phpbb/viewtopic.php?p=9#p9) |
| [piCore](http://www.tinycorelinux.net/welcome.html) <br> *The Core Project is a highly modular based system with community build extensions.* | High | 35 MB | - | [Download](http://www.tinycorelinux.net/9.x/armv6/) | [Setup](http://tinycorelinux.net/9.x/armv6/releases/RPi/README) |
| [Raspbian Lite](https://www.raspberrypi.org/downloads/raspbian/) <br> *Raspbian without the graphical desktop, based on Debian.* | Low | 1.2 GB | - | [Download](https://www.raspberrypi.org/downloads/raspbian/) | [Setup](https://www.raspberrypi.org/documentation/installation/installing-images/README.md) |
| [ReceiverOS](https://airframes.io/) <br> A highly optimized Debian-based operating system focused on radio applications, properly multi-platform capable by harnassing Armbian's build system. | Low | 800 MB | - | [Download](https://download.receiveros.com) | [Setup](https://documentation.receiveros.com) |
| [Ubuntu Core](https://ubuntu.com/download/iot/raspberry-pi-2-3-core) <br> *A lean, strictly confined and fully transactional operating system for IoT.* | Medium | - | - | [Download](https://ubuntu.com/download/iot/raspberry-pi-2-3-core) | [Setup](https://ubuntu.com/download/iot/raspberry-pi-2-3-core) |

### Full

- [Android Things](https://developer.android.com/things/hardware/raspberrypi.html) - Android Things lets you experiment with building smart, connected device applications.
- Armbian
- [FedBerry](http://fedberry.org) - A Fedora Remix specifically built for use with Raspberry Pi® 2/3 Model B computers.
- [Gentoo Linux](https://wiki.gentoo.org/wiki/Raspberry_Pi) - Flexible Linux based Raspberry Pi OS and uses Portage software management to increases security and streamlines performance.
- Raspbian
- [RISC OS](https://www.riscosopen.org/content/downloads/raspberry-pi) - A fast and easily customised operating system for ARM devices (non-Linux).
- [SUSE Linux Enterprise Server](https://www.suse.com/products/arm/) - SUSE Linux Enterprise Server for Arm is an enterprise-grade Linux distribution that is optimized for unique 64-bit Arm chip capabilities.
- Ubuntu
- [Ubuntu MATE](https://ubuntu-mate.org/raspberry-pi/) - Ubuntu MATE for the Raspberry Pi provides a complete, familiar, desktop environment that can be used for basic desktop computing.
- [Windows IoT Core](https://docs.microsoft.com/en-us/windows/iot-core/windows-iot-core)
  
### Specialized

- [Kali Linux](https://docs.kali.org/kali-on-arm/install-kali-linux-arm-raspberry-pi) - Linux distribution largely focused on security and pentesting.
- [LibreELEC](https://libreelec.tv) - A lightweight ‘Just enough OS’ Linux distribution purpose-built for Kodi on current and popular mediacentre hardware.
- [OctoPi](https://octoprint.org) - Manage and control 3D printers.
- [OpenElec](https://openelec.tv) - A small Linux based Just Enough Operating System (JeOS) built from scratch as a platform to turn your computer into a Kodi media center.
- [OpenMediaVault](https://www.openmediavault.org) - The next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more.
- [OpenWrt](https://openwrt.org) - Linux-based open source wireless router with extensibility.
- [OSMC](https://osmc.tv/) - A free and open source media center built for the people, by the people.
- [pi-TopOS](https://www.pi-top.com/products/os) - A focus on programming and gaming, intended for the pi-Top, but works on any Raspberry Pi.
- [PiNet](http://pinet.org.uk) - Centralized user accounts and file storage system for a Raspberry Pi classroom.
- [RaspiBlitz](https://github.com/rootzoll/raspiblitz) - Run a full Lightning Node.
- [RetroPie](https://retropie.org.uk) - Turn your Raspberry Pi into a retro-gaming machine, based on Raspbian.
- [ROKOS](https://rokos.space) - Bitcoin full node.

## Projects

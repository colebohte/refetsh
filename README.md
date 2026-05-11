# Refetsh

Refetsh is an improved and remastered version of [fet.sh](https://github.com/eepykate/fet.sh) by eepykate.

```
  coleb@cole-debian
  ---------------------------------------
            os ~ Debian 13 GNU/Linux 'Trixie'
          host ~ HP Laptop 14-dk1xxx
        kernel ~ 6.12.57+deb13-amd64
        uptime ~ 1 week, 6 days, 35 minutes
          pkgs ~ 4250
         shell ~ bash 
      terminal ~ xterm-256color
  ---------------------------------------
    resolution ~ 1366x768
            de ~ X-Cinnamon 48.7
            wm ~ Mutter (Muffin)
         theme ~ Orchis-Dark-Compact
         icons ~ Papirus
  ---------------------------------------
           cpu ~ AMD Athlon Gold 3150U with Radeon Graphics (4) @ 2.4GHz
           gpu ~ AMD ATI Radeon Vega Series / Radeon Vega Mobile Series
        memory ~ 4045MiB / 5846MiB
          swap ~ 917MiB / 5165MiB
  ---------------------------------------
    sys rating ~ 3.3 / 15.0

```

## Features

*   Written in `sh` to ensure compatibility and speed without unnecessary dependencies.
*   Displays OS, kernel, uptime, package counts (Apt, RPM, NixPkgs, Pacman, Flatpak), shell, DE/WM details, and full hardware specs (CPU, GPU, RAM, Swap).
*   Includes a built-in "Hardware Experience Index" out of 15.0 based on your actual CPU thread count and RAM capacity.

## Requirements

Refetsh relies on standard utilities:
*   `grep`, `awk`, `cut`, `sed` (Standard coreutils)
*   `free`, `nproc`, `lspci`, `lscpu` (Hardware info)
*   `xdpyinfo` (For resolution detection)
*   `gsettings` (For GNOME theme/icon detection)<br>
<sub>Most of these come installed in most distros out of the box</sub>

## Installation

### Package Manager
*   *AUR*: `paru -S refetsh-git` or yay `yay -S refetsh-git`<br>
<sub>At the moment, Refetsh is only on the AUR</sub>

### Manual
1.  Clone & enter the repo; `git clone https://github.com/colebohte/refetsh.git && cd refetsh`
2.  Run the installer script; `chmod +x install.sh && ./install.sh`

# Refetsh

Refetsh is an improved and remastered version of [fet.sh](https://github.com/eepykate/fet.sh) by eepykate.

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

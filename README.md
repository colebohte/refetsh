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

1.  **Clone or download** the script.
2.  **Make it executable**:
    ```bash
    chmod +x refetsh

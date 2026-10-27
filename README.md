# NeoArcadeOS

A Batocera-inspired retro gaming operating system built for fast boot, streamlined arcade navigation, and a polished emulator-first experience.

<p align="center">
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/v1-final2.png" alt="NeoArcadeOS interface" width="900" />
</p>

## Overview

NeoArcadeOS is an experimental gaming OS designed to provide a lightweight, bootable emulation experience inspired by Batocera but customized for a more personal and modern arcade workflow.

The project focuses on:

- fast boot into a game-first interface
- emulator and ROM management
- USB installation workflow
- customizable arcade-style navigation
- a clean, console-presented user experience

## Features

- Bootable ISO workflow for USB or optical media
- Batocera-style layout for ROM, BIOS, and emulator storage
- Quick access to emulator and system configuration
- Built for arcade and retro-game usage
- Recovery consoles and desktop access for troubleshooting
- Lightweight, fast-launch system design

## Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/boot1.png" alt="Boot screen 1" width="420" />
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/run1.png" alt="Run screen" width="420" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/usb1.png" alt="USB setup" width="420" />
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/v1-ui.png" alt="UI preview" width="420" />
</p>

## Quick start

1. Download the latest `.iso` build from the repository releases or project artifacts.
2. Write the image to a USB drive using Rufus, balenaEtcher, or `dd`.
3. Boot the system in BIOS or UEFI mode.
4. Launch games directly from the menu or configure the system as needed.

### Example USB write (Linux)

```bash
sudo dd if=gamingos-v1.0.iso of=/dev/sdX bs=4M status=progress
```

## Repository structure

This repository includes:

- ISO-related build artifacts and checksums
- screenshot assets for the system UI and boot flow
- build logs and package metadata
- configuration and usage documents

## Project status

NeoArcadeOS is currently in active development and is best understood as a custom retro gaming OS prototype and showcase project.

## Notes

This project aims to create a polished, arcade-first environment inspired by legendary console-style frontends while remaining lightweight and approachable for experimentation.

## License

No license has been declared for this repository yet. If you plan to distribute or share the project publicly, consider adding an open-source license in GitHub repository settings.

## Contributing

If you want to improve the project, feel free to fork the repo, test the build, share screenshots, suggest enhancements, or help refine the interface and boot experience.

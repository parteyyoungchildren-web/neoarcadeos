# NeoArcadeOS

<div align="center">
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/v1-final2.png" alt="NeoArcadeOS Interface" width="980" />
</div>

<p align="center">
  <strong>Arcade power. Console simplicity. A new era of retro gaming.</strong>
</p>

A Batocera-inspired retro gaming operating system built for fast boot, streamlined traversal, and a clean emulator-first experience.

## Overview

NeoArcadeOS is an experimental gaming OS designed to deliver a lightweight, bootable retro gaming environment inspired by the feel of Batocera, but shaped around a more custom, modern arcade workflow.

The project aims to provide:

- ultra-fast boot into a game-first interface
- clean navigation for emulators and game libraries
- a USB-installation workflow for easy setup
- portability across BIOS and UEFI systems
- a polished, console-like experience for arcade gaming

## Why NeoArcadeOS?

The goal is simple: build a retro gaming OS that feels immediate, focused, and immersive.

Instead of overwhelming the user with unnecessary complexity, NeoArcadeOS prioritizes:

- speed
- simplicity
- reliable boot behavior
- a strong arcade aesthetic
- a familiar game library layout

## Features

- Bootable ISO image for USB or CD-style installation
- Batocera-inspired structure for ROMs, BIOS files, and emulators
- Game-first launcher experience
- Recovery consoles and desktop access for diagnostics
- Lightweight desktop and system environment
- Flexible storage layout for user data and media
- Custom UI previews and build progression snapshots

## Screenshots

<div align="center">
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/boot1.png" alt="Boot Screen" width="420" />
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/run1.png" alt="Runtime Screen" width="420" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/usb1.png" alt="USB Setup" width="420" />
  <img src="https://raw.githubusercontent.com/parteyyoungchildren-web/neoarcadeos/main/v1-ui.png" alt="UI Preview" width="420" />
</div>

## Quick Start

1. Download the latest ISO build from the repository artifacts or release section.
2. Write it to a USB drive using Rufus, balenaEtcher, or `dd`.
3. Boot the system in BIOS or UEFI mode.
4. Launch games directly from the menu or configure emulator settings.

### Linux example

```bash
sudo dd if=gamingos-v1.0.iso of=/dev/sdX bs=4M status=progress
```

## Repository Structure

This repository contains:

- ISO build artifacts and checksums
- screenshot assets for boots, UI, and gameplay flow
- logs from build and root filesystem generation
- package metadata and source checksums
- project documentation and setup notes

## Project Status

NeoArcadeOS is currently in active development and is best understood as a custom retro gaming OS prototype and showcase project.

The repo is intended to evolve toward a cleaner, more polished, and more complete arcade operating system experience.

## Roadmap

Planned focus areas include:

- refining boot flow and startup polish
- improving navigation and UI consistency
- organizing emulator and ROM handling
- enhancing install and recovery workflows
- creating a stronger platform identity and branding

See [docs/ROADMAP.md](docs/ROADMAP.md) for more detail.

## Contributing

Contributions are welcome.

If you want to help improve the emulator workflow, UI design, system setup, or project documentation, please read [CONTRIBUTING.md](CONTRIBUTING.md) and open a pull request with your ideas.

## License

This project is currently unlicensed. If you plan to distribute or share it publicly, adding an official open-source license is recommended.

See the repository's license settings or add one through GitHub to define distribution rules.

## Final Note

NeoArcadeOS was built as a passion project with a big goal: create a fast, stylish, and approachable gaming operating system capable of standing alongside the best console-focused frontends.

This repo is designed to grow from a bold prototype into a well-structured, professional project.

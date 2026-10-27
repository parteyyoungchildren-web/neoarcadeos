GamingOS 1.0 - buildv1
=======================

gamingos-v1.0.iso   290455552 bytes
sha256              ae3bd72d9e555452208d55f70d1f4e14d3c1aa64a141f7ef585123a23de03fed
built               2026-10-27 01:57
base                SliTaz cooking x86_64 (slitaz-firefox-x86_64-cooking.iso)


WRITE IT TO A USB STICK (Rufus)
-------------------------------
  Device         your stick  (every file on it is erased)
  Boot selection choose this .iso
  Partition      MBR
  Target         BIOS or UEFI
  When asked for "ISO Image mode" or "DD Image mode" -> pick DD.

The image is hybrid: the same file boots from a CD/DVD, from a USB stick in
legacy BIOS, and from a USB stick in UEFI (it carries an EFI partition).

Other writers:
  Windows : Rufus in DD mode, or balenaEtcher
  Linux   : sudo dd if=gamingos-v1.0.iso of=/dev/sdX bs=4M status=progress


WHAT HAPPENS WHEN IT BOOTS
--------------------------
  isolinux menu (wait 4 seconds) -> kernel -> the game interface on tty1.
  No login prompt: it starts like a console.

    ENTER       play          left/right  change system     up/down  change game
    F1          file manager  F2          add emulator      F3       diagnostics
    F4          rescan        F5          hardware          F6       storage
    F7          controllers   F8          emulator settings Q        quit to shell

  Recovery, always available:
    Ctrl+Alt+F2 .. F6  text consoles, login tux / tux
    gamingos-desktop   starts the graphical desktop when wanted
    gamingos-web       web portal on http://<ip>:8099 (token printed on screen)
    boot label "safe"  uses the stock SliTaz boot path instead of the fast one


WHERE YOUR FILES GO (Batocera layout, so an existing collection drops in)
-------------------------------------------------------------------------
  /userdata/roms/<system>/     games
  /userdata/bios/              BIOS files you supply
  /userdata/emulators/         AppImage / .exe / native emulators
  /userdata/saves/, /userdata/savestates/, /userdata/cheats/
  /userdata/system/configs/    configuration (never touched by an update)
  /userdata/system/logs/       launch log - the first place to look
  ~/RetroOS                    a shortcut to /userdata
  USB sticks: /media/<label>/roms/<system>/ is merged into the same library,
  and F6 remembers a location permanently.

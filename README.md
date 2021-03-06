# MiniUI-ScummVM-Pak

ScummVM pak for MiniUI using the ScummVM libretro core for the Miyoo Mini built by [StupidHoroscope](https://github.com/StupidHoroscope), including the aux/additional data files and themes.

# Release Versioning

Release version numbers follow the [ScummVM](https://github.com/scummvm/scummvm) releases.

# Installation

Download the release zip and extract to the root of your SD card.

# Updating

Download the release zip and extract to the root of your SD card, overwriting any existing files and folders.

To manually update the libretro core, replace the `scummvm_libretro.so` file in `Emus/SCUMMVM.pak` with the new version.

To manually update the aux/additional data pack, replace the extra and themes folders in `Bios/SCUMMVM` with the contents from the new version.

# Usage

Usage is the same as with any of the other MiniUI emulators.

Copy games into their own folders under the `Roms/ScummVM (SCUMMVM)` folder.

Save states are __NOT__ supported.  Press the Start button to bring up the ScummVM menu and save and load there.

## Audio Noise

Enable Speed Hack in the emulator options to eliminate audio noise if you're experiencing any.

## Loading and Quitting Games

Which game file to load is different for each game.  If you select the wrong file, the system will hang and the battery needs to be pulled to power off.

Only exit through the MiniUI menu.  If you exit through the ScummVM launcher, the system will hang and can only be powered off by pulling the battery.

# Sources

ScummVM-MiyooMini https://github.com/StupidHoroscope/ScummVM-MiyooMini

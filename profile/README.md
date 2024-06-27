# the KITTY Computer Organization REPO

the KITTY is a (currently in-development) 65c02-based open source homebrew computer geared towards text mode and PETSCII-inspired graphics and games. The design uses only in-production parts and custom discrete logic circutry·

**Useful Links**
* [Online Manual](https://kitty-6502.github.io/)
* [Hardware Schematic](https://github.com/KITTY-6502/hardware/blob/main/Docs/schematics/v2a.pdf)
* [WIP Emulator](https://github.com/kitty-6502/KittyEMU)
* [Discord Server](https://discord.gg/pZZFwxz5js)
* [Cohost Posts](https://cohost.org/smal/tagged/KITTY%20Computer)

> At the moment the hardware is still in active prototype development, and there is still no stable PCB revision, this page will be updated once that happens.

## Features
* **CPU:** 8bit 65c02 CPU running at an average ~2.2Mhz
* * 3Mhz Bus
* * Alternate drop-in support for a 16bit 65c816 upgrade
* **RAM:** 28Kib of RAM
* * 2KiB used as Video RAM
* **VIDEO:** Character Based Graphics
* * 256x256 Pixel Resolution at 50Hz (PAL)
* * 32x32 tiles with per-tile character and color control
* * 16 Possible Colors
* * Fixed font of 256 ascii-compatible characters
* * RGB Output via SCART Connector
* **AUDIO:** Custom "Wavetable" audio
* * 4 Channels of audio, 3 melodic and 1 percussive
* * 1byte (8x1) wavetables
* * 4bit+4bit stereo volume control
* **PORTS:** 2 Cartridge Ports used for Programs, Expansion and Peripherals
* * Each Cartridge contains up to 128 banks of 32Kib for a total maximum 4Mib Address Space
* **INPUT:** Custom 40-key mechanical keyboard matrix

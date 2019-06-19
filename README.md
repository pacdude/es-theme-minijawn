# Minijawn 1.0
A theme for EmulationStation specifically designed for small screens (like the RetroFlag GPi Case). 

## About
MiniJawn is a small theme I put together to have a nice-looking theme for my RetroFlag GPi. The screen is small and not that high-definition, so having a big, bold UI was a must. And since this is running on a Raspberry Pi Zero, I didn't feel like doing a whole lot.

## Supported Consoles
Version 1 of this theme supports:
- MAME/Arcade
- Atari 2600
- Atari 5200
- Atari 7800
- Game Gear
- Game Boy
- Game Boy Advance
- Game Boy Color
- Sega Genesis / Megadrive
- NES
- Neo Geo Pocket Color
- PlayStation
- SNES

There is also support for the RetroPie menu. Feel free to leave any issues about consoles you would like supported.

## Not Implemented Yet
- Grid mode is not implemented yet. Once I understand how it works a little more, I'll do something with it, I guess.
- I'm trying to figure out a graceful fallback method in the event there's something you've installed that the theme doesn't support yet. It's not going well so far.
- I haven't tried this theme out on a screen resolution larger than 320x240. The theme's raw files are designed at 320x240 right now. I guarantee it will look like ass on a larger display. I may spruce it up in a future update.

## Installation Instructions
Type this into your Terminal: 

`sudo git clone --recursive --depth 1 "https://github.com/pacdude/minijawn.git" "/etc/emulationstation/themes/minijawn"`

Or, you can download as a ZIP file, unzip the thing, then stick the minijawn folder in configs/all/emulationstation/themes.

## Suggested Settings
In Emulation Stations' UI settings, I would set Carousel Transitions to ON, Transition Style to Fade, Gamelist View Style to Detailed, and On-Screen Help to OFF.


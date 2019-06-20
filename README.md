# MiniJawn
A theme for EmulationStation specifically designed for small screens (like the RetroFlag GPi Case). 

![MiniJawn 1.0 Title Screen](https://c10.patreonusercontent.com/3/eyJwIjoxfQ%3D%3D/patreon-media/p/post/27746437/a62326ef3c034d24a4cbb4f080ca2dc0/1.jpeg?token-time=1562112000&token-hash=b8XWjP5zZAkBGBuVzrvAsTvqQCIIKMuUzwJgfdkmu2c%3D "MiniJawn 1.0 Title Screen")

## About
MiniJawn is a small theme I put together to have a nice-looking theme for my RetroFlag GPi. The screen is small and not that high-definition, so having a big, bold UI was a must. And since this is running on a Raspberry Pi Zero, I didn't feel like doing a whole lot. View more images at [my Patreon page](https://www.patreon.com/posts/27746437).

![MiniJawn 1.0 Collage](https://preview.redd.it/nq9uypzhsi531.png?width=960&crop=smart&auto=webp&s=e3635d75cbaab23a8ed079357b3e74b5e5a4600e "MiniJawn 1.0 Collage")

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
- PC Engine / TurboGraphix16
- Neo Geo Pocket Color
- PlayStation
- SNES
- Ports

There is also support for the RetroPie menu. Feel free to leave any issues about consoles you would like supported.

## Not Implemented Yet
- Grid mode is not implemented yet. Once I understand how it works a little more, I'll do something with it, I guess.
- I'm trying to figure out a graceful fallback method in the event there's something you've installed that the theme doesn't support yet. It's not going well so far.
- I haven't tried this theme out on a screen resolution larger than 320x240. The theme's raw files are designed at 320x240 right now. I guarantee it will look like ass on a larger display. I may spruce it up in a future update.

## Installation Instructions
SSH into your Pi, or exit Emulation Station to the command prompt. Type the following lines, one at a time:

`cd /opt/retropie/configs/all/emulationstation/`

`mkdir themes`

`cd themes`

`git clone https://github.com/pacdude/minijawn.git`

Or, you can download as a ZIP file, unzip the thing, then stick the minijawn folder in /configs/all/emulationstation/themes. (If that folder doesn't exist, create it.)

## Suggested Settings
In Emulation Stations' UI settings, I would set Carousel Transitions to ON, Transition Style to Fade, Gamelist View Style to Detailed, and On-Screen Help to OFF.

## Changelog

1.1: Theme now has a fallback for logos that don't exist. It's not great but it works. Ports, Final Burn Alpha, PCEngine and TurboGraphix16 now have support for icons and marquees.

1.0: Initial Release
